# Name Badge

Using React create a website that looks/works like this:

!https://coursework.vschool.io/content/images/2015/07/namebadge.png

## **Requirements**

- The user should be able to input in the badge fields.
- Upon submit, the badge fields should be cleared, and a new badge should be displayed below the badge form.
- Each time the user submits a badge, each badge will be printed below the form in a list.
- Specify input types to correspond with the required information.
- Add a minimal character count of 3 for each field.
- Note: The new badge should not appear until after it is submitted.
- If any of the input fields are empty the Submit button should be disabled
- Write validation code to make sure the phone number field only has numbers (no dashes or special characters, must look like this `9757653323`

### Optional

- Make the color of the badge heading background alternate on each list item (ie Red, Blue, Red, Blue (see the [dynamic rendering write up](https://coursework.vschool.io/dynamic-rendering-in-react/))

## Game Plan

- Start writing sudo code
- What components will you need?
- What values of state do you need?

## Recommendation

- Store all badges in an array in state
- Display each badge by mapping through the badges array.

> Remember to submit your assignment by pushing it to Github!