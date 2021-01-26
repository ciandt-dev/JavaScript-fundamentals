# JavaScript - Fundamentals #

This is an overview of the JavaScript language to help new developers get up and running.

Content is splitted into small modules with suggestion time to complete the activy.
Could be studied by day as individual, group and/or dojo.

Obs: after finishing this _"course"_ you can continue to the [nodeJS - Fundamentals](https://github.com/ciandt-dev/NodeJS-fundamentals) repository.

## Table of contents ##

* [Content index](#content-index)
* [Implementing solutions for exercises](#implementing-solutions-for-exercises)
* [Coverage](#coverage)
* [Lint](#lint)

## Content index ##

### Module 1 (1h) ###
* Variables - [Javascript.com](https://www.javascript.com/learn/variables); [MDN](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/Vari%C3%A1veis)
* Strings - [Javascript.com](https://www.javascript.com/learn/strings); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
* Numbers - [Javascript.com](https://www.javascript.com/learn/numbers); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)
* Booleans - [Javascript.com](https://www.javascript.com/learn/booleans); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)
* [Null](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null)
* [Undefined](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
* Operators - [Javascript.com](https://www.javascript.com/learn/operators); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators)
* Conditionals- [Javascript.com](https://www.javascript.com/learn/conditionals); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
* [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

> [Exercise 1](./docs/exercises/1.module.md)

### Module 2 (1h) ###
* Objects - [Javascript.com](https://www.javascript.com/learn/objects); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)
* Arrays - [Javascript.com](https://www.javascript.com/learn/arrays); [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
* [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates#Date_object)

> [Exercise 2](./docs/exercises/2.module.md)

### Module 3 (1h) ###
* [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
    * Online tool: [regex101](https://regex101.com/)
* Functions - [Javascript.com](https://www.javascript.com/learn/functions); [MDN](https://developer.mozilla.org/en-US/docs/Glossary/Function)
    * [Parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#Function_parameters)
    * [Arguments object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#Using_the_arguments_object)

> [Exercise 3](./docs/exercises/3.module.md)

### Module 4 (2h) ###
* [Custom objects ("Class")](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS)
    * [Prototypes](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes)
    * [Inheritance](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance)

> [Exercise 4](./docs/exercises/4.module.md)

### Module 5 (1h) ###
* [Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

> [Exercise 5](./docs/exercises/5.module.md)

### Module 6 (1h) ###
* [Error](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling#Exception_handling_statements)
* [Try/Catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch)
* [console](https://developers.google.com/web/tools/chrome-devtools/console/console-reference)

> [Exercise 6](./docs/exercises/6.module.md)

### Module 7 (1h) ###
* [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
* [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

> [Exercise 7](./docs/exercises/7.module.md)

### DOJO (2h) ###

> [DOJO - JS Fundamentals](./docs/exercises/dojo.md)

[[ :top: ]](#)

* * *

## Implementing solutions for exercises ##

We strongly recommend checking if your solutions are correct using the [TDD paradigm](https://en.wikipedia.org/wiki/Test-driven_development "Test-Driven-Development").

For this, follow bellow instructions.

### Setup environment ###

```shell
1. Make sure you have NodeJS >= 6 installed.
2. Clone this repo
3. cd JavaScript-fundamentals
4. npm install
```

### Implementing your solutions ###
Your solutions must be implemented on `lib/module${n}.js`.

So for exercises of module1, you must edit `lib/module1.js`.

In this file you'll see comments indicating where to implement your solution.
You'll just export a function returning your answer.

### Checking if your solution is correct ###

To test _a **specific** solution of yours_ you can do:

```shell
npm run `test${n}`
```

For instance, if you want to see how's your solution for module4, you should do:

```shell
npm run test4
```

* If the test fails it'll show on the console what's the spectation of solution, so you can fix it and the test runner will automatically check the solution again.
* If the current testing exercise succeded, it'll check the solution of the next exercise of the module.
* If you want to stop the test runner, just press _ctrl+c_.

To test _**ALL** solutions_ from all modules:
```shell
npm test
```

[[ :top: ]](#)

## Coverage ##

If you want to check tests coverage:

```shell
npm run cover
```

[[ :top: ]](#)

## Lint ##

To check if your code is attending to standards:

```shell
npm run lint
```

[[ :top: ]](#)
