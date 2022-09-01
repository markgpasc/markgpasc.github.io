---
layout: essay
type: essay
title: "The First JS Journey"
# All dates must be YYYY-MM-DD format!
date: 2022-08-31
published: true
labels:
  - Computer Science
---

<img width="250px" class="rounded float-start pe-4" src="../img/JSES6.jpg" alt = "JS ES6 logo">


 
## Initial Thoughts

My first encounter with JavaScript, JS, wasn’t until I began studying Data Structures and Algorithms. At the time, I was learning C and C++, which gave me the foundation to easily understand programming language syntax. The syntax of JS is much like C, which made JS easier for me to understand. While reading solutions to dynamic programming problems I noticed JS is not strictly typed like C. Oftentimes when reading JS code, it’s easier to make sense of an algorithm implementation due to the functionality JS provides.


## The JS way and ES6

Working through the ES6 guide introduced me to new ways of copying objects into other variables for use in a function. Prior to learning JS, I would struggle making sure the functions I wrote had the proper return types. Creating functions in JS with ES6 standards showed me elegant and easier ways of creating functions that I had never seen before. For example, copying array contents and checking for character uniqueness can all be done in one line. 
<br>```function isUnique(str) {return [...new Set(str)].length == [...str].length;}```<br>
Furthermore, returning multiple things types in an array is possible in JS. JS and ES6 standards offer an intuitive and readable code implementation that can be easier to understand for programmers looking at the code.

## Is JS good?

JavaScript is a great language for a new learner to get started with computer programming. Because, a newer programmer will not have to worry about what’s really going on in memory to create a basic function such as copying variables to other variables. A new programmer can write their own code adding functionality to a web application. However, because JS hides a lot of what’s really going on in memory, it can be easy to forget that memory is not infinite. Computer operations come at a hardware cost. As problems become more complex, it's important to understand how programs manage memory. If a new programmer chooses to learn JS, I think it’s worth it to look into what functions are really doing in memory.

## WODs and Athletic Programming Mindset
<img class="rounded float-start pe-4" width="400" height="233" src="../img/keyboard-animegif.gif" alt="quick typing keyboard gif">




Learning any skill takes proper practice and repetition. The athletic programming approach allows me to get reps and practice in while under a time constraint. So far, I’ve found that being under time constraint while working on a WOD is very stressful. However, once I complete the WOD I'm able to better recall the programming practices I’ve employed. After a review of ES6 standards, looking back at a WOD allowed me to create multiple solutions in a basic JS and following ES6 standards. For example, copying function input to an array can be written with ES6 standard in one line using the spread operator. Or, function input can be copied by creating an empty array and using a for loop to copy input to the empty array.
