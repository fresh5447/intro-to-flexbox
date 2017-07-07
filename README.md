### Project Setup:

1) Create a proeject that has:
  `index.html`
  `css/styles.css`
  `README.md`

2) Ensure your `HTML` file is using the bootstrap boiler plate code, add content to your `README.md`

3) Run your project locally using brower-sync to ensure that is is working.

`browser-sync start --server --files "*.html, css/*.css, js/*.js"`

4) Create a repository at Github.com and push your code up.

### What is flexbox?
 - Create responsive layouts without using margin, padding, and floats.
 - Intelligently figures out what do to do with your layout, regardless of size and context.

### Resources
- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox Froggy](http://flexboxfroggy.com/)

### Display Flex
In order to implement flex properties you need a `flex container` (parent) which will make all the immediate children `flex items`

## Aligning and Centering


#### justify-content: What to do with the main axis extra space?
flex-end, flex-start, center, space-between, space-around


#### align-content / align-items

how are items aligned on the cross axis (make sure you pay attention to the size of the container) (align-items is stretch by default) (base-line example - make fonts different size - items are based on bottom of font size)

flex-end, flex-start, center, space-between, space-around

align-content is for multiple lines;

Update the height of the container to see this in action.



#### align-self

Can be applied to specifically one flex item.


### Flex direction (main and cross axis)
  - row (default) / row-reverse
  - column / column-reverse

  Update the width of the flex-item, to see this in action.



### Using Calc to implement a layout with Margin
If we want our items to take up exactly 1/3rd of the screen, yet have a little margin. The problem is margin is not part of the box model - you become over budget.

```
  margin: 10px;
  width: calc(33.333% - 20px)
```



### order: Reorder flex-items
How to reorder elements of the DOM. Works similar to z-index, default is 0;

Give order rule to flex-item;


### Vertically center example

flex-direction: column;
min-height: 100vh;
justify-content: center


## Sizing with flex properties


### Sizing with the flex property
Note: Flex item!
flex: 1; distribute evenly.
Can tell box 2 to have double the space.

flex: 1 is actually flex-grow; flex-shrink; and flex-basis
too much space, not enough,

flex-grow default is 0;

### Flex Container within flex container
Build panels example. and show how to build a cool little footer for each example.

----
