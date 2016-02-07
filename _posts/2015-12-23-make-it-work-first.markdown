---
title:  "Make It Work First"
date:   2015-12-23 08:45:00 -0500
categories: software-development life-lessons
---
As I became more experienced in software development and started to tackle more complicated problems, one of the issues I would sometimes have is that it can feel hard to just get started. I would feel paralyzed because I would want everything to be perfect from the start. This was also partly caused as I was learning more and more development best practices, and wanting to use all of them in every project, right from the get-go. What I ended up discovering is that the best advice is to just make something that works, even if it’s not the best solution possible. In writing the first draft is just about getting the words down on paper—the real magic comes after multiple rewrites. Similarly, in software development, if you have something that works, you can gradually refactor it until it becomes what you want it to be.

When starting a hard problem, some best practices that I don’t worry so much about now:

* Hard-coding values
* Excessive copying and pasting
* Descriptive variable names
* Caching data
* Efficient data structures
* General performance
* Factoring out shared functionality into separate functions
* Good documentation

Pretty much the only thing I try to do in a first draft is create an implementation that works, and is reasonably clear about what I am trying to do and how I am doing it. Once that is done, it becomes much easier to implement some of the more advanced software development techniques in the list above that were previously ignored. Some of them become much easier, for instance creating descriptive variable names. On the first pass it can be very difficult to give variables good names, as you’re not really sure what they really represent, or even what you’re trying to do. Looking back after you have a working implementation however, it is always much clearer, and it can be humorous how inappropriate your original name were. Creating shared constants and functions also works the same way, as it is much easier to see where code is duplicated and what the common factors are.

In short, make it work and then make it perfect, and you’ll never go wrong.
