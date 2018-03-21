---
layout: post
title:  "Things Mimicking Other Things"
date:   2013-09-30
categories: projects
hieroglyph: "&#x131A4;"
---

[**Things Mimicking Other Things**](http://csvoss.scripts.mit.edu/thingsmimickingotherthings) is an interactive exploration of animals, camoflage, and mimicry.

It uses [Vivagraph.js](https://github.com/anvaka/VivaGraphJS) to draw an interactive, draggable graph. Although the page is static, it is updated from basic data using a Python script whenever I add new entries.

The hardest part was getting performance just right: small images need to be converted to thumbnails (which is done using [Python Image Library](http://www.pythonware.com/products/pil/)), and big images need to be pre-loaded in the background.

See the code on [GitHub](https://github.com/csvoss/thingsmimickingotherthings).
