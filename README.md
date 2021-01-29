[t-gummer.github.io](http://t-gummer.github.io)
================

# An R Markdown Website\!

To build the website, run
[`rmarkdown::render_site()`](http://rmarkdown.rstudio.com/rmarkdown_websites.html).
This website is hosted via [Github Pages](https://pages.github.com/).
The source is available at
<https://github.com/t-gummer/t-gummer.github.io>.

# Sources

  - <https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html>
  - <https://www.emilyzabor.com/tutorials/rmarkdown_websites_tutorial.html>
  - <https://jules32.github.io/rmarkdown-website-tutorial/>

# Updating the README

Due to the unusual fact that README’s in R Markdown websites, use the
following after updating the README:

``` r
rmarkdown::render("README_source.Rmd", output_file = "README.md", output_format = "github_document")
```
