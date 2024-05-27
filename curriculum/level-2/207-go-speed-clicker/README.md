# Go Speed Clicker

For this assignment, reference the last two articles. Make a site that tracks how many times the user has clicked anywhere on the page (or a specific button if you prefer) and displays that click count to the user. Then, using localStorage or sessionStorage, make it so the number of clicks will remain on the screen even after the site is refreshed.

**Extra credit:** Put a countdown timer (10-30 seconds) on the page that stops the user's clicks from counting towards the total after the timer ends.

# setTimeout and setInterval

`setInterval` and `setTimeout` are two of the higher order functions in Javascript. Higher order functions take a function as one of their arguments like we see below:

```jsx
setTimeout(function(){});

```

`setInterval` and `setTimeout` provide a way for you to tell your program to run a function or evaluate an expression after a specified amount of time has passed. While the first argument is setting what should happen, the second argument is for setting the time.

```jsx
// setTimeout(arg1, arg2)

setTimeout(function(){}, 1000)

```

The time argument is set in an amount of milli-seconds, meaning 1000 = 1 second. The `setTimeout` above will run that function after 1 second has passed. Let's see an example of this:

```jsx
setTimeout(function(){
   console.log('hello!');
}, 1000);

// 1 second later
'hello!'

```

Set Timeout is great for having your program run a function once, but what if you needed your function to occur every 1 second on a repeated basis? You would use the other method `setInterval()`.

```jsx
setInterval(function(){
   console.log('hello');
}, 1000)

// 1 second
'hello!'
// 2 seconds
'hello!'

```

Now that you have your function running on a specified interval, how do you then tell your program to stop that interval? For this, you will need to first adjust your original setInterval call and store it in a variable:

```jsx
var intervalID = setInterval(function(){
   console.log('hello!')
}, 1000)

```

The variable you assign to setInterval will store the ID for that interval. You can think about the ID being like the off switch for the interval or timeout you set. When you need to have an interval or timeout stopped, you call the `clearInterval(intervalID)` or `clearTimeout(timeoutID)` and pass in the ID of the one you need stopped. Here is a *sudo* example of an interval running for 2 seconds, and then it is cleared with `clearInterval`.

```jsx
var intervalID = setInterval(function(){
   console.log('hello!')
}, 1000);

// 1 second
'hello!'

// 2 seconds
'hello!'

clearInterval(intervalID)

```

Now with those basics let's write a function that outputs some text to the console, and then pass that into setInterval to run on a reoccurring basis.

```jsx
function sayHello(){
   console.log("Hello!");
}

var intervalID = setInterval(sayHello, 1000);

```

This would do the exact same thing as our setInterval from before, but we just wrote the function before calling set interval and then passed the function into it.

> Remember, you would not want to use the ( ) after putting sayHello as the first argument (ex: sayHello( )). Using the ( ) calls a function, and that would tell your program to run that function immediately rather than on the interval you are setting.
> 

**Practice**

Now let's use setInterval and setTimeout together to have a function run every second for 5 seconds, and then have it cleared.

```jsx
function sayHello(){
   console.log('hello!');
}

function stopSayingHello(){
   clearInterval(intervalID)
}

var intervalID = setInterval(sayHello, 1000);

setTimeout(stopSayingHello,  6000)

```

> setTimeout can also be set to a variable if you need to have the setTimeout stop before it executes the function you gave it. Ex: var timeoutID = setTimeout(arg1, arg2). If you did this, you would use the clearTimeout(timeoutID) method instead of clearInterval(setIntervalID)
> 

**Even more practice**

Now that we have a handle on the basics, let's see a practical use of this to make a clock using Javascripts's Date constructor.

```jsx
<body>
    <div>
        <h1 id="time-display"></h1>
    </div>

    <script>
        var display = document.getElementById('time-display');

        function getTime(){
            var now = new Date();
            var hour = now.getHours();
            var min = now.getMinutes();
            var sec = now.getSeconds();

            display.textContent = `${hour}:${min}:${sec}`}

        setInterval(getTime, 1000)
    </script>
</body>

```

If you are following along, you'll notice that when the seconds, minutes, or hours are less than 10, the time looks like this:8:5:2

To fix this, we just need to add a little more logic to our function to tell it to add a '0' before the number if it's less than 10.

```jsx
<body>
    <div>
        <h1 id="time-display"></h1>
    </div>
    <script>

        var display = document.getElementById('time-display');

        function getTime(){
            var now = new Date();
            var hour = now.getHours();
            var min = now.getMinutes();
            var sec = now.getSeconds();
            if(hour < 10){
                hour = `0${hour}`;
            }
            if(min < 10){
                min = `0${min}`;
            }
            if(sec < 10){
                sec = `0${sec}`;
            }

            display.textContent = `${hour}:${min}:${sec}`;
        }

        setInterval(getTime, 1000);
    </script>
</body>

```

More on setInterval and setTimeout can be found [here](https://www.w3schools.com/jsref/met_win_setinterval.asp).

> Remember to submit your assignment by pushing it to Github!