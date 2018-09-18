## Cleaning Up

We have a little bit of clean-up to do to finish up our app...

First, move your event listeners into a function called `addEventListeners`.

```
const addEventListeners = () => {
  nextButton.addEventListener('click', getNextDog);
  previousButton.addEventListener('click', getPreviousDog);
}
```