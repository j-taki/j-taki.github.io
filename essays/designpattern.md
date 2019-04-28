---
layout: essay
type: essay
title: "Design Patterns"
date: 2019-04-7
labels:
  - Software Engineering
  - Design Patterns
---

# An early pattern

I was just listening to a podcast today about "Zero" and I think that its quite beautiful how the concept of 0 was implemented very much as a design pattern. 
Previous to the concept of 0, people who kept account of thigns like grain stores didn't have a way to represent the absence of a number. So counting and tallying 500 things 
was considerably exhausting. 0 allowed people to uniformly represent the absense of something, and it allowed for the use of base 10 couting. In itself, this is a design pattern that allowed the 
human race to evolve from representing numbers in tallys to sequenced digits that communicated the same meaning much faster.
Today, this design pattern is taught as a default because it is a proven best practice to communicating the idea of a number that everyone will understand. 

## Observing patterns
Design patterns in software solve similar problems. They are a best practice for modeling information. I can see a few places where I've used some design patterns in Meteor. 
In figuring out how a user will get notifications from companies that they are following, I think we have been using the 'Observer Pattern' to solve this (or something simliar). 
A reference to each subscribed student is saved within the company collection. When a change in the company happens, each student in that array is notified of the company update. 
We haven't fully figured it out yet but it is intresting to see that how we had diagramed this out to work was an actual design pattern. 
