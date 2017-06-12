## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.

Scope is the accessibility of functions and variables within a section of code.
When code is executed functions and variable are hoisted to the top of their scope.  Only declarations are hoisted.
Compartmentalization is dividing your code into different sections and limiting the scope of certain variables and functions so that they are not overwritten by other code.
### Provide examples for all three, below:

#### Scope:
var x = 1
console.log(x) // 1
function () {
  var x = 2
  console.log(x) // 2
}

console.log(x) // 1
#### Hoisting:
test()
function test () {
  console.log(2)
}


#### Compartmentalization:
var x = 1

function () {
  var x = 2
}
