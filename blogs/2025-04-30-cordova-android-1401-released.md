---
title: "Cordova Android 14.0.1 Released!"
url: "https://cordova.apache.org/announcements/2025/04/30/cordova-android-14.0.1.html"
date: "Wed, 30 Apr 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that we have just released <code>Cordova Android 14.0.1</code>! This is one of Cordova's supported platforms for building Android applications.</p>

<ul>
  <li><a href="https://www.npmjs.com/package/cordova-android">cordova-android@14.0.1</a></li>
</ul>

<p><strong>To upgrade:</strong></p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>cordova platform remove android
cordova platform add android@14.0.1
</code></pre></div></div>

<p><strong>To install:</strong></p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>cordova platform add android@14.0.1
</code></pre></div></div>

<h2>Release Highlights</h2>

<h3>Fixes</h3>

<ul>
  <li><strong>Fetching Gradle Path for Windows</strong></li>
</ul>

<p>Resolved an issue in Windows environments where projects containing spaces in their paths could not be built due to changes in how the Gradle path was fetched.</p>

<ul>
  <li><strong>Setting Gradle's java.home</strong></li>
</ul>

<p>Resolved an issue where the user-defined environment variable <code>JAVA_HOME</code> or <code>CORDOVA_JAVA_HOME</code> was not being used to set the <code>java.home</code> property for the Gradle Wrapper.</p>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Fixes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-android/pull/1795">GH-1795</a> fix: configure gradle <code>java.home</code></li>
  <li><a href="https://github.com/apache/cordova-android/pull/1793">GH-1793</a> fix(windows): get gradle path with <code>which</code> command</li>
</ul>
