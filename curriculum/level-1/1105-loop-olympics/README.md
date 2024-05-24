# Loop Olympics

For this exercise you are only **required** to complete the **Preliminary** and **Bronze** medal portions. Once you have completed these two portions you are allowed to move on in the curriculum. This exercise will get progressively more difficult with each challenge. The Silver and Gold medal portions of this exercise are **optional**. You are welcome to attempt these additional challenges if you would like to go the extra mile!

---

# **Preliminaries**

1. Write a for loop that prints to the console the numbers 0 through 9.
2. Write a for loop that prints to the console 9 through 0.
3. Write a for loop that prints these fruits to the console.`**const fruit = ["banana", "orange", "apple", "kiwi"]**`

---

# **Bronze Medal**

1. Write a for loop that will push the numbers 0 through 9 to an array.
2. Write a for loop that prints to the console only even numbers 0 through 100.
3. Write a for loop that will push every other fruit to an array.
`const fruit = ["banana", "orange", "apple", "kiwi", "pear", "peach"]`

---

# **Silver Medal**

1. Write a loop that will print out all the names of the people of the people array
2. Write a loop that pushes the names into a `names` array, and the occupations into an `occupations` array.
3. Write a loop that pushes every other name to an array starting with the first person, in this case "Harrison Ford", and every other occupation to *another* array starting with, in this case, "Singer".

Think about what good names for the arrays would be. Since it will be an array of each name or occupation, the plurals of name and occupation would be appropriate.

```jsx
const peopleArray = [
  {
    name: "Harrison Ford",
    occupation: "Actor"
  },
  {
    name: "Justin Bieber",
    occupation: "Singer"
  },
  {
    name: "Vladimir Putin",
    occupation: "Politician"
  },
  {
    name: "Oprah",
    occupation: "Entertainer"
  }
]

// ["Harrison Ford", "Vladimir Putin"] // names
// ["Singer", "Entertainer"] // occupations

```

---

# **Gold Medal - Nesting**

1. Create an array that mimics a grid like the following using nested `for` loops:

```jsx
[[0, 0, 0],
[0, 0, 0],
[0, 0, 0]]

```

2.Create an array that mimics a grid like the following using nested `for` loops:

```jsx
[[0, 0, 0],
[1, 1, 1],
[2, 2, 2]]

```

3.Create an array that mimics a grid like the following using nested `for` loops:

```jsx
[[0, 1, 2],
[0, 1, 2],
[0, 1, 2]]

```

1. Given a grid like the previous ones, write a nested `for` loop that would change every number to an x.

```jsx
var grid = [["x", ...],
            ["x", ...],
            ["x",...], ...]

```

### **A bigger picture**

You'll begin to learn even more how important arrays are in development. The optional challenges in this practice use nested arrays. These are used to represent grids. Many board games would be simulated using 2 dimensional arrays.

### **If you get stuck**

This is a top go to pattern for code challenges:

1. Define your accumulator - [], {}, 0, or ""
2. Build on it using your for loop
3. return or log your accumulator

> Remember to submit your assignment by pushing it to Github!