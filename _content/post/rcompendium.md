---
date: "2021-04-17"
title: rcompendium
subtitle: Makes easier the creation of R package or research compendium
image: "https://raw.githubusercontent.com/FRBCesab/rcompendium/main/man/figures/hexsticker.png"
available:
  cran: "https://cran.r-project.org/package=rcompendium"
  github: "https://github.com/frbcesab/rcompendium"
  website: "https://frbcesab.github.io/rcompendium"
contact:
  name: Nicolas Casajus
  url: "https://www.fondationbiodiversite.fr/en/membre/nicolas-casajus"
summary: The aim of this package is to make easier the creation of R package or research compendium (i.e. a predefined files/folders structure) so that users can focus on the code instead of wasting time organizing files. A full ready-to-work structure is set up with some additional cool features.
tags:
- r-packages
- cran
- development
- compendium
- reproducibility
- git
- github
---

In the area of open science, making reproducible analyses is a strong prerequisite. But sometimes it is difficult 1) to find the good structure to organize files and 2) to set up the whole project. The aim of the package `rcompendium` is to make easier the creation of R package/research compendium (i.e. a predefined files/folders structure) so that users can focus on the code/analysis instead of wasting time organizing files.

A full ready-to-work structure will be set up with the following features:

- Initialization of the [GIT](https://git-scm.com/) version control.
- Creation of a minimal R package structure (`DESCRIPTION` and `NAMESPACE` files, and `R/` and `man/` folders).
- Creation of additional files (`LICENSE.md`, `inst/CITATION`, etc.).
- Creation of a *Get started* vignette in `vignettes/`.
- Setting the units tests process.
- Creation of a `README.Rmd` with HexSticker (template) and badges.
- Autocompletion of maintainer information.
- Creation of a GitHub repository.
- Configuration of GitHub Actions to automatically:
    - check and test package (`R CMD Check`);
    - report the code coverage (`covr`);
    - build and deploy website (`pkgdown`).

This package heavily relies on the R packages [`devtools`](https://devtools.r-lib.org) and
[`usethis`](https://usethis.r-lib.org) and follows recommendations made by [Hadley Wickham & Jenny Bryan](https://r-pkgs.org) and [Ben Marwick](https://peerj.com/preprints/3192/).
