# Forms and JS Events

## - Form Controls
There are several types of form controls that you can use to collect information from visitors to your site.
1. ADDING TEXT:
>Text input (single-line): Used for a single line of text such as email addresses and names.

>Password input: Like a single line text box but it masks the characters entered.

>Text area (multi-line): For longer areas of text, such as messages and comments. 

2. Making Choices:
>Radio buttons: For use when a user must select one of a number of options.

>Checkboxes: When a user can select and unselect one or more options.

>Drop-down boxes: When a user must pick one of a number of options from a list.

## - Form Structure
- **<*form*>**: Form controls live inside a <*form*> element. This element should always carry the action attribute and will usually have a method and id attribute too.
- ***action*** :Every <*form*> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
_ ***method***: Forms can be sent using one of two methods: get or post.
----------------------------------
## List
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 
It can be used on rules that apply to the <*ol*>, <*ul*>, and <*li*> elements.

1. Unordered Lists
For an unordered list you can use the following values:
 - none
 - disc
 - circle
 - square

2. Ordered List
For an ordered (numbered) list you can use the following values:
- decimal
>1 2 3
- decimal-leading-zero
>01 02 03
- lower-alpha
>a b c
- upper-alpha
>A B C
- lower-roman
>i. ii. iii.
- upper-roman
>I II III

-----------------------

## Events 
- TRADITIONAL DOM EVENT HANDLERS
All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.

>element.onevent = functionName ;

- EVENT LISTENERS 
Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers.

>element.addEventlistener('event', functionName [, Boolean]) ;

- THE EVENT OBJECT
When an event occurs, the event object tells you information about the event, and the element it happened upon.

----------------------
&copy; **Source:** 
-  [the Duckett HTML book:](https://wtf.tw/ref/duckett.pdf)
-  [javascript and jquery interactiv Book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01TTSXQT5M/javascript_and_jquery_interactive_jon_du.pdf?c=1618418988-21b29523d81fd117)



