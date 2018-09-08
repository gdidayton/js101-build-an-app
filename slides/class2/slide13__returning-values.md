## Returning Values

You can have a function give you back a value, to use later.

```
function square(num) {
  return num * num;
}

console.log(square(4));       // outputs '16'

var squareOfFive = square(5); // squareOfFive equals '25'
```

`return` will immediately end a function.