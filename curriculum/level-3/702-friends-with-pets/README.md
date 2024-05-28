# Friends with pets

Build a simple React app that has a `<FriendList />` component, a `<Friend />` component and a `<Pet />` component.

In `<FriendList />`, `.map()` through an array of friends. Each friend will have an array of pets. Feel free to use array at the bottom of this write up. In your `.map()`, render a `<Friend />` component, passing through the name, age, and pets of each friend as props.

`<Friend />` Should display the info nicely. Use some styles and appropriate HTML(JSX) tags. `<Friend />` Should also `.map()` through the pets array and render `<Pet />`. Pets should also be displayed nicely.

Think about how you display strings, numbers, and arrays while building this app.

```jsx
const friends = [
  {
    name: "Ben",
    age: 29,
    pets: [
      {
        name: "spot",
        breed: "tabby"
      },{
        name: "John Johnson",
        breed: "husky"
      },{
        name: "Bear the bear",
        breed: "Grizzly"
      }
    ]
  },{
    name: "Bob",
    age: 31,
    pets: [
      {
        name: "Sally",
        breed: "Australian Shepard"
      }
    ]
  },{
    name: "Marcus",
    age: 25,
    pets: [
      {
        name: "Indy",
        breed: "Akita"
      },{
        name: "Anna",
        breed: "persian cat"
      }
    ]
  },{
    name: "Jacob",
    age: 20,
    pets: [
      {
        name: "fluffy",
        breed: "sphynx cat"
      },{
        name: "patches",
        breed: "sphynx cat"
      },{
        name: "tiger",
        breed: "sphynx cat"
      },{
        name: "oscar",
        breed: "sphynx cat"
      }
    ]
  }
]

```

> Remember to submit your assignment by pushing it to Github!