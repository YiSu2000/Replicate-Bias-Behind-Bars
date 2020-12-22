# Replicate-Bias-Behind-Bars

This repo contains code and data for Replicating 'Bias Behind Bars' under Bayesian setting, created by Yi Su. The purpose is to create a report that replicates the results of "Bias Behind Bars". The sections of this repo are: inputs and outputs.

Inputs contain data that are unchanged from their original. Since they are not to be shared publicly, the inputs folder has been hidden from Github.

We used dataset from Correctional Service of Canada, this was requested by Tom Cordoso, the author of "Bias Behind Bars". 
The article and the methodology instructions provided by Tom Cordoso, and the CSC website are included below: 

-[Tom Cardoso, Bias Behind Bars: A Globe Investigation Finds a Prison System Stacked against Black and Indigenous Inmates, The Globe and Mail, 2020, www.theglobeandmail.com/canada/article-investigation-racial-bias-in-canadian-prison-risk-assessments/.]

-[Tom Cardoso, How we did it: How The Globe uncovered systemic bias in prisoners' risk assessments}, The Globe and Mail, 2020, https://www.theglobeandmail.com/canada/article-investigation-racial-bias-in-canadian-prisons-methodology/]

-[Correctional Service of Canada, Commissioner's Directives, 2018, www.csc-scc.gc.ca/acts-and-regulations/005006-0001-en.shtml]

-[The CSC dataset is distributed by Tom Cardoso at: www.theglobeandmail.com/files/editorial/News/n w-na-risk-1023/The_Globe_and_Mail_CSC_OMS_2012-2018_20201022235635.zip]

Outputs contains the codes and pdf file of the report and supporting materials.

- Fin._BiasBehindBars_Su.Rmd and Fin._BiasBehindBars_Su.pdf, these are the codes for the report and the output report itself
- references.bib, this is all the references used in the report, written in biblatex format
- model1f, 1m, 2f, 2m.rds, there are the resultant models using `brms`.
- Fin._BiasBehindBars_Su.log is the log file automatically created when knitting the rmarkdown file.

The Replicate-Bias-Behind-Bars.Rproj is the R project where all the work of the report occurred, this is included for reproducibility.
