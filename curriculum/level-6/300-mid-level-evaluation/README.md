# Mid Level Skill Check

This is a moment for you to test your coding skills and prepare yourself for an interview. Below you will see two code challenges for you to complete. You will also need to add comments or pseudo-code to your project in order to describe your process. Next you will complete a quiz that will test the knowledge you have gained so far. Once you have completed the challenges, schedule an assessment to review with an instructor and do a third coding challenge live!

# Code Challenges

## **Extract Initials**

Write a function called **`extractInitials`** that takes an array of full names and returns a new array containing only the initials of each name.

```jsx
function extractInitials(names) {
  
  };

const fullNames = ['John Doe', 'Alice Johnson', 'Bob Smith'];
const initialsArray = extractInitials(fullNames);
console.log(initialsArray); // Output: ['JD', 'AJ', 'BS']
```

## **Filter Object Array by Property**

Write a function called **`filterByProperty`** that takes an array of objects and a property name as input. The function should return a new array containing only the objects that have a specific value for the given property.

```jsx
function filterByProperty(objects, propertyName, propertyValue) {
  
}

const people = [
  { name: 'Alice', age: 30, country: 'USA' },
  { name: 'Bob', age: 25, country: 'Canada' },
  { name: 'Charlie', age: 35, country: 'USA' },
  { name: 'David', age: 28, country: 'Australia' },
];

const filteredByCountry = filterByProperty(people, 'country', 'USA');
console.log(filteredByCountry);
```

> Remember to submit your assignment by pushing it to Github!