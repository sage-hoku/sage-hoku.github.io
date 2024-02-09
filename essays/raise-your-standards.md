---
layout: essay
type: essay
published: true
title: "Raise Your Standards: Setting the ground rules with ESLint"
date: 2024-02-08
labels:
- Javascript
- IntelliJ
- ESLint
---
<img class="img-fluid" src="../img/eslint/ESLint-Clickbait.jpg" alt="">
<h2>Good code means less work</h2>When it comes to software engineering, one of the most easily overlooked topics is the way we format the code we write.  Yet, writing script in a neat, understandable way is one of the most essential ways we can communicate our code's uses and functionality with each other. On top of that, writing clean code helps to ensure the readability and re-usability of our programs, ensuring functions can be read at a glance and reducing time spent debugging and fixing formatting errors. I really didn't care much for coding standards until our class delved into ESLint, thinking they were a collection of mostly insignificant constraints, but now I can kinda see that they're useful on both a personal and professional scale.

<h2>The lint adds up</h2>
Certainly, many minute details like the number of spaces in a tab, or whether you choose to put your 'else' in front of a curly brace or below it, are arbitrary constraints that can often change how, and whenever, we need them to. Fortunately, coding standards can be helpful for much more than just making a file look put-together. I learned through using ESLint that the rules we use to format our code provide a common framework of guidelines not only to adhere to, but also to rely upon. Each rule represents the result of a rational line of logic, and learning and following it will inevitably save precious time and brainpower in the long run. ESLint also allows for custom rules to be created, setting the foundation to further streamline a user's workflow.

<h2>Seeing red</h2>
...Despite all this, I really, truly hated ESLint starting out with it. We implemented the coding standard's rules into our IDE, IntelliJ, with its settings configured to flag each rule violation as an outright error. This caused bright red squigglies to appear under code snippets it deemed "incorrect", which I found could be a little frustrating during our timed assignments. For general coding, the extra on-screen noise initially seemed like it would be a problem, but as I got used to it with time, some of the more common rules wormed their way into my unwrinkled brain. I began to enjoy watching the errors disappear as the file's auto-format command would run, and once or twice, manually moving the lines around as the editor suggested revealed a few problems with the way <i>I</i> had written a statement. All in all, I still have yet to fully adjust to ESLint, but definitely would rather code with it than to brave the depths of the editor alone.



