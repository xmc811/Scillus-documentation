---
title: "Installation"
draft: no
date: '2019-10-03'
lastmod: '2019-12-21T12:50:10Z'
weight: 10
---

Scillus is still undergoing active development. Please use the following code to install the development branch on GitHub:

```R
install.packages("devtools")
library(devtools)

install_github("xmc811/Scillus", ref = "development")
library(Scillus)
```

Note:

Errors may occur during the installation of dependency packages. Usually it can be solved by re-installing the relevant packages.

If you would like to check the source code on GitHub, don't forget switching to the development branch.
