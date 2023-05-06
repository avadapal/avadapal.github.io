---
title: "Duoram: A Bandwidth-Efficient Distributed ORAM for 2- and 3-Party Computation"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2015-10-01
venue: '32nd USENIX Security Symposium'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>32nd USENIX Security Symposium</i>. 1(3).'
---
We design, analyze, and implement Duoram, a fast and bandwidth-efficient distributed ORAM protocol suitable for secure 2- and 3-party computation settings. Following Doerner and shelat's Floram construction (CCS 2017), Duoram leverages (2,2)-distributed point functions (DPFs) to represent PIR and PIR-writing queries compactly—but with a host of innovations that yield massive asymptotic reductions in communication cost and notable speedups in practice, even for modestly sized instances. Specifically, Duoram introduces a novel method for evaluating dot products of certain secret-shared vectors using communication that is only logarithmic in the vector length. As a result, for memories with  addressable locations, Duoram can perform a sequence of  arbitrarily interleaved reads and writes using just  words of communication, compared with Floram's  words. Moreover, most of this work can occur during a data-independent preprocessing phase, leaving just  words of online communication cost for the sequence—i.e., a constant online communication cost per memory access.

[Download paper here](http://academicpages.github.io/files/paper3.pdf)

Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>32nd USENIX Security Symposium</i>. 1(3).