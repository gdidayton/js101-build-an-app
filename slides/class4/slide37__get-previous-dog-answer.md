## Problem Solving

Here is what `getPreviousDog` should look like:

```
const getPreviousDog = () => {
  const numberOfDogs = dogs.length - 1;
  if (dogIndex === 0) {
    dogIndex = numberOfDogs;
  } else {
    dogIndex = dogIndex - 1;
  }
  setDogPhoto(dogs[dogIndex]);
  setDogName(dogs[dogIndex]);
  setDogTricks(dogs[dogIndex]);
};
```