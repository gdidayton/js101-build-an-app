## DOM Nodes: innerHTML

You can also use innerHTML to add HTML elements inside of other HTML elements.

For example, if I have an empty `<ul>` node and I want to add a set of list items, I would create a string with the HTML for those list items and use `innerHTML` to add it inside the `<ul>` element.

```
const listItems = '<li>come</li><li>sit</li><li>stay</li>';

listElement.innerHTML(listItems);
```

This will create:

```
<ul>
  <li>come</li>
  <li>sit</li>
  <li>stay</li>
</ul>
```