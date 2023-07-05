
# introduction to programming

## tinker, learn, apply, create

### [how to use](https://login.codingdojo.com/m/667/15297/111615)
    1. spot the pattern
    2. reading content
    3. algo app
    4. code challenge


### [parts of an app]()
    - frontend 
    - backend
    - database

## variables and data types

### [variables and data types](https://login.codingdojo.com/m/667/15298/111618)

variables
: things that hold information: data
: access info/data by calling name

data types
: **types** of data: number, string, null/undefined, boolean

```js
var nyNum = 42;
var pi = 3.145
var myString = "This is a 'string' of characters";
var myVar = null;
var isAdmin = true 
```

comments
: used to explain code to other developers or your future self
: ignored by the interpreter

### [about trace]()
### [core: code challenge: create variables]()
### [core: algo app level 1]()

## order of operations

### [overview](https://login.codingdojo.com/m/667/15299/111622)

>The order that you learned in math classes still holds true for programming, where the programming language will work from left to right, first evaluating operations that are inside of parenthesis, then evaluating multiplication and division, and finally evaluating addition and subtraction. 

```js
var PEMDAS = "please excuse my dear aunt sally!"
PEMDAS = "parenthesis, exponents, multiplication(left to right), division(left to right), addition(left to right), and subtraction(left to right)"
```


### [trickier concepts](https://login.codingdojo.com/m/667/15299/111623)

- exponents:

```js
Math.pow(6, 2);
6 ** 2;
```


## commenting

### [introduction to comments](https://login.codingdojo.com/m/667/15301/111629)

```js
// like this

/*
 or like this...
*/

```
### [optional: practice commenting]()


## arrays

### [arrays](https://login.codingdojo.com/m/667/15300/111626)

array
: a *data structure* used to store a **collection** of data
: data can be *primitive* or *compound*

```js
var testScores = [98, 76, 54, 77, 67, 99, 74];
```

- add (create) items

```js
testScores.push(81);
console.log(testScores); // [98, 76, 54, 77, 67, 99, 74, 81]
```

- access (read) items

```js
console.log(testScores[0]); // 98
```
- modify (update) items
- 
```js
testScores[1] = 100;
console.log(testScores); // [98, 100, 54, 77, 67, 99, 74, 81]
```

- remove (delete)items

```js
testScores.pop();
console.log(testScores); // [98, 76, 54, 77, 67, 99, 74]
```
 - length of arrays

```js
console.log(testScores.length); // 7
```


### [core: code challenge: predict arrays]()
### [practice: algo app: arrays]()


## conditionals

### [conditionals](https://login.codingdojo.com/m/667/15302/111634)

```js
if (condition) {    
    // what to do if condition is true
}
else if (2nd condition) { // can have 0 to many of these statements    
    // what to do if 2nd condition is true
}
else {  // can have 0 or 1 of these statements    
    // what to do if none of the previous conditions are met
}

```
### [a tool: t-diagrams]()
### [core: code challenge: get in that ride]()


## problem solving for coders

### [approaching a problem]()
### [pseudo-code & comments: a deeper look]()
### [practice: academic honesty]()


## cognitive tools: digging deeper into metacognition

## operations

### [modulo]()
### [other operators]()

## loops 1

### [`for` loops](https://login.codingdojo.com/m/667/15303/111639)

```js
for(var start; stop; step){}
```
### [loop tips](https://login.codingdojo.com/m/667/15303/111640)
### [practice: code challenge: loop-d-loop]()
### [core: algo app level 4 & 5]()


## functions and parameters

### [functions]()
### [practice: code challenge: predict functions]()
### [return]()
### [practice: code challenge: `return`]()
### [practice: code challenge: debug]()
### [parameters]()
### [practice: code challenge: parameters]()
### [optional: code challenge: operators]()

## cognitive tools: failure, shame, and resilience

## loops 2

### [all about `break`]()
### [core: algo app level 7]()


## belt prep

### [belt tips and strategies]()
### [practice: algo app level 12]()
### [practice: algo app challenges]()

## loops 3

### [`while` loops]()
### [thinking aloud: building a `for` loop and a `while` loop]()