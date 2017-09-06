## Installing/Loading packages
Packages provide set of functions that can help you automate certain processes. To use them, first you need to install the package into your local computer and second to attach/load the package for use.

R packages are stored in repositories, from which uses can download and use. Three options are shown here. The central R repository is [CRAN](https://cran.r-project.org/). A biology-related central repository is [bioconductor](http://www.bioconductor.org). Packages can be also downloaded from [github](http://www.github.com) accounts of the different users. In each case you should use different approaches to download it. To install a package type: 
```
# install from CRAN
install.package("package_name", dependencies = TRUE)  # don't forget the ""

# install from bioconductor
## if 'https://' URLs are not supported use 'http://'
source("https://bioconductor.org/biocLite.R")
biocLite("package_name")  

# install from github
## first install devtools package and then download the package from github
install.packages("devtools")
devtools::install_github("username/repository_name", dependencies = TRUE)
```

After installing, to attach/load a certain package type:
```
library(package_name) # without the ""
```

[Back to Readme](https://github.com/tkostas/R-resources)