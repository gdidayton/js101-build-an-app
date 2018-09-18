## DOM Nodes: innerHTML

You can also use `innerHTML` to change things inside of DOM nodes.

For example, if I have a `<p>` element, I can use `innerHTML` to add text to it.

```
paragraphElement.innerHTML = 'I love dogs!';
```

Will change **`<p></p>`** to **`<p>I love dogs!</p>`**


### Caution!

`innerHTML` completely replaces what is currently inside your element.