
# [ShinyDevSeries](https://shinydevseries.com/) - Barret Schloerke


* `reactlog`
  * `reactlog` provides a visual insight into that _black box_ of Shiny reactivity
  * Site: https://rstudio.github.io/reactlog/
  * Demos:
    * (Launch reactlog: `cmd + F3` or `ctrl + f3`)
    * `shiny::runApp("reactlog/reactlog-pythagorus.R")`
    * `shiny::runApp("reactlog/reactlog-pythagorus-broken.R")`
    * `shiny::runApp("reactlog/reactlog-cranwhales.R")`
    * `shiny::runApp("reactlog/reactlog-anti-pattern.R")`

* `learnr`
  * The `learnr` package makes it easy to turn any R Markdown document into an interactive tutorial. Tutorials consist of content along with interactive components for checking and reinforcing understanding.
  * Site: https://rstudio.github.io/learnr/
  * Demos:
    * RStudio Primers: https://rstudio.cloud/learn/primers
    * Allison Horst
      * Post: https://education.rstudio.com/blog/2020/05/learnr-for-remote/
      * Demo: https://allisonhorst.shinyapps.io/missingexplorer/
      * Source: https://github.com/allisonhorst/explore-na
    * Sortable
      * Site: https://rstudio.github.io/sortable/
      * Demo: https://rstudio.github.io/sortable/tutorials/tutorial_question_rank.html

* `plumber`
  * `plumber` allows you to create a web API by merely decorating your existing R source code with `roxygen2` style comments.
  * Site: https://www.rplumber.io/
  * Demos:
    * NEW - Hex logo and website!
    * NEW - pipe-able programatic interface
      * Demo: `plumb(dir = "plumber/pipe") %>% pr_run()`
    * NEW - POST body parsing
      * Process incoming POST body data
      * Ex: HTML forms, multipart forms, csv, tsv, json, yaml, feather and rds.
      * Like serializers, register new POST body parsers
      * Site: https://www.rplumber.io/reference/parsers.html
    * More Serializers!
      * Serialize outgoing route data
      * Ex: plain `text`, `json`, `yaml`, `csv`, `tsv`, `rds`, `feather`
      * NEW - Register image serializers: `svg`, `tiff`, `bmp`, `pdf`. (Pre existing: `png`, `jpeg`)
      * Site: https://www.rplumber.io/reference/serializers.html
    * NEW - Download return values as attachments!
      * Site: https://www.rplumber.io/reference/as_attachment.html
      * Demo: `plumb_api("plumber", "16-attachment") %>% pr_run()`
    * NEW - Async / promises
      * Demo: `plumb("plumber/plumber-future.R") %>% pr_run()`
    * NEW - API UIs (rapidoc)
      * Register new User Interfaces to look at your API
      * Demo: `plumb(dir = "plumber/rapidoc") %>% pr_run()`
  * Thank you to Bruno Tremblay (`@meztez`) for his heavy contributions to plumber!
