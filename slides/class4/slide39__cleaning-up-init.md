## Cleaning Up

Create an `init` function and move into it your initial calls of `setDogPhoto`, `setDogName`, and `setDogTricks`. 

Add a call to `createEventListeners`.

```
const init = () => {
  setDogPhoto(dogs[0]);
  setDogName(dogs[0]);
  setDogTricks(dogs[0]);
  addEventListeners();
};
```