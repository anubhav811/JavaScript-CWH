
### Operators

#### Arithmetic Operators

- Add , Sub 
- Div (Returns precise float value)
- Mul
- Exponent (**)
- Modulus (%)
- Increment (++) / Decrement (--)

#### Comparison Operators

- ==   equal to
- !=   not equal to
- ===  equal value and type
- !==  not equal value or not equal type
-  ?   ternary operator

#### Logical Operators

- &&   logical AND
- ||   logical OR
- !    logical NOT

```
let a = 45;
let b = 4;

console.log("a + b = ", a + b);
console.log("a - b = ", a - b);
console.log("a / b = ", a / b);
console.log("a * b = ", a * b);
console.log("a ** b = ", a ** b);
console.log("a % b = ", a ** b);
console.log("a++", a++); // a = 45
// Now value is increased , a = 46 here
console.log("++a", ++a); // Value is increased here itself , a = 47;
console.log("a-- ", a--); // a = 47;
// Now value is decreased ,  a=46;
console.log("--a ", --a) // Value is decreased here itself , a=45



// Comparison Operators

let x = 5;
let y = "5";

console.log(x == y);  // true
console.log(x != y);  // false 
console.log(x === y); // false
console.log(x !== y); // true


```