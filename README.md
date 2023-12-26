
#My Academic CV

I built this following [Eduardo Fernandez](https://github.com/EduardoFernandezC) who followed [JooYoung Seo](https://github.com/jooyoungseo/jy_CV). The scripts follow a bookdown structure where each section of the CV is one separate `.Rmd` file. To render the complete document, you need to knit the `index.Rmd` file (using the latest [rmarkdown](devtools::install_github('rstudio/rmarkdown')), [pandoc](https://pandoc.org/installing.html) among other R libraries). The order of the sections is specified by `_bookdown.yml.` You can define several `.bib` entries according to the section you want the information printed out.

The CV is based on a template from `vitae::awesome` with minor modifications to the `awesome-cv.cls` file for personal customizations in letter color and style.
