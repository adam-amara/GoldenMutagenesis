README
================
Chris Ulpinnis & Pascal Püllmann
2018-10-11

<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis-CI Build Status](https://travis-ci.org/ipb-halle/GoldenMutagenesis.svg?branch=master)](https://travis-ci.org/ipb-halle/GoldenMutagenesis)

# GoldenMutagenesis

The Golden Gate cloning technique has been proven to be a highly
efficient toolbox for a variety of cloning setups. Based on its modular
concept it is particularly suitable for the use in multiple-site
mutagenesis approaches. In this technical note we developed a protocol
termed Golden Mutagenesis for the rapid, easy, reliable and cheap
formation of mutagenesis libraries. One to five positions could be
altered in parallel or simultaneously within two days. To facilitate the
implementation of this technique, this R-library has been developed for
the automated primer design and the graphical evaluation of sequencing
results to determine the quality of the library.  
This library is currently still under development and will be enhanced
by an R shiny web-application.

## Installation

You can install GoldenMutagenesis from github with:

``` r
# install.packages("devtools")
devtools::install_github("ipb-halle/GoldenMutagenesis")
```

## Example

To start with this library we recommend to have a look on our
vignettes\!  
[Point
Mutagenesis](https://github.com/ipb-halle/GoldenMutagenesis/blob/master/vignettes/Point_Mutagenesis.md)  
[Multiple Site Directed Mutagenesis -
Example1](https://github.com/ipb-halle/GoldenMutagenesis/blob/master/vignettes/MSD.md)  
[Multiple Site Directed Mutagenesis -
Example2](https://github.com/ipb-halle/GoldenMutagenesis/blob/master/vignettes/MSD2.md)  
[Multiple Site Directed Mutagenesis -
Example3](https://github.com/ipb-halle/GoldenMutagenesis/blob/master/vignettes/MSD3.md)  
[Quick Quality
Control](https://github.com/ipb-halle/GoldenMutagenesis/blob/master/vignettes/QQC.md)  

## Interactive Example

## You can try out our interactive user notebooks for Mutagenesis:

### Multiple Site Directed

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ipb-halle/GoldenMutagenesis/binder?filepath=notebooks%2FMSD_USER.ipynb)

### Single Point
#### Notebook
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ipb-halle/GoldenMutagenesis/binder?filepath=notebooks%2FSPM_USER.ipynb)
##### Webinterface alpha
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/culpinnis/gmshinyalpha/master?urlpath=shiny)
### Domestication only

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ipb-halle/GoldenMutagenesis/binder?filepath=notebooks%2FDomesticate_only_USER.ipynb)
