---
layout: post
title:      "JavaScript Syntax"
date:       2019-06-21 20:26:35 +0000
permalink:  javascript_syntax
---


For this blog I want to do a rundown of key takeaways for JavaScript syntax, especially some topics that clicked best for me upon review.

# Semicolons
As a copy editor, the fact that I could run my code with or without a semicolon at the end of each statement really began to stress me out. This is covered first thing in the JS curriculum, but it really only clicked for me once I'd done a lot of coding myself. JavaScript syntax *does* require semicolons, but the semicolons can be entered either by the user or by *automatic semicolon insertion*, where the JavaScript does just that -- automatically inserts semicolons into our code. Either way works, but the code always runs with semicolons.

# Arrow Functions
Arrow functions, at first, seemed a little...underwhelming. For a very simple example, this code:
```
function notArrow() {
return "Hello"
}
```
will return the same thing ("Hello") as this code:
```
var arrow() => {
return "Hello"
}
```

However, once arguments are added, the clean up and enhanced readability become more clear.
Here's a basic function written with arrow syntax.
```
var withArg(x) => {
return x
}
```
When there is an argument the parens are optional. (Note that for no arguments, like arrow(), the parens *are* required). We can clean up a little and arrive at this:
```
var withArg = x => {
return x
}
```
Finally, the arrow function gives an implicit return. We can express the same function like this:
```
var withArg = x => x
```
All three of these will return x, but with knowledge of arrow functions, the third is much simpler and much more readable.
