# ***Operators and Loops***

## ***comparision operators(evaluation condition)***
 ![caca](https://theaccessbuddy.files.wordpress.com/2012/10/image4.png)
 you can use them to compair values with each others, for example you could compair some value from the script from one that the user enter.AND WE SHOULD know that the output for this is boolean(true of false)

 we have a lot of examples for the evalution condition:

 ### IS EQUAL TO ==
 its compair if 2 values are the same 
 ### IS NOT EQUAL TO !=
 its check if 2 values are not the same 
 ### STRICT EQUAL TO ===
 its check if 2 values if thay are from the same type and the same value 
 ### STRICT NOT EQUAL TO !==
 the oposit of ===
 ### GREATER THAN >
 its check if the first number is bigger than the second one 
 (workes only with number)
 ### LESS THEN <
its check if the first number is less than the second one 
 (workes only with number)

 ## ***Loops***
 ![fff](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Loops.jpg)
the loops has a condition at first the condition is checked,if its true, the block inside the loop will be run. at the end the condition will be checked again and so on until the condition gives you an false output.

we mainly have 3 types of loops 

### 1-For loop

and it used when you want to run a code for spicific number of times and it has the following form:
```
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```
### 2-while loop 
it is uesed when you dont know how many times the code will run. an it has the following form 
```
while (i < 10) {
  text += "The number is " + i;
  i++;
}
```
### 3-do while loop 
its the same as the while loop but it the code inside the block has to be run at least one time even if the condition gives you false from the start. and it has the following form:
```
do {
  text += "The number is " + i;
  i++;
}
while (i < 5);
```