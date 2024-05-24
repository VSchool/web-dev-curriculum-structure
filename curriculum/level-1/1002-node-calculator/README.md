# Node Calculator

You are going to create a calculator in pure JavaScript using `NodeJS` and `readline-sync`.

### **Your script must have:**

- A function that adds two numbers and returns the result
- A function that multiplies two numbers and returns the result
- A function that divides two numbers and returns the result
- A function that subtracts two numbers and returns the result
- Each function will have 2 parameters, `num1`, `num2`
- On the console the prompt will print to the user:
- *Please enter your first number* (store that number)
- *Please enter your second number* (store that number)
- *Please enter the operation to perform: **add**, **sub**, **mul**, **div*** (then store the operation)
- Based on the operation entered by the user, you will call one of your 4 functions to perform the correct operation
- You will then print to the console: *The result is: [the result]*

### **To get set up:**

- `cd` into the folder you'll be working in.
- run `npm install readline-sync`
- At the top of your JS file, include `**const readline = require("readline-sync")**`
- For documentation on the `readline-sync` package, check out the [readline-sync docs on npmjs.org](https://www.npmjs.com/package/readline-sync)
- There are two places we run JavaScript. The browser and node. Only node has `require` defined, so you’ll need to run your file with `node filename.js`

Tips:

Spend some time making sure you know the difference between a function call's "argument" and a function's "parameter".

- You will have an if statement run a different function depending on what the user chooses on the third readline prompt.
    
    ```js
    const operator = readlinesync.keyIn("do you want to (a)dd, (s)ubract, (d)ivide, or (m)ultiply?")
    
    if(){
    
    }
    ```
    

A function can take values as arguments and a function will return a value. If you console log the function call, you can see that value.

```js
console.log(add(3, 4))
```

> Remember to submit your assignment by pushing it to Github!