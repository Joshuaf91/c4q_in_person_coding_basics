A control structure is a block of programming that analyzes variables and chooses a direction in which to go based on given parameters.

## Objectives
* [What is a conditional?](#what-is-a-conditional)
* [if statement](#if-statement)
* [if else statement](#if-else-statement)
* [Evaluate to booleans](#evaluate-to-booleans)

### What is a conditional
How does the computer handle different situations?
It uses conditionals. This is the foundation of programming.


### if statement
The conditional statement must evaluate to a boolean value `true` or `false`. 
```
if(condition statement){
  //do something
}
```

### if else statement
The bellow code will evaluate do the else block of code because 2>1 is not true.
```
if(2>1){
  console.log('it is greater')
}else{
  console.log('it is not greater')
}
```
We can even use variables to evaluate the conditional and combine else with if.
```
var myst1 = 10
var myst2 = 30
if(myst1>myst2){
  console.log('myst1 is greater then myst2')
}else if(myst2 > myst1){
  console.log('myst2 is greater then myst1')
}else{
  console.log('WHATS GOING ON?')
}
```

### Evaluate to booleans
The following is a common way to evaluate booleans.

| BOOLEAN | evaluate |
|:--------------:|:--------:|
| Equals | == |
| Not Equals | != |
| Greater than | > |
| Less than | < |
| Greater than or equal to | >= |
| Less than or equal to | <= |

###### Questions
* what is wrong with the code bellow?
  * ```
  if myVariable = 10 {
    console.log("myVariable was equal to 10")
  else {
    console.log("myVariable was NOT equal to 10")
  }
  ```
* Given a number tell me if its even or odd
* Given a string tell me if it matches your name

