---
title: "A Material Point Method for Nonlinearly Magnetized Materials"
collection: publications
permalink: /publication/2021-12-01-A-Material-Point-Method-for-Nonlinearly-Magnetized-Materials
excerpt: 'We propose a novel numerical scheme to simulate interactions between a magnetic field and nonlinearly magnetized objects immersed in it...'
date: 2021-12-01
venue: 'ACM Transactions on Graphics (TOG)'
paperurl: 'https://doi.org/10.1145/3478513.3480541'
citation: 'Yuchen Sun*, <b>Xingyu Ni</b>* (joint 1st authors), Bo Zhu, Bin Wang, and Baoquan Chen. 2021. A material point method for nonlinearly magnetized materials. <i>ACM Trans. Graph</i>. 40, 6, Article 205 (December 2021), 13 pages.'
---
## Abstract

We propose a novel numerical scheme to simulate interactions between a magnetic field and nonlinearly magnetized objects immersed in it. Under our nonlinear magnetization framework, the strength of magnetic forces is effectively saturated to produce stable simulations without requiring any hyper-parameter tuning. The mathematical model of our approach is based upon Langevin’s nonlinear theory of paramagnetism, which bridges microscopic structures and macroscopic equations after a statistical derivation. We devise a hybrid Eulerian-Lagrangian numerical approach to simulating this strongly nonlinear process by leveraging the discrete material points to transfer both material properties and the number density of magnetic micro-particles in the simulation domain. The magnetic equations can then be built and solved efficiently on a background Cartesian grid, followed by a finite difference method to incorporate magnetic forces. The multi-scale coupling can be processed naturally by employing the established particle-grid interpolation schemes in a conventional MLS-MPM framework. We demonstrate the efficacy of our approach with a host of simulation examples governed by magnetic-mechanical coupling effects, ranging from magnetic deformable bodies to magnetic viscous fluids with nonlinear elastic constitutive laws.

## Links

\[[Paper](http://Univstar.github.io/files/siga21magnetic.pdf)\]

\[[Video (YouTube)](https://youtu.be/2zqJ1wvverA)\] \[[Video (bilibili)](https://www.bilibili.com/video/BV1a44y1e76n)\] 
