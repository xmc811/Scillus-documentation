---
title: Home
---

[<img src="https://github.com/xmc811/Scillus/blob/master/Scillus.png" style="max-width:15%;min-width:40px;float:right;" alt="Scillus" />](https://github.com/xmc811/Scillus)

# Scillus

### Seurat wrapper for enhanced processing and visualization of scRNA-seq data

This is a minimal example to show how you can render arbitrary Rmd files on a website based on [**blogdown**](https://github.com/rstudio/blogdown). The key is that you add an R script `build.R` under the `R/` directory (in which you can use one line of code `blogdown::build_dir('static')`), and put your Rmd files under the `static/` directory. See the brief documentation in the [**blogdown** book](https://bookdown.org/yihui/blogdown/static-files.html).

It does not matter which output formats your Rmd files are generated to; `build_dir()` will call `rmarkdown::render()` to render them. On this example website, I provided two examples (R packages [**xaringan**](https://github.com/yihui/xaringan) and [**bookdown**](https://github.com/rstudio/bookdown) are required):

- [Installation of Scillus](vignettes/installation.html).
- [Preparation of configuration files](vignettes/configuration.html).
