---
title: "Installation"
draft: no
date: '2019-10-03'
output:
  html_document:
    self_contained: no
  pdf_document: default
lastmod: '2019-12-21T12:50:10Z'
weight: 10
---

Please use the following code to install and load the package:

```R
install.packages("devtools")
library(devtools)

install_github("xmc811/Scillus", ref = "development")
library(Scillus)
```

Note:

Errors may occur during the installation of dependency packages. Usually it can be solved by re-installing the relevant packages.
