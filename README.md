# cra-template-reduxStarter

# Welcome to My Custom Template featuring Redux

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
- Chakra UI
- axiosWithAuth
- PrivateRouter component

Redux boilerplate is set up with combine reducers and has a simple counter reducer used in one of the routes that use's react-redux's beautiful hooks to access actions and state from reducer's.

Reducer and action folders are inside a store folder so they are in the same spot.

```
| src |
| --- | components
| --- | *store* |
| --- | ------- |actions*
| --- | --- | reducers*
| App.js
| index.js
```

Routes are set in App.js and all components for routes are built in components folder.
