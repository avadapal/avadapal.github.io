---
title: "Duoram: A Bandwidth-Efficient Distributed ORAM for 2- and 3-Party Computation"
author: "Adithya Vadapalli, Ryan Henry, Ian Goldberg"
collection: publications
permalink: /publication/2023-10-01-paper-title-number-3
excerpt: ' '
date: 2023-10-01
venue: '32nd USENIX Security Symposium'
---
We design, analyze, and implement Duoram, a fast and bandwidth-efficient distributed ORAM protocol suitable for secure 2- and 3-party computation settings. Following Doerner and shelat's Floram construction (CCS 2017), Duoram leverages (2,2)-distributed point functions (DPFs) to represent PIR and PIR-writing queries compactly—but with a host of innovations that yield massive asymptotic reductions in communication cost and notable speedups in practice, even for modestly sized instances. Specifically, Duoram introduces a novel method for evaluating dot products of certain secret-shared vectors using communication that is only logarithmic in the vector length. As a result, for memories with  addressable locations, Duoram can perform a sequence of  arbitrarily interleaved reads and writes using just  words of communication, compared with Floram's  words. Moreover, most of this work can occur during a data-independent preprocessing phase, leaving just  words of online communication cost for the sequence—i.e., a constant online communication cost per memory access.

[Download paper here](http://academicpages.github.io/files/paper4-duoram.pdf)
