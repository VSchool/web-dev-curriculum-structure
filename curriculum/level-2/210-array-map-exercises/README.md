# Array Map Exercises

<aside>
💡 Feel free to copy and paste the function and tests in this assignment.

</aside>

### **1) Make an array of numbers that are doubles of the first array**

```jsx
function doubleNumbers(arr){
  // your code here
}

console.log(doubleNumbers([2, 5, 100])); // [4, 10, 200]

```

---

### **2) Take an array of numbers and make them strings**

```jsx
function stringItUp(arr){
  // your code here
}

console.log(stringItUp([2, 5, 100])); // ["2", "5", "100"]

```

---

### **3) Capitalize the first letter of each name and make the rest of the characters lowercase**

```jsx
function capitalizeNames(arr){
  // your code here
}

console.log(capitalizeNames(["john", "JACOB", "jinGleHeimer", "schmidt"])); 

// Output:
// ["John", "Jacob", "Jingleheimer", "Schmidt"]

```

---

### **4) Make an array of strings of the names**

```jsx
function namesOnly(arr){
  // your code here
}

console.log(namesOnly([
    {
        name: "Angelina Jolie",
        age: 80
    },
    {
        name: "Eric Jones",
        age: 2
    },
    {
        name: "Paris Hilton",
        age: 5
    },
    {
        name: "Kayne West",
        age: 16
    },
    {
        name: "Bob Ziroll",
        age: 100
    }
]));
// ["Angelina Jolie", "Eric Jones", "Paris Hilton", "Kayne West", "Bob Ziroll"]

```

---

### **5) Make an array of strings of the names saying whether or not they can go to The Matrix**

```jsx
function makeStrings(arr){
  // your code here
}

console.log(makeStrings([
    {
        name: "Angelina Jolie",
        age: 80
    },
    {
        name: "Eric Jones",
        age: 2
    },
    {
        name: "Paris Hilton",
        age: 5
    },
    {
        name: "Kayne West",
        age: 16
    },
    {
        name: "Bob Ziroll",
        age: 100
    }
]));
// ["Angelina Jolie can go to The Matrix",
// "Eric Jones is under age!!",
// "Paris Hilton is under age!!",
// "Kayne West is under age!!",
// "Bob Ziroll can go to The Matrix"]

```

---

### **6) Make an array of the names in `h1`s, and the ages in `h2`s**

```jsx
function readyToPutInTheDOM(arr){
  // your code here
}
console.log(readyToPutInTheDOM([
    {
        name: "Angelina Jolie",
        age: 80
    },
    {
        name: "Eric Jones",
        age: 2
    },
    {
        name: "Paris Hilton",
        age: 5
    },
    {
        name: "Kayne West",
        age: 16
    },
    {
        name: "Bob Ziroll",
        age: 100
    }
]));
// ["<h1>Angelina Jolie</h1><h2>80</h2>",
// "<h1>Eric Jones</h1><h2>2</h2>",
// "<h1>Paris Hilton</h1><h2>5</h2>",
// "<h1>Kayne West</h1><h2>16</h2>",
// "<h1>Bob Ziroll</h1><h2>100</h2>"]
```


> Remember to submit your assignment by pushing it to Github!