---
layout: essay
type: essay
title: Semantic VS Bootstrap
date: 2019-02-21
labels:
  - UX
---

Semantic UI and Twitter bootstrap are two of the most popular and well established open-source UI frameworks around.  Both have similarities and unique strengths.  Differences in usability and design play a part in the contrast between the two. How do we pick one over the other? How do we survive in this world of choices?

## UI Frameworks at a glance
Building a UI framework from scratch is not an easy thing. The idea is that an application should have consistent styling throughout itself, and therefore CSS classes allow for reusability and flexibility.  The maintainers of UI frameworks make decisions on things like:
* How many columns fit in a grid?  (Semantic uses 16, bootstrap 12)
* At what screen-size does the app rearrange its contents?
* What are the default color choices?

Because both Semantic & Bootstrap are well seasoned, customization is easy to figure, and documentation is well written. The choice  becomes one of opinion. 

## Semantic UI
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTo8zvpLzusOWyUJT7G8PeAOL0VkSRwq7AmxYCQ-TsTvJMZSa2JdQ)
Using Semantic  is both easy and difficult at the same time.  Much like the English language, Semantic uses class names to describe the element. 
`ui center aligned container`  is a quite literal translation of what will appear on the screen.  The drawback to this is that there are so many adjectives, it is hard to remember which ones work for which elements. Does `right` work on `menu`  as well as  `icon`?  I think that getting started with semantic is easy, but it to the next step with more complex layouts will be a steeper learning curve. 

## Bootstrap
![](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2018/04/1525068825bootstrap-logo-png-logo-228.png)
Bootstrap has been around for a long time and I may be biased towards the way it is designed. Unlike semantic where adjectives would precede the noun like `menu`, Bootstrap prefers that you declare the noun first and then add additional style classes after.   For example,  the classes for a large red button would be `btn btn-lg btn-warning`.  Each class is specific to the component and has more specific styling that goes into it.  
My gripe with this is now that there are so many class names to remember for each element that I will never truly remember them all.  

## In contrast
I see the benefit of using naming conventions of Semantic UI because even though there is a learning curve associated with the styling of components,  the keywords are all the same. In comparison to Bootstrap, semantic is much simpler. The naming conventions in Semantic still irritate me though because I do like how Bootstrap declares what it is first instead of last. 

In terms of documentation, I think Bootstrap has better documentation.  Aside from having more examples, bootstraps docs also include a handy search feature which makes it easier when I can’t remember the name of a feature but can describe it. 

So far I’ve found more resources online for bootstrap examples and reference sheets compared to available resources for Semantic UI, so Bootstrap wins in that category for now. 

Both frameworks rely on JQuery to perform some javascript functionality on elements.  However, I’ve read that more and more web designers are trying to get away from the JQuery library.  A good example of this is Github who just last year removed JQuery completely from their bootstrap styled application ion. 
