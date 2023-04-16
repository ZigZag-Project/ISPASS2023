---
title: "Tutorial on the ZigZag project at ISPASS 2023"
layout: splash
permalink: /tutorial/
header:
  overlay_color: "#FFF"
  overlay_filter: "0.5"
  overlay_image: /assets/images/leuven3.jpg
excerpt: "Hardware Architecture-Mapping Design Space Exploration for Deep Learning Accelerators"
---


## Overview

We're hosting a hands-on tutorial on the ZigZag project at [ISPASS 2023](https://ispass.org/ispass2023/){:target="_blank"} in Raleigh, North Carolina.

This tutorial will take place on Sunday April 23rd from 8 AM - 12 PM.

## What is the ZigZag project?
Building efficient embedded deep learning (DL) systems requires a tight co-design between DNN algorithms, hardware, and algorithm-to-hardware scheduling, a.k.a. dataflow or mapping. Different hardware architectures (single-core or multi-core accelerators) are being designed, supporting many different scheduling possibilities, for different optimizing targets (energy,latency, memory footprint). However, owing to the large joint design space, finding an optimal solution through RTL simulation or physical implementation becomes infeasible. To tackle this problem, a unified high-level DL accelerator design space exploration (DSE) framework infrastructure, called ZigZag, is proposed. 

[ZigZag](https://github.com/ZigZag-Project/zigzag){:target="_blank"} targets rapid DSE for DNN accelerator platforms supporting an broad set of hardware architectures and workload scheduling scenarios beyond other existing frameworks. 

[Stream](https://github.com/ZigZag-Project/stream){:target="_blank"} is an extension of ZigZag capable of modeling multi-core DNN acceleration employing fine-grained layer-fused processing.

## What will you learn in this tutorial?

This tutorial will introduce the unified DSE framework infrastructure and demonstrate the capabilities of ZigZag and Stream by guiding participants through several DSE experiments step-by-step. By the end of the tutorial, participants will have a complete view of the DL accelerator and scheduling design space and will have gained enough knowledge to deploy the open-source frameworks as their own personal customized DSE tool.

## Tutorial Contents

| Time                | Content                                                                                                 |
| ------------------- | ------------------------------------------------------------------------------------------------------- |
| 8.30 AM - 8.50 AM   | Introduction of the ZigZag project                                                                      |
| 8.50 AM - 9.30 AM   | Assessing the hardware performance of running a DNN on a single-core accelerator with fixed mappings    |
| 9.30 AM - 10.00 AM  | Optimizing mapping performance of a single-core accelerator with built-in automatic mapping exploration |
| 10.00 AM - 10.20 AM | Break                                                                                                   |
| 10.30 AM - 11.00 AM | Understanding & customizing the hardware architecture definition for other dataflows                    |
| 11.00 AM - 11.45 AM | Expanding the hardware to multi-core architectures with layer-fused processing using Stream             |
| 11.45 AM - 12.00 PM | Concluding remarks                                                                                      |

## Tutorial Organizers

| People                                                                                  |
| --------------------------------------------------------------------------------------- |
| [Arne Symons](https://micas.esat.kuleuven.be/team/00123840){:target="_blank"}           |
| [Linyan Mei](https://micas.esat.kuleuven.be/team/00110246){:target="_blank"}            |
| [Dr. Guilherme Paim](https://gppaim.wordpress.com/){:target="_blank"}                   |
| [Prof. Marian Verhelst](https://micas.esat.kuleuven.be/team/00043529){:target="_blank"} |

[![](https://user-images.githubusercontent.com/84473288/232055045-33fe65f3-ba45-450c-ae32-72bc383af6d6.svg)](http://micas.be)

