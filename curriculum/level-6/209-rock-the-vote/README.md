# Rock the Vote

> The Rock the Vote/RTV project is broken into 4 parts throughout the level. Finish each set of requirements as you progress through the curriculum.

## Introduction

You will create a full-stack application with user authentication using Node, React, Express, Mongoose, and MongoDB that allows users to post and upvote or downvote political issues.

This assignment has the most challenging requirements at V School. Collaborate with peers to tackle the project effectively.

## Overview

By the end of the project, you will have implemented the following features:

- A login/signup page required to access any part of the application.
- A web page displaying a list of political issues, each with:
  - A title and description.
  - The ability to be upvoted or downvoted (users can only vote once per issue).
  - Items ordered by upvotes, with the most upvoted at the top.
  - The total number of votes displayed.
- A page for logged-in users to add new issues.
- A page for logged-in users to view all their issues.
- The ability to comment on issues (unlimited comments per issue).
- A backend with models and routes for persisting issues, comments, and votes.
- A React-based front end.
- A Node/Express backend.
- A MongoDB database using Mongoose for modeling.
- User authentication managed with dotenv, jsonwebtoken, and expressJwt.

The application must support `GET`, `POST`, `PUT`, and `DELETE` operations.

## Project Parts

### Part 1 - Setting Up the Server

**Requirements:**

- Create the following models:
  - `User.js`
  - `Issue.js` (related to the user who created it)

- Implement the following routes:
  - **Authentication Routes:**
    - `POST /signup`: Register a new user.
    - `POST /login`: Authenticate a user and return a token.
  - **Issue Routes:**
    - `GET /issues`: Retrieve all issues.
    - `POST /issues`: Create a new issue.
    - `PUT /issues/:issueId`: Update an existing issue.
    - `DELETE /issues/:issueId`: Delete an issue.
    - `GET /users/:userId/issues`: Retrieve all issues created by a specific user.

### Part 2 - Setting Up the Front End

**Requirements:**

- Users should be able to log in and sign up.
- Users should be able to add issues.
- Create a public page to display all issues.
- Create a profile page to display the user's issues.

### Part 3 - Adding Password Encryption and Protected Routes

**Requirements:**

- Encrypt passwords at the database level and exclude them from the user object sent to the front end.
- Automatically reroute users upon login/logout.
- Protect profile and public pages with routes that require a token to access.

### Part 4 - Adding Comments and Upvotes/Downvotes

**Requirements:**

- Allow users to leave comments on issues.
- Display comments underneath the issue they were made on.
- Allow users to upvote or downvote issues.
- Ensure each user can upvote an issue only once.

> Remember to submit your assignment by pushing it to Github!