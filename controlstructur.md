## Objectives
* [What is a conditional?](#what-is-a-conditional)
* [what is a Loop](#loop)

### What is a conditional
How does the computer handle different situations?
It uses conditionals. This is the foundation of programming.
```
if(condition statement){
  //do something
}else{
  //do something else
}
```
The conditional statement must evaluate to a boolean value `true` or `false`.

```
if(1>2){
  console.log('it is greater')
}else{
  console.log('it is not greater')
}
```
|  Date      | Lesson |
|:----------:|:------:|
| 2016-07-18 |[Environment & Tools](lessons/env-and-tools)<br> [Intro to Pair Programming](lessons/pair-programming) |
| 2016-07-19 |[Workshop Review](lessons/javascript-fundamentals/workshop-review) |
| 2016-07-20 |[Types, Strings, and Numbers](lessons/javascript-fundamentals/types-strings-and-numbers) |
| 2016-07-21 |[Objects and Arrays](lessons/javascript-fundamentals/objects-and-arrays)|
| 2016-07-22 | [Intro To HTML and CSS Part 1](lessons/html-and-css/intro-to-html-and-css-part-1) |
We can even use variables to evaluate the conditional.
```
var myst1 = 10
var myst2 = 30
if(myst1>myst2){
  console.log('myst1 is greater then myst2')
}else{
  console.log('myst2 is greater then myst1')
}
```
| BOOLEAN | evaluate |
|:-----------------------:|:--------:|
| Equals | == |
| Not Equals | != |
| Greater than | > |
| Less than | < |
| Greater than or equal to | >= |
| Less than or equal to | <= |