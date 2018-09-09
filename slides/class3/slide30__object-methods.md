## Object methods

Objects can also hold functions.

```
const casey = {
  name: 'Casey',
  age: 14,
  tricks: ['come', 'stay', 'sit', 'smile'],
  wag: () => {
    console.log('Casey is happy to see you!');
  }
}
```

Call object methods using dot notation:

```
casey.wag();
```