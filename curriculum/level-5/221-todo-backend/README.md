# Todo Backend

# Objectives

Create a simple Express Server that manages a list of todos (which at this point will just be held in an array on the server, since we haven't gotten to including databases yet).

Todos should have a data format similar to:

```jsx
{
    "name": "The name",
    "description": "The description of the todo"
    "imageUrl": "http://www.myimage...."
    "completed": false
    "_id": "23k4lh23h2"
}
```

Create endpoints that:

- allows new todo items to be posted to the array,
    - When posting a new todo, you must generate a unique id for that todo (consider using the `uuid` npm package),
- returns the entire list of todos,
- allows the user to update a todo by its `_id`,
- allows the user to delete a todo by its `_id`, and
- allows the user retrieve a single todo by its `_id`.

> Remember to submit your assignment by pushing it to Github!