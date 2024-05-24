# Employee Records

You are to create a collection of employee's information for your company. Each employee has the following attributes:

1. Name

1. Salary

1. Job title
1. Status

First, you will create an empty array named `employees`

Next, you will create an `Employee` constructor with the first three attributes defined at the time of instantiation and the fourth will be defaulted to `"Full Time"`.

This constructor will also have a method called `printEmployeeForm` that prints the employee's information to the console.

(e.g. `"Name: Bob, Job Title: V School Instructor, Salary: $3000/hour, Status: Part time"`)

You will then:

1. Instantiate three employees
2. Override the status attribute of one of them to either "Part Time" or "Contract"
3. Call the `printEmployeeForm` method for each employee
4. Put the generated employees into the `employees` array using whichever method you prefer.

Here's a refresher for the constructor syntax. Attempt writing yours without using the following code:

```jsx
function Car (year, make, model) {
    // use the "this" keyword to reference each object
    // that is created from this constructor
    this.year = year;
    this.make = make;
    this.model = model;
}

// then we "instantiate" (create a new object from) our constructor with the "new" keyword and pass in the parameters:

var myTacoma = new Car(2015, "Toyota", "Tacoma");

```

### **A bigger picture**

These functions mimic classes, which is a pattern from more object oriented programming languages.

In React, you will use classes to help instantiate instance "components" on the DOM. One of these components could be a post. Each post needs a title, maybe some text, and probably some methods to help with editing or deleting it.

### **If you get stuck**

If you haven't done a focused session attempting the above requirements, these next few tips won't be that useful.

The syntax for default parameters look like you're assigning the parameter a value. This will only be the value if an argument gets passed in.

Think about why default parameters would need to go at the end of the parameter list, after any parameters that would need required values to be passed as arguments.

> Remember to submit your assignment by pushing it to Github!