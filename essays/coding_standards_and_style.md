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
Working on collaborative projects the idea of readble code is a neccessity. This can be described in two ways; the harder being coding clearly, with useful variable names and easy to follow code (ie. not "spagetti code"); and then coding style: how you write and organize comments, where you put whitespaces and brackets, and so on. The first is harder to define, and only comes with practice, but the later could be more defined as coding standards. One such example is how you would write a conditional block:
```js
if (condition)
{
  //Here is one way to write a block
}
if (condition2) {
  //Here is another common way to write a block
}
```
Both are correct ways to write a block; they are easy to read, and both functionally work exactly the same: compilation gets rid of whitespace anyways, and both take the same amount of memory and storage after compilation. However, despite ESLint thinking either is fine, I was told by someone I shouldn't have used the first method, and that I should have used the second. This is where I disagree with coding standards: in this case someone else's standard. In order to understand why I disagree, you must first look back to the point of coding standards: to make readable, and easy to understand code. This does not mean that there is one standard to rule them all, but instead there are a few rules to abide by when creating your own style. There are certainly ways you could make a bad style, but equally there are multiple countless "correct ways" to style your typing, whitespace, and comments. Style in code has one purpose and one purpose only, to make code more readable; so to say that there is only one way you should style your code, is a fruitless waste of time and energy; and as I have used and honed my personal style without problems, readability or functionality-wise, it was even insulting in a way.
## Final Thoughts on Coding Standards
When I think of readablity I like to think back to my ICS 212 professor's analogy; that when programming was new, computers were relatively slow, and extremely expensive, while programmers were cheap: so the computer was prioritized, and efficiency and number of lines were most important, because running the computer for longer would cost the comnpany money. Nowadays powerful computers are relatively cheap, but programmers are not, so now a company's best interest is the programmer; and so readability, and simplicity, are key to a company making a better use of their money.

So in this case, coding style is greatly important, even costing the company; however, if you're spending more time trying to fit someone else's style to a T, you'll end up wasting time trying to make it look "pretty" for them, instead of writing in your own efficient and also readable style that you're already used to typing; and ultimately, wasting time, not coding.
