---
authors: 
  - admin
  
featured: true
date: ""
tags: 'test'
title: 'Portfolio test post'
The code below dmeonstatrates two colour palettes in the
[viridis](https://github.com/sjmgarnier/viridis) package. Each plot
displays a contour map of the Maunga Whau volcano in Auckland, New
Zealand.

Viridis colours
---------------

    image(volcano, col = viridis(200))

![](index_files/figure-markdown_strict/unnamed-chunk-2-1.png)

Magma colours
-------------

    image(volcano, col=viridis(200, option = "A"))

![](index_files/figure-markdown_strict/unnamed-chunk-3-1.png)
---