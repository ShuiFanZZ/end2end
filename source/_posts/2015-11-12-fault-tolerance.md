---
layout: post
title: "Distributed System"
date: 2015-11-12 19:42:24
comments: false
description: "Key-value server with fault tolerance."
keywords: "Distributed System, Fault Tolerance, C"
category: welcome
image: /images/fault.jpg
tags:
- welcome
---

In this project, we implemented a simple distributed database with fault tolerance. Each server has 1 replica: A->B->C->...->A. Each server handles key-value queries from clients. Heart beat messages are sent regularly to check if all the servers are alive. When a server is down and detected, a server revival process will be triggered.

[Code](https://gitfront.io/r/ShuiFanZZ/cBGYQREjz3hJ/fault-tolerance/)