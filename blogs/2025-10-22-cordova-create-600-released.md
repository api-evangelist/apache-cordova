---
title: "Cordova Create 6.0.0 Released!"
url: "https://cordova.apache.org/announcements/2025/10/22/cordova-create-6.0.0.html"
date: "Wed, 22 Oct 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that <code>cordova-create@6.0.0</code> has been released. This is the library used behind-the-scenes of the Cordova tooling for creating a Cordova project.</p>

<h2>Release Highlights</h2>

<p>The most notable changes in this major release were:</p>

<ul>
  <li>Updated the library's npm dependencies.</li>
  <li>Increased in the Node.js engine requirement to <code>&gt;=20.17.0 || &gt;=22.9.0</code>.</li>
</ul>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Breaking Changes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-create/pull/99">GH-99</a> chore!: upgrade <code>@cordova/eslint-config@6.0.0</code></li>
  <li><a href="https://github.com/apache/cordova-create/pull/98">GH-98</a> chore!: bump package dependencies
    <ul>
      <li><code>cordova-app-hello-world@7.0.0</code></li>
      <li><code>cordova-common@6.0.0</code></li>
      <li><code>cordova-fetch5.0.0</code></li>
      <li><code>tmp@0.2.5</code></li>
      <li><code>rewire@9.0.1</code></li>
      <li><code>jasmine@5.10.0</code></li>
      <li><code>npm-package-arg@13.0.0</code></li>
      <li>Bumped node engine requirement <code>&gt;=20.17.0 || &gt;=22.9.0</code></li>
    </ul>
  </li>
  <li><a href="https://github.com/apache/cordova-create/pull/94">GH-94</a> chore!: bump node requirement &amp; npm dependencies</li>
</ul>

<p><strong>Chores &amp; CI:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-create/pull/103">GH-103</a> chore: add <code>.npmrc</code> &amp; update ignore files</li>
  <li><a href="https://github.com/apache/cordova-create/pull/102">GH-102</a> chore: replace <code>nyc</code> with <code>c8</code></li>
  <li><a href="https://github.com/apache/cordova-create/pull/101">GH-101</a> chore: update project defaults</li>
  <li><a href="https://github.com/apache/cordova-create/pull/100">GH-100</a> chore: ci and license updates</li>
  <li><a href="https://github.com/apache/cordova-create/pull/97">GH-97</a> chore(deps): bump <code>tmp</code> from 0.2.3 to 0.2.4</li>
  <li><a href="https://github.com/apache/cordova-create/pull/96">GH-96</a> ci: use <code>macos-15</code> instead of <code>macos-latest</code></li>
  <li><a href="https://github.com/apache/cordova-create/pull/93">GH-93</a> ci(workflow): add release-audit &amp; license config</li>
  <li><a href="https://github.com/apache/cordova-create/pull/92">GH-92</a> chore(deps-dev): bump <code>brace-expansion</code> from 1.1.11 to 1.1.12</li>
  <li><a href="https://github.com/apache/cordova-create/pull/91">GH-91</a> chore(deps): bump <code>cross-spawn</code> from 7.0.3 to 7.0.6</li>
  <li><a href="https://github.com/apache/cordova-create/pull/90">GH-90</a> chore(deps): bump <code>micromatch</code> from 4.0.5 to 4.0.8</li>
  <li><a href="https://github.com/apache/cordova-create/pull/88">GH-88</a> chore(deps): bump <code>braces</code> from 3.0.2 to 3.0.3</li>
  <li><a href="https://github.com/apache/cordova-create/pull/86">GH-86</a> chore(deps): Update npm deps, add Node 20 to CI</li>
  <li><a href="https://github.com/apache/cordova-create/pull/87">GH-87</a> ci: update <code>codecov@v4</code> w/ token</li>
</ul>
