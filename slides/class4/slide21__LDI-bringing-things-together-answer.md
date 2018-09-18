## Let's Develop It

Here is what your new function should look like

```
const setDogTricks = (dog) => {
  const tricksArray = dog.tricks;
  let tricksList = '';
  for (var i = 0; i < tricksArray.length; i++) {
    tricksList += '<li>' + tricksArray[i] + '</li>';
  }
  tricksListElement.innerHTML = tricksList;
}
```

Now, just like we did before, call it with the first item in your `dogs` array.