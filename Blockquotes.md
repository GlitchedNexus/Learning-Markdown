# Blockquotes
Sometimes we want to represent a portion of the text like
a quote, a definition or a side topic. In such cases, we can employ 
blockquotes.

We can create a blockquote by adding `>` to the beginning of the content
we want to put in the blockquote.

For example,

> This is a blockquote

To ensure compatibility across markdown processors, put blank lines before and after blockquotes.

Now, we are not limited to having only sentences within our blockquotes.
We can have a multitude of different combinations. These are given below.

## Blockquotes with paragraphs
Creating blockquotes containing paragraphs is quite simple. Just add `>` to the beginning of each line of the paragraph including the blank space separating the the two paragraphs. An example of this is given below.

> This is the first paragraph.
>
> This the second paragraph.

## Lists Within Blockquotes
Sometimes you want to highlight bullet points using blockquotes. The rule stays the same, add a `>` before each list element and you have a blockquote containing a list like the one shown below.

> Groceries:
> - Milk
> - Eggs
> - Brocolli

## Headings Within Blockquotes
Sometimes we may want to have separate content within a blockquote. We can add headings within blockquotes in such cases as we would in any other part of our markdown file. Just remember to add a `>` before each line when doing so. An example is given below.

> # Something important
> I felt this content deserved special attention and should be separated from the rest of the information on this page.
> ## This a subheading
> This is subsection of this.

## Nested Blockquotes

You can have blockquotes within blockquotes as well! Just add an extra `>` to the beginning of each line of the nested content. Let us look at an example.

> This is outer blockquote.
>
>> This is the inner blockquote.
>
> This is the outer blockquote again.

## LaTeX Within Blockquotes
We can also contain mathematical formulae within block quotes using LaTeX equations. As we saw before, just add `>` to the beginning of each line and you are good to go!

> Force can be expressed in terms of the mass and acceleration of a body using th relation below,
> $$F = ma.$$
