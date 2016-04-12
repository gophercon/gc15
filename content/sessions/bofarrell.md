+++
author = ["Brian Ketelsen"]
date = "2015-03-21T16:03:09-04:00"
linktitle = "Bill O'Farrell"
title = "Bill O'Farrell"
talk = "Porting Go to the IBM z Architecture"
subtitle = "A Community Event Hosted By GopherAcademy"
speakerimage = "/2016/img/speakers/bill-ofarrell.jpg"
speaker = "bofarrell"
+++

At the IBM Linux on z Systems Open Source Ecosystem team, we have ported the Go language tooling (compiler, assembler, linker) to the Linux on z platform.

This tutorial will cover both the process we followed in doing so, some of the challenges we faced, and some of the performance hiccups and opportunities we encountered along the way.

The challenges included bootstrapping a compiler and runtime themselves written in the target language, designing a strategy for relocation, and finding ways to exploit z architecture strengths.
