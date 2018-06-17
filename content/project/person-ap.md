+++
# Date this page was created.
date = "2018-06-12"

# Project title.
title = "Alison Parton"

# Project summary to display on homepage.
summary = "Postdoctoral research associate"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "ap.JPG"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["person", "post-doc"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/ap_header.jpg"
caption = "<i>A dynamic energy budget model.</i>"

[social]
    github  = "https://github.com/a-parton"
    twitter = "https://twitter.com/Alison_Parton"
    linkedin = "https://www.linkedin.com/in/alison-parton"
    bitbucket = "https://bitbucket.com/a_parton"
    envelope = "mailto:A.Parton@sheffield.ac.uk"
    graduation-cap = "https://scholar.google.com/citations?user=WAul8voAAAAJ&hl=en"

+++

<br>

I am a statistical ecologist with a background in modelling continuous-time animal movement using data obtained by GPS telemetry. My current role involves developing an ABC framework for parameterising physiologically structured population models. See my webpage for more details [here](http://alisonparton.co.uk/). 

Physiologically structured population models (PSPMs) allow the life histories of individuals and the resulting population dynamics to be modelled by linking the processes underpinning individual variation to resource competition. An important class of PSPMs is based on a dynamic energy budget (DEB) which outlines the relationship between an individual’s resource acquisition, growth, development, maintenance, and reproduction. By aggregating individuals through their competition for a shared resource, the DEB can be scaled up to the population process. Often, PSPMs are evaluated against data in an informal way by selecting ‘reasonable’ parameters from literature and comparing observed patterns. Here, we aim to infer the parameters of the PSPM in a robust way, based on observations. Solving this inverse problem is challenging, and we approach this by implementing approximate Bayesian computation (ABC) to avoid the need to evaluate an explicit likelihood. We demonstrate this using observations and a DEB for the _Soay sheep_ of St Kilda.
