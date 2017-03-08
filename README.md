### Preliminary:

1) Clone repository:
  - https://github.com/fresh5447/intro-to-flexbox.git
2) `cd intro-to-flexbox `

3) User your tool of choice to run web project:
  - Reccomended: browser-sync  

### What is flexbox?
intelligently figures out what do to do with your layout, regardless of size and context;

### flex containers & flex items

### flex direction (main and cross axis)
  - row / row-reverse
  - column / column-reverse

main axis and cross axis


STEPS:

Add a container css class and give it display: flex;
Make this container 100vh
Update container to user flex-direction: column

JC - horizontal

add width to boxs and show flex-wrap
300px then 33.33%
margin 10px breaks it. Over budget.
width: calc(33.3333% - 20px);
padding: 10px;
width: calc(33.33333% - 20px);
margin: 10px;

## Reordering: Move DOM elements without moving your DOM.

Now we are modifying the flex item

flex: 1; Will take all the width and distribute it evenly.

order: default is 0;

## Justify content: Aligning and centering things.
add border to show.
add to container
felx-end, flex-start, center, space-between, space-around

vertically center: flex-direction: column, min-height: 100vh; jc-center

## Align items: Instead of working on main access; working on cross-access;
Give container some height; stretch is the default; flex-start; baseline;

## Align content: what do we do with the extra space when we have multiple rows? space between; space-around;
align-content: center;
justify-content: center;

### Alignself
can apply to individual item

### Flexbox sizing with the flex property
Note: Flex item!
flex: 1; distribute evenly.
Can tell box 2 to have double the space.

flex: 1 is actually flex-grow; flex-shrink; and flex-basis
too much space, not enough,

flex-grow default is 0;

### Flex Container within flex container
Build panels example. and show how to build a cool little footer for each example.
