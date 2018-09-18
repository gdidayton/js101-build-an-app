## Let's Develop It

Here is what your function should look like:

```
const setDogPhoto = (dog) => {
  dogPhotoUrl = dog.photoUrl;
  dogPhotoElement.setAttribute('src', dogPhotoUrl);
}
```

And when you call it: 

```
setDogPhoto(dogs[0]);
```