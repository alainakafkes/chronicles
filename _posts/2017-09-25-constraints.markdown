---
layout: post
title: "Thinking Inside the Box"
date: 2017-09-25
categories:
---

It's been a little over a month (!!) since I started working at Medium. I've made it through the "I know absolutely nothing" phase, and now I'd place myself on the gradual upward curve of the [Dunning-Kruger effect graph](https://i.stack.imgur.com/aW6bZ.png)... but still near the bottom of that slope of enlightenment.

One month in, I have a gained a better grasp on what I do and don't know.

Becoming cognizant of the limits of my knowledge has paradoxically made me feel more independent. In my third or fourth week, I noticed that I was able to work through tasks and build features myself. I can whip up a solution in code on my own.

As proud as that makes me feel, I am aware that my solutions aren't always the best solutions. In fact, they are often _not_ the best solutions. Sometimes my solutions fall flat because I don't develop them within well-thought-out problem-solving **constraints**.

You bet I just emboldened constraints for a reason. I've long been told that "experience" distinguishes senior software engineers from their junior counterparts, but I never understood what "experience" meant. I abstractly thought that more years of engineering meant a greater likelihood of exposure to a panoply of problems, which in turn generated the skills to handle those problems.

But, last week, I realized that you don't become a senior software engineer just by existing in the industry for a certain number of years. **Senior software engineers are unique in that they have ample experience in determining which rules they must abide by—and which ones they can break—when solving a problem**. Within these constraints, they are able to create code as beautiful as it is functional.

Here are a few examples of what I call constraints:
- This method must utilize [dependency injection](https://en.wikipedia.org/wiki/Dependency_injection) to its fullest.
- This codebase must abide by the model-view-controller pattern.
- This UI element must be able to load in X milliseconds so that the user isn't left hanging.
- This feature must be built with the smallest amount of new code possible.

Why do constraints matter? Well, just as a painter might constrain herself to a canvas of a given size, an engineer who places constraints on a problem must be thoughtful about her solution. **Using constraints ensures that an engineer will come up with a solution that obeys the appropriate regulations, yes, but also one that will push them to their limits**. Thinking _inside_ of the box fosters both resourcefulness and creativity.

Let me illustrate the difference that constraints make in problem-solving.

When I solve problems, I have trouble wrapping my head around many constraints at once. Maybe I write code that matches a design spec but that takes too long to render. Maybe I wrote a method that uses dependency injection, but it over-communicates the details by instantiating unnecessary variables.

So far, I haven't been able to cater to all the right constraints ahead of time. When I submit a pull request for review, it gets flooded with suggestions for improvement.

When a senior engineer takes on a problem, she reflects upon multiple constraints for a while before even touching the keyboard. Some examples of constraint-building actions include drawing a diagram of how a new button should handle touch events, asking questions of a designer about a design spec, and searching for existing, similar code to see how other engineers before her have solved a given problem.

Scoping out a problem with constraints leads to senior engineers producing pull requests that require less iteration than my own because they found a more optimal solution early on. Setting constraints allows them to solve problems more efficiently than me.

I conclude that **well-scoped constraints set senior engineers apart from junior engineers**, so they're something that junior engineers like myself should start to incorporate into our workflow.

Going forward, I intend to reflect upon as many constraints as I can think of before I write code. As I mentioned in a [previous blog post](https://alainakafkes.github.io/chronicles/2017/08/28/feelings.html), I write down accomplishments, lessons, and TODOs at the end of every day. I'll extend this habit by writing down constraints for the problem, feature, or issue that I'm working on in order to scope it out early on.

I challenge all the junior engineers out there to join me in thinking inside the box (of constraints), too.

*To be updated about new posts in the Chronicles of a Junior Dev saga, follow me on [Twitter](https://twitter.com/alainakafkes)!*
