# Markdown Example

You can find every command and help on this site, [GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

<!-- COMMENTS:
This content will not appear in the rendered Markdown -->

What to learn in this smal tutorial:
- unordered list
- ordered list
- text formatting
- code
- tables
- [links](#code)
- images
- autolists
- lists

### Nested list
1. First list item
   - First nested list item
     - Second nested list item

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5


## Text formatting
Normal
*italic*
_italic_
**bold**
__bold__
~~Strikethroug~~

Bold and nested italic:
**This text is _extremely_ important**

This is a <sub>subscript</sub> text

This is a <sup>superscript</sup> text

Text that is not a quote

> Text that is a quote


The background color is `#ffffff` for light mode and `#000000` for dark mode.

## Code
### Inline

You can print to the terminal using: `puts "Hello world"`

### Multi line code
#### Without highlighting
```
def hello_world
    print("Hello World!")
```
#### With highlighting
Highlighting codes for each coding language
```py
def hello_world
    print("Hello World!")
```


## Tables
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |


## Footnotes
Dette funket jo veldig dårlig!

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.


## Alerts
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

