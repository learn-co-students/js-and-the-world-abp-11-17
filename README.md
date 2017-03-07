### Objectives

Understand how javascript influenced the web.  

### Javascript: it's kinda a big deal

So in the previous lesson we learned the answer to what is javascript.  Javascript adds behavior to our HTML.  Or in dev speak:
  * Javascript is a scripting language created to bring interactivity to the browser

What is this interactivity?

  1. Move, remove or add HTML.  Javascript can move, remove or add content to our site.  
  2. Find specific pieces of HTML so that it knows what to remove, where to add specific content, or what to change.
  3. Javascript can listen and respond to specific events that occur in our browser.  

Javascript is not:

  * Java
  

  > Note: Java is a very different language and is not technically related to or even all that similar to javascript.  

Various tools and libraries are built in Javascript like:

  * React, Ember and Angular
  * NodeJS
  * React Native - library for building iOS and Android phone apps.
  * D3 a charts animation library

![alt text][d3js]
[d3js]: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/d3-js.jpg
> Sample of charts made with D3, a charts animation library

Because javascript is the language of the browser, and users interact with websites through browsers, it is no surprise of Javascript's popularity.  A widespread developer survey showed that over 85% of full-stack developers use javascript.  

But it wasn't always this way.

### Javascript's early years: shunned and unloved

Javascript was built by Netscape.  In 1995, Netscape's browser dominated the web, and owned over three quarters of the browser market.  Marc Andreessen, Netscape's founder, asked one of his developers, Brendan Eich, to embed a programming language in the browser.  Brendan wrote the language in just ten days.  Javascript was born.

Javascript was written in 1995.  And then...

![alt text][crickets]
[crickets]: https://s-media-cache-ak0.pinimg.com/564x/fb/d5/85/fbd58544cfd2d580a236892f54e28593.jpg
> Crickets


There were no updates to the language until 2009.   

Let's think about that.  This is the difference between 1995 and 2009 in cell phones.

**Cell Phones in 1995**
![alt text][pager]

[pager]: https://i.cbc.ca/1.2929253.1422020251!/fileImage/httpImage/image.jpg_gen/derivatives/16x9_620/pager.jpg


  > Yea in 1994, there were nearly twice as many pagers in use 60 million as cell phones 34 million.  Javascript was written in 1995.  

**Cell Phones in 2009**

![alt text][iphone]

[iphone]: https://www.imore.com/sites/imore.com/files/styles/w800h450crop/public/field/image/2013/08/iphone_3gs_hero_4x3.jpg?itok=127Ggb7j&timestamp=1377020381

> The iPhone had been around since June 2007.  In 2009, it was the world's third most popular cell phone.  Javascript was updated in 2009.

So while cell phones went from pagers to smartphones, Javascript remained unchanged.  

Why?

### 1995 - 2005: Fake language to tour de force

For its first ten years of existence, professional developers did not really consider Javascript a programming language.  Designers occasionally used it to add some slick animation, but the important parts of a  website like retrieving specific data, and performing calculations, was done with some other programming language.  

Then in 2005, something happened.  Google Maps launched.  Before google maps there was Mapquest.  And every time a user wanted to view another part of a map, he would have to wait for a full page refresh and the page to fully reload.  


![alt text][maps]
[maps]: https://i.ytimg.com/vi/-HLrC4nbghw/maxresdefault.jpg
> Google Maps showed that Javascript could make websites feel like an interactive Desktop application.

With Google maps, a user could drag around the map and it would smoothly update.  There would be no full refresh.  The user could smoothly interact with a webpage as if it were a desktop application, or a video game.  

The technology behind this type of interactivity was called an XHR, which stands for XMLHTTPrequest (XML-HTTP-request).  XHR allows a website to receive new data (like a set of street names and coordinates of a different location) without a page refresh.  This is important - because while a site like Google Maps could not send a detailed map of the entire planet to any user going to it's website, it could send the new map information as a user dragged his cursor around.  So it felt to the user like all of that information was always on his computer.  And all of this occurred without a page refresh.  

With this, programmers began to look at Javascript as a medium for creating interactive web applications.  

### 2005-Present: Javascript Emerges

Soon after the debut of Google Maps, programmers began trying to fix Javascript and developed tools like JQuery and Node.js.  (We'll talk about JQuery later.)

By 2010, Javascript frameworks were released.  Frameworks allow developers to code more easily by encouraging specific practices, and including useful libraries.  In 2010, Google released the AngularJS framework, and today it is used by 10,000 companies including PayPal and the Youtube.  In 2013, Facebook released React, which today is used by companies like Netflix, Yahoo!, and Khan Academy.  Additional frameworks like React Native allow developers to build professional grade Android and IPhone apps with Javascript.  

![alt text][javascript]
[javascript]: https://airpair-blog.s3.amazonaws.com/wp-content/uploads/2014/08/urishaked-jscompare-2.png

### Upgrades to Javascript

In 2015, the powers that make Javascript updated the language, to make it more developer friendly.  With all of these updates to Javascript, and with the flexibility that the language provides, the Javascript community is still rapidly developing best practices as to how to write Javascript code.  Dan Abramov made a major contribution to how programmers use Javascript with Redux in 2015.

![alt text][abramov]
[abramov]: https://i.ytimg.com/vi/xsSnOQynTHs/hqdefault.jpg

### The Point

This is the world where you begin your Javascript journey.  Not with language and tools that are mature and polished, but emergent and still developing.  Where with these new patterns and frameworks, even the most experienced developers have only been exposed to them for a couple of years.  And where developers question how their long held tenets apply to this new world.  

And to think all of this about shuffling around some HTML, and rearranging the DOM.  But how do we even use Javascript to interact with our HTML?  Great question.  Let's use that to begin our coding journey, and take each of the components of Javascript behavior in turn.
