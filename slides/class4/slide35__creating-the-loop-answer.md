## Problem Solving

Here is what your `getNextDog` should look like now:

```
const getNextDog = () => {
  if (dogIndex === dogs.length-1) {
    dogIndex = 0;
  } else {
    dogIndex = dogIndex + 1;
  }
  setDogPhoto(dogs[dogIndex]);
  setDogName(dogs[dogIndex]);
  setDogTricks(dogs[dogIndex]);
}
```