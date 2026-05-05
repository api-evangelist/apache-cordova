---
title: "Cordova Fetch 5.0.0 Released!"
url: "https://cordova.apache.org/announcements/2025/08/29/cordova-fetch-5.0.0.html"
date: "Fri, 29 Aug 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that <code>cordova-fetch@5.0.0</code> has been released. This is the library used behind-the-scenes of the Cordova tooling for fetching of Cordova platforms and plugins.</p>

<h2>Release Highlights</h2>

<p>The most notable changes in this major release were:</p>

<ul>
  <li>Updated the library's npm dependencies.</li>
  <li>Increased in the Node.js engine requirement to <code>&gt;=20.9.0</code>.</li>
</ul>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Breaking Changes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-fetch/pull/131">GH-131</a> chore(npm)!: bump <code>cordova-common@6.0.0</code></li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/125">GH-125</a> chore!: bump node requirement &amp; npm dependencies</li>
</ul>

<p><strong>Chores:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-fetch/pull/136">GH-136</a> chore(README): update badges</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/135">GH-135</a> chore: update &amp; add source code license headers</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/130">GH-130</a> chore: bump <code>@cordova/eslint-config</code></li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/127">GH-127</a> chore(coverage): Move from <code>nyc</code> to <code>c8</code> for code coverage</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/124">GH-124</a> chore(deps-dev): bump <code>brace-expansion</code> from 1.1.11 to 1.1.12</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/122">GH-122</a> chore(deps): bump <code>cross-spawn</code> from 7.0.3 to 7.0.6</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/120">GH-120</a> chore(deps): bump <code>micromatch</code> from 4.0.5 to 4.0.8</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/119">GH-119</a> chore(deps): bump <code>braces</code> from 3.0.2 to 3.0.3</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/116">GH-116</a> chore(deps): Update some dependencies, add Node 20 to CI</li>
</ul>

<p><strong>CI:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-fetch/pull/137">GH-137</a> ci: workflow updates</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/128">GH-128</a> ci(workflow): update release-audit &amp; license config</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/123">GH-123</a> ci: Add licence checker workflow</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/121">GH-121</a> ci: Fix dependabot code scanning errors</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/118">GH-118</a> ci: Set up CodeQL analysis</li>
  <li><a href="https://github.com/apache/cordova-fetch/pull/117">GH-117</a> ci: update codecov@v4 w/ token</li>
</ul>

<p><strong>Tests:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-fetch/pull/126">GH-126</a> test: drop <code>file-url</code></li>
</ul>
