+++
speakertitle="Engineer at Google"
author = ["Rick Hudson"]
date = "2015-04-14"
linktitle = "Go GC: Solving the Latency Problem"
title = "Go GC: Solving the Latency Problem"
speakerimage = ["/images/speakers/rick-hudson.jpg"]
speakerpage=["/speakers/rick-hudson"]
+++

Long garbage collection (GC) pauses stand directly in the way of Go's growth. It is an important, and often times the only, technical reason practitioners give for not migrating to managed runtimes such as Go. If Go is to live up to its promise of providing a better place for developers it must eliminate long GC pauses. This talk presents and discusses the new 1.5 low latency concurrent GC. Motivations will be given, performance numbers will be presented, we will deep dive into some technical challenges, but more importantly we will discuss why this approach fits well with the Go language.

