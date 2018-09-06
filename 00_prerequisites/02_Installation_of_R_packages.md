
# Installation of required R packages

The following R packages are required for the successful completion of the following workshop modules:
1. Gene Expression 
2. QTL Mapping 

## Gene Expression
In the gene expression module we will be undertaking a differential gene expression analysis. For this, we will make use of the [DESeq2]() R package. To install this package, copy and paste the commands below in your R console:

`source("https://bioconductor.org/biocLite.R")`
`biocLite("DESeq2")`


## QTL Mapping

QTL mapping workshop will require the installation of three R libraries:
1. [qtl2](https://kbroman.org/qtl2/)
2. [GGally](https://github.com/ggobi/ggally)
3. [ggplot2](https://ggplot2.tidyverse.org/)

Copy and paste the commands below in you R console:

`install.packages("qtl2", repos="http://rqtl.org/qtl2cran")`
 
`install.packages("ggplot2")`

`install.packages("GGally")`


