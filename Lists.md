# Lists
Lists are a fundamental means of organizing information. As such, it is vital to know how to create and manipulate lists.

## Ordered Lists
When working with lists it is natural we may want ordered lists. We can create ordered lists by adding a number followed by a period before declaring a list element. This is shown below.

1. Element One
2. Element Two
3. Element Three

Note that we only need to ensure that the first element has the delimiter `1.`` the delimiters preceding the following elements of the list do not need to be in a correct sequence. An example is given below.

1. Element One
8. Element Two
3. Element Three
1. Element Four

### Nested Ordered Lists
Use indentation to declare nested lists.

1. Element One
2. Element Two
    1. Sub-element One For Element Two
    2. Sub-element Two For Element Two
    3. Sub-element Three For Element Two
3. Element Three

## Unordered Lists
Sometimes we don't want any inherent order within our lists. In such cases, we can use unordered lists. To create an unordered list we can use any of the following delimiters:
- `-`
- `*`
- `+`

Regardless of which delimiter you choose, ensure that an individual list contains only a single delimiter to ensure consistent results when using different markdown processors.

Examples of lists using each of the following delimiters are given below.

- Element One
- Element Two
- Element Three

* Element One
* Element Two
* Element Three

+ Element One
+ Element Two
+ Element Three

As you can Regardless of which method we choose, you get the same result.

To have a number followed by a period in a list item, you must use the escape character `\`.` to make sure the content is rendered correctly.

### Nested Unordered Lists
We use indents to create nested lists. An example is given below.

- Element One
- Element Two
    - Sub-element One For Element Two
    - Sub-element Two For Element Two
    - Sub-element Three For Element Two
- Element Three

## Additional Elements Within Lists
For elements like mathematical expressions or paragraphs simply indent the element you want to add by four spaces or one tab. Some common examples are discussed below.

### Paragraphs Within Lists

Sometimes you may want to have paragraphs within a list.

- Element One
- Element Two
    Paragraph describing something related to element two.
- Element Three
    To give an example of a longer paragraph element that can further reinforce the content we are talking about, here is an extra long paragraph that may talk about something that may be related to paragraph three or not!

As we can see, the continuity of the list is preserved.

### Mathematical Expressions Within Lists
Say you want to have a list of common algebraic relations. You can simply achieve this by adding latex equations as the content of your list like the one shown below.

- $$(a+b)^2 = a^2 + b^2 + 2ab$$
- $$(a-b)^2 = a^2 + b^2 - 2ab$$
- $$(a+b)(a-b) = a^2 - b^2$$

We can add other elements as well like text!

- Square of the sum of two variables:
    $$(a+b)^2 = a^2 + b^2 + 2ab$$
- Square of the difference of two variables:
    $$(a-b)^2 = a^2 + b^2 - 2ab$$
- Product of the sum and difference of two variables:
    $$(a+b)(a-b) = a^2 - b^2$$


You can do the same with order lists as well.

### Blockquotes Within Lists

Like all the preceding examples we just add indents and we're good to go!

- Element One
- Element Two
    > Paragraph describing something related to element two.
- Element Three
    > To give an example of a longer paragraph element that can further reinforce the content we are talking about, here is an extra long paragraph that may talk about something that may be related to paragraph three or not!