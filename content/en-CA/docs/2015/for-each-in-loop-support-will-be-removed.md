---
title: "`for-each-in` loop support will be removed"
date: "2015-10-25T23:45:00-07:00"
categories: ["javascript"]
tags: []
versions: ["future"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=824289"
      title: "Bug 824289 - Hide \"for each\" from web content regardless of the JS version"
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1293205"
      title: "Bug 1293205 - Warn about non-standard for-each regardless of JS version number"
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1293305"
      title: "Bug 1293305 - Disable non-standard for-each on nightly-only"
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1083470"
      title: "Bug 1083470 - Remove SpiderMonkey support for E4X for-each"
---
The support for the [`for each...in`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for_each...in) statement, [deprecated since Firefox 37](https://www.fxsitecompat.com/en-CA/docs/2015/for-each-in-loops-are-now-deprecated/) will be removed in the near future because it's not a part of the ECMAScript 2015 (ES6) spec. Use the standard [`for...of`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of) statement instead.

**Update**: Firefox 51 and later will warn about `for-each-in` in the console regardless of the JavaScript version.

**Update 2**: The `for-each-in` loop support has been disabled on the Firefox Nightly channel since Firefox 53.
