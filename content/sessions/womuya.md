+++
author = ["Brian Ketelsen"]
date = "2015-03-21T16:03:09-04:00"
linktitle = "Wisdom Omuya"
title = "Wisdom Omuya"
talk = "Go Vendoring Deconstructed"
speakerimage = "/2016/img/speakers/wisdom-omuya.jpg"
speaker = "womuya"
sessionscheduled = "July 11th"
sessiontime = "11:40am - 12:10pm"
+++

Vendoring has been a major struggle for Go developers. Many of us have had to vendor packages to build dependences into our projects - usually by performing ugly rewrites of import paths.

Go 1.5 introduced the GO15VENDOREXPERIMENT environment variable which simplifies this process and avoids those rewrites.

In this talk, I'll demonstrate why and how we switched to the vendor experiment at MongoDB, and I'll give practical advice on how you can use this feature in your projects.
