# Mid-level 4

Do NOT use notes or external resources when taking Quiz.  Use this opportunity to test what you’ve learned so far. Complete the quiz [here](https://docs.google.com/forms/d/e/1FAIpQLSeToM0v3e_lsogN8oXLCN4UCuKEQlB8SkCyj4lxy5m1UfKj7A/viewform?usp=sf_link).

[](https://docs.google.com/forms/d/e/1FAIpQLSeToM0v3e_lsogN8oXLCN4UCuKEQlB8SkCyj4lxy5m1UfKj7A/viewform?usp=sf_link)

# Mid-level evaluation

This is a moment for you to test your coding skills and prepare yourself for an interview. Below you will see two code challenges for you to complete. You will also need to add comments or pseudo-code to your project in order to describe your process. Next you will complete a quiz that will test the knowledge you have gained so far. Once you have completed the challenges, schedule an assessment to review with an instructor and do a third coding challenge live! 

## Filter Anagrams

Write a function called **`filterAnagrams`** that filters an array of words to find and return an array containing only the words that are anagrams of a given target word.

**Understand the Problem:**
Before you start coding, make sure you understand what the challenge is asking. You need to filter a given array of words to find the anagrams of a target word. Anagrams are words that have the same letters but in a different order.

```jsx
function filterAnagrams(arr, target) {
  
}

const words = ['listen', 'silent', 'dog', 'god', 'hello', 'world'];
const target = 'enlist';

const anagrams = filterAnagrams(words, target);
console.log(anagrams); // Output: ['listen', 'silent']
```

## **Sort by Multiple Criteria**

Write a function called **`sortByMultipleCriteria`** that takes an array of objects representing people, each with a **`name`** (string) and **`age`** (number) property. The function should return a new array with the people sorted first by age in ascending order, and then by name in alphabetical order.

```jsx
function sortByMultipleCriteria(people) {

}

const people = [
{ name: 'Alice', age: 30 },
{ name: 'Bob', age: 25 },
{ name: 'Charlie', age: 35 },
{ name: 'David', age: 25 },
];

const sortedPeople = sortByMultipleCriteria(people);
console.log(sortedPeople);

// Expected outcome: [
//  { name: 'Bob', age: 25 },
//  { name: 'David', age: 25 },
//  { name: 'Alice', age: 30 },
//  { name: 'Charlie', age: 35 }
// ]
```

> Remember to submit your assignment by pushing it to Github!