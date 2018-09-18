## Let's Develop It

We're going to use our `setDogName` function to change the `dogName` node so that it lists the name of the first dog in our dogs array.

You're going to have to do a couple of things here:

- Change your `setDogName` function in a couple of ways:
  - It should take one argument (`dog`), instead of `name` and `age`
  - The `dog` argument will be an object, so you'll need to find the `name` and `age` properties and save them as variables
  - instead of returning a string, it will need to change the `innerHTML` of your `dogName` node.

- Call your `setDogName` function and give it as an argument the first object in your `dogs` array.