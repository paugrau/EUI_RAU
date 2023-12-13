# EUI's Research Analytics Unit

Some potentially useful resources:

## Reproductibility
* https://www.biostat.wisc.edu/~kbroman/presentations/steps2rr.pdf
* https://egap.org/resource/10-things-to-know-about-project-workflow/

## Data management

* https://cghlewis.com/blog/data_mgmt_resources/
* https://cghlewis.com/blog/data_clean_02/
* Essential resource to think about how to organize data in speadsheets and why: [(Broman & Woo, 2017)](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989)

## Data cleaning
* https://kbroman.org/Talk_DataCleaning2023/data_cleaning.pdf

### R packages

* https://cran.r-project.org/web/packages/janitor/vignettes/janitor.html

## Data visualization

* https://www.data-to-viz.com
* https://r-graph-gallery.com

### Maps

* https://cengel.github.io/R-spatial/mapping.html
* https://r-spatial.org/r/2018/10/25/ggplot2-sf.html

## Research Design

Two great books on Causal Inference. The Mixtape has an emphasis on the maths beyond it, while The Effect might be more hands-on. Both provide snippets of code for the analyses.
* https://theeffectbook.net
* https://mixtape.scunning.com

To delve more into the specifics of different methods, the Mixtape Sessions are an incredible resource. Provides [slides and code](https://github.com/Mixtape-Sessions/).
* https://www.mixtapesessions.io/sessions/

### Difference in differences

* Repository of recent advances in DiD methods, focus on its application: https://asjadnaqvi.github.io/DiD/

## Data analysis
* [MLU-EXPLAIN](https://mlu-explain.github.io): Visual explanations of core machine learning concepts. Including [OLS](https://mlu-explain.github.io/linear-regression/), and [logistic regression](https://mlu-explain.github.io/logistic-regression/). 
* https://lakens.github.io/statistical_inferences/
  
### R packages

* Report results: https://modelsummary.com/index.html
* Marginal effects (eg interactions): https://marginaleffects.com

## Misc
* https://tilburgsciencehub.com
  * On how to create a [website](https://tilburgsciencehub.com/tutorials/code-like-a-pro/hugo-website/hugo-website-overview/).
* https://egap.org/methods-guides/
* [The ~~Epidemiologist~~ Political Scientist R Handbook](https://epirhandbook.com/en/index.html)
* General advice (also technical) on writing: https://macartan.github.io/teaching/how-to-write
* Effective abstracts: https://www.fabriziogilardi.org/resources/papers/good-abstracts.pdf

### Webscraping
Using R, generally you can use the package "rvest" for static pages or "RSelenium" for dynamic ones. Before scrapping, take into account ethical and legal considerations (eg. respecting website terms of service, avoiding server overload, and ensuring compliance with legal regulations), this [guide](https://finddatalab.com/ethicalscraping) provides an introduction.
* These fantastic [slides](https://www.rselenium-teaching.etiennebacher.com/#/title-slide) by Etienne Bacher provides almost all that is necessary to successfully extract information from static and dynamic webpages.
