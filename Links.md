# Links
Links allow us to create relations between multiple sources of information. If you are familiar you are familiar with obsidian you already know that links are fundamental building blocks of your personal knowledge management system. 

Enough with the off-topic discussion. The syntax for links is as follows

`[Text](Link "Title")`

- The text is what will be rendered as the hyperlink.
- The link is the path to the resource.
- The title is the text displayed when we hover on the hyperlink. It is OPTIONAL.

An example of a link is given below.

> [Gravitational Waves](https://en.wikipedia.org/wiki/Gravitational_wave "The most interesting topic ever") is the most intriguing part of physics in my opinion!

You can also apply text formatting on links to make the text bold or italicized or both! You can even add code contained within backticks as the text representing the hyperlink.

If you simply wish to render links or emails with no text you can enclose the links with angle bracks (`<>`) as follows:

`<link>`

Giving us something like

<https://en.wikipedia.org/wiki/Gravitational_wave>

Since there is an inconsistency between how markdown processors process links, ensure that you encode any spaces in your URL with `%20` to ensure interoperability.

## Reference-style Links
These are simply a cleaner way to write links. Here we break down the hyperlink text and the link into separate pieces as follows

`[text][<link label>]`

- The link label acts as a key that helps to identify the destination. You can have multiple versions of the same label.

The link label has the syntax

`[<link label>]: <link> "title"`

- The title which is displayed when we hover over the hyperlink can be contained within double quotes, single quotes, or parentheses. This is optional.

Example:

> [Gravitational Waves][1] is the most intriguing part of physics in my opinion!

[1]: https://en.wikipedia.org/wiki/Gravitational_wave "The most interesting topic ever"