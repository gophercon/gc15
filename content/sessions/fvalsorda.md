+++
author = ["Brian Ketelsen"]
date = "2015-03-21T16:03:09-04:00"
linktitle = "Filippo Valsorda"
title = "Filippo Valsorda"
talk = "cgo: Safely Taming the Beast"
speakerimage = "/2016/img/speakers/filippo-valsorda.jpg"
speaker = "fvalsorda"
sessionscheduled = "July 12th"
sessiontime = "02:00pm - 02:50pm"
+++

cgo is a powerful tool, but using it right becomes subtle when memory starts to be shared between C and Go.

Thankfully since Go 1.6 the rules to follow are clear and the cgo behavior well defined.

In this talk we will look at cgo's capabilities and functioning, understand the issues related to memory management and garbage collection, and learn to develop safely around them to build bindings, but also static binaries and even C libraries.
