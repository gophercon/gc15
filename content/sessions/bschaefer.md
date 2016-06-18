+++
author = ["Brian Ketelsen"]
date = "2015-03-21T16:03:09-04:00"
linktitle = "Bernerd Schaefer"
title = "Bernerd Schaefer"
talk = "Go Without the Operating System"
speakerimage = "/2016/img/speakers/bernerd-schaefer.jpg"
speaker = "bschaefer"
sessionscheduled = "July 12th"
sessiontime = "10:10am - 10:40am"
+++

Go lets you to compile your program into stand-alone binaries which can be safely shared across systems without worrying about a missing dependency.

But there's one thing even a stand-alone executable depends on: the operating system. What if you could remove that dependency, too?

AtmanOS is a project built to explore that question.

It allows you to compile ordinary Go programs and run them on cloud providers like Amazon's EC2, without a traditional operating system.

Let's explore how it works, how to use it, and some considerations for putting it into production.
