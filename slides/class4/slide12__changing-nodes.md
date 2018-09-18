## Changing DOM Node Attributes

You can access and change attributes of DOM nodes using dot notation.

To change this element:

```
<img id="kittenPic" src="http://placekitten.com/g/200/300" alt="cat"/>
```

We could change the src attribute this way:

```
const imgKitten = document.getElementById('kittenPic');

// will return src attribute on image
imgKitten.src

// will set our src to a new src
imgKitten.src = 'http://placekitten.com/g/600/500';
```