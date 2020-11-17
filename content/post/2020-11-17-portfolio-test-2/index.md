---
title: 'Portfolio test #2'
author: Clara A. Stafford
date: '2020-11-17'
categories:
  - portfolio
  - TidyTuesday
tags:
  - test
summary: This is a second test of integrating R code and R output in an Md file
lastmod: '2020-11-17T00:04:58-05:00'
featured: yes
image:
  caption: ''
  focal_point: ''
  preview_only: no
---

The code below demonstrates two colour palettes in the
[viridis](https://github.com/sjmgarnier/viridis) package. Each plot
displays a contour map of the Magma Whau volcano in Auckland, NZ.

Viridis colours
---------------

    image(volcano, col = viridis(200))

![](index_files/figure-markdown_strict/unnamed-chunk-2-1.png)

Mgma colours
------------

    image(volcano, col = viridis(200, option = "A"))

![](index_files/figure-markdown_strict/unnamed-chunk-3-1.png)
