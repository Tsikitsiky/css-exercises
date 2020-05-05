# CSS exercise 38: Keyframe animations

You've asked for looping and infinite animations… that's what Keyframe Animations are for!

No need for a higher-specificity selector to drive them too, you can set animations on the base styles of any element.

Let's do some research:

1. Keyframe Animation setup needs some unique code, what does it start with ?
```
It has to start with `@keyframes` keyword and followed by name and curly braces which instore the keyframe selectors 0% and 100% or from and to.
```
1. What makes the keyframes code different to the rest of CSS?
```
You only use the name of the keyframe after the @keyframes code but not other thing like brakets.
```
1. How do we use a keyframe animation we set up earlier as a property in a ruleset for an element?
```
By calling it with animation-name property.
```
1. Keyframe animations have other keywords that aren't available in `transitions`, what are these keywords?
```
infinite, alternate, reverse, alternate-reverse, running and pause.
```
1. How many properties can we animate at once?
```
As many as we want as long as the properties are animatable.
```
1. What properties are animatable?
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
