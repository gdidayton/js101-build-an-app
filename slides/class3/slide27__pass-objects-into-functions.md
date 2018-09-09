## Passing Objects into Functions

Just like other data types, objects can be passed into functions:

```
var dog = {
  name: 'Casey',
  age: 14,
};

function describeDog(dog) {
  console.log(`${dog.name} is ${dog.age} years old`);
}

describeDog(dog);
```
