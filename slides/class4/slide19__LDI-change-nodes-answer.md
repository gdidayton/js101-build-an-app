## Let's Develop It

Here is what your function (and function call) should look like now:

```
const setDogName = (dog) => {
  dogName = dog.name;
  dogAge = dog.age;
  dogNameElement.innerHTML = `${dogName}, age ${dogAge}`;
}

setDogName(dogs[0]);
```