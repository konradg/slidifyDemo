---
title       : Shiny Test App
subtitle    : Developing Data Products Course
author      : Konrad Gorski
job         : Coursera 2015
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: konradg
  repo: slidifyDemo
---
## What sample Shiny app should I build?

I asked myself this question one day before the deadline.

# The answer?

No idea. So I just made a quick example.

---

## What does the app do?

# Well, not much

It's just a simple histogram of a random data (normal distribution). For a demo of reactive text, a simple string reversal feature was introduced, using the following function:


```r
paste(rev(strsplit('Sample input', NULL)[[1]]), collapse='')
```

```
## [1] "tupni elpmaS"
```

---

## How do I use it?

Just move the slider around to change the number of samples used for the histogram. You can also enter any text to see it reversed.
Sorry, had no time to go any further than this really simple example!

---

## Is that it?

For now unfortunately I'm afraid so, but I will consider these tools seriously for creating actual data products. I love the straightforward way of creating Shiny apps and Slidify presentations. This **may** be the beginning of a beautiful friendship with Data Science...

## So, what score do I need to give you?

Up to you - I apologize for not finding enough time to make something actually useful. Anyhow, I believe whatever _is_ there, actually works correctly. Thanks and keep up the good work with the fantastic world of Data Science!
