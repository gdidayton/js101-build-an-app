## Problem Solving

Here is what your `getNextDog` function should look like now.

```
const getNextDog = () => {
  dogIndex = dogIndex + 1;

  setDogPhoto(dogs[dogIndex]);
  setDogName(dogs[dogIndex]);
  setDogTricks(dogs[dogIndex]);
}
```

Click your **Next Dog** button a few times. You should see the dogs changing! 🎉🎉