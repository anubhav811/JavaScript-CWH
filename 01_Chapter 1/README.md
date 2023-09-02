Q1 . Create a variable of type string and try to add a number to it 
Q2. Use typeof in previous question to find typeof of the result object
Q3. Create a const , can you change it to hold a number later
Q4. Try to add a new key to const object in Q3 . Are you able to do it

```
// Q1 
let a = "Anubhav";
let b = 4;
console.log(a + b); // output:Anubhav4

// Q2 
console.log(typeof (a + b));
// string

// Q3
const a1 = {
  name: "Anubhav",
  section: 1,
  isStudent: true
}
// a = "Harry"
// Gives error : SyntaxError: Identifier 'a' has already been declared

// Q4
const a2 = {
  name: "Anubhav",
  section: 1,
  isStudent: true
}
a2['friend'] = "Krina"

console.log(a2);
// No error
// { name: 'Anubhav', section: 1, isStudent: true, friend: 'Krina' }


```