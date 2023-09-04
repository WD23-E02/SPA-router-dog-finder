# React Router Dog Finder
[![Status overview badge](../../blob/badges/.github/badges/main/badge.svg)](#-results)


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

[//]: # (autograding info start)
# <img src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" alt="" data-canonical-src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" height="31" /> Results
> ⌛ Give it a minute. As long as you see the orange dot ![processing](https://raw.githubusercontent.com/DCI-EdTech/autograding-setup/main/assets/processing.svg) on top, CodeBuddy is still processing. Refresh this page to see it's current status.
>
> This is what CodeBuddy found when running your code. It is to show you what you have achieved and to give you hints on how to complete the exercise.


### Start Page

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status0.svg) | The inital route is "/dogs" |
| ![Status](../../blob/badges/.github/badges/main/status1.svg) | Three dogs are shown on the page, using the images from `src/images/` |

### Dog Details

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status2.svg) | App navigates to correct route when a dog is clicked |

### Redirect

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status3.svg) | Non-existent routes redirect to Home page |

### Dog pages content

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status4.svg) | Each dog page has info and image of the dog |
| ![Status](../../blob/badges/.github/badges/main/status5.svg) | The content is below the list of dogs |



[🔬 Results Details](../../actions)
[🐞 Tips on Debugging](https://github.com/DCI-EdTech/autograding-setup/wiki/How-to-work-with-CodeBuddy)
[📢 Report Problem](https://docs.google.com/forms/d/e/1FAIpQLSfS8wPh6bCMTLF2wmjiE5_UhPiOEnubEwwPLN_M8zTCjx5qbg/viewform?usp=pp_url&entry.652569746=SPA-router-dog-finder)


[//]: # (autograding info end)