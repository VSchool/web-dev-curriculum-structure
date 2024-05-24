# String Methods Exercise

Write a function that takes a string as a parameter and returns the same string in all capital letters followed by all lowercase letters.

```jsx
capilizeAndLowercase("HelLo") // => "HELLOhello"

```

---

Write a function that takes a string as a parameter and returns a number that is half the string's length, rounded down.

> Hint: You'll need to use Math.floor().
> 

```jsx
findMiddleIndex("Hello") // => 2
findMiddleIndex("Hello World") // => 5

```

---

Write a function that uses `[slice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)` and the other functions you've written to return the first half of the given string.

```jsx
returnFirstHalf("Hello") // => "He"
returnFirstHalf("Hello World") // => "Hello"

```

---

Write a function that takes a string as a parameter and returns that string where the first half is capitalized, and the second half is lowercase.

> Hint: If your string length is odd, use Math.floor() to round down.
> 

```jsx
capilizeAndLowercase("Hello") // => "HEllo"
capilizeAndLowercase("Hello World") // => "HELLO world"

```

---

### **Optional Code Challenge**

> (This one is a step up in difficulty and utilizes the .split() string method and .join() array method):
> 

Write a function that takes a string as a parameter and capitalizes any character that follows a space.

```jsx
capitalize("hey friends! practice practice practice!") // -> "Hey Friends! Practice Practice Practice!"
```

> Remember to submit your assignment by pushing it to Github!