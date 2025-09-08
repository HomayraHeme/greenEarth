1) Difference between var, let, and const

var: Function-scoped, hoisted, can be redeclared/updated.

let: Block-scoped, not hoisted in the same way, can be updated but not redeclared.

const: Block-scoped, must be initialized, cannot be updated or redeclared.



 2) Difference between map(), forEach(), and filter()

map(): Transforms each element → returns a new array.

forEach(): Iterates over elements → does not return a new array.

filter(): Returns a new array with elements that match a condition.


3) What are arrow functions in ES6?
   Arrow functions in ES6 are a shorter way to write functions.
They:

Have a concise syntax.

Do not have their own this or arguments (they inherit from the surrounding scope).

Are often used for shorter, cleaner code.

ex:const add = (a, b) => a + b;


4) How does destructuring assignment work in ES6?
    It’s a shortcut to extract data without writing multiple lines.

From arrays → assign values by position.

From objects → assign values by property name.
ex:const [a, b] = [1, 2];  
const {name, age} = person;



5) Explain template literals in ES6. How are they different from string concatenation?
   Template literals in ES6 are strings written with backticks.

They allow:

Variable interpolation (insert variables directly inside a string).

Multi-line strings without using special characters.

Difference from concatenation: Template literals are cleaner, more readable, and don’t require + to join strings.
ex:`Hello ${name}, you are ${age} years old.`

   

