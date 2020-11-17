---
title: 'Portfolio test #3'
author: Clara A. Stafford
date: '2020-11-17'
slug: []
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2020-11-17T00:39:08-05:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---



The code below demonstrates two colour palettes in the [viridis](https://github.com/sjmgarnier/viridis) package. Each plot displays a contour map of the Magma Whau volcano in Auckland, NZ.

## Viridis colours


```r
image(volcano, col = viridis(200))
```

![](index_files/figure-html/unnamed-chunk-2-1.png)

## Magma colours


```r
image(volcano, col = viridis(200, option = "A"))
```


![](index_files/figure-html/unnamed-chunk-3-1.png)