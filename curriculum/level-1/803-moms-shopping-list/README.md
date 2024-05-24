Your mom is frustrated by her propensity to lose slips of paper with writing on them, specifically her shopping lists. She knows that you're a really smart web developer and assumes that you can easily make her a website to keep track of her shopping list.

### **Project Requirements Overview**

Using HTML, CSS, and JavaScript, write a simple shopping list app. There must be an input box to add new items, and an [x] button to delete items. The data does not have to persist a page refresh (because there's no API right now).

You should be able to delete items by clicking the [x]:

### **Setup**

Use the following [repo](https://github.com/VSchool/moms-shopping-list-start) to start your project. This code will help you understand any patterns you should use when completing this assignment.

```bash
git clone https://github.com/VSchool/moms-shopping-list-start
```

To remove the nested `.git` folder, follow these instructions:

```bash
cd moms-shopping-list-start
rm -rf .git
```

> 
Note: The three items already there are to show how the rest should be structured, but should be removed or commented out before moving on to part 2.
> 

### **Parts**

Each part is it's own task. It would be beneficial to have someone look at your code before moving from one part to the next.

### **Part 1**

- A user will be able to add list items to the pre-built `ul` using the pre-built form
- New list items should have the same format as the `li`'s that come with the git repo

### **Part 2**

- A user will be able to delete items using an items delete button

### **Extra Credit**

- A user will be able to click the "edit" button and see an input box appear
- When the user clicks the "edit" button, a "save" button replace the "edit" button
- The input box will automatically have the value of the list item
- The user can edit and "save" the input box's value
- On save, the input box will disappear, and the new value will appear

### **Passing criteria: Demo to an instructor**

An instructor or TA will sit with you for a demonstration of this project during your mid-level assessment. They will be assessing your proficiency in the following areas:

- Difference between web app and web site
- Build very basic web apps (site is functional and based on user interaction)
- Understand JSON

Passing off this project completes the Web Applications, Level 1 branch of the skills tree.

### **Tips for when you are stumped.**

Take a minute to practice the problem solving process without these notes.

Come to your Level 1 assessment with this assignment ready to show to the instructor.

Remember the note in the above requirements to delete the items from the HTML.

To break down creating a new list item:

- Write an event listener that listens for a "submit" on the form. Prevent the default refresh that happens on submits.
- Be able to log the string the user types into the input box to the console after the submit. Keep the console open and look often for JS errors there.
- Use the three steps of creating a new element.
    1. create the element
    2. edit properties like textContent or the style object
    3. append the element to the DOM

> Remember to submit your assignment by pushing it to Github!