#### Problem
- Write a JS program to generate a randomm number and store it in a variable . The program then takes an input from the user to tell them whether the guess was correct , greater or lesser than the original number
100 - (no of guesses) is the score of the user . The program is expected to terminate once the number is guessed . Number should be between 1-100

#### Solution
```
const num = Math.floor(Math.random() * 101);
const triesAllowed = 100;
let guess;
let tries = 0;
while(tries==triesAllowed || guess!=num){
  guess = prompt("Guess");
  if(guess>num)
      console.log("Guess lower");
  else if(guess<num)
      console.log("Guess higher");
  tries++;
}
if(tries<=triesAllowed)
    console.log("You won ! Your score is : ",100-count);
else
    console.log("You lost")
```