+++
speakertitle="Engineer at Google"
author = ["Rick Hudson"]
date = "2015-04-14"
linktitle = "Rick Hudson"
title = "Rick Hudson"
speakerimage = "/images/speakers/rick-hudson.jpg"

+++
Go GC: Solving the Latency Problem

Long garbage collection (GC) pauses stand directly in the way of Go's growth. It is an important, and often times the only, technical reason practitioners give for not migrating to managed runtimes such as Go. If Go is to live up to its promise of providing a better place for developers it must eliminate long GC pauses. This talk presents and discusses the new 1.5 low latency concurrent GC. Motivations will be given, performance numbers will be presented, we will deep dive into some technical challenges, but more importantly we will discuss why this approach fits well with the Go language.

---

Richard L. Hudson (Rick) is best known for his work in memory management including the invention of the Train, Sapphire, and Mississippi Delta algorithms as well as GC stack maps which enabled garbage collection in statically typed languages like Java, C#, and Go. He has published papers on language runtimes, memory management, concurrency, synchronization, memory models and transactional memory. Rick is a member of Google's Go team where he is working on Go's GC and runtime issues.
