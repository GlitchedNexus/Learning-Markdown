# Paragraphs
Say we want to break text into paragraphs. We can simply do this
by leaving a blank line between the two paragraphs.

We separate this paragraph from the text above by leaving a blank line
before the paragraph.

Also, note that unless we are putting paragraphs inside lists. We must not
put tabs or spaces at the start of the paragraph. Keep the lines left aligned
to prevent formatting errors.

# Line Breaks

Sometimes you don't want to separate content into different paragraphs but just
want to start on a new line. In that case, just leave 2 or more blank
spaces (trailing whitespace) at the end of the previous line and press enter.  
Now your cursor is on a new line!

# Adding Emphasis 💅

## Bold
To make text bold, simply enclose it with `**` on both sides as follows
`**Your text goes here**`. Now we must ensure that we have any preceding or trailing
white spaces in the string we are trying to enclose. Below is an example of bold text.

**This text is bold**

## Italics
Similar to the way we make textbold, to make text italics, simply enclose it with
`*` on both sides as follows `*Your text goes here*`. Now we must ensure that we have
any preceding or trailing white spaces in the string we are trying to enclose.
Below is an example of italicized text.

*This text is italicized*

## Bold & Italics

Sometimes you want a piece of text to be both bold and italicized. In these cases
we can enclose the text in question using `***` on both sides as we did in the 
cases for bold and italics as follows, `***Your text goes here***`. Below is an 
example of bold and italicized text.

***This is the fancy text.***

# Horizontal Rules
Sometimes you want to add horizontal rules to show the separation between different sections of your markdown file. In such cases, we can add horizontal rules using one of the following delimiters on a line by themselves.:

- Three or more asterisks (`***`)
- Three or more dashes (`---`), 
- Three or more underscores (`___`) 

Here is an example

> # Topic One
> Content for topic one goes here!
> ***
> # Topic Two
> Content for topic two goes here!

# Escape Characters
Sometimes we want to use characters that we use to format a markdown file as part of our content. in such cases, we use escape sequences. The characters you can escape are:
- Asterisk: `\*`
- Underscore: `\_`
- Curly braces: `\{ \}`
- Square brackets: `\[ \]`
- Brackets: `\( \)`
- Hash: `\#`
- Plus: `\+`
- Minus: `\-`
- Period: `\.`
- Exclamation point: `\!`