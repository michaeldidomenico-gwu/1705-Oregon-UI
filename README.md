# Oregon Unemployment Insurance
Encouraging active planning to speed return to employment among the unemployed.

# Workflow

The `datasetup.Rmd` file creates the working file(s) --- one at the individual level and one at the level of the office. 

The `analysis.Rmd` file does the analysis.

To create the html output that we link to below one might do the following (after downloading data and putting it in `Data/`)

```
Rscript -e "library(rmarkdown);render('datasetup.Rmd')"
Rscript -e "library(rmarkdown);render('analysis.Rmd')"
```

Here is the [HTML Version of these Results](https://htmlpreview.github.io/?https://github.com/sbstusa/oregonui/blob/master/analysis.html)

