# Responsive Color Grid From Scratch

Using `display: inline-block` or `display: grid` to create a webpage that looks like this:

!https://coursework.vschool.io/content/images/2015/07/boot.png

<aside>
💡 We suggest using `display: inline-block`, since `display: grid` has yet to be covered in the curriculum.

</aside>

Here are the colors:

- `#F5C6D6`
- `#EE2E84`
- `#85CFD8`

```
display: inline-block;
    border: 2px solid white;
    width: 50%;
    background-color: #EE2E84;
```

- `#8DC63F`
- `#E76E34`

To practice media queries, you must make this color grid keep it's regular form (look like the picture above) on screens above 768px (large screens). Once below 768px(small screens), each color must expand to the full-width of its container, so it looks like this:

!https://coursework.vschool.io/content/images/2016/08/Screen-Shot-2016-08-15-at-1-34-18-PM.png

(This image is zoomed out so as to be able to show all the colors. Your boxes will remain the same height and space apart/same size white border as above.)

### Important Tips while using `display: inline-block`**:**

- It's easiest to get the even white "spacing" by actually using a thick, white border around the shapes.
- In order to use percentage widths (like `width: 50%`) and not have them wrap, you'll need to add the following line to the top of your CSS:

```css
* {
    box-sizing: border-box;
    font-size: 0px;
}
```

> Remember to submit your assignment by pushing it to Github!