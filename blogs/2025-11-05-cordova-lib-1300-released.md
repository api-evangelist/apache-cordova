---
title: "Cordova Lib 13.0.0 Released!"
url: "https://cordova.apache.org/announcements/2025/11/05/cordova-lib-13.0.0.html"
date: "Wed, 05 Nov 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that <code>cordova-lib@13.0.0</code> has been released. This is the main library behind the Cordova CLI, handling project and build operations.</p>

<ul>
  <li><a href="https://www.npmjs.com/package/cordova-lib/v/13.0.0">cordova-lib@13.0.0</a></li>
</ul>

<h2>Release Highlights</h2>

<p>The most notable changes in this major release are:</p>

<ul>
  <li>Updated the library's npm dependencies.</li>
  <li>Increased the Node.js engine requirement to <code>&gt;=20.17.0 || &gt;=22.9.0</code>.</li>
  <li>Dropped support for the <code>cordova serve</code> command.</li>
  <li>Dropped support for the <code>create plugin</code> command.</li>
  <li>Added support for listing available emulators with the <code>cordova emulate &lt;platform&gt; --list</code> command.</li>
</ul>

<p>Please report any issues you find by following the <a href="https://github.com/apache/cordova#filing-a-bug">How to File a Bug</a> guide!</p>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Breaking Changes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-lib/pull/964">GH-964</a> chore(npm)!: bump <code>write-file-atomic@7.0.0</code></li>
  <li><a href="https://github.com/apache/cordova-lib/pull/961">GH-961</a> chore!: update dependencies &amp; node requirement</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/957">GH-957</a> feat!: remove <code>cordova serve</code> command</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/955">GH-955</a> chore(npm)!: bump various packages</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/953">GH-953</a> feat(plugman)!: remove <code>create plugin</code> support</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/949">GH-949</a> chore!: bump node requirement &amp; npm dependencies</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/958">GH-958</a> chore!: remove deprecated platform data</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/959">GH-959</a> chore!: remove unused templates</li>
</ul>

<p><strong>Features:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-lib/pull/952">GH-952</a> feat: replace <code>dep-graph</code> dependency w/ custom class</li>
</ul>

<p><strong>Fixes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-lib/pull/944">GH-944</a> fix(emulator): Support listing emulators with <code>--list</code></li>
</ul>

<p><strong>Chores:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-lib/pull/963">GH-963</a> chore: update <code>package-lock.json</code></li>
  <li><a href="https://github.com/apache/cordova-lib/pull/960">GH-960</a> chore: various updates to the root files</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/956">GH-956</a> chore(npm): bump <code>@cordova/eslint-config@6.0.0</code></li>
  <li><a href="https://github.com/apache/cordova-lib/pull/946">GH-946</a> chore(deps-dev): bump <code>brace-expansion</code> from 1.1.11 to 1.1.12</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/939">GH-939</a> chore(deps): bump <code>path-to-regexp</code> and express</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/937">GH-937</a> chore(deps): bump <code>cross-spawn</code> from 7.0.3 to 7.0.6</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/938">GH-938</a> chore(ci): Fix failing dependabot PRs</li>
</ul>

<p><strong>CI &amp; Others:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-lib/pull/954">GH-954</a> ci: various workflow improvements</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/950">GH-950</a> ci(workflow): update release-audit &amp; license config</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/945">GH-945</a> ci: Add node 22 and 24 to CI testing matrix</li>
  <li><a href="https://github.com/apache/cordova-lib/pull/941">GH-941</a> Keep final new line in <code>package.json</code></li>
  <li><a href="https://github.com/apache/cordova-lib/pull/942">GH-942</a> Persist relative paths on disk</li>
</ul>
