# Pokemon List

The following exercise should be completed in vanilla JavaScript.

Use `https://api.vschool.io/pokemon` as your URL for your Axios request to get the big list of Pokémon.

It will be easiest to do this in steps:

- Step one - get the data
- Step two - display the data

# **Step One**

Write a function that runs an `axios` get request, the response data will be structured like this:

```json
{
    name: 'Charmander',
    resource_uri: 'api/v1/pokemon/8/'
},
{(Another pokemon object)},
{(Another pokemon object)},
{(Another pokemon object)},
...
etc.

```

Tip: You won't be able to use node for this, because HTTP requests only exists in a browser. So you'll need to use an HTML file that links to your JavaScript and run it in the browser.

# **Step Two**

Make each Pokémon's name show up on a separate line in the browser.

You will be using a for loop to iterate through each pokemon object, and some DOM manipulation to add nodes for each Pokémon.

- The data that comes from the URL endpoint above is complex. Notice that the "objects" property is an array, so you'll need to index into it's 1st item in order to get any of the Pokémon names (`data.objects[0]...`);

### **Hints**

- Use `console.log()` to test your request to see the data you’re getting back


> Remember to submit your assignment by pushing it to Github!