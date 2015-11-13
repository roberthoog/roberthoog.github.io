---
layout: post
title:  Humming along to the song... "are we human..." by The Killers
date:   2015-11-09 16:47:13
categories: techie talk
---
## Stupid headlines aside...

... This here piece of text is about the humans.txt, robots and this first project of setting it all up. 

##What do you think of pre-compiling your CSS?
It's great as long as most of it is automatic and you don't have to dive in their and get your hands dirty.
     
## Compare to regular CSS
Less repetition of course. I always disliked having to write " margin: 0 auto" or a font stack. Now that'll be gone. 

But there is so much I have not tried yet. Added a variable or two and used a few.

## Which techniques did you use?
Variable for font-stack is the first that comes to mind.

## Pros and cons?
Takes time to get into and cumbersome (for me) to set up the environment with Vagrant, Webstorm etc. I plan on using 
it with sublime text 3 later, which is my editor of choice since years.

##What do you think of static site generators?
Wonderful! The best thing is the lack of a database. 

##What type of projects are they suitable for?
Anyone who runs a (smaller) blog, businesses willing to keep up to date with customers, magazines and TV-stations. They
 only limit I can see, which is one of its major upsides, is the lack of a database. Fora very heavy Wordpress or 
 Drupal site with thousands of posts my uneducated guess is... perhaps not. Let it grow - if that is what it 
 wants to. 

##What is robots.txt and how have you configure it for your site?
 Robots.txt is  a simple text file placed on the server containing instructions for search enginge crawlers. Perhaps you don’t want your site indexed at all, or certain pages or folders, like cgi-bin full of scripts. The file must be placed in the the root directory of the web server.
 
 I set mine to index nothing as this page is far, far from completion. And I think it is unwise to publish things 
 before they are fully functional and finished. Been there, done that.
 
 But there is a myriad of different useful settings you can define in this file. And for a big site, it's crucial not
  to overlook the importance of a well designed robots.txt

## What is humans.txt and how have you configure it for your site?
 Another text file with information on the website. Who made it? What team(s) were a part of the creation and when was the last update? Who gets credited and for what? How do I reach them and are they on Twitter? Is the geek behind the navigation system married to a cousin?
 It’s a way to humanize a site and get to know a bit more about the creators and what made the website possible
 besides frameworks, IDEs and whatnot. 
 
 My own was short and sweet since I am the only one on the project. Just a few lines with contact info, update and 
 what tools were used in the building process.

## How did you implements comments to blog posts

Shock! Disqus was the easiest artefact in the world to implement and run. It worked on the first try, and as far as I 
can tell, it runs smoothly. I tried a post and it's there. I had great help from Google.

## What is Open Graph and how do you make use of it?
Open Graph is when you can have a Facebook interaction on your website. There are also for example Twitter Cards, but
 OGP is when you must add certain meta tags to your header and by the interaction can help the site grow and expand.



<div id="disqus_thread"></div>
<script>
/**
* RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
* LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables
*/
/*
var disqus_config = function () {
this.page.url = localhost:4000; // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');

s.src = '//shadowbound.disqus.com/embed.js';

s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>