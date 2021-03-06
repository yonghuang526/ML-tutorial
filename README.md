# ML-tutorial
UIHC machine learning tutorial

The 'doc' repository contains the 3 sessions Rmarkdown files.
If you open one of these files in Rstudio, you have the option to 'Knit' it and it will generate an HTML document containing R commands.

There is also a Shiny application (interactive), where you can upload your data set and apply some standard machine learning approaches.

Important: if you plan to run the Shiny application, you want to install the following R packages:
* shiny: interactive user interface running in R
* glmnet: generalized linear model with Elastic-Net implementation
* DT: render DataTable, better than Shiny default. Allows to color cells
* ggplot2: nice graphical tool
* RColorBrewer: nice color palette
* randomForest: package for learning ... random forest model
* LiblineaR: one of numerous SVM R packages

When all those packages are installed, you can open `server.R` in Rstudio and click on the 'Run App' button (top right green arrow).

TODO:

* The 'Classification' part is under development.
* Consider different performance measures if binary or multiclass classification is considered
* Include standard SVM kernels
