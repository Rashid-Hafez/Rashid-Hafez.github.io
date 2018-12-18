---
layout: post
title: Implementing Systematic Proceedures for Very Large Matrix Operations on the GPU Using CUDA
image: /img/CUDA.png
tags: [Dissertation, CUDA, GPU, Parallel, NVIDIA]
---

It is well known that the device is used because of its parallel computational power and speed, it is a usefull device to reduce the workload on the CPU for many stages of the graphics pipeline, such as rasterization. GPU's are often used nowadays for purposes other than for purely rendering applications, this is known as General Purpose Computing, and these devices are often refered to as GPGPUs (general-purpose GPU). However, there exists such one large limitation with using such a powerful device, that is the limitation on memory storage available on the GPU. 

My dissertation aims to tackle the issue of using the GPU to operate on data larger than the available memory on the GPU. This final year project involves many hurdles to tackle such as, familiarising myself with NVIDIA's architecture and general purpose computing language for the GPU (CUDA), and critically analysing past research papers similar to my topic, and implementing an efficient systematic method to dynamically store data larger than the GPUs memory onto the GPU.

You can view my full project [here]({{ site.url }}/img/Report.pdf)
