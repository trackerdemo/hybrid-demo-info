---
layout: default
title: Hybrid Demo
description: Hybrid demo tests the integration of websites which use btt.js tag into Native apps that are using the native Android or iOS SDKs. In that case the session that is used by the native apps should also be passed on to the website so that on the dashboard we can see both in the same session.
---

## Inspecting

Inspecting a webview is very important while development/testing in order to debug a website to check it's network, dom, run some js, etc. It can be a little hard to debug a website running in a webview as it doesn't provide an inbuilt inspecting panel. Follow the steps below to inspect a website running in a webview:

- Android : [Remote Debugging](https://developer.chrome.com/docs/devtools/remote-debugging/webviews)
- iOS : [Enabling the Inspection of Web Content in Apps](https://webkit.org/blog/13936/enabling-the-inspection-of-web-content-in-apps/)
