## Calling Functions from HTML

You can call a function directly from your HTML code:

```
<button id="myBtn" onclick="sayHi()>Click Me</button>
```

```
const sayHi = (event) => {
  alert('Hi!');
}
```