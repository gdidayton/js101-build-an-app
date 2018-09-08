## Boolean Variables

Some values are considered [falsy](https://developer.mozilla.org/en-US/docs/Glossary/Falsy) and will evaluate to `false` in a Boolean context.

```
// the following variables will evaluate as false

var myName = '';
var numOfKids = 0;
var isMarried;     // remember a variable with no value is undefined
```

`null` and `NaN` will also evaluate as `false`.

Everything else evaluates as `true`.