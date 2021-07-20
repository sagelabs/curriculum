---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.

    // An array characters:
    let c = ['h', 'e', 'l', 'l', 'o', ' ', 'w', 'o', 'r', 'l', 'd'];

    // Type your code here:

---

# Array of Character to a String

---

## Content

> 👩‍💻 Your task is to write a program that will:
> - **take an array of characters as input**
> - **transform it into a string**
> - **output the result**

Example array to use:
```javascript
let c = [
  'h', 
  'e', 
  'l', 
  'l', 
  'o', 
  ' ', 
  'w', 
  'o', 
  'r', 
  'l', 
  'd'
];
```


To achieve this, you can use the following concepts:
- function declaration (`function something(x) { ... }`)
- flow control (`for...of`)

Learning is best when we give it an honest try. Even if we make a mistake, we'll remember it and do better next time.

That being said, if you're not sure how to get started, check out this footnote[1]. 

When you're finished, feel free to share your solution with the community, join in on discussions and upvote solutions from your fellow learners!

Remember, learning is more effective when we do it with others.

> 💡 Take a look at [how you can format text using markdown](https://www.enki.com/glossary/general/markdown-formatting).

> 💡 The guidelines above are just suggestions. Feel free to include other concepts in your solution as you see fit. The implementation is up to you.

> 🤓 Happy learning! Open the playground and start coding!


---

## Footnotes

[1: Hints]

Create an empty string and use a `for...of` loop to go through every character of the array, concatenating each character to the empty string.