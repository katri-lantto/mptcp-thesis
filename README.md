# MPTCP Thesis

This repository contains a patch for the work done for the thesis titled *Exploring Performance Balancing in a Meshed Satellite MultiWAN Using MPTCP*. The thesis was performed in a kernel with some work which was not publicly available. The patch in this repo was created on the [Linux Yocto v5.15.60 tag](https://git.yoctoproject.org/linux-yocto/tag/?h=v5.15.60d), and adds multiple Scheduling and Congestion Control Algorithms which can be used through modprobe.

The code in this project was mainly adapted from the deprecated [Multipath TCP repo](https://github.com/multipath-tcp/mptcp) which contained some algorithms.