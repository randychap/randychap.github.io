---
layout: post
title: "Hello World"
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2016-06-15T04:27:55-04:00
---

Well some say better late than never and I suppose that's the case with this blog which I should have started years ago. 
To be honest I never got into the whole WordPress thing because I never really felt the need for blogging nor did I want 
to deal with the possibility of security vulnerabilities due to using a backend.

However, these days having a blog or portfolio is absolutely paramount if you are going to convince others of your 
capabilities such as potential employers or show your greatest works. Even if you don't have much to show on your blog, 
it's a great way for people to see your thinking process and how you've evolved over time.

Another big thing these days is that many websites aren't as complex and clunky as they used to be since many are built 
modularly on a "use what you need" basis. With the resurgence of static websites across the web it goes to show that 
less is more when you are throwing out the complexities that come along with attaching a database so it only makes 
perfect sense to use a static site generator for a project involving a blog or portfolio such as this.

### Choosing my static site generator: Jekyll vs Hexo ###
I had to choose a static site generator and there were many to choose from, however, in the end the two that stood out
the most for me was Jekyll and Hexo. Jekyll has been around for awhile and is officialy what GitHub pages supports. Hexo
is the new contender on the block with some promising features, although they pretty much do the same thing.

#### Speed #####
Of these two static site generators, it had seemed that Hexo was the faster of the two in generating static pages. 
Sure, for a few pages it did not seem like much a difference but when regenerating hundreds of pages those few seconds 
can quickly add up and become a few minutes longer. The winner here is clearly Hexo.

#### Setup ####
The cool thing about Hexo is that you just need Node.js installed so you can use npm. Setting up a hexo project is as 
easy as running the hexo init command and you can install any necessary add-on modules to the project using npm. With Jekyll
you will need to install Ruby, and likely bundler as well to help with any project depencies. Jekyll uses Gemfiles to 
determine all the projects dependencies which is similar to pip. Overall setup is pretty similar in both cases so I'm 
going to say it's a draw here.

#### Support / Community ####
One thing with Hexo that I felt was lacking was in the community and documentation support. Many of the articles and guides
on how to setup Hexo were mostly in Chinese and much of the community developed content didn't seem to be as detailed as it 
was for Jekyll which had a plethora of information and content due to how long its been around. Jekyll takes the point here.

#### Conclusion ####
In the end I decided to choose Jekyll because of its larger developer community and established documentation which made it
easier for me to just jump in and create content without interrupting my workflow. However, in the future I may decide to 
switch to Hexo once its more developed and established. Afterwards I'll revisit my comparison of these two static site 
generators once I've got a better handle of the two. Until then stay tuned for more blog posts. 

Cheers!