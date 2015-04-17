+++
speakertitle = "Software engineer at Restless Bandit"
author = ["Sarah Adams"]
date = "2015-04-14"
linktitle = "Code Generation For The Sake Of Consistency"
title = "Code Generation For The Sake Of Consistency"
speakerimage = ["/images/speakers/sarah-adams.jpg"]
speakerpage=["/speakers/sarah-adams"]
+++

Maintaining consistency within a growing project is a challenge. I have struggled with my company's Go web API as it has grown over the past two years, trying to find a nice solution to this intra-project consistency problem without resorting to a large-scale framework.

In my mind, there are three general layers to project consistency:
- consistency in implementation among similar bits of code
- consistency in black-box behavior among similar endpoints or commands
- consistency between actual behavior and documented behavior (documentation accuracy)

This talk will outline how I have leveraged small-scale code and documentation generator tools for each of the three layers outlined above, specifically for the sake of consistency in a growing Go application without using a large-scale framework.

