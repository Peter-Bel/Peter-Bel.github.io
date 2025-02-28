---
layout: essay
type: essay
title: "My Developer Trials through TypeScript"
# All dates must be YYYY-MM-DD format!
date: 2025-01-23
published: true
labels:
  - Programing
  - Learning
summary: "An essay detailing my experience working with Typescript."
essayurl: https://peter-bel.github.io/essays/typescript.html
---

<img width="200px" class="rounded float-start pe-4" src="../img/typeS_im.png">

I have never used TypeScript in all my programming experience. But, so far TypeScript seems to be a userfriendly and competent programming language. When I first started using the language, I noticed it felt very similar to JavaScript. This observation turned out to be accurate as I learned that TypeScript is a syntactic superset of JavaScript. Since I have plenty of experience with JavaScript, a lot of the basics of the language felt intuitive to learn. 

# TypeScript and JavaScript

While very similar to JavaScript, there are many important differences between JavaScript and TypeScript. Most notably, the syntax and compatibility of both languages work a bit differently. TypeScript is statically typed while JavaScript is dynamically typed. This means that variables in TypeScript must be declared when they’re created, but in JavaScript, the variable doesn’t have to be declared. There are also minor differences in syntax, such as how mathematical equality is handled: JavaScript uses “==” for loose equality and “===” for strict equality, while TypeScript emphasizes static type-checking and often enforces stricter comparisons. Another major difference is that TypeScript can compile into JavaScript. This effectively allows the user to develop a program in both languages which can speed up a lot of the programming process. I have yet to use this feature of TypeScript, but I feel like this makes the language quite effective from a software engineering standpoint. Programming in TypeScript is also programming in JavaScript, and with the support tools provided to the TypeScript language, it can improve the overall code quality of a project.

# Work through WODs

One of the first WODs I worked on was a simple algorithm that detects if a string is fully made of unique characters. Even with this simple algorithm, there's a clear difference in how functions are initialized. The TypeScript code uses annotations to specify the static data type used while JavaScript doesn’t. But, other than that, the code was quite similar to JavaScript and easy to get used to. Here’s the full code documentation:

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

# Final thoughts

From my short time learning, I found Typescript to be an intuitive and useful programming language. It’s similar to other languages I know, but it’s also different enough to hold its own unique utility. I hope to further my abilities with this language and utilize it effectively in the future. 
