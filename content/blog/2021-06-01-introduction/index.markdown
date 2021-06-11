---
title: "Introduction"
subtitle: "Aqui esta el subtitle"
excerpt: "Aqui posarem algun text així que estigui bé"
date: 2021-06-01
author: "Jordi Martínez Blanch"
draft: false
images:
series:
tags: 
  - buhh
categories:
  - modeling
  - IntlCoop
layout: single
bibliography: [../../../static/bib/one.bib]
link-citations: true
---

## Some penguins to start

This is the first entry in my brand new blog. Many ideas are stored in my head on how to organize the information. At the end this blog is just a way to organize my own ideas on several topics I will be glad to know if this liked to you, so please feel free to give any feedback in the contact section down there below [Leblanc](#ref-Leblanc2004) ([2004](#ref-Leblanc2004)).

The main idea is that this blog complements with more explanations in a funny and relaxed way each of the points in my thesis, relating to each article I write, a kind of supplementary part of each article relating them all.

Lo del spoonfull series que apareix al blog podria fer-se per cada un dels grans temes de la tesi, en base al llibre bookdown que estem preparat:

-   directives: I will continuously refer to many of the European directives and International reports on … .
-   Pests
-   Pesticides
-   Monitoring programs
-   Chemometrics
-   Tot lo del software a sac
-   Fer tota la relacio amb els SDGs i ICCC reports, sobretot des del punt de vista de dades i bbdd.
-   Git
-   links a sac de videos de youtube i tal.
-   

I per que no, escriure tb sobre temes more advanced issues like AOP, chemical mixtures… amb totes les referencies als articles i llibres que he anat llegint.

Aquest blog és el lloc on aniré linkant cada un dels milers de links que tinc de cada un dels temes, per donar-los un context a cada un d’ells.

``` r
library(tidyverse)
```

    ## -- Attaching packages --------------------------------------- tidyverse 1.3.1 --

    ## v ggplot2 3.3.3     v purrr   0.3.4
    ## v tibble  3.1.2     v dplyr   1.0.6
    ## v tidyr   1.1.3     v stringr 1.4.0
    ## v readr   1.4.0     v forcats 0.5.1

    ## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
library(palmerpenguins)
```

``` r
ggplot(data = penguins, 
       aes(x = flipper_length_mm)) +
  geom_histogram(aes(fill = species), 
                 alpha = 0.5, 
                 position = "identity") +
  scale_fill_manual(values = c("darkorange",
                               "darkorchid",
                               "cyan4"))
```

    ## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.

    ## Warning: Removed 2 rows containing non-finite values (stat_bin).

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />

Mes

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-Leblanc2004" class="csl-entry">

Leblanc, Gerald. 2004. “A Textbook of Modern Toxicology.” In, edited by Ernest Hodgson, Third, 463–78. John Wiley & Sons, Inc. <https://doi.org/10.1002/0471646776.ch26>.

</div>

</div>
