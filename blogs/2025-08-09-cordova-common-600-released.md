---
title: "Cordova Common 6.0.0 Released!"
url: "https://cordova.apache.org/announcements/2025/08/09/cordova-common-6.0.0.html"
date: "Sat, 09 Aug 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that <code>cordova-common@6.0.0</code> has been released. This is one of the libraries used behind-the-scenes by nearly all of the Cordova tooling and provides utilities for dealing with things like <code>config.xml</code> parsing.</p>

<h2>Release Highlights</h2>

<p>The most notable changes in this major release were:</p>

<ul>
  <li>Removal of <code>superspawn</code>, which also dropped the npm dependencies <code>q</code> and <code>cross-spawn</code>.</li>
  <li>Update to the <code>&lt;resource-file&gt;</code> directive to allow directories and their contents to be copied.</li>
  <li>Update to the <code>&lt;config-file&gt;</code> and <code>&lt;edit-config&gt;</code> directives to support finding unprefixed <code>Info.plist</code> files.</li>
  <li>Increase in the Node.js engine requirement to <code>&gt;=20.9.0</code>.</li>
</ul>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Breaking Changes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-common/pull/239">GH-239</a> feat!: change <code>resource-file</code> behavior to support directory contents</li>
  <li><a href="https://github.com/apache/cordova-common/pull/236">GH-236</a> feat!: remove <code>superspawn.js</code></li>
  <li><a href="https://github.com/apache/cordova-common/pull/231">GH-231</a> feat!: remove <code>superspawn</code> &amp; npm packages <code>q</code> &amp; <code>cross-spawn</code></li>
  <li><a href="https://github.com/apache/cordova-common/pull/235">GH-235</a> dep(npm)!: bump <code>@cordova/eslint-config@6.0.0</code></li>
  <li>Bumps <code>node &gt;=20.9.0</code></li>
  <li><a href="https://github.com/apache/cordova-common/pull/228">GH-228</a> chore!: bump <code>node &gt;=20.5.0</code> &amp; upgrade npm packages</li>
</ul>

<p><strong>Features:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-common/pull/212">GH-212</a> feat: Support finding an unprefixed <code>Info.plist</code> file</li>
</ul>

<p><strong>Chores:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-common/pull/240">GH-240</a> chore: update <code>package-lock.json</code></li>
  <li><a href="https://github.com/apache/cordova-common/pull/232">GH-232</a> chore(tests): Improve test coverage</li>
  <li><a href="https://github.com/apache/cordova-common/pull/229">GH-229</a> chore(coverage): Move from <code>nyc</code> to <code>c8</code> for code coverage</li>
  <li><a href="https://github.com/apache/cordova-common/pull/238">GH-238</a> dep(npm): update w/ rebuilt <code>package-lock.json</code></li>
  <li><a href="https://github.com/apache/cordova-common/pull/237">GH-237</a> refactor(bom): Bring <code>strip-bom</code> in as util</li>
</ul>

<p><strong>CI &amp; Refactoring:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-common/pull/234">GH-234</a> ci: use macos-15</li>
  <li><a href="https://github.com/apache/cordova-common/pull/233">GH-233</a> ci(workflow): update release-audit &amp; license config</li>
  <li><a href="https://github.com/apache/cordova-common/pull/230">GH-230</a> ci: add permissions block &amp; commit hash pinning of third-party actions</li>
</ul>
