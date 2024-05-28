# Changing Themes Using Context

# Mastery task overview

Using what you have just learned about React Context, you are tasked with making a `ThemeProvider` context for a new application.  Your goal is build a home page that offers a dark and a light theme.  This theme can be toggled by the user.

This will be excellent practice in linking up the Provider and Consumer parts of Context around your app (getting used to the syntax) while working on your CSS that corresponds with the different themes.

# Criteria

For this task you must do the following:

- Provide a Dark and a Light theme
- Have at least 3 display components:
    - ex: Navbar, Footer, Main
- Create a `ThemeProvider` component that manages the themes using Context.
- Wrap your context provider around the whole app, like so:

```jsx
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import {ThemeContextProvider} from "./themeContext"

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
	<ThemeContextProvider>
	    <App />
	</ThemeContextProvider>
);
```

Below is a MVP example, but strive to take it further!

!https://res.cloudinary.com/dp6bgfdh8/image/upload/v1715876673/Web Development/Level 4/changing-themes-using-context.gif

## Take it further

- Instead of a toggle, make it a option drop down menu with multiple themes provided.
- Have at least one of the themes change the physical layout of the website.

> Remember to submit your assignment by pushing it to Github!