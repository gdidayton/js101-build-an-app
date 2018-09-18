## Let's Develop It

Let's add some event listeners!

You'll see we already have the HTML for two buttons: **Previous Dog** and **Next Dog**. And you should already have some code in your JavaScript that finds those buttons and saves them to a variable.

It should look like this:

```
const nextButton = document.getElementById('next');
const previousButton = document.getElementById('previous');
```

Now I want you to add event listeners to both of those elements.
- Create two functions, `getPreviousDog` and `getNextDog` that each print something to the console (doesn't matter what).
- Add event listeners for both of your button elements that call the appropriate function.