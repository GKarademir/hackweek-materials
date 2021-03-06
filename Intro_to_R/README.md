# Intro to R for astronomy

You can run the content in RStudio via binder. Just click the badge below to start it up.

RStudio: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ADACS-Australia/hackweek-materials/master?urlpath=rstudio)

This session includes slides (made using R markdown) and tutorials. The tutorials are a selection of the primers developed by RStudio for rstudio.cloud. All credits go to them.

You can find them all on github: https://github.com/rstudio-education/primers or by visiting https://rstudio.cloud/

---

## Requirements

You will need R (the programming language) and preferably RStudio (an IDE for R) installed.
- Go to [CRAN](https://cran.r-project.org/index.html), the Comprehensive R Archive Network to downlaod R.
- You can download the RStudio IDE [here](https://rstudio.com/products/rstudio/download/#download).
- You can also follow this online tutorial: https://learnr-examples.shinyapps.io/ex-setup-r/ 

The packages we will use throughout the tutorial are:
- tidyverse
- devtools
- learnr
- xaringan
- gapminder
additional:
- Rfits
- Rwcs

To install these open RStudio and type the following in the panel called 'Console':
```R
install.packages("tidyverse")
install.packages("devtools")
install.packages("learnr")
install.packages("xaringan")
install.packages("gapminder")
```

To install the additional packages run:
```R
library(devtools)
install_github("asgr/Rwcs")
install_github("asgr/Rfits")
```
