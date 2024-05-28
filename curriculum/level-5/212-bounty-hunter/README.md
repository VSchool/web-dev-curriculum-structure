# Bounty Hunter

> This project is broken into four parts through level 5. Work on each step as you get to it in the curriculum.

# Introduction

You are a bounty hunter of the Old Republic. Your parents were killed by a Sith Lord as a child and your goal in life is to kill all the Sith and Jedi.

In order to help you in your quest, and since you are a do-it-yourself kind of bounty hunter, you have learned programming so you can keep track of your bounties and kills!

# Objective

Using Express, create an API on the `/bounty` route that:

1. `GET`s a list of all bounties
2. `POST`s new bounties,
3. `DELETE`s a bounty
4. `PUT`s (updates) a bounty

Since we haven't started connecting to MongoDB quite yet, you can just save your bounties in a `bounties` array in your server code. Keep in mind that since it isn't being persisted anywhere, anytime you make a change to your server code and restart the server, you'll lose all your bounties.

A bounty object should have:

- First Name
- Last Name
- Living (Boolean)
- Bounty Amount (number)
- Type (‘Sith’ or ‘Jedi’)
- ID (a unique identifier. Use the `uuid` package to generate unique ids. - `npm install uuid` and check the [docs](https://www.npmjs.com/package/uuid) to see how to use it. It's as simple as requiring the package and running `uuid.v4()`)

Since there isn't a front end set up yet, you'll just use Postman to interact with the server and update the data.

# Requirements for Part 1 - Server Setup and `GET` and `POST`Routes.

Since we don't have a *good* way to tell the server which item we want to `PUT` and `DELETE` yet, we'll start out just by writing the `GET` and `POST` endpoints.

- Write a `GET` endpoint that gets all bounties from the array and sends them to the client.
- Write a `POST` endpoint that adds a new bounty object to the array of bounties.

- Remember, you'll have to play the part of the database and add an `id` property to the incoming bounty before saving it to the array of bounties. This way you'll be able to easily look it up by its `id` property in order to update and delete it later.


# Requirements for PART 2 - **Adding `PUT` & `DELETE`**

After learning about `req.params`, now add endpoints that allow you to:

- `DELETE` a bounty from the bounties array, and
- `PUT` (update) an existing bounty.

You'll need to pass the `uuid` you added when `POST`ing new bounties as a URL Parameter to the endpoint in order to have a reference to the object you want to update or delete.

# Requirements for PART 3 - Client Setup

For this part you will have to [set up a full stack React application](https://coursework.vschool.io/setting-up-a-full-stack-react-application/). Since you do not have a database yet, ignore the `/models` folder contained in the example. You instead will have something like `bountyData.js` which contains your data.

You will now build a client-side React interface for the server you created!

Your app should be a CRUD application - it should be able to: 

- Create (POST) new bounties,
- Read (GET) existing bounties and show them to the user of your site,
- Update (PUT) existing bounties (e.g. if you wanted to up the price for a bounty), and
- Destroy (DELETE) bounties from the list of all bounties.

You will need to use everything you've learned about state management, HTTP, and forms!

The design is up to you, so have fun with it!


# Requirements for PART 4 - Mongoose

Since you already have the routes set up and working (from the previous [bounty hunter exercise](https://coursework.vschool.io/the-original-bounty-hunter/)), the first step is to create a data model. You can refer to [this document](https://coursework.vschool.io/mongoose-basics/) if you need a refresher on how to use mongoose.

Once the data model is created (preferably in a file separate from your routes) it's time to add mongoose queries to your routes. For example, when handling GET requests, use the find query to get a list of all the bounties:

- Create a Model
- Add Mongoose Queries to each request type in order to get the necessary information. 

> Remember to submit your assignment by pushing it to Github!