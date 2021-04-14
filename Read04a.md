# Dynamic web pages with JavaScript
![2](https://blogjob.com/trmeson/files/2019/08/JavaScript-code-410x370.jpg)
## HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER :
- ### < html> CONTENT LAYER . html files 
This is where the content of the page lives. The HTML gives the page structure and adds semantics. 
- ###  {Css} PRESENTATION LAYER . css files
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).
- ### javascript() BEHAVIOR LAYER .js files
This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files. 
## CREATING A BASIC JAVASCRIPT : 
JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day. 
> - var today= new Date();
>- var hourNow = today.getHours();
>- var greeting;
>- if (hourNow > 18) {
>- greeting= 'Good evening!';
>- else if (hourNow > 12) {
>- greeting = ' Good afternoon!';
>- else if (hourNow > 0) {
>- greeting = 'Good morni ng!';
>- else {
>- greeting = 'Welcome! ' ;
>- document .write( ' < h3>' +greeting + ' </ h3> '); 
### JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML 
When you put the script tag inside the body it will rin inside the body, and if you put it after the footer tag in will run there.
## WHAT IS A VARIABLE? 
> A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

> When you write JavaScript, you have to tell the interpreter every individual step that you want it to perform. This sometimes involves more detail than you might expect.

>Think about calculating the area of a wall; in math
the area of a rectangle is obtained by multiplying two
numbers:
> width x height = area 
