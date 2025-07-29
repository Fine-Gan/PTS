# PTS
PTS: A Three-Dimensional Joint Optimization Method for Accelerating Multi-Job Distributed DNN Training
# Abstract
As DNN models and dataset sizes grow rapidly, communication bottlenecks in distributed training become critical, especially in multi-job scenarios where overlapping traffic peaks lead to congestion and long tail latencies. We propose PTS, a framework that jointly optimizes communication along three dimensions- time shift scheduling, congestion control, and gradient compression. By modeling periodic communication patterns and applying the Weierstrass theorem, we derive a closed form optimal solution. On a real GPU cluster, ATS outperforms Cassini, achieving up to 1.4× speedup in average iteration time and up to 2.4× reduction in 99th percentile latency.
# Purpose
The purpose of this project is to provide relevant implementation code from the paper [PTS: A Three-Dimensional Joint Optimization Method for Accelerating Multi-Job Distributed DNN Training].
# Statue
The paper is currently under review and the source code will be made available when the paper is accepted.
