---
layout: post
title: "link demo"
categories: tools
---

link demo with markdown syntax and jekyll syntax

## markdown link works 

- [home](../index.md) 
- [next](2002-04-21-test-date.md)


## jeklly link also works 


- [home url]({{ site.url }})    no working

- [home base url]({{ site.baseurl }})

- [post link demo]({{ site.baseurl }}{% post_url 2022-04-26-this-post-demonstrates-post-content-styles %})

- [baseurl value:]({{ site.baseurl }})

- [url value: ]({{ site.url }})

- [back](./2022-04-26-this-post-demonstrates-post-content-styles.md) 
- [next](./2022-04-27-example2%20.md)