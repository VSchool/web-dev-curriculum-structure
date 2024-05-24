Write a game that lets a user escape a room. The character finds him/herself locked in a room. In order to escape the room, your character needs to find the key in the room and then open the door. There's also a hole in the wall in the room. If your character puts his hand in the hole, he dies.

# **Game start:**

Tell the user their options:

1. Find the key, or
2. Put hand in hole
3. Open the door
    
    

They can't open the door unless they find the key first.They die if they put their hand in the hole.

# **JavaScript tools that may help**

- while loop
- variables
- booleans
- if/else if/else OR switch statement
- `readline-sync` (syntax for installing and using below)

# **To use `readline-sync` in your game:**

In terminal:

```jsx
# cd into escape room's folder
npm install readline-sync

```

In your JavaScript code:

```jsx
const readline = require("readline-sync");
const name = readline.question("What is your name? ");

```

Problem solving approach:

Attempt this assignment using just the requirements above. If you get stumped, it's ok to read through the following tips. Attempt the problems solving process by yourself first! It's the best way to get better at it.

You may find yourself asking where to start. This program will need to ask the user a question over and over. Because of this, we will need a loop.

The program will ask the same question, but respond in different ways depending on things that vary. Before our loop, we may need to define a couple variables.

I don't want to give away the whole assignment, but imagine we were interested in counting how many times the user was asked a question. We could define `count` and set it to 0. What variables would you want to define before the for loop for the requirements of this assignment?

These variables will toggle. What data type would be good for a toggle?

Make sure you know the difference between the assignment operator `=` and the "is equal to" operators, `==` and `===`.

You will use if statements, and likely nested if statements to solve this code challenge.

console.logs are a must!! Make sure you know what lines in what order will run when the user (you, as the tester) does different things. Console.logs will confirm what you know, or show you where you're thinking about things wrong. You may need a friend to talk it through, but the console will get you in the right direction!

> Remember to submit your assignment by pushing it to Github!