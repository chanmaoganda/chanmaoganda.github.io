---
title: mathor-cup-2023-D
date: 2024-05-05
tags: 
    -1 math model 
    -2 mathor cup
mathjax: true
---

# mathor-cup-2023-D

## Problem
#### we have some trucks and some excavators, assume `truck` kinds and `excavator` kinds are given, we only need to find a solution to make the most profit.

## Solution
### This is the target function:
$$ 
max \left[160 \times (\sum\limits_{i}{V_{i}\times R_{i}\times 20 \times(x_{i} - 0.5{z_{i}})}-7 \times (\sum\limits_{i}C_{i}^{oil}\times x_{i} +\sum\limits_{j}C_{j}^{oil}\times n_{j}))- [\sum\limits_{i}(C_{i}^{ren}+C_{i}^{wei})\times x_{i} + \sum\limits_{j}(C_{j}^{ren}+C_{i}^{wei})\times n_{j}]\right]\times 60
$$

### here are the constraints:
* $\sum\limits_{i}C_{i}^{cai}\times x_{i}\le 2400$
* $n_{j}+z_{i}=m_{i}\times x_{i}, \forall j\in J, \forall i \in I$
