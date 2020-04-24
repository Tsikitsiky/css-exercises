# CSS exercise 32: The Calc function

This function saved a lot of headaches when it came out. It makes arithmetic easy, and reproducible, but where it really shines is in mixing units.

Here are some questions you should try answer through your research:

1. What values can a `calc()` function support?
```
It supports these following values: lenght, frequence, angle, time, percentage, number and integer.
```
1.How can we adjustthis function `calc(2 +3 * 4)` so that it equals `20`? Hint: Apply the rules in PEDMAS / BODMAS.
```
Calc function uses the rule of operator precedence to deal with it(division and multiplication first), if you want to specify or change the order of the calculation use brackets.
```
1. Can we use a `calc()` function to convert one type of unit to another type of unit?
```
No
```
1. If we want to convert a unitless number to a unit value, what do we have to do?
```
We multiply that unitless number to 1unit of the unit needed.
```
1. Why do the *plus* and *minus* operators inside the function need spaces around them?
```
Without space, the browser treates the operator as invalid because it takes as if it is a negative or positive number.
```
1. How can we convert a value into a negative value?
```
By multiplying it by -1
```
1. Can the `calc()` function work with colour values? e.g. a light red plus a light red should equal a darker red.
```
No
```
