# Web-Scraping-with-R

## Project to Illustrate Web Scraping with R
This project seeks to collect resources and provide examples of web scraping with R

## A bit on web scraping
Web scraping allows the extraction of data elements from them HTML and/or CSS of a website.

*ALWAYS* ensure that you have permission from the site before scraping. This is done by checking the `robots.txt` file of a site. This can be done simply with the library `robotstxt` `paths_allowed()` command.

For example, to determine if you can scrape a site, you can run the following:
```
library(robotstxt)
paths_allowed(
  paths = c("https://www.imdb.com/")
)
```

If the result is `TRUE`, you are permitted to scrape the site.

## A little help selecting the right elements
There are a few ways to select elements from a webpage.
1. Viewing the page source, which is not user friendly.
2. Inspecting the page via developer tools in any major browser.
3. Selector Gadget (<https://selectorgadget.com/>), which allows point and click selection of elements.

## Presentation
This project was undertaken to present Web Scraping in R.

The .html files do not render directly as a true .html file in GitHub. GitHub & BitBucket HTML Preview works well to convert these .html files into viewable webpages. Try it here https://htmlpreview.github.io/.

The presentation (work-in-progress) [can be accessed here](https://htmlpreview.github.io/?https://github.com/mjhendrickson/Web-Scraping-with-R/blob/master/web-scraping-with-r.html#/).
