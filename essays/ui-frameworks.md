---
layout: essay
type: essay
title: "UI with purpose"
# All dates must be YYYY-MM-DD format!
date: 2025-02-27
published: true
labels:
  - HTML
  - CSS
  - Bootstrap 5
summary: "Detailing my experience with HTML, CSS, and Bootstap 5."
essayurl: https://peter-bel.github.io/essays/ui-frameworks.html
---

<img width="200px" class="rounded float-start pe-4" src="../img/html_css_boot.png">

I have very limited experience with HTML and CSS, and I have absolutely no experience when it comes to using UI frameworks like Bootstrap 5. So, as one can imagine, my learning experience with HTML and Bootstrap 5 has been very difficult. HTML is a very unique langauge that takes a lot of adjustment, and Bootstrap 5 also take as much time to get used to as any other langauge. 

# HTML and CSS

While very similar to JavaScript, there are many important differences between JavaScript and TypeScript. Most notably, the syntax and compatibility of both languages work a bit differently. TypeScript is statically typed while JavaScript is dynamically typed. This means that variables in TypeScript must be declared when they’re created, but in JavaScript, the variable doesn’t have to be declared. There are also minor differences in syntax, such as how mathematical equality is handled: JavaScript uses “==” for loose equality and “===” for strict equality, while TypeScript emphasizes static type-checking and often enforces stricter comparisons. Another major difference is that TypeScript can compile into JavaScript. This effectively allows the user to develop a program in both languages which can speed up a lot of the programming process. I have yet to use this feature of TypeScript, but I feel like this makes the language quite effective from a software engineering standpoint. Programming in TypeScript is also programming in JavaScript, and with the support tools provided to the TypeScript language, it can improve the overall code quality of a project.

# Bootstrap 5

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

# Experiences and Challenges

# Final thoughts

I don't find much utility in using UI frameworks at the moment. I've yet to learn how to properly use all the main functions provided by HTML and CSS. This makes implimenting a different UI framework both difficult and confusing. 
