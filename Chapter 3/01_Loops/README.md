## Loops and Functions

#### Types of for loop in JS

- for loop
- for in loop -> loops through the keys of an object
```
for(key in object){
    // Code to be executed
}

// Example

let obj = {
    anubhav : 90,
    krina : 90,
    harry : 60
}

for(let a in obj){
    console.log("Marks of " + a + " are " + obj[a] );
}

```
- for of loop -> loops through the values of an object
```
for(variable of iterable){
    // Code to be executed
}

// Example

for(let a of "Anubhav"){
    console.log(a);
}
/* Output:
A
n
u
b
h
a
v
*/ 


iterable -> iterable data structure like arrays , string etc
```
