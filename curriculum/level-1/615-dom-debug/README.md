# Troubleshooting DOM Issues

> Important Note: This assignment is designed to challenge your troubleshooting skills. It's meant for individuals who are confident in their ability to solve complex problems. If you find yourself genuinely stuck, you can reveal the final section on this page, which serves as a guide. Keep in mind that this guide is a work in progress, and don't hesitate to seek help if you're stuck for more than 10 to 15 minutes.

---

## Getting Started

1. **Clone the Repository**
    
    ```bash
    git clone https://github.com/VSchool/dom-debug
    ```
    
2. **Delete `.git` Folder**
    
    ```bash
    cd dom-debug
    rm -rf .git
    ```
    
3. **Open `index.html` in Browser**
    
    Open the `index.html` file in your preferred browser. The instructions are based on using the Chrome developer tools, but Firefox and Opera are also compatible.

---

## Objective

Your objective is to add new items to a list and independently change the background of each item. The text for each item should be extracted from an input box. You can start with either a white or red background for each item.

---

## Troubleshooting Steps

1. **Address Console Errors**
    - Start by tackling any console errors that appear.
2. **Explore the Sources Tab**
    - If there are no immediate console errors, navigate to the `sources` tab in your browser's developer tools.
3. **Set Breakpoints**
    - Instead of using multiple `console.log` statements, utilize breakpoints to pause code execution at specific lines.

---

1. **Independent Troubleshooting**
    - After setting breakpoints, trigger the action that should invoke the function.
2. **Code Correction and Iteration**
    - Attempt to identify and fix the issue on your own by analyzing the code and applying your understanding of programming concepts.
3. **Collaboration and Asking for Help**
    - If your individual troubleshooting efforts aren't yielding results, don't hesitate to ask for assistance.

### **Additional Strategies**

- **Handling Property Errors**
    - If you encounter errors related to properties not being found, it often means you're trying to access a property on an undefined object.
- **Inspecting Objects with `console.dir()`**
    - Use the `console.dir()` function to print the properties and values of objects to the console, allowing you to inspect their structure.
- **Using Conditional Breakpoints**
    - Set breakpoints with conditions to pause execution only when specific conditions are met.

> Remember to submit your assignment by pushing it to Github!