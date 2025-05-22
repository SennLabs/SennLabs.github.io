---
date: 2025-12-21
title: Android Compute
slug: AndroidCompute
categories:
  - Programming
  - Project
tags:
  - Android
  - ClusterCompute
  - HPC
#hide: [toc, tags]
publish: true
comments: true
---



<!-- more -->

## Computer Clusters vs Grids
### Cluster
A Cluster is a group of computers that are generally treated as a single system
This system works together together with each node set to perform the same task, controlled and scheduled by software. 



Generally these computers are located physically close to each other and are connected via LAN
Because of the local connection, these computers can have frequent communication with each other and/or the master node
Clusters can be used to allow for high availability and/or load balencing
Due to the high interconnect speeds, Distrobuted File systems can be implimented

The "Beowolf" cluster is an popular form of a cluster
With the drop in price of low power SBC, Small clusters have increased in popularity

### Grid
Grid Computing allows for distrobuted computation, Often implimented over the world via the internet.
Each Node is given a different task to complete.
Due to the spacing, design and available network speeds, Grid Computing is implimented where nodes do not need to communicate with each other.

Grid Systems also can impliment cycle-scavenging, this can allow for machines to run the calculations in the background or while idle - See HTCondor
Volunteer Computing projects have made large use of these systems