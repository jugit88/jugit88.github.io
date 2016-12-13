---
layout: post
title: My Journey through CS3112
---

##Intro
When I began this course, I was really unsure about the direction I was going to take. I had never been in a course where
I was given the freedom to work on anything I choose. I began thinking about what is important to me and how I can make a project
based on that. I've always loved Twitter, so I figured I would do something with their search API. Twitter is rich
with information, but sometimes hard to parse. Eventually, I came to the conlusion I wanted to create an Aggregator site that would
curate content on twitter. 

##Process
###Issues
I knew this would be a difficult project, but it's safe to say that the project is way more difficult I originally ancitipated. 
I had some prior experience working with APIs, but the sheer amount of data needed to effectively create an aggregator, along with the 
cost to store the data in a server was overwhelming,to say the least. In addition, the Twitter API standard rate limits that are typical
among for-profit companies.
###Solutions
To mitigate some of the issues above, my strategy was to use various cluster computing technologies  
such as [Hadoop](http://hadoop.apache.org/), [Apache Spark](http://spark.apache.org/), [Apache Mesos](http://mesos.apache.org/),etc.
In short, these technologies make it easier to process, manage, and store large amounts of data. The Twitte API is a harder workaround,
as getting authorization can prove difficult depending on your task.
##Tools Used in the Class
#####Languages: Python, R
#####Frameworks: [Hadoop](http://hadoop.apache.org/), [Apache Spark](http://spark.apache.org/), [Apache Mesos](http://mesos.apache.org/)
#####Database: NoSQL([Redis](https://redis.io/) w/[JSON](http://www.json.org/) as data)
#####APIs: [Twitter Search](https://dev.twitter.com/rest/public/search)
