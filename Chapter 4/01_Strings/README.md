### Strings

- Can be created using single or double quotes.

#### Template literals

- Template literals use backtics instead of quotes to define a string

```
let name = `Anubhav`;
```
- With template literals , it is possible to use both single as well as double quotes inside a string

```
let sentence = `The name "is" Anubhav's `
```
- We can insert variables directly in template literals . This is called string interpolation

```
let a = `This is ${name}`
```


#### Escape Sequence Characters

```
let name = 'Adam D'Angelo';
```

If we try to print the above string javascript will misunderstand it

We can use a single quote escape sequence to solve the problem

let name = 'Adam D\'Angelo';

Similary we can use \ inside a string with doubles quotes

let name = "Anubha\"v";
console.log(name.length) -> 8

Other escape characters
- \n -> newline
- \t -> tab
- \r -> carriage return


#### String Properties and Methods

- name.length 
- name.toUpperCase()
- name.toLowerCase()
- name.slice(2,4) -> from 2 to 4 , 4 not included
- name.slice(2) -> from 2 to end
- name.replace("Bhai","Bhau") -> if first argument string is not found, nothing happens
- name.concat(ogString,stringToAdd);
- name.trim() -> removes whitespaces from start and end
- sentence.includes(word) -> returns a boolean
- str.startsWith(substr);
- str.endsWith(substr);

Strings are immutable , these methods return new strings , and dont change the original string.