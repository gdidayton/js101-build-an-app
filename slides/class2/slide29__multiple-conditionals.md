## The if/else statement

If you have multiple conditions, you can use `else if`.

```
const age = 30;

if (age >= 35) {
  console.log('You can vote AND run for President!');
} else if (age >= 30) {
  console.log('You can vote AND run for the Senate!');
} else if (age >= 18) {
  console.log('You can vote!');
} else {
  console.log('You can\'t vote, but you can write your representatives.');
}
```