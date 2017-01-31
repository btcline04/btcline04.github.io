---
layout: post
title:  "NBA Scoring Leaders CLI Gem"
date:   2017-01-31 18:24:41 -0500
categories: jekyll update
---

Man, the training wheels sure came off with this project. I was vaguely familiar with ruby gems and the command line interface before this project, but I didn't quite understand exactly how to make a CLI work. One of the biggest challenges for me as I dive deeper and deeper into software engineering is just starting. I'm a reader - I want to know everything there is know about a topic before I even begin. Sometimes, that works to my benefit. Other times, like when I'm starting a project, it can work to my detriment. It took me awhile to get going on this one. I didn't know where to begin. 

I'm thankful that Rubygems.org exists so that I could look at other published gems to get a general idea of what I needed to do. Coming across the command { highlight ruby %} bundle gem {% endhighlight %} was probably the most helpful thing I encountered along the way. It gave me a solid foundation with which to start.

I knew I wanted to create a gem involving the NBA, and I ultimately settled on creating one that allowed me to pull up the individual scoring leaders in each season dating back to 1946. 

Scraping the website that I wished to pull my data from was one of the biggest challenges for me. The HTML table that my information was located in was poorly formatted and it made it difficult for me to really get at what I wanted to scrape. It took a bit of troubleshooting, but I eventually got what I needed. 

I feel more confident in my abilities after creating something like this from scratch. The gem that I've created will be able to scrape data and pull it from the live webpage. This was important to me. As more years and information get added, I wanted my gem to still be able to work.

Going forward, I'd like to publish this gem to RubyGems.org and add a bit more functionality. I hope to be able to make it a little bit easier to read as it prints to the terminal. I'm looking forward to the challenge.