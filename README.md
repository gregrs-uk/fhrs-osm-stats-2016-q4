# fhrs-osm-stats

The graphs created using the [RMarkdown](http://rmarkdown.rstudio.com) code in `graphs.Rmd` can be used to track the impact of the [OpenStreetMap Autumn Quarterly Project 2016](https://wiki.openstreetmap.org/wiki/UK_2016_Q4_Project:_Food_Hygiene_Ratings), which involves using Food Hygiene Rating Scheme data to enrich the map. The code uses [CSV files](http://gregrs.dev.openstreetmap.org/fhrs-stats/) created by the [FHRS/OSM comparison tool](http://gregrs.dev.openstreetmap.org/fhrs/).

During the Quarterly Project, I will try to upload the [generated graphs](http://gregrs.dev.openstreetmap.org/fhrs-stats/graphs.html) weekly. If you would like to create/modify the graphs for yourself, you will need to:

* Download [R](http://www.r-project.org) and [RStudio](http://www.rstudio.com) and probably [RMarkdown](http://rmarkdown.rstudio.com) support for [RStudio](http://www.rstudio.com)
* Download at least two of the [CSV files](http://gregrs.dev.openstreetmap.org/fhrs-stats/) to form a before/after pair
* Modify the CSV file paths near the top of `graphs.Rmd` to match your downloaded files
* Use [RStudio](http://www.rstudio.com) to knit the [RMarkdown](http://rmarkdown.rstudio.com) document, creating `graphs.html`
