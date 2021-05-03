# CSS Layout
### - Building Blocks
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

### - Containing Elements
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

### - Normal Flow 
1. position:static
In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:
position: static;

2. position:relative 
Relative positioning moves an element in relation to where it would have been in normal flow

3. position:absolute
When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) 

4. position:fixed
Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.

### - CSS Frameworks
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

-------------
&copy; **Source:** 
-  [the Duckett HTML book:](https://wtf.tw/ref/duckett.pdf)