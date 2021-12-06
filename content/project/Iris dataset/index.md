---
date: "2021-10-02"
external_link: ""
image:
  caption: Photo from Unsplash
  focal_point: Smart
links:
- icon: github
  icon_pack: fab
  name: github-data
  url: https://github.com/EdwardHill15/Data.git/
#slides: example
summary: An example of using the in-built project page.
tags:
#- Deep Learning
title: Iris dataset and analysis
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
---
title: "iris"
author: "Edward Hill"
date: "2-10-2021"
output: html_document
---

```{r, echo=FALSE}
data <- iris
library(DT)
table <- datatable(iris, extensions = "Buttons",
                   options = list(dom='Bfrtip',
                                  buttons = c('copy', 'csv', 'excel', 'pdf', 'print')))
table
```
