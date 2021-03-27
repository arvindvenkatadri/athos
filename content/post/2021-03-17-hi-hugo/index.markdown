---
title: Hi Hugo
author: 'Arvind Venkatadri'
date: '2021-03-17'
slug: hi-hugo
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: 'r Sys.Date()'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

Testing with a demo post using blogdown + Hugo!


```r
library(tidyverse)
```

```
## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.0 ──
```

```
## ✓ ggplot2 3.3.3     ✓ purrr   0.3.4
## ✓ tibble  3.1.0     ✓ dplyr   1.0.5
## ✓ tidyr   1.1.3     ✓ stringr 1.4.0
## ✓ readr   1.4.0     ✓ forcats 0.5.1
```

```
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```

```r
summary(diamonds)
```

```
##      carat              cut        color        clarity          depth     
##  Min.   :0.200   Fair     : 1610   D: 6775   SI1    :13065   Min.   :43.0  
##  1st Qu.:0.400   Good     : 4906   E: 9797   VS2    :12258   1st Qu.:61.0  
##  Median :0.700   Very Good:12082   F: 9542   SI2    : 9194   Median :61.8  
##  Mean   :0.798   Premium  :13791   G:11292   VS1    : 8171   Mean   :61.7  
##  3rd Qu.:1.040   Ideal    :21551   H: 8304   VVS2   : 5066   3rd Qu.:62.5  
##  Max.   :5.010                     I: 5422   VVS1   : 3655   Max.   :79.0  
##                                    J: 2808   (Other): 2531                 
##      table          price             x               y               z        
##  Min.   :43.0   Min.   :  326   Min.   : 0.00   Min.   : 0.00   Min.   : 0.00  
##  1st Qu.:56.0   1st Qu.:  950   1st Qu.: 4.71   1st Qu.: 4.72   1st Qu.: 2.91  
##  Median :57.0   Median : 2401   Median : 5.70   Median : 5.71   Median : 3.53  
##  Mean   :57.5   Mean   : 3933   Mean   : 5.73   Mean   : 5.74   Mean   : 3.54  
##  3rd Qu.:59.0   3rd Qu.: 5324   3rd Qu.: 6.54   3rd Qu.: 6.54   3rd Qu.: 4.04  
##  Max.   :95.0   Max.   :18823   Max.   :10.74   Max.   :58.90   Max.   :31.80  
## 
```


```
## `geom_smooth()` using formula 'y ~ x'
```

```
## Warning: Removed 2 rows containing non-finite values (stat_smooth).
```

```
## Warning: Removed 2 rows containing missing values (geom_point).
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-1.png" width="672" />

