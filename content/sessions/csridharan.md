+++
author = ["Brian Ketelsen"]
date = "2015-03-21T16:03:09-04:00"
linktitle = "Cindy Sridharan"
title = "Cindy Sridharan"
talk = "Building an Origin Cache for Images"
speakerimage = "/2016/img/speakers/cindy-sridharan.jpg"
speaker = "csridharan"
+++

At Imgix, our multitiered caching layer forms an important components of our real­time image processing and delivery service. This talk will shed light on what necessitated the system and the architecture, how several of the language’s inbuilt constructs, newer features (like the library introduced in 1.5 which enabled us to do our own dns resolutions that helped replace nginx‘s own resolver in the old architecture) well as the tooling were used to design, implement and test the cache filling, eviction and purging logic, and more interestingly, our experience ‘productionizing this’, tuning the system to handle disparate traffic patterns, evaluating performance pre and post production, the mistakes made, challenges faced and lessons learned building this.
