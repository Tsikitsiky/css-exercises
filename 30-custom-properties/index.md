# CSS exercise 30: Custom Properties

It's time to change the way we think about- and use CSS.
Custom Properties allow us to write less code, and at the same time make our CSS more powerful. Gone are the days of writing comments containing the algorithms we use for layouts, when we can let Custom Properties define them for us.

So, to get started, let's do some research:

1. What characters do we *have* to use when defining a Custom Property's name?
```
We have to use double hyphen to define a Custom Property name.
```
1. What characters can't we use in a Custom Property name?
```
Space and period (full stop)
```
1. What possible values can we assign to a new Custom Property?
```
All CSS value can be assigned to a new Custom Property.
```
1. When is it useful to create Custom Properties using the `:root` or `html` selector? When is it not? Hint: *scope*
```
If the use of the property is globally across the html, it is useful to create the CP using the `:root` or `html`
```
1. After we've defined a new Custom Property, how can we recall or use that Custom Property? What function do we use?
```
We can use the CP by putting `var` function .
```
1. There are several ways to override or change a Custom Property. Can you name at least 3?
```
set a new one, use @media querry,...
```
1. Why are Custom Properties useful?
```
Custum Properties are useful because it reduces repetition, makes you write less code and you use one point of control.
```
1. What is the only aspect (or part) of CSS syntax that we can use Custom Properties for?
```
We can only use it inside a declaration block i.e it is tied to a selector
```
