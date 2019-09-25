---
layout:     post
title:      "Optimization of Convolution Layer in Neuro Network of MXNet for GPU"
date:       2017-12-15 12:00:00
author:     "Susie"
tags:
    - C
    - Parallel Programming
    - GPU
    - System Programming
---


<div>
<a href="https://github.com/Susieeeeeeeeee/Applied-Parallel-Programming-Project" style="color:lightblue;">Github Source</a>
<ul>
  <li>Converted convolution into matrix multiplication by unrolling input features and filters</li>
  <li>Implemented tiling method for memory reuse, and double buffering to reduce synchronization overhead using CUDA</li>
  <li>Classified 10000 images in 60ms with the speedup of 80 times compared to baseline</li>
</ul>
</div>
