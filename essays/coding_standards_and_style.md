---
layout: essay
type: essay
title: Coding Standards and Style
# All dates must be YYYY-MM-DD format!
date: 2020-09-21
labels:
  - Software Engineering
  - Learning
---
## Using JSLint for Javascript
[//]: # "Many people think of “coding standards” in a trivial way—i.e. minutae such as how many spaces to indent, or whether you place the close-curly-brace on a new line by itself. I, on the other hand, think that if you can only implement one software engineering technique to improve quality, it should be coding standards. Indeed, I believe some coding standards can actually help you learn a programming language. Do you agree? After your first week of using ESLint with IntelliJ, what are your impressions? Are you finding that getting the green checkmark is painful, or useful, or both, or something else entirely? Write an interesting, informative essay on coding standards that addresses some or all of the above questions, or goes in a different direction entirely regarding coding standards. Make sure it provides your personal perspective and useful insights."
Using JSLint in Intellij has been a mostly good experience. The plugin seems to only work as much as is needed to give suggestions for simple problems that would otherwise go unnoticed, and I appreciate the suggested automatic fixes. The one problem I had using it though had more to do with the nature of the language itself, when a library is included in an html file, such as Underscore, and that library is used in a javascript program, it wasn't able to identify what Underscore functions were, and therefore gave warnings to correct code. The nice thing about ESLint is that it allows you to practice good coding standards, and avoid pointless lines and bad habits; along with getting you used to typing in a readable manner.
## Coding Style and Typing Readably
Working on collaborative projects the idea of readble code is a neccessity. This can be described in two ways; the harder being coding clearly, with useful variable names and easy to follow code (ie. not "spagetti code"); and then coding style: how you write and organize comments, where you put whitespaces and brackets, and so on. The first is harder to define, and only comes with practice, but the later could be more defined as coding standards. One such example is how you would write a conditional block.
