---
layout: post
title:  "Visual Traceroute: mapping packets"
date:   2013-04-30
categories: projects
hieroglyph: "&#x1329D;"
---

[**Traceroute**](http://csvoss.scripts.mit.edu/traceroute) is a tool for visually tracing packets through the Internet, from MIT's servers to any website.

It uses `traceroute` to fetch IP addresses, maps those IP addresses to coordinates using [ipinfo.io](http://ipinfo.io/), and plots those coordinates with the [Google Maps API](https://developers.google.com/maps/).

This was inspired by a class I took in spring 2013: our class designed an exhibit about the Internet, [*Net Works*](http://web.mit.edu/museum/exhibitions/samplingmit/networks/), for the MIT Museum.

See the code on [GitHub](https://github.com/csvoss/traceroute).
