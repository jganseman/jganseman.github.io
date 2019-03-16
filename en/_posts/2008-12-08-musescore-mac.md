---
layout: post
title: MuseScore for Mac
lang: en
lang-ref: musescore-mac
category: varia
tags: [varia, english]
---

In 2008 I was pretty fond of [MuseScore](https://musescore.org) (pre-1.0), which existed mainly on Linux and Windows. I had just switched to Mac to develop other cross-platform software, so I wanted MuseScore on OSX as well. Most of the underlying libraries were cross-platform, and the OSX subsystem is pretty similar to Linux, so it should not be too difficult... I could show a [prototype version in December 2008](https://musescore.org/en/blog/2008/12/04/mac-os-prototype-version).

It turned out the peculiarities of compiling C++ on mac, and some really dodgy issues with the font and typesetting system, were very hard to solve. With the help of the other MuseScore developers and one particularly useful bugfix in the [Canorus](https://sourceforge.net/projects/canorus/) project (they had the same font problem), in April 2009 I published the [first alpha version](https://musescore.org/nl/node/1453) of MuseScore on OSX (10.4 or 10.5).

I moved on to other projects and have not contributed to the MuseScore codebase since, but still regularly meet up with the core developers at events like [FOSDEM](https://musescore.org/en/node/279421).
