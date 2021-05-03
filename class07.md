# Object-Oriented Programming, HTML Tables
## Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

## What's a Table?
A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.
#### - The <*table*> element is used to create a table. The contents of the table are written out row by row.
#### - You indicate the start of each row using the opening <*tr*> tag. (The tr stands for table row.) It is followed by one or more <*td*> elements (one for each cell in that row). At the end of the row you use a closing <*/t*r> tag.
#### - Each cell of a table is represented using a <td> element. (The td stands for table data.)

## Constructor Notation
#### - CREATING AN OBJECT WITH PROPERTIES & METHODS
- LITERAL NOTATION
A colon separates the key/value pairs. There is a comma between each key/value pair

>var hotel = {
>name: 'Quay' ,
>rooms: 40,
>booked: 25,

>chec kAvailability: function() {

>return this.rooms - this .booked;

>}
>} ;


- OBJECT CONSTRUCTOR NOTATION
The function can be used to create multiple objects. The this keyword is used instead of the object name.

>function Hotel(name, rooms, booked) {

>this.name = name;

>th i s.rooms = rooms;

>this.booked = booked;

>this.checkAvailability = functio n()

>return this . rooms - this.booked;

>} ;

>var quayHotel =new Hotel('Quay', 40 , 25);

>var parkHotel =new Hotel('Park', 120, 77);
------------------------------------------------

&copy; **Source:** 
-  [javascript and jquery interactiv Book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01TTSXQT5M/javascript_and_jquery_interactive_jon_du.pdf?c=1618418988-21b29523d81fd117)
- [HTML & CSS Book](https://wtf.tw/ref/duckett.pdf)
- [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)