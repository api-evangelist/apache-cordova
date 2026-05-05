---
title: "Cordova iOS 8.0.1 is now available!"
url: "https://cordova.apache.org/announcements/2026/03/12/cordova-ios-8.0.1.html"
date: "Thu, 12 Mar 2026 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that we have just released <code>Cordova iOS 8.0.1</code>! This is one of Cordova's supported platforms for building iOS applications.</p>

<p>This release contains fixes for several bugs that were reported against the 8.0.0 version.</p>

<ul>
  <li><a href="https://www.npmjs.com/package/cordova-ios">cordova-ios@8.0.1</a></li>
</ul>

<p><strong>To upgrade:</strong></p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>cordova platform remove ios
cordova platform add ios@8.0.1
</code></pre></div></div>

<p><strong>To install:</strong></p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>cordova platform add ios@8.0.1
</code></pre></div></div>

<h2>Release Highlights</h2>

<ul>
  <li>
    <p><strong>Fixed search paths for plugin libraries/frameworks</strong></p>

    <p>Plugins that included frameworks as embedded libraries were causing app builds to fail due to Xcode using the wrong path when trying to link the framework bundle. Xcode should now look for these frameworks at the correct path.</p>
  </li>
  <li>
    <p><strong>Fix for local file <code>/_app_file_/</code> URLs not loading</strong></p>

    <p>URLs returned by <code>window.WkWebView.convertFilePath()</code> and the File plugin's <code>FileEntry.getUrl()</code> were not being handled properly by the WebView to return file contents from the device filesystem. This should now work as expected, matching the behaviour from earlier cordova-ios versions.</p>
  </li>
  <li>
    <p><strong>Fix crash on cancelled WebView requests</strong></p>

    <p>When serving content from a custom scheme, if a request was started and cancelled before it finished loading, there was a chance the app could crash. We now ensure that scheme requests are properly closed when cancelled and avoid race conditions.</p>
  </li>
  <li>
    <p><strong>Ensure Swift package deployment targets are set</strong></p>

    <p>If a custom deployment target was set and a plugin relied on that deployment target, it was possible for Xcode to report errors due to the Swift package manager not reflecting that updated deployment target. We now propagate the <code>&lt;preference name="deployment-target"&gt;</code> value to the Package.swift file that references plugins.</p>
  </li>
  <li>
    <p><strong>Ensure consistent normalization of the app name</strong></p>

    <p>If an app name contained non-ASCII characters, Xcode could produce an app bundle that failed App Store validation checks. By ensuring the app product name is consistently normalized, apps should pass validation regardless of the characters in their name.</p>
  </li>
</ul>

<!--more-->
<h2>Changes include:</h2>

<p><strong>Fixes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-ios/pull/1618">GH-1618</a> fix(xcode): Fix library search paths for target</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1621">GH-1621</a> fix(xcode): Ensure we do NFD normalization on <code>PRODUCT_NAME</code></li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1616">GH-1616</a> fix(spm): Ensure the deployment target always gets set</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1606">GH-1606</a> fix(webview): Ensure scheme task is always finished</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1610">GH-1610</a> fix(scheme): Fix <code>/_app_file_/</code> URLs not working</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1612">GH-1612</a> fix(spm): Set deployment target in Package.swift</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1597">GH-1597</a> fix(spm): git-ignore Swift Package Manager build artifacts</li>
</ul>

<p><strong>Others:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-ios/pull/1614">GH-1614</a> doc(readme): improve badges</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1622">GH-1622</a> refactor(versions): Refactor version code for test reliability</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1619">GH-1619</a> chore(deps): Update to latest jasmine &amp; c8 versions</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1623">GH-1623</a> chore(ci): draft release</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1624">GH-1624</a> chore: cleanup license headers</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1625">GH-1625</a> chore: add DEVELOPMENT.md &amp; cleanup README.md</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1598">GH-1598</a> Add missing trailing new line</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1601">GH-1601</a> chore: Remove compileBitcode from export options</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1611">GH-1611</a> chore: set swift-tools-version to 5.9</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1599">GH-1599</a> chore(deps): bump lodash from 4.17.21 to 4.17.23</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1592">GH-1592</a> doc(readme): add minimum <strong>iOS</strong> version</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1591">GH-1591</a> doc(readme): add Link to <strong>iOS</strong> Platform Guide</li>
  <li><a href="https://github.com/apache/cordova-ios/pull/1588">GH-1588</a> chore: update release audit workflow &amp; license headers</li>
</ul>
