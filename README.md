# events  
Openscapes events: <https://openscapes.org/events>

## Before you begin

Install daily releases of Quarto and RStudio
- https://quarto.org/docs/get-started/
- https://dailies.rstudio.com/

## Create an event post

Start a new event post `/posts/yyyy-mm-dd-slug/index.qmd` by copying the most recent similar post, like a Community Call or Champions Cohort. 

The thumbnail image to appear in the Events list page should be 520 x 520px. It is called in YAML `image: picture.png`.

To keep a post as a draft we can:
- set YAML `draft: true`, and remove it to publish, OR
- if our workflow is to submit an event in a GitHub pull request (PR), set the PR as Draft and when ready, convert the PR to Ready to Review so it will be published when the PR is merged. 

Render the event post locally before making the PR.

## Quarto tips

See our own [Making open-source documents with Quarto](https://openscapes.github.io/quarto-website-tutorial/).

Use ISO-8601 date format in YAML to avoid issues e.g. in citation.
