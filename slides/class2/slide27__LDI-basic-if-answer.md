## Let's Develop It

Here is what your `dogAge` function should look like:

```
cost dogAge = (age) => {
  if (age < 2) {
    return 'Puppy';
  }
}
```

And here is how you can print the result to the console:

```
console.log(dogAge(9)); // should not print anything
console.log(dogAge(1)); // should print 'Puppy'
```