## querySelector and querySelectorAll

You can also use `querySelector()` and `querySelectorAll()`.

To find one element:

```
<img id="kittenPic" src="http://placekitten.com/g/200/300" alt="cat"/>
```

```
document.querySelector('.kittenPic'); // returns one element
```

To find multiple elements:

```
<ul>
  <li>Daisy</li>
  <li>Tulip</li>
</ul>
```

```
document.querySelectorAll('li'); // returns an array of elements
```