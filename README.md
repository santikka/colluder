# Full Law Identification under Missing Data with Categorical Variables: Replication Materials

The Finnish Bachelor's Graduate Survey 2016 data is available at: <https://urn.fi/urn:nbn:fi:fsd:T-FSD3185>

First, ensure that the required data file (`daF3185_eng.csv`) exists in the same directory as the main RMarkdown document (`replication.Rmd`). Install the required packages by running:
```
install.packages(c("data.table", "Deriv", "kableExtra", "knitr", "R6causal", "rmarkdown"))
```
Next, ensure that your working directory is set to the same directory as the RMarkdown document and the data (e.g., via the `setwd()` command). Finally, simply knit the document into a .pdf file to reproduce the results. You can do this e.g., from RStudio or directly from R by running:
```
rmarkdown::render("replication.Rmd", "pdf_document")
```
This reproduces all of the tables in the main paper.
