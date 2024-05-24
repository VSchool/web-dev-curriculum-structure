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



## Submitting your assignment

To submit your assignment, you need to push your changes to GitHub. Follow these steps:

### Using Git Command Line

Follow these steps to push your changes to GitHub using Git command line.

Open your Terminal and follow the steps below:


1. **Add Your Changes**: Add the files you have worked on. If you want to add all changes:
   ```git add .```

   If you want to add only a specific folder, use:
   ```git add path/to/your/folder```

2. **Commit Your Changes**: Commit the changes with a meaningful message:
   ```git commit -m "Add assignment submission for [your name]"```

3. **Push to GitHub**: Push the changes to the GitHub repository:
   ```git push origin main```

### Using VSCode's Source Control

Alternatively, you can use VSCode's built-in Source Control feature:

1. **Open the Repository**: Click on the source control tab in VSCode.

2. **Stage Your Changes**: Stage the files you want to submit by clicking the "+" icon next to each file or folder in the Source Control view.

3. **Commit Your Changes**: Enter a commit message in the text field at the top of the Source Control view and press Enter to commit your changes.

4. **Push to GitHub**: Click the three dots (...) in the top-right corner of the Source Control view and select "Push" from the dropdown menu to push your changes to GitHub.

### Example: Pushing a Specific Folder

If you only want to push changes from a specific folder (e.g., `assignments/week1`), you can do so using either method above.

By following these steps, you can successfully submit your assignment to GitHub using either Git command line or VSCode's Source Control.
