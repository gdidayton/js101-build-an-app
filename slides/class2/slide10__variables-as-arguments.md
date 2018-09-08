## Arguments

You can also pass `variables` into functions. These variables do not need to have the same name as the function arguments.

```
function addOne(num){
  const newNumber = num + 1;
  console.log(`You now have ${newNumber}`);
}

// Declare variables
const numberOfKittens = 5;
const numberOfPuppies = 4;

// Use them in functions
addOne(numberOfKittens);
addOne(numberOfPuppies);
```