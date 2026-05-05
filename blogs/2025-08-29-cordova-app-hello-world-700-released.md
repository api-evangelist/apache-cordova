---
title: "Cordova App Hello World 7.0.0 Released!"
url: "https://cordova.apache.org/announcements/2025/08/29/cordova-app-hello-world-7.0.0.html"
date: "Fri, 29 Aug 2025 00:00:00 +0000"
author: ""
feed_url: "https://cordova.apache.org/feed"
---
<p>We are happy to announce that <code>cordova-app-hello-world@7.0.0</code> has been released. This is the default app template used when creating a new Cordova App project though Cordova CLI.</p>

<h2>Release Highlights</h2>

<p>The most notable changes in this release were:</p>

<ul>
  <li>Setting the <code>body</code> element's <code>box-sizing</code> to <code>border-box</code> to avoid the <code>safe-area-inset</code> padding that caused scrolling issues</li>
  <li>Disabled the <code>overscroll</code> behavior of the root element to remove rubber-banding effects.</li>
  <li>Used modern, unprefixed CSS directives.</li>
  <li>Updated default template's package ID to <code>org.apache.cordova.hellocordova</code>.</li>
</ul>

<!--more-->
<h1>Changes include:</h1>

<p><strong>Fixes:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-app-hello-world/pull/98">GH-98</a> fix(css): Fix extra padding causing scrolling</li>
</ul>

<p><strong>Chores:</strong></p>

<ul>
  <li><a href="https://github.com/apache/cordova-app-hello-world/pull/99">GH-99</a> chore: updated defaults, license headers &amp; added release audit workflow</li>
  <li><a href="https://github.com/apache/cordova-app-hello-world/pull/78">GH-78</a> chore: correct <code>access</code> inline comment</li>
</ul>
