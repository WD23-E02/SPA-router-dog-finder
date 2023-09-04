# React Router Dog Finder

Build an app that routes to different dogs and displays information on that dog when you're at that route.

The routes look like this:

- `/dogs` is the homepage and shows Title contains _"Hello"_ as text and all three dogs.
- Clicking on a dog _Image_ from the homepage takes you to that dog's route. For example clicking on Whiskey will take you to `/dogs/whiskey` as a dog info page.
    - Use the same dog names from the images. __whiskey, tubby, hazel__
    - Dog info page should contain _"Age"_ and _the image of the dog_ if there is `this.props.currentDog` exists.
- Clicking on the _"Hello"_ Title og the dogs takes you to the homepage `/dogs`. 
- `/` and every other endpoint not listed should redirect you to `/dogs`.
- App has two routes: 
    - `/dogs` 
    - `/dogs/:name`
    - Both of them render the `Dogs` component.
- `Dogs` maps should be over the dog info, and renders a `Dog` component for each dog.

Here's an image of what the app looks like. It should look the same once you've refactored it!

![dog finder app](./dog-finder.gif)