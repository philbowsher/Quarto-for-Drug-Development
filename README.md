# Quarto-for-Drug-Development
Workshop and examples for Quarto for Drug Development

Language-agnostic drug development / Multilingual drug development 

In this hands-on session, we will do the following:

Part 1: Intro to Quarto

Part 2: Sample workflow

Data?

In order to pracitice visualizing data with thousands of observations while also investigating a biologically relevant question, we will use data from the Broad's [Cancer Dependency Map](https://depmap.org/portal/), a compendium of genome-wide CRISPR screens across hundreds of cancer cell lines, to identify genetic vulnerabilities.

https://depmap.org/portal/download/all/

sample_info.csv

Questions about the data?

First, let's create a repo...https://github.com/new

Lets import the data? First, lets create a workflow in Quarto to house the code.

how? via tidyverse https://r4ds.had.co.nz/

Let's wrangle & viz the data

Can you make the ggplot2 examples interactive with plotly?

Now lets build in params

https://quarto.org/docs/computations/parameters.html

How do we share this workflow?

Let's publish a plotly visualization outside of quarto to PSC by clicking the blue publish icon in the upper right hand corner of the RStudio source pane. be Where is "Publish with Source Code"?

Once published, take some time to play with the RStudio Connect interface. How would you restrict access to your app? Can you visit your neighbour's app? Change the access controls so your neighbour can view your app.

https://docs.posit.co/connect/user/git-backed/

rsconnect::writeManifest()

https://quarto.org/docs/publishing/
https://pins.rstudio.com/

Can I email this report to people?

What could we have done better? renv

How do we make this look better? Quarto websites...

https://quarto.org/docs/websites/

What about shiny? https://jjallaire.shinyapps.io/diamonds-explorer/

https://quarto.org/docs/interactive/shiny/

What about the Multilingual part? Example using python.
