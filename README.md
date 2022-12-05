# Causal Analysis of Hotel Booking Cancellations

#### Please install the required python packages

```
pip install > requirements.txt
```

### The causalNex library requires R and R tools 

[R for windows 10]( https://cran.r-project.org/bin/windows/base/)
[R tools for windows 10](https://cran.r-project.org/bin/windows/Rtools/rtools42/rtools.html )

###R packages

..1.pcalg
..2.devtools
..3.BiocManager
..4.RCIT [github_repository_RCIT](https://github.com/Diviyan-Kalainathan/RCIT)
..5.Sparsebn (dependencies --> sparsebnUtils,ccdrAlgorithm,discretedcAlgorithm)

###Installation command for R packages

```
(install.packages(‘package_name’,lib=’R_library_folder_path’,repos=NULL)
```

### Installation command for sparsebn R package
[Link for Sparsebn package](http://cran.nexr.com/web/packages/sparsebn/index.html)

```
install.packages('sparsebn_0.1.2.zip', lib='C:/Program Files/R/R-4.2.2/library',repos = NULL)
```

###BiocManager Packages

..1.graph
..2.RBGL
..3.Rgraphviz

### Installation command for BiocManager

```
BiocManager::install("package_name")
```
