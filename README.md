# events
Openscapes events: <https://openscapes.org/events>


## Distill tips

From <https://themockup.blog/posts/2020-08-01-building-a-blog-with-distill/>

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