# Problem Solving Practice

Write a function that takes an array of numbers and returns the largest (without using `Math.max()`)

```jsx
// test data
console.log(largest([6, 13, 250, 3)) // => 250
console.log(largest([3, 5, 2, 8, 1])) // => 8
console.log(largest([-13, 40, 3, 0, 19, 22])) // => 40
```

---

Write a function that takes an array of words and a character and returns each word that has that character present.

```jsx
// test data
console.log(lettersWithStrings(["$hello!", "%%^%%", "test!"], "!") => // => ["$hello!", "test!"]
console.log(lettersWithStrings(["#3", "$$$", "C%4!", "Hey!"], "!"))  // => ["C%4!", "Hey!"]
console.log(lettersWithStrings(["yellow", "green", "^up^", "down", "dog"], "h"))  // => []
```

---

Write a function that takes a num1 and num2 and returns whether num1 is divisible by num2.

```jsx
// test data
console.log(isDivisible(4, 2)) // => true
console.log(isDivisible(9, 3)) // => true
console.log(isDivisible(15, 4)) // => false

```

### **A Bigger Picture**

Breaking problems down into approachable problems is an important skill. The [four steps of the problem-solving process](https://coursework.vschool.io/problem-solving/) are a good place to start.

The more of these puzzles you solve, the more patterns you'll see. It'll take time and focus to develop the deductive reasoning to use old patterns you've seen to solve new problems.

Having the syntax memorized and a good understanding of the tools available to you will really help, but much of that will come with practice.

### **If you get stuck**

Remember to log your function call:

```jsx
console.log(isDivisible(4, 2))

```

If that command logs `undefined`, it's likely because the function isn't returning anything. Make sure your function is returning something!

That something will likely get defined before a for loop and returned after.

Making sure you've done step 1 correctly (understanding the problem) will save you heartache in any code challenge problem-solving.

> Remember to submit your assignment by pushing it to Github!