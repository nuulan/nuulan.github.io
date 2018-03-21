---
layout: post
title:  "Carbonate: randomly-generated practice problems for organic chemistry"
date:   2013-01-31
categories: projects
hieroglyph: "&#x132B2;"
---


[**Carbonate**](http://orgo.mit.edu/) [currently down] creates interactive organic chemistry practice problems, both simple one-step quizzes or complicated multi-step synthesis problems. It is intended as a tool to help organic chemistry students study.

The website uses the Django web framework to connect a drag-and-drop frontend UI with a Python backend that extensively represents the logic for chemical reactions. It's capable of parsing molecules and applying reactions from [Unit 1 and Unit 2](http://orgo.mit.edu/orgo/reactions/) of [MIT 5.12](http://ocw.mit.edu/courses/chemistry/5-12-organic-chemistry-i-spring-2003/) (Organic Chemistry I). It uses the [OpenBabel](http://openbabel.org/wiki/Main_Page) chemistry library to render molecules, and can interconvert between its molecule format (Python objects) and [SMILES](http://www.daylight.com/dayhtml/doc/theory/theory.smiles.html) strings.

Built in collaboration with Felix Sun. Received the “MIT Utility Award” in [6.470](http://6.470.scripts.mit.edu/2013/), MIT's web programming competition.

[orgo.mit.edu](http://orgo.mit.edu/) [currently down] currently runs Carbonate 1.0; [**Carbonate 2.0**](https://github.com/csvoss/carbonate-simplified) has not yet been deployed. 

See the code on [GitHub](https://github.com/csvoss/carbonate).
