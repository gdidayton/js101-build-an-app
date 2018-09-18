## DOM Nodes: Getting and Setting Attributes

You can also use [getAttribute](https://developer.mozilla.org/en-US/docs/Web/API/Element/getAttribute) or [setAttribute](https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute)

```
<img id="kittenPic" src="http://placekitten.com/g/200/300" alt="cat"/>
```

We could change the src attribute this way:

```
const imgKitten = document.getElementById('kittenPic');

// will return src attribute on image
imgKitten.getAttribute('src');

// will set our src to a new src
imgKitten.setAttribute('src', 'http://placekitten.com/g/600/500');
```