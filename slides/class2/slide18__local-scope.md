## Local Scope
A variable declared inside a function has a `local scope` and can only be accessed within that function.

```
const whatIsAwesome = () => {
  var awesomeGroup = 'Girl Develop It';              // Local scope
  console.log(awesomeGroup + ' is pretty awesome.'); // Will work
}

whatIsAwesome();

console.log(awesomeGroup + ' is pretty awesome.'); // Won't work
```