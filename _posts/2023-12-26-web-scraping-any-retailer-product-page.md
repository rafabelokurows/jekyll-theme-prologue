---
title: Scraping basically any produt page with R
author: Rafael Belokurows
layout: post
---

When you are in the Retail business - or any business, for that matter, sometimes you need to obtain product data from the web page of some retailer and it's amazing the amount of information some of them provide. This obviously varies widely from company to company, but some examples of information are comprehensive product descriptions, barcodes, prices, images, etc..

However, obtaining all the info you want using web scraping techniques can be quite challenging, since there are a lot of factors to consider:
- Webpage layouts can be very different from one page to another
- Some pages load their content dynamically, which mean simply loading the static HTML won't do the trick
- As the scripts are usually heavily dependent on page structure and fixed element names, there's no guarantee that the script you develop for one product page will work for another

If you are (still) reading this, stick around, 'cause I'm gonna share some stuff I wish I knew when I first started web scraping product pages. 
Disclaimer: While R is usually not the tool of choice when it comes to web scraping, it does an incredible job nonetheless. If you are a R user (or at least want to learn it), that's great. If you plan on using Python, don't sweat it, most of what I'll show here will translate almost 1:1 to the Python ecossystem.

## Tricks up our sleeves

Before moving to the nitty-gritty of web scraping, let's see some auxilary tools and initial set up necessary:

### SelectorGadget for finding element names in a HTML page

https://chromewebstore.google.com/detail/selectorgadget/mhjhnkcfbdhnjickkkdbjoemdmbfginb

### Selenium for dynamic page navigation

I recommend using Firefox navigator


## Some real-life examples

Static pages
Dynamic HTML loading
Selenium for ghost browsing

