# CSS exercise 21: Positioning

Today we're going to be working with the `position` property, and its values:

- `relative`
- `absolute`
- `fixed`
- `sticky`

Positioning is a layout-breaking form of layout. i.e. it pulls elements out of the normal flow, and one has to use known dimensions to account for these positioned elements.

First up though, what is the default value for `position`?
```
Its default value is `static`
```

Try answer these questions too:

- What are some of the other properties you need to supply when using any non-default position value?
```
Float, z-index, display, top, left, right, and bottom.
```
- What is the inferred `display` value of an element that has been *positioned*?
```
It depends on the position. It may be inline or block if the posittion is static or relative, and only block if the position is absolute or fixed.
```
- One of the non-default values for `position` still maintains a box in the flow of the document. Which one is it?
```
relative
```
- What is special or significant about `fixed` and `sticky` positioning?
```
They don't take their offset from the parent but from the viewport.
```
- When positioning an element *absolutely*, how can we lock that element's coordinates to its parent element?
```
By setting top, bottom, left and right into auto.
```
- What are `absolute` positioned layouts useful for?
```
 - its parent has no children that are in the normal flow, so therefore its height collapses to zero.
 -the absolutely positioned box will appear exactly where it would have if it wasn’t positioned.
```
- Sometimes if you put two absolutely positioned elements in the same physical space, they'll stack, i.e. only one will be visible on top. What are the rules here? Why is a certain element on top? How can we adjust that ourselves?
```
we can not absolutely positioned two elements in the same physical space because they get out of the document flow. We can ajust that by using z-index.
```
- What is CSS's 'Stacking Context'?
```
A stacking context is a 3D conceptualization of an HTML element relative to a user facing the viewport (the area being currently viewed) or web page. Elements occupy this imaginary z-axis in order according to their attributes.
```
