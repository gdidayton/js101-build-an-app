## Calling Functions from JavaScript

You can call a function from the addEventListener:

```
<button id="myBtn">Click Me!</button>
```

```
const button = document.getElementById("myBtn");

button.addEventListener("click", (event) => {
  alert("Hi!");
});
```

or

```
const button = document.getElementById("myBtn");

const sayHi = (event) => {
  alert("Hi!");
};

button.addEventListener("click", sayHi);
```