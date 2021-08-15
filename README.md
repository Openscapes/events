# events
Openscapes events: <https://openscapes.org/events>

Note: to avoid [date issues](https://github.com/rstudio/distill/issues/315), install from github: 

```r
# install.packages("devtools")
devtools::install_github("rstudio/distill")
```

Create an event post: 

create_post(title="nwfsc", date="2021-09-17" )


## Distill tips

From <https://themockup.blog/posts/2020-08-01-building-a-blog-with-distill/>

writing text and `code`

`print("hello")`

```r
create_post(
  title, # mandatory
  author = "auto",
  slug = "auto", # generates a website slug (URL)
  date_prefix = TRUE, # adds date for sorting
  draft = FALSE, 
  edit = interactive()
)
```

```r
install.packages("devtools")
devtools::install_github("rstudio/rmarkdown")
devtools::install_github("yihui/knitr")
devtools::install_github("rstudio/distill")
```