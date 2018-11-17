---
layout: post
title:  "Thoughts of pre-compiling CSS"
date:   2018-11-14 15:06:54 -0600
categories: jekyll update
comments: true
---

## To pre-compile or not to pre-compile

### Personal thoughts
My personal filosofy is to not add anything if its not  necessary. There should be a very good reason to add even the smallest of libraries, bundler, minifier, development environment with things like three shaking, HMR and so on. Its not that the functionality is bad per se but for alot of environment it doesnt add anything to the actual end result but add overhead, complexity and startup times and so on... JavaScript fatigue is very real and should not be encouraged.

When it comes to using a preprocessor such as Sass and Less there is reaason to add it when the project becomes more dependant on personal styleing and serveral components getting a rehaul from what is being shown as standard. The namespacing techniques are great and so are variables and mixins. These are making deveopment and maintenence of so much easier. Everything build doesnt need and enterprise level boilerplate.

### For the project
Used variables and nesting to create namespaces. Had some mixins at one point just for the hell of it but the became pretty redundant and got removed. Have som variables for the the potential additional components using the same. Same principles for CSS as with JS — keep it DRY and simple. Dont overdo nesting, never more than three levels is good guideline i found.

### Conclusion
The syntax provided for writing LESS/STYLUS/SASS solves problems that native CSS cant do by itself today. In the future will CSS have this functionality build in and the middle step of compiling it down to regular css will not be necessary.

Custom properties, a soon to standard functionality of native CSS, can store varialbes and functions.

> Less is more, ditch LESS
