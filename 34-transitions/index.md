# CSS exercise 34: Transitions

Transitions offer us the simplest form of animation in CSS.

The word *transition* means to 'change from one state to another'. In CSS, these transitions occur per element, per property.

1. The first state is the initial state, or how the element was to begin with.
1. The second state, or target state, is what the element will become.

Transitions take care of all the intermediate stages between those two states.

OK, so let's hunker down and learn more about transitions!

1. The `transition` property is a 'shorthand property'. What other properties are included in this shorthand property?
```
transition-delay,
transition-duration,
transition-property,
transition-timing-function.
```
1. What is the difference between a timing function, delay, and duration?
```
timing function: how intermediate values are calculated.

delay: time before start when the value change.

duration: the length of the animation.
```
1. What CSS properties are *animatable* using transitions?
```

all
backdrop-filter
background
block-size
border
bottom
box-shadow
caret-color
clip
color
columns
filter
flex
font
gap
height
inline-size
inset
left
letter-spacing
line-clamp
line-height
margin
mask
opacity
order
padding
right
rotate
row-gap
scale
scrollbar-color
shape-image-threshold
shape-margin
shape-outside
tab-size
text-decoration
text-decoration-color
text-decoration-thickness
text-emphasis
text-emphasis-color
text-indent
text-shadow
text-underline-offset
top
transform
translate
vertical-align
visibility
width
word-spacing
z-index
zoom
```
1. Can we select more than one property to transition at a time? If so, how?
```
Yes, 1- we have to separate them with commas using `-transition-property`.
     1- `all` keyword
     1- commas using `transition:`
```
1. How can we set or define the desired transition state, using CSS?
```
By setting an initial state with the same property before you set the desired state using `pseudo-classes` like :hover, :active, :focus.
```
1. Do we need transitions? What makes them useful?
```
Yes in certain cases. What makes it useful is the way that it provides a time for a change to be made instead of simultaneousily.
```
1. At what point can transitions become a problem?
```
When you have to wait for it to finish i.e it too long to wait for.
```
1. Transitions don't work reliably with the `auto` keyword being one of the end states. Why is that?
```
Because the browser is calculating the value before it changes and with auto there is no defined number.
```
1. How can we stagger transitions? i.e. make a number of child elements all start at different times?
```
By adding transition delay.
```
