# COMPARISON OPERATORS :
###  EVALUATING CONDIRIONS:
you can evaluate a situation by comparing one value in the cript to what you expect it might be. The result will be a Boolean: true or false.

> -  "==" ---> IS EQUAL TO  | "!=" ---> IS NOT EQUAL TO|
> - "===" ---> SRTICT EQUAL TO  | "!==" ---> SRTICT NOT EQUAL TO
> -  ">" ---> GREATER THAN | "<" ---> LESS THAN 
> - ">=" ---> GREATER THAN OR EQUAL TO | " <=" ---> LESS THAN OR EQUAL TO 
# LOGICAL OPERATORS:
Comparison operators usually return single values of TRUE of False . Logical operators allow you to compare the results of more than one comparison operator.
### Example: 
> ((5<2) && (2>=3))

#### THE LOGICAL OPERATORES ARE: 
##### 1- "&&" ---> LOGICAL #AND
##### 2- "||" ---> LOGICAL #OR
##### 3= "!" ---> LOGICAL #NOT

# LOOPS 
![2](https://learntocodetogether.com/wp-content/uploads/2019/02/backGroundJSTutorials-1024x586.jpg)

Loops check a condition. if it returns TRUE, a code block will run. Then the condition will be checked again and if it still returns TRUE, the code block will run again. it repeats until the condition returns FALSE.
### - WHILE:
if you don't know how many times the code should run, you can use a WHILE loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is TRUE.
##### Example:
> - var i = l ;
 - var msg = ' ' ;
 - while (i < 10) {
- msg += i + ' x 5 = ' + (i * 5) + '<br I>'; i++;
- document .getEl ementByid( ' answer') . innerHTML = msg;

### - FOR:
if you need to run code a specific number of times, use FOR look. (it is the most common loop.) in a FOR loop, the condition is usually a counter which is used to tell how many times the loop should run.

> for(var 1 = 0; i < 10; i++ ) {
  document.write(i);
}


&copy; Source: [javascript and jquery interactiv Book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01TTSXQT5M/javascript_and_jquery_interactive_jon_du.pdf?c=1618418988-21b29523d81fd117)