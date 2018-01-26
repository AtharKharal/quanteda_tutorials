---
title: "Install packages"
weight: 10
draft: false
---

## Install R Studio

**quanteda** runs solely on [base R](https://cran.r-project.org/), but [R Studio](https://www.rstudio.com/products/rstudio/download/) makes it easy to write your code and inspect your data.

## Install quanteda

First, you need to have **quanteda** installed.  You can do this from inside RStudio, from the Tools... Install Packages menu, or simply using

```r
install.packages("quanteda")
```

If you are feeling adventurous, you can install the latest build of **quanteda** from its [GitHub code page](https://github.com/quanteda/quanteda).

Note that on **Windows platforms**, it is also recommended that you install the [RTools suite](https://cran.r-project.org/bin/windows/Rtools/), and for **OS X**, that you install [XCode](https://itunes.apple.com/gb/app/xcode/id497799835?mt=12) from the App Store.


## Install other packages

We will use the **readtext** package to read in different types of text data in this tutorials. Again, you can do this from inside RStudio, from the Tools... Install Packages menu, or simply using


```r
install.packages("readtext")
```

We will also use extra dataset in tutorials that are available in **quanteda.corpora***


```r
install.packages("devtools")
devtools::install_github("quanteda/quanteda.corpora")
```

## Extra packages

This tutorials do not cover syntactical analysis, but you should install **spacyr** to perfrom part-of-speech tagging, entity recognition, and dependency parsing. It provides interface to the spaCy library and works well with **quanteda**. Note that you need to have Python installed to use the **spacyr** package. See the [package description](https://github.com/quanteda/spacyr/blob/master/README.md) for more information.


```r
install.packages("spacyr")
```
