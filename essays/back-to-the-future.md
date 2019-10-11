---
layout: essay
type: essay
title: Back to the Future
# All dates must be YYYY-MM-DD format!
date: 2019-10-10
labels:
  - Semantic UI
  - UI Frameworks
---
 After experiencing 90's nostalgia with html, we're finally brought back to the look of modern websites with the use of Semantic UI. 
 
<div class="ui small image">
  <img class="ui image" align="centered" src="https://miro.medium.com/max/500/1*H4Q0WVU0Hzt4DEcwVgZwbQ.jpeg" height="180px" width="300px">
</div>


I'm not sure if Semantic UI is as difficult as learning a new programming language, but I do think it's somewhat comparable. It's easy to understand most of the syntax similar to html, just like it was easy to understand how the syntax for javascript was similar to java. It seems like one of the advantages of using Semantic UI would be how similar its syntax is to written/spoken English. For example, if you want something to be a specific color or size you can add it to the class; this feature seems like it can get confusing since it effects the name of your class. If you create several classes with many characteristics, I could see differentiating them all could become difficult.

I definetly need to continue using Semantic UI to understand its capabilities better. When recreating the [Teddy Fresh](https://teddyfresh.com/) website, I wanted to create bigger spaces between some sections in the footer, but the only way I understood how to do this was by using dividers. Using fitted dividers allowed me to place spaces smaller than regular dividers, but it didn't provide as much space as I wanted.
```
<div class="ui list">
        <div class="footer item">GET NOTIFICATIONS ABOUT NEW ARRIVALS AND RESTOCKED ITEMS!</div>
        <div class="ui fitted hidden divider"></div>
        <div class="ui fitted hidden divider"></div>
        <div class="ui fitted hidden divider"></div>
        <div class="ui labeled input">
          <input type="text" placeholder="Enter your email address">
        </div>
```
I had to use three fitted dividers to get a small space between two items in my list, the amount of dividers used in my footer section was insane.
