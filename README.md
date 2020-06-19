# Smartphone apps for the treatment of mental disorders: Data, analysis and computational environment

R Markdown notebook for the paper ["Smartphone apps for the treatment of mental disorders: a systematic review"](https://mhealth.jmir.org/)

> Miralles I, Granell C, Díaz-Sanahuja L, Van Woensel W, Bretón-López J, Mira A, Castilla D, Casteleyn S.
> Smartphone apps for the treatment of mental disorders: a systematic review.
> Submitted to JMIR mHealth and uHealth
> DOI: 10.2196/14897


[![](https://img.shields.io/badge/JMU-http%3A%2F%2Fdoi.org%2F10.2196%2F14897-yellow.svg)](https://doi.org/10.2196/14897)


Complementing the published article, we have created a [dashboard](https://rpubs.com/cgranell/jmu2020) to allow readers to interactively explore the review results. 


This repository is archived on Zenodo:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3609267.svg)](https://doi.org/10.5281/zenodo.3609267)

## Reproduce Online

Click the "Binder" button below to open the notebook on [binder.org](https://mybinder.org/).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cgranell/apps-mental-disorders-jmir/master?urlpath=rstudio)

In the RStudio page, open the file `analysis.Rmd`, the _main analysis file_. Then select "Knit > Knit to HTML" to render the document, which includes the complete analysis workflow, and display it in your browser. 

Alternatively, click on the file  `analysis.html`, the results of the analysis, and select `View in Web Browser` to display it. 

## Reproduce locally

Open the main analysis file `analysis.Rmd` with RStudio. Then select "Knit > Knit to HTML" to render the document. If you have errors rendering it, try running each chunk to locate the problem.

The Markdown document does not include code to install required packages. Run the code in the file `install.R` to install all dependencies.

## Reproduce locally with Docker (more on this soon)


## Files in this repository

 - `analysis.Rmd`: R Markdown document with the code to conduct the analysis and create the figures and tables of the paper.
 - `analysis.html`: HTML rendering of the analysis document.
 - `Dockerfile`: A recipe for the computational environment using [Docker](https://en.wikipedia.org/wiki/Docker_(software)).
 - `install.R`: R script file executed during creation of the Docker image to install required dependencies.

`data` folder: 
 - `all_data.rda`: Data items extracted from the surveyed papers (rda format).
 - `all_data.csv`: Data items extracted from the surveyed papers (csv forma).

`figs` folder:
 - output figures 

## License

The documents in this repository are licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

All contained code is licensed under the [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/).

The data used is licensed under a [Open Data Commons Attribution License](https://opendatacommons.org/licenses/by/).