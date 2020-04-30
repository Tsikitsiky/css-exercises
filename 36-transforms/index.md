# CSS exercise 36: Transforms

The `transform` property is a powerful way to change many aspects of an element, mainly through applying changes to the element's geometry.

Let's look a little deeper at `transform`.

1. Name the functions we can use in a `transform`'s value?
```
 translate(),
 scale(),
 rotate(),
 skew(),
 matrix(),
 perspective
```
1. Why do we have to use separate functions, in order, and as values, e.g. `transform: scale(0.5) rotate(45deg);` when we could have had separate properties like: `transform-scale: 0.5;`, or `transform-rotate: 45deg`?
```
When you want to override one of them, it is good to separate them but if not it is better to not separate them to keep the order.
```
1. Often, we want to move the central pin or axis of the transform away from its default position. What property do we use to set that?
```
We transform-origin
```
1. Why is it preferable to use `transform: translate()` rather than `position` and its associated properties?
```
Using `transform: translate()` is better because it has smoother affect.
```
1. When an element is translated / transformed, what happens to the flow of the document? Therefore, what layout method is `transform` similar to?
```
The flow of the document doesn't change when an element is transform. It is similar to `position: relative`
```
1. What problems can you run in to when overriding a `transform` in a more specific selector?
```
If the function is not set in the more specific selector, it will be displayed by the default value.
```
1. If we want to go 3D, we need to use another property to set the view over the scene. What is that property?
```
Perspective and the use of z axis
```
1. We can control what the transform uses in its calculations in terms of the box model. What property can we use to adjust this?
```
Transorm-box property.
```
