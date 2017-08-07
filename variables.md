## Objectives
* [What is a variable?](#what-is-a-variable)
* [Be able to name the six JavaScript types](#javascript-types)
* [Manipulating variables](#manipulating-variables)
* [Printing to your screen](#print-to-screen)

### What is a variable
A variables is a container for storing data values. Think of a variable as a box that holds a value.

##### Variable names

You want the name of your variables to be as clear as possible.

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter, $ or _
* Names are case sensitive (y and Y are different variables)
* Reserved words (like JavaScript keywords) cannot be used as names

##### Naming convention
 camelCase every new word starts with an uppercased letter ***what we will be using***
 snake_case every word start is seperated by an _

###### What Variable names are vaild?
* `var helloWorld;`
* `var 897;`
* `var $hello;`
* `var @name;`
* `var _something;`
* `var 98things;`
* `var dance59;`
* `var $hello_world_98;`

### JavaScript types
In some languages you need to specifically declare data types, but JavaScript is dynamic, which means you do not need to explicity declare the type.

##### Primitive data types
* `var numbertype = 1`
* `var stringtype = 'string'`
* `var undefinedtype = undefined`
* `var nulltype = null`
* `var symboltype = Symbol('foo')` *** you dont have to worry about this one for now new to ES6***

##### Complex data types
* `var object = []`
* `function functiontype(){}`

You can check the type of any piece of data by using the typeof keyword. For example, typeof 'test' would return 'string', and typeof 5 would return 'number'.

###### Name the following data types
* `var mysteryVariable = 12341`
* `var mysteryVariable = '12341'`
* `var mysteryVariable = function (){}`

### Manipulating variables
Variables values can be changed by using `=` this is called variable assignment.

##### Variable Assignment
`
var dog
dog = 'harry'
`
here I create a variable called `dog` and then on the second line I assigned it a string value `'harry'`.

##### Variable manipulation
* `var netWorth = 0 // Variable is created `
* `netWorth = netWorth + 1000000 // new value is 1000000`
* `netWorth = networth / 1000 // new vaule is 1000`
* `netWorth = networth * 1000 // new vaule is 1000000`
* `netWorth = networth  1000 // new vaule is 1000000`
here `netWorth` is initialized with a value 0 then reassigned its previous value + 1000000.

Most arithmetic operators (-,*,/) do not work with strings. The + operator can be used to "add" or concatenate strings together.

* `var name = 'James'`
* `name = name + ' ' + 'Bond'`

You can even add two variables together

* `var firstName = 'James'`
* `var lastName = 'Bond'`
* `var fullName  = firstName + ' ' + lastName`

###### Manipulate the following variables

* create variables firstName, lastName, fullName then set their values to your name. Assign fullName using firstName and lastName seperating them with a space.
* create variables that its name is the same as your partners and its value is a random number given by that partner and add your age to it.

### Print to screen

* `console.log('hello')`
* `console.log(19213)`
* `console.log(firstName)`

this is a command that allows you to print to your screen. ***This does not do anything other then scream it to the world***


