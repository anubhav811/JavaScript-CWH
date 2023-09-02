### Primitive Data Types
 -set of basic data types in JS

#### NNBBSSU
- Null
- Number
- Boolean 
- BigInt
- String
- Symbol
- Undefined

```
// NN BB SS U
let a = null;
let b = 345
let c = true;
let d = BigInt("546")+BigInt("32");
let e = undefined 
let f ; // same as undefined ; 
let g = Symbol("I am a symbol")

console.log(a,b,c,d,e,f,g);



console.log(typeof a);  // object
console.log(typeof b);  // number
console.log(typeof c);  // boolean
console.log(typeof d);  // bigint
console.log(typeof e);  // undefined
console.log(typeof f);  // undefined
console.log(typeof g);  // symbol

```


### Object - Non Primitive Data Type
- an object is a standalone entity, with properties and type


```
const item = {
    "Anubhav" : true,
    "Krina" : 20,
    "Harry" : false
} 

console.log(item["Anubhav"]); // returns true

```