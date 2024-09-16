---
title: "End-to-end Kernel Learning via Generative Random Fourier Features"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2023-01-01
venue: 'Pattern Recognition'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Random Fourier features (RFFs) provide a promising way for kernel learning in a spectral case. Current RFFs-based kernel learning methods usually work in a two-stage way. In the first-stage process, learning an optimal feature map is often formulated as a target alignment problem, which aims to align the learned kernel with a pre-defined target kernel (usually the ideal kernel). In the second-stage process, a linear learner is conducted with respect to the mapped random features. Nevertheless, the pre-defined kernel in target alignment is not necessarily optimal for the generalization of the linear learner. Instead, in this paper, we consider a one-stage process that incorporates the kernel learning and linear learner into a unifying framework. To be specific, a generative network via RFFs is devised to implicitly learn the kernel, followed by a linear classifier parameterized as a full-connected layer. Then the generative network and the classifier are jointly trained by solving an empirical risk minimization (ERM) problem to reach a one-stage solution. This end-to-end scheme naturally allows deeper features, in correspondence to a multi-layer structure, and shows superior generalization performance over the classical two-stage, RFFs-based methods in real-world classification tasks. Moreover, inspired by the randomized resampling mechanism of the proposed method, its enhanced adversarial robustness is investigated and experimentally verified.