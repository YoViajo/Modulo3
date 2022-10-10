---
title: "Módulo 3"
author: "Eric Armijo"
date: "2022-10-10"
output: 
  html_document:
    keep_md: true 
    fig_width: 6
    fig_height: 6
    toc: yes
    toc_float: true
    code_folding: hide
---



## R Markdown {#nexsteps .emphasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

### Gráfico del conjunto de datos Cars


```r
plot(cars)
```

![](html_document_files/figure-html/cars-1.png)<!-- -->

## Including Plots

You can also embed plots, for example:

### Gráfico del conjunto de datos Pressure

![](html_document_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## Una lista corta

* manzanas
* plátanos
* naranjas

## Una ecuación simple

$$ Y = \beta_0 + \beta_1*X $$


