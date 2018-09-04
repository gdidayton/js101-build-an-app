## Combining strings and numbers

You can use concatenation to mix strings and numbers. When you do this, JavaScript will treat the number like a string.

```
const numberOfAnimals = 6;
const typeOfAnimal = 'dogs';
const allTheAnimals = `I have ${numberOfAnimals} ${typeofAnimal}`;
console.log(allTheAnimals);
```