# cra-template-reduxStarter

# Welcome to My Custom Template featuring Redux and Chakra Ui

## How To Install

### yarn

`yarn create react-app <app-name> --template reduxStarter`

### npm

`npm init react-app <app-name> --template reduxStarter`

### npx

`npx create-react-app <app-name> --template reduxStarter`

### global

> If create-react-app is installed globally on your computer you can use this command:

`create-react -app <app-name> --template reduxStarter`

## What makes it extra?

Bushido plus template comes with a placeholder private route / auth configuration.

Just like regular create-react-app but so much more. This template includes:

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

Redux boilerplate is set up with combine reducers and has a simple counter reducer used in one of the routes that use's react-redux's beautiful hooks to access actions and state from reducer's.

Reducer and action folders are inside a store folder so they are in the same spot.

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

App.js is ready for Routes and all components for routes are to be built in the components folder.
I have included axiosWithAuth as well as a PrivateRoute component to complete most of the boilerplate.
