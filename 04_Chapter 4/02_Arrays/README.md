### Arrays

- Arrays are variables that can hold more than one value and that too of different types

```
const a = ["banana","apple","grapes"];
```
This is valid
```
const b = [4,"Anubhav",false];
```

This is also valid

- typeof arrays is oject

#### Array Methods

1) toString() -> converst to string with comma seperated values

2) join() -? joins all the array elements using a seperator

```
let a = [5,6,4];
a.join("-") ->  "5-6-4"
```
3) pop() 

4) push(ele) 

5) shift() -> removes first element and returns it

6) unshift() -> add element to the beginning . returns new array length

7) delete 
```
delete arr[1];
```

8) concat() 

```
    let a1 = [1,2,3];
    let a2 = [4,5,6];
    let a3 = [7,,8,9];

    a1.concat(a2,a3); -> [1,2,3,4,5,6,7,8,9]
```

9) sort()
```
a.sort()
```
The default sort order is ascending, built upon converting the elements into strings, then comparing their sequences of UTF-16 code units values.
Hence the above method might not give correct output if the user wants to sort array of nums

instead we can use
```
const numbers = [12,1,23,24,5];
// ascending
numbers.sort(function(a, b){return a-b}); 
// descending
numbers.sort(function(a, b){return b-a}); 

```


10) splice () -> add new items to array

const numbers = [1,2,3,4,5];
numbers.splice(2,1,23,24);

first argument => position to add
second argument => no of elements to remove
third and so on => elements to be added;

11) slice() -> slices out a piece from an array . creates new array

```
const num = [1,2,3,4]
num.slice(2) -> [3,4]
num.slice(1,3) -> [2,3]
```

12) reverse()

#### Looping through arrays

1) forEach Loop

```
const a = [1,2,3]
a.forEach((value,index,array)=>{
    // function logic
});

```

2) map() -> creates a new array by performing some operation on each array element

```
const a = [1,2,3]
a.map((value,index,array)=>{
    return value*value;
})
```

Map creates a new array , foreach is used to do some operation

3) filter() -> Filters an array with values that passes a test . Create a new array

```
const a = [1,2,3,4,5]
a.filter(greater_than_5);
```

4) reduce -> reduces an array to a single value
```
const numbers = [1,2,3,4,5]
 
let arr = numbers.reduce((a,b)=>{
  return a+b
})

console.log(arr)  // 15
// add is a function
```

5) Array.from -> to create an array from any other object

```
Array.from("Anubhav")
```