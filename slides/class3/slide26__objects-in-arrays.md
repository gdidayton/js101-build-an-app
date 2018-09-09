## Arrays of Objects

Because arrays can hold any data type, they can also hold objects.

```
const dogs = [
  {name: 'Casey', age: 14},
  {name: 'Harper Lee',  age: 4}
];

for (var i = 0; i < dogs.length; i++) {
  var dog = dogs[i];
  console.log(`${dog.name} is ${dog.age} years old.`);
}
```

