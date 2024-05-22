# VIICTR Bio Crawler

## Introduction

This repository contains a [notebook](./crawl_bios.ipynb) that demonstrate how to crawl all the HTML docs (i.e., bios) from [VICCTR Profiles](https://profiles.viictr.org/) then convert the docs to PDFs. This document explains how to use the crawler.

## How to use

First, visit [https://profiles.viictr.org/search/](https://profiles.viictr.org/search/) to create a search.

Next, put the input to specify what you would like to find then click the search button

After seeing the query, copy the entire URL from the address bar in your browser. 

At the end, add a cell with the following code lines.

```
url = "<copied_address>"
path = "<where_you_want_to_store>"
crawl_bios(url, path)
```

## TODO 

- create a `.py` script