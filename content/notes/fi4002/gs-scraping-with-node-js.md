---
title: "gs scraping with node.js"
date: 2023-10-25T05:17:00+08:00
authors: ['Sparisoma Viridi']
tags: ['fi4002']
draft: false
math: true
url: "0112"
---
{{< toc >}}


## introduction
+ Google Scholar data can be scaped without coding but use a online web scaping tool, e.g. Octoparse ([Jones, 2023](https://www.octoparse.com/blog/scrape-google-scholar)) or ParseHub ([Miranda, 2022](https://www.parsehub.com/blog/scrape-google-scholar/)).
+ Python and Beautiful Soup, one of its package for parsing HTML and XML, can be also used to scrape Google Scholar data ([iWeb Data Scraping, 2023](https://iwebdatascrapingservices.medium.com/how-to-scrape-google-scholar-data-using-python-a0d5a26b385f)), which must pay attention to IP blocks due to simple API ([Ganesan, 2020](https://proxiesapi-com.medium.com/scraping-google-scholar-with-python-and-beautifulsoup-850cbdfedbcf)).
+ There is also Python package written for Google Scholar scaping, which requires only few lines of codes ([DataKund, 2022](https://pypi.org/project/scrape-google-scholar/)).
+ PHP with the help of Simple HTML DOM Parser are able to collect data of hundreds of lectures from several faculties in a university ([Putri et al., 2021](https://conference.upnvj.ac.id/index.php/senamika/article/view/1390)).


## reading materials
+ [How to use Google Scholar: A short introduction to search literature in internet](https://medium.com/@6unpnp/how-to-use-google-scholar-c7d80baaeb6e).
+ [Install Node.js: Server-side web applications using JavaScript](https://medium.com/@6unpnp/install-node-js-25f576ed92f5).
+ [Scraping your webpage: Using Node.js to scrap you GitHub Pages webpage](https://medium.com/@6unpnp/scraping-your-webpage-f4fde3a465db).
+ [Node.js and Google SERP: Following the steps from Khandelwal story](https://medium.com/@6unpnp/node-js-and-google-serp-36031458b0ac).
+ [Random HTTP headers User-Agent: One way to reduce being blocked while web scraping](https://medium.com/@6unpnp/random-http-headers-user-agent-23bcdd8c0537).


## assignment
+ Read the reading materials and perform the activity described if you have not done it yet.
+ Modify the given code to scrape Google Scholar SERP for three search words.
+ Record the statistics in the form of output program for
  - each word result
  - each pair of two words in arbitrary order
  - all three words in arbitrary order
  - all three words in a phrase
+ Analyze the four results and make a conclusion.
+ Make a report for this assignment in a form a story in Medium.
+ Report the link on https://github.com/dudung/lecture-notes/issues/18 before Friday 27th, October 2023, 0900 GMT+07.
+ Prepare for presentation in the class on Friday 27th, October 2023, during the class 0900-1040 GMT+07.