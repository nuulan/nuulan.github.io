---
layout: post
title:  "Fun with Time Travel: implementing retroactive data structures"
date:   2014-05-01
categories: projects
hieroglyph: "&#x13040;"
---

For my final project in [6.851: Advanced Data Structures](https://courses.csail.mit.edu/6.851/), I [**implemented algorithms**](https://github.com/csvoss/retroactive) for retroactive data structures using Python.

[Retroactive data structures](http://en.wikipedia.org/wiki/Retroactive_data_structures) are data structures in which operations and queries are allowed to be made in the past, updating the data structures as if history itself had been rewritten.

For example, consider a list datastructure in which we're allowed to insert or remove operations from the past:

{% highlight python %}
>>> y = FullyRetroactive([1,2,3])
>>> y.insertAgo(appendOne, tminus=0)
>>> y.insertAgo(appendSix, tminus=0) ##This one should come last
>>> y.insertAgo(appendTen, tminus=2) ##This one should come first
>>> y.query()
[1, 2, 3, 10, 1, 6]   ## The current state of the data structure
>>> y.query(1)
[1, 2, 3, 10, 1]
>>> y.query(2)
[1, 2, 3, 10]
>>> y.query(3)
[1, 2, 3]   ## The state of the data structure way back in the past
{% endhighlight %}

Read more about it at [GitHub](https://github.com/csvoss/retroactive).
