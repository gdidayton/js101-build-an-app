## Global Scope

A variable declared outside of a function has a <code>global scope</code> and can be accessed anywhere, even inside of functions.

```
const awesomeGroup = 'Girl Develop It'; // Global scope

const whatIsAwesome = () => {
  console.log(awesomeGroup + ' is pretty awesome.'); // Will work
}

whatIsAwesome();
```