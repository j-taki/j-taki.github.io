---
layout: essay
type: essay
title: Linters n' stuff
# All dates must be YYYY-MM-DD format!
date: 2019-02-07
labels:
  - coding
  - best-practices
---

# I demand order!
So here I am writing some javascript or ruby and I'm in the flow of things. As I'm writing, I'm not concerned with writing clean code or design patterns; I just want to make the dang thing work. Really that is the most fun part of it all anyways right? Who even enjoys refactoring? Well, lucky for people like us there are code linters like ESlint and Rubocop. Linters allow you to code and will check your work in real time to make sure you are using best practices in syntax and styling.

## But Why
I too have preferences on how I like to indent and style some parts of my code. I personally like spaces between my argument parentheses so I can see the value names easier. However, Coding standards exist for much more important reasons than to be one person's annoyance. Imagine working on a team of 10 people, and while some of them like tabs, others like spaces. Without the team agreeing to one standard, each line in a file might be subject to different styles depending on who wrote it. So optimistically a team is following the same standards.

## Generally Accepted Standards
But wait standards get better. Why create your teams own standards when you can just use someone else's right? AirBnB's ES6 standards are well received in the JS community. Being familiar with common best practices of a language will make it easier for teams to onboard new people who are also familiar with those rules. It also means that you as an individual now have found a well traversed path of learning.

The most important part about following a coding standard is that as we try to understand someone else's code (coworker, teammate, random github repo owner) it makes it that much easier to follow their thought process. I've seen some people strive to fit complex methods onto one line as a challenge, but is chaining and nesting methods together really literate? Imagine how much effort it took to fit it all onto one line, and then imagine how much effort it would take for someone else to decypher. In the book clean code uncle Bob even says that methods ideally aren't more than 4 lines long. I think that writing clean code is important and to do so, we must always keep understandability at the top of mind.

# Using ESLint
ESlint is supported in many IDEs like Idea, VSCode, or Atom. The beautiful part of this specific linter and using the AirBnB style guide is that not only will it underline the error for you, it will actually suggest an improvement to your code. Sure its not perfect, and in some cases may be outright annoying; but consider how the benefits outweigh the costs.