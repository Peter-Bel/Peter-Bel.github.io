---
layout: essay
type: essay
title: "Reflection on Typescript Bootcamp"
# All dates must be YYYY-MM-DD format!
date: 2023-01-23
published: true
labels:
  - Programing
  - Learning
---

<img width="200px" class="rounded float-start pe-4" src="../img/typeS_im.png">

I have never used Typescript in all my programming experience. But, so far Typescript seems to be a userfriendly and competent programming language. When first using the language, I felt it was most similar to JavaScript. This observation was accurate as I would learn that Typescript is a syntatic superset of JavaScript. Since I have plenty of experience with JavaScript, a lot of the basics of the language felt intuitive to learn. 

###TypeScript and JavaScript

While very similar to JavaScript, there are many important differences between JavaScript and Typescript. Most notably, the syntax and compatibility of both languages work a bit differently. Typescript is statically typed while JavaScript is dynamically typed. This means that variables in Typescript must be declared when they’re created, but in JavaScript, the variable doesn’t have to be declared. There’re also minor changes to mathematical functions (JavaScript uses “==” while TypeScript uses “===”) and initializing functions. Another major difference that I’ve yet to fully experience with is that Typescript can compile into JavaScript. This effectively allows the user to develop a program in both languages which can speed up a lot of the programming process. I have yet to use this utility of Typescript, but I feel like this makes the language quite effective from a software engineering standpoint. Programming in Typescript is also programming in JavaScript, and with the support tools provided to the Typescript language, it can improve the overall code quality of a project.  

###Work through WODs

One of the first WODs I worked on was a simple algorithm that detects if a string is fully made of unique characters. Even with this simple algorithm, there's a clear difference in how functions are initialized. The Typescript code uses Collins to specify the static data type used while JavaScript doesn’t. But, other than that, the code was quite similar to JavaScript and easy to get used to. Here’s the code in full:

```cpp
function isUnique(str: string): boolean {
    const seen: Map<string, boolean> = new Map();
    for (let i = 0; i < str.length; i ++) {
        const l = str[i];
        if (seen.get(l)) return false;
        else seen.set(l,true);
    }
    return true;
}
console.log(isUnique('abcde'));  // prints true
console.log(isUnique('abcdea')); // prints false
```
So far, the WODs have been interesting and simple to learn, and the “athletic programming” format that the WODs enable helps to gain experience in fast programming. It’s a great form of practice to improve the speed and memory at which I can write code. Since better speed is rewarded, there’s a greater incentive to write quickly and activate my computational neural pathways.

###Final thoughts

