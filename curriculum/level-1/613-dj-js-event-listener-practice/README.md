# DJ JS - Event listener practice

You're starting your business as a strictly online DJ (DJ JS) and you want to start by creating a website where people can change the color of a square on the page by interacting with different HTML Events.

The square's color will change as follows:

- Blue when the mouse hovers over the square
- Red when the mouse button is held down over the square
- Yellow when the mouse button is let go over the square
- Green when the mouse is double clicked in the square
- Orange when the mouse scroll is used somewhere in the window (not just over the square).
- You should also be able to press the first letter of the colors (typing "r" on the keyboard for "red", for example) and have the box change to that color. Check out the key and keyCode property of `e.target`

Attempt these requirements. If you become discouraged, included are things to consider.

Take a minute to think through how you would implement all of these event listeners.

You will need a different event for each event. Keyboard events are triggered by any key.

```.addEventListener``` will be called on your square 6 times.

The scroll event will only fire the it’s if there is enough content to scroll. Try “wheel”!

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
