## Objectives
* [What is a variable?](#what-is-a-variable)
* Be able to name the six [JavaScript types](#javascript-types)

### What is a variable
A variables is a container for storing data values. Think of a variable as a box that holds a value.

##### Variable names

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

