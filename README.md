# Welcome to My Custom Template featuring Redux and Chakra Ui

## How To Install

### yarn

`yarn create react-app <app-name> --template reduxstarter`

### npm

`npm init react-app <app-name> --template reduxstarter`

### npx

`npx create-react-app <app-name> --template reduxstarter`

### global

> If create-react-app is installed globally on your computer you can use this command:

`create-react -app <app-name> --template reduxstarter`

## What is included?

This template includes:

- axios
- react-redux
- react-router
- react-router-dom
- redux
- redux-logger
- redux-thunk
- redux dev tools
- styled-components
- Chakra Ui
- axiosWithAuth
- PrivateRouter component

Redux boilerplate is set up but is blank for you to populate as you wish.

Reducers, Actions, and Types folders are inside a STATE folder.

```
| src |
| --- | components
| --- | *state* |
| --- | ------- |actions*
| --- | ------- |reducers*
| --- | ------- |types*
| App.js
| index.js
```

App.js is ready for Routes and all components for said Routes are to be built in the components folder.
I have included axiosWithAuth as well as a PrivateRoute component to complete most of the boilerplate.
