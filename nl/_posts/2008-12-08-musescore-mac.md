---
layout: post
title: MuseScore voor Mac
lang: nl
lang-ref: musescore-mac
category: varia
tags: [varia, nederlands]
---

In 2008 gebruikte ik graag de [MuseScore](https://musescore.org) partituur-editor (pre-1.0), die toen enkel bestond op Linux en Windows. Ik was net naar Mac overgeschakeld om cross-platform softwareontwikkeling te kunnen doen, dus wou MuseScore ook op OSX. De meeste onderliggende libraries waren cross-platform, en het OSX subsysteem lijkt nogal op Linux, dus dat zou niet te moeilijk mogen zijn... Ik kon een eerste [prototype tonen in december 2008](https://musescore.org/en/blog/2008/12/04/mac-os-prototype-version).

Bleek dat er nogal wat eigenaardigheden zaten aan het compileren van C++ op Mac, waarbij vooral de problemen met het lettertype en de rendering erg moeilijk op te lossen waren. Met hulp van de andere MuseScore developers en een erg nuttige bugfix in het [Canorus](https://sourceforge.net/projects/canorus/) project (zij hadden hetzelfde lettertypeprobleem), kon ik in april 2009 de [eerste alpha versie](https://musescore.org/nl/node/1453) van MuseScore op OSX (10.4 of 10.5) bekendmaken.

Nadien namen andere projecten mijn tijd in beslag en ik heb sindsdien niet meer bijgedragen aan de MuseScore codebase. Ik ontmoet de developers echter nog altijd regelmatig op events zoals [FOSDEM](https://musescore.org/en/node/279421).
