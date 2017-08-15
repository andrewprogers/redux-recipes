# Redux-Recipes

This is a side project by [Andrew Rogers](www.github.com/andrewprogers) whose sole purpose is to try and build a first app using using redux and associated tools.

## Goals
- Build a client-side app that a user can use to:
  - Add Recipes, persist them to local storage
  - View Recipes
  - Scale recipes
- Make use of redux library to manage state
- Write idiomatic react-redux code that utilizes 'container' components and 'display' components
- extract actions to a file of action-generators
- Use redux with react-router to switch between recipe index and show pages, while maintaining state across the application

## Testing
While I'm generally a proponent of testing, I find it easier to not test-drive apps built purely to practice new skills. Testing will likely be minimal on this project until the end, when I would like to return to add some redux action and reducer-specific tests.

## Deployment

Not yet deployed, but stay tuned! The project can easily be run locally with:
```shell
$ yarn install
$ yarn start
```
