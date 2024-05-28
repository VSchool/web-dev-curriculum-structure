# CSS Gradient Generator Tool

Develop a UI tool that lets users create a gradient and generates cross-browser CSS code of that gradient to be used in any application.

 
Example:
https://loom.com/share/bea48cb96cd749eb9f6addaa961290e0

## Requirements

1. It must be able to accept 2 color inputs (or 3 if you prefer) and a number input to represent the angle
2. Render a preview box that displays the current gradient
3. Generate cross-browser CSS code in a text box as shown below. The user should be able to copy this code.

```css
background: linear-gradient(50deg, #FFFF00 , #000000); 
-moz-background: linear-gradient(50deg, #FFFF00 , #000000); 
-webkit: linear-gradient(50deg, #FFFF00 , #000000)

/*for 3 color inputs, you can simply add the 3rd color*/
background: linear-gradient(50deg, #FFFF00 , #000000, #FF0000); 
```

## Hints & Tips

1. You’ll want to display the actual code in a box instead of just rendering the gradient. One such way is by using the `<textarea>` tag. It’s also a type of form element, so you’ll have to treat it like you would any controlled component in React like the `<input>` element. Refer to the [docs](https://reactjs.org/docs/forms.html#the-textarea-tag) for more information.
2. The textbox should be read only. The user should not be able to edit the code inside of it. If you’re using `<textarea>` to display the code, you can add a readOnly prop to it:
    
    ```jsx
    <textarea readOnly value="Text area text goes here"/>
    ```
    
3. You can choose to either have a “Generate Code” button that outputs the code once the user selects their gradient, or omit the button and output code every time the input changes. To implement the latter, consider using `useEffect`

## Extra Credit Challenge

1. User can add or remove gradient colors (but there must be a minimum of 2 colors)


> Remember to submit your assignment by pushing it to Github!



> Remember to submit your assignment by pushing it to Github!