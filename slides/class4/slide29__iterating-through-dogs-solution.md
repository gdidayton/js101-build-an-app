## Problem Solving

How are we going to have our page load the information for the next dog when we click the `next dog` button?

**We create our own iterator!**

- At the top of your code, create a `let` variable called `dogIndex` and set it to equal `0`
- Inside your `getNextDog` function, add 1 to `dogIndex`, then call `setDogPhoto`, `setDogName`, and `setDogTricks`, giving each one the item in the dogs array that matches the number in `dogIndex`.