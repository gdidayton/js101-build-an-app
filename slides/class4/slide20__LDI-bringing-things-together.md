## Let's Develop It

Let's bring a few of our new skills together. Create a new function called `setDogTricks`. It needs to:
- take a `dog` object as an argument
- save the `tricks` array from the `dog` object as a variable named `tricksArray`
- create a `let` variable called `tricksList` that contains an empty string
- use a `for loop` to loop through the `tricksArray` and:
  - create a list item (`<li>` element) that contains each trick
  - use string concatenation to add each list item to the `tricksList` variable
- After your `for loop`, set the innerHTML of the `tricksListElement` to equal `tricksList`