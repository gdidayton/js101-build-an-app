## Loops and Logic

You can add other statements or logical operators inside the loops.

```
// Count from 1 to 100

for (let i = 1; i <= 100; i++) {
  if (i % 3 === 0) {
    // Says 'Fizz' after multiples of three
    console.log(' Fizz');
  } else if (i % 5 === 0) {
    // Says 'Buzz' after multiples of five
    console.log(' Buzz');
  } else {
    console.log(i);
  }
}
```