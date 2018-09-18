## DOM Access by Tag Name

You can also get HTML elements by their `tag` using this method:

```
document.getElementsByTagName(tagName);
```

To find:

```
<ul>
  <li>Daisy</li>
  <li>Tulip</li>
</ul>
```

We would use:

```
const listItems = document.getElementsByTagName('li');

for (let i = 0; i < listItems.length; i++) {
  var listItem = listItems[i];
}
```