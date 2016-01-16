---
title:  "Why Null Is Not Equal To Null"
date:   2015-07-04 10:30:00 -0500
categories: development
---
I was reading [SQL Antipatterns](http://www.amazon.com/SQL-Antipatterns-Programming-Pragmatic-Programmers/dp/1934356557) by Bill Karwin, and he had a great metaphor for why null is not equal to null.

The gist of it is, null in computer science is similar to the phrase “I don’t know”. If someone asked me the GDP of France I would say “I don’t know”, or null. If they then asked me the GDP of Germany, I would also say “I don’t know,” or null. Even though the answers to both questions are “I don’t know,” that doesn’t mean that the GDP of both countries is the same. It might be, but the only answer to the question “Is the GDP of both those countries the same?” is “I don’t know.” This is also the same of the inverse question,  “Is the GDP of both those countries different?” While the answer might be true, the only answer can be, “I don’t know.”

And that is why null is not equal to null.