+++
author = "Sergio Méndez"
title = "Serverless Functions at the Edge with Knative and K3s - Sergio Méndez, USAC University, KnativeConNA, Detroit"
date = "2022-11-10"
description = ""
tags = [
    "kubernetes",
    "cncf",
    "cloudnative",
    "serverless",
    "edgecomputing",
    "knative"
]
+++
Running code at edge could be challenging when running your programs using low power consumption devices. These devices often use ARM processors that match the low power consumption edge environments and have limited CPU and RAM to run your code. This talk is going to cover the basics of running serverless functions at the edge using Knative deployed at the edge in a light weight Kubernetes K3s. The demo of this session will show how to install Knative at the edge in a single node K3s cluster in a Raspberry Pi device as our edge device using an ARM processor. It also explained how this configuration can run your code in an efficient way managing endpoints for your code and concurrency using the internal envoy based proxy Contour that runs at the edge. At the end of the session we explain the pros and cons of running serverless functions at the edge and the challenges for development when using ARM devices, and how Knative with K3s can solve common edge computing use cases like smart farms, smart cities, etc.

[Event Link](https://sched.co/1AGbN) | [Photo](https://twitter.com/ClowderSpace/status/1584603806372753410) | [Slides](https://b.link/KnativeConNAK3s2022)
<!--more-->
### Video

{{< youtube _MFAg1IeOG8 >}}

<br>
### Tweet

{{< twitter user="salaboy" id="1584595018886811649" >}}

<br>