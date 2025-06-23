CSS List Styles
Lists are a common element in web design used to prevent content from being un-organized. CSS allows you to style lists to match the design aesthetic and improve the readability of the web page.

Following are the various techniques for styling HTML lists.

Unordered list styling
To style unordered lists (bulleted lists), we can change the list item marker.

Syntax:

ul {
    list-style-type: value;
}

The value can be:

disc: (default) - Filled circle marker
circle: hollow circle marker
square: a filled square marker
none: No marker (remove bullets)


Ordered Lists Styling
For ordered lists (numbered lists), we can customize the list item numbering.

Syntax:

ol {
    list-style-type: value;
}

The value can be any of the following:

decimal: (default) - Decimal numbers (1, 2, 3, etc.)
decimal-leading-zero: Decimal numbers with leading zeros (01, 02, 03, etc.)
lower-roman: lowercase Roman numbers (i, ii, iii,...)
upper-roman: uppercase Roman numbers (I, II, III,...)
lower-alpha: lowercase alphabetical letters (a, b, c, etc.)
upper-alpha: uppercase alphabetical letters (A, B, C, etc.)


List-style position
The 'list-style-position' property determines where the list markers (bullets or numbers) are placed in relation to the content.

It has two values:

inside: (default) List markers are inside the content's box. This is the default behavior.
outside: List markers are outside the content's box, typically to the left of the content, creating a hanging indent effect.


Removing the default list styles
To remove default list styles (bullets or numbers), set the 'list-style' property to 'none'.



Custom List Style
To set a custom list style, set the 'list-style-type' to your new required custom style.
