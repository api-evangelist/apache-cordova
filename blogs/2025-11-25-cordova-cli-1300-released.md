---
title: "Cordova CLI 13.0.0 Released!"
url: "https://cordova.apache.org/announcements/2025/11/25/cordova-cli-13.0.0.html"
date: "Tue, 25 Nov 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that <code>cordova@13.0.0</code> has been released! This is the latest version of the Cordova command-line interface (CLI) used for creating and building Cordova apps.</p>

<ul>
  <li><a href="https://www.npmjs.com/package/cordova/v/13.0.0">cordova@13.0.0 on npm</a></li>
</ul>

<p><strong>To upgrade a global installation:</strong></p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>npm uninstall <span class="nt">-g</span> cordova
npm <span class="nb">install</span> <span class="nt">-g</span> cordova@latest
</code></pre></div></div>

<p>Note: If you are installing Cordova locally in a project (not globally), simply omit the <code>-g</code> flag.</p>

<h2>Release Highlights</h2>

<p>The most notable changes in this major release include:</p>

<ul>
  <li>Updated npm dependencies.</li>
  <li>Increased Node.js engine requirement to <code>&gt;=20.17.0 || &gt;=22.9.0</code>.</li>
  <li>Removed <code>telemetry</code>.</li>
</ul>

<p>One of the main dependencies that was updated is <strong>cordova-lib</strong>, which for provides the core CLI functionality for managing platforms and plugins, including adding and removing them. Among the breaking changes in this release, the <code>cordova serve</code> command has been removed.</p>

<p>We recommend checking out the following blog posts for updates on related packages that also apply to Cordova CLI:</p>

<ul>
  <li><a href="https://cordova.apache.org/announcements/2025/11/05/cordova-lib-13.0.0.html">Cordova Lib 13.0.0</a></li>
  <li><a href="https://cordova.apache.org/announcements/2025/10/22/cordova-create-6.0.0.html">Cordova Create 6.0.0</a></li>
  <li><a href="https://cordova.apache.org/announcements/2025/08/29/cordova-fetch-5.0.0.html">Cordova Fetch 5.0.0</a></li>
  <li><a href="https://cordova.apache.org/announcements/2025/08/29/cordova-app-hello-world-7.0.0.html">Cordova App Hello World 7.0.0</a></li>
  <li><a href="https://cordova.apache.org/announcements/2025/08/09/cordova-common-6.0.0.html">Cordova Common 6.0.0</a></li>
</ul>

<p>Please report any issues you find by following the <a href="https://github.com/apache/cordova#filing-a-bug">How to File a Bug</a> guide!</p>

<ul>
  <li><a href="https://github.com/apache/cordova-cli/issues">Cordova CLI - Issue Tracker</a></li>
  <li><a href="https://github.com/apache/cordova-lib/issues">Cordova Lib - Issue Tracker</a></li>
  <li><a href="https://github.com/apache/cordova-create/issues">Cordova Create - Issue Tracker</a></li>
  <li><a href="https://github.com/apache/cordova-fetch/issues">Cordova Fetch - Issue Tracker</a></li>
  <li><a href="https://github.com/apache/cordova-serve/issues">Cordova Serve - Issue Tracker</a></li>
  <li><a href="https://github.com/apache/cordova-common/issues">Cordova Common - Issue Tracker</a></li>
</ul>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Breaking Changes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-cli/pull/678">GH-678</a> feat!: bump dependencies &amp; node engine requirement</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/633">GH-633</a> feat!: remove telemetry feature</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/672">GH-672</a> chore(npm)!: bump various npm packages</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/666">GH-666</a> chore!: bump node requirement &amp; npm dependencies</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/642">GH-642</a> chore!: Prepare for next major</li>
</ul>

<p><strong>Fixes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-cli/pull/662">GH-662</a> fix: bump @babel/helpers</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/640">GH-640</a> fix: remove potential error when setting exit code</li>
</ul>

<p><strong>Others:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-cli/pull/679">GH-679</a> chore: update release audit workflow &amp; license headers</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/677">GH-677</a> chore(deps-dev): bump js-yaml from 4.1.0 to 4.1.1</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/676">GH-676</a> chore(deps): bump glob from 10.4.5 to 10.5.0</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/673">GH-673</a> chore: license headers</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/671">GH-671</a> chore(deps): bump tmp from 0.2.3 to 0.2.4</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/668">GH-668</a> chore(coverage): Move from nyc to c8 for code coverage</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/667">GH-667</a> chore(deps): bump on-headers and compression</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/665">GH-665</a> chore(deps-dev): bump brace-expansion from 1.1.11 to 1.1.12</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/658">GH-658</a> chore(deps): bump systeminformation from 5.22.11 to 5.23.8</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/657">GH-657</a> chore(deps): bump path-to-regexp and express</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/654">GH-654</a> chore(deps): bump cross-spawn from 7.0.3 to 7.0.6</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/655">GH-655</a> chore(ci): Add code scanning &amp; fix dependabot failures</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/646">GH-646</a> chore(deps): bump micromatch from 4.0.7 to 4.0.8</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/652">GH-652</a> chore(deps): bump cookie and express</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/643">GH-643</a> chore: Update dependencies</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/637">GH-637</a> chore(deps): bump express from 4.18.2 to 4.19.2</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/639">GH-639</a> chore(deps): bump tar from 6.2.0 to 6.2.1</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/641">GH-641</a> chore(deps): bump braces from 3.0.2 to 3.0.3</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/635">GH-635</a> chore(deps): bump ip from 2.0.0 to 2.0.1</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/631">GH-631</a> chore: Rolled dependencies to the latest non-breaking versions</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/670">GH-670</a> ci: various workflow improvements</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/669">GH-669</a> ci(workflow): update release-audit &amp; license config</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/656">GH-656</a> ci: use apache-rat-action@v1 (tag)</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/638">GH-638</a> ci: update codecov@v4 w/ token</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/636">GH-636</a> ci: update release audit workflow</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/630">GH-630</a> ci(gh-action): add Apache RAT &amp; package license checker workflow</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/554">GH-554</a> doc(create): update default values</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/428">GH-428</a> doc: update <code>README</code>.md</li>
  <li><a href="https://github.com/apache/cordova-cli/pull/616">GH-616</a> doc: update &amp; refactor cli reference</li>
</ul>
