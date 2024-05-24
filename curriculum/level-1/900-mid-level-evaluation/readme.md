# Mid Level 1

This is a time for you to test your coding skills and prepare yourself for an interview. Below you will see two code challenges for you to complete. You will also need to add comments or pseudo-code to your project in order to talk through your process and solutions. Next, you will complete a quiz that will test the knowledge you have gained so far. Once you have completed the challenges, schedule an assessment to review with an instructor where you will complete a third coding challenge live!

HTML

```jsx
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Events</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 id="heading">Hello, World!</h1>
		<p>I'm a paragraph</p>
    <button id="changeButton">Change Text</button>
    
    <script src="script.js"></script>
</body>
</html>

```

### Instructions for Using the HTML File:

1. **Copy the HTML Code:**
    - Copy the provided HTML code from the browser or text editor.
2. **Open Visual Studio Code (VS Code):**
    - Open Visual Studio Code (VS Code) on your computer.
3. **Create a New File:**
    - Create a new file in VS Code.
4. **Paste the HTML Code:**
    - Paste the copied HTML code into the new file.
5. **Save the File:**
    - Save the file with an appropriate name and the `.html` extension (e.g., `index.html`).
6. **Open the HTML File in a Browser:**
    - Double-click the saved HTML file to open it in your default web browser.
7. **Verify Functionality:**
    - Upon opening the HTML file in a browser, you should see the text "Hello, World!" displayed as the heading.
8. **Continue with Next Steps:**
    - Once you have confirmed that the HTML file is displaying correctly, you can proceed with completing the JavaScript challenges as described below.

## Code Challenges

### Challenge 1: Change Text Content (DOM Manipulation)

### Problem Statement:

Create a function called **`changeTextContent`** that changes the text content of an HTML element with a specific ID.

### Instructions:

1. Write a JavaScript function called **`changeTextContent`** that takes two parameters:
    - `elementId`: The ID of the HTML element whose text content needs to be changed.
    - `newText`: The new text content to be set for the element.
2. Inside the function, use `document.getElementById()` to select the HTML element with the specified `elementId`.
3. Set the `textContent` property of the selected element to the value of `newText`.
4. Test the function by calling it with different element IDs and new text content.

### Example:

```jsx
function changeTextContent(elementId, newText) {
 // your code goes here
}

// Test the function with different element IDs and new text content
changeTextContent('heading', 'Welcome to my website!');
changeTextContent('paragraph', 'This is a sample paragraph.');

```

### Challenge 2: Add Event Listener (DOM Events)

### Problem Statement:

Create an event listener for a button element that changes the text content of another HTML element when clicked.

### Instructions:

1. Write JavaScript code to add an event listener to a button element in the HTML file.
2. When the button is clicked, call the `changeTextContent` function (from Challenge 1) with appropriate parameters to change the text content of another HTML element.
3. Test the event listener by clicking the button and verifying that the text content of the specified HTML element is updated accordingly.

>Make sure to take the mid-level quiz as well!

> Remember to submit your assignment by pushing it to Github!