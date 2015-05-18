---
layout: project
title:  "Julia Port of Projective Dictionary Pair Learning"
date:   2015-05-18 19:18:53
author: QU Xiaofeng
categories:
- project
img: dpl.jpg
thumb: thumb02.jpg
carousel:
- dpl.png
client: Volunteer
website: https://github.com/quxiaofeng/ProjectiveDictionaryPairLearning.jl
---
#### Introduction
Discriminative dictionary learning (DL) has been widely studied in various pattern
classification problems. Most of the existing DL methods aim to learn a synthesis
dictionary to represent the input signal while enforcing the representation coef-
ficients and/or representation residual to be discriminative. However, the l_0 or
l_1-norm sparsity constraint on the representation coefficients adopted in most DL
methods makes the training and testing phases time consuming. We propose a new
discriminative DL framework, namely projective dictionary pair learning (DPL),
which learns a synthesis dictionary and an analysis dictionary jointly to achieve
the goal of signal representation and discrimination. Compared with conventional
DL methods, the proposed DPL method can not only greatly reduce the time
complexity in the training and testing phases, but also lead to very competitive
accuracies in a variety of visual classification tasks.
