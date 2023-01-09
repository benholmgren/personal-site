---
title: Discrete Morse Theory
layout: post
post-image: "https://benholmgren.github.io/personal-site/assets/images/gradient3.png"
description: Discrete Morse theory.
tags:
- discrete 
- Morse
- theory
---

Discrete Morse theory is the extension of classical Morse theory on smooth manifolds to the discrete setting. It can be deeply promising, though it is not a silver bullet, in broad applications throughout topological data analysis.


> ### Linear Time Methods to Compute Discrete Morse Functions

I am currently leading a paper establishing the first improvements since 2004 on the 
computation of discrete Morse functions for two-manifolds, which we accomplish in
linear time. We also provide a very slick gradient descent heuristic for realistic
data in higher dimensions. Joint with my outstanding mentors in Montana: Brittany 
Fasy, Brad McCoy, David Millman, and Binhai Zhu. The plan is to submit this in 
February to ICALP, 2023. I also implemented this algorithm in C++: please inquire
if you have interest in the implementation.

> Full preprint scheduled to be released here on 1/10/2022

[Linear Time Computation of Discrete Morse Functions Over Two Manifolds (Preprint)](../assets/ICALP2023.pdf)

> ### CCCG 2020: If You Must Choose Among Your Children, Pick the Right One

Brittany Fasy, Brad McCoy, David Millman, and I published a paper in CCCG 2020, titled
[If You Must Choose Among Your Children, Pick the Right One](../../assets/cccg20.pdf)

Abstract: Given a simplicial complex K and an injective function f from the vertices of K to R, we consider algorithms that extend f to a discrete Morse function on K.
We show that an algorithm of King, Knudson and Mramor can be described on the directed Hasse diagram of K.
Our description has a faster runtime for high dimensional data with no increase in space.

[[Slides]](../assets/cccg20-slides.pdf) [[Talk]](https://www.youtube.com/watch?v=kHpD-J4EzI8&t=607s)

[Arxiv](https://arxiv.org/abs/2103.13882)

> ### NCUR 2021 Poster on Computing Discrete Morse Functions Using the Hasse Diagram.

Title: 'Generating a Discrete Morse Function in Near Linear Time'

Abstract: Persistent homology has emerged as a powerful series of techniques for data analysis, and can be greatly enhanced by discrete Morse theory. We attempt to increase the viability of discrete Morse theory in such a setting by generating discrete Morse functions with greater efficiency. That is, given a simplicial complex K and an injective function f from the vertices of K to the real numbers, we consider algorithms that generate a discrete Morse function on K which results from extending f. We show that an algorithm of King, Knudson and Mramor can be described on the directed Hasse diagram of K. Our description has a faster runtime for high dimensional data with no increase in space. We also propose an additional problem related to generating discrete Morse functions on dynamic data.

[Poster](../assets/ncur21.pdf)

> ### DMT Applications in Neuroscience

For a final project in my Advanced Algorithm topics course in Fall 2020, Ryan Hansen and I
outlined an equivalent Morse theory framework to categorize neurons based on their morphologies
as is done via radial filtrations by Kathryn Hess et. al. We don't provide any time complexity
improvements, but as DMT improves this becomes increasingly possible. Plus, applying DMT to
things is just a whole bunch of fun.

[[Talk]](https://www.youtube.com/watch?v=ml7zRu7SsTI&t=2s)


> ### Nifty Poking Video

As a collaborative project between students in the fields of design and computational geometry, Brad McCoy, Marco Huot, and I made a video to illustrate some of the motivations for discrete Morse theory.

[[Video](https://vimeo.com/393067859)] [[Paper](../assets/socg-video.pdf)]
