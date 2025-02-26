---
layout: post
title: How robots.txt indirectly impacts a website's performance
author: Tan
---
A robots.txt is primarily used to tell search engine such as google, bing ...etc. which pages on your site that they can or can not indexing or crawling. It can indirectly impact a website's performance. But......How it is possible ??
 

Ok, let check it together with the assumption that we are alread know what is the the robots.txt 


##  How robots.txt Works
-----
A robots.txt file is a simple text document with no formatting and The basic premise is to allow or disallow access to bots (automated traffic) to areas of your site.

Bots, spiders, web crawlers, and user agents all amount to the same thing — automated traffic.

Bot and web crawlers (such as Googlebot) can visit your site multiple times per day and check your robots.txt file first. By default, Bot and web crawlers can access all the pages of your website that they find. The robots.txt file tells them not to it.

One side of the note here is the normal visitor won't effected by the robots.txt because they will access your web page directly.

##  Why the Robots.txt can impact to your web performance
-----

Yes, if you read the sessions above you might already understand why it can impact to the web performance. 
If your robots.txt did not configured properly it can not protect the weak area and data on your website from the bot and web crawler and then the bot and crawler can directly access to this area such as the data form, login page, cart page and checkout page, the page with the dynamic data load from the backend application and so on, the website area that was not under CDN caching  

And with the concurrent'session from those bots and crawler it will consume a lot of your resources and the final the thing is your website performance is impacted

##  Conclusion
-----

Today we can hear the AI anywhere and in all of the tech conversation, and the data is the primary important input for the AI, one of the data resources for the AI training is coming from the automation crawler and bot. 

So, Protect your sensitive data and saving your resources is the most important things and the first step of the protect the data and saving money for the resources is configuring properly your robots.txt  

The post is just the personal point of view and experience that i am have been working  

Thank you so much for your time and please do not hesitate to let me know your thought from the comment form bellow
