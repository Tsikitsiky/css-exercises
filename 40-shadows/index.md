# CSS exercise 40: Shadows

There are two types of shadows:

1. Box Shadows, or the shadows that run around or inside a box
1. Text Shadwos, or the ghostly shadow outlines of text.

Let's do some research on these shadows…

1. `box-shadow` and `text-shadow` have very similar value syntax. Where do they differ?
```
text-shadow doesn't accept thickness, and inset unlike box-shadow.
```
1. If I wanted to create a hard-edge shadow, one that looks like a solid border, what combination of values would I need to use?
```
It is the combination of `blur` and `thickness` which creates a hard-edge shadow.
```
1. Is it possible to create a shadow on a circular element? What about a polygon?
```
It is possible when using `border-radius` but `clip-path` not as it can be polygone or ellipse.
```
1. Is it possible to create multiple shadows on the same element?
```
Yes we can by separating them by commas.
```
