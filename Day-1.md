**The react-dom package provides DOM-specific methods that can be used at the top level of your app and as an escape hatch to get outside of the React model if you
  need to. Most of your components should not need to use this module.**

**The <Provider /> makes the Redux store available to any nested components that have been wrapped in the connect() function.**

**The BrowserRouter component has a basename prop, which accepts a string as its value in case the React app is hosted from a sub-directory.**

**StrictMode is a tool for highlighting potential problems in an application. Like Fragment , StrictMode does not render any visible UI.**

**React Router uses component structure to call components, which display the appropriate information.**

**React router does partial matching, so /users partially matches /users/create , so it would incorrectly return the Users route again! The exact
param disables the partial matching for a route and makes sure that it only returns the route if the path is an EXACT match to the current url.**

**The connect() function connects a React component to a Redux store. It provides its connected component with the pieces of the data it needs from the 
store, and the functions it can use to dispatch actions to the store.**

**Curly Braces are used to import single(specific) property , whereas the word without braces is import entire object form that file.**

**useStyles is a react hook. You can use it in function component only. This line creates the hook: const useStyles = makeStyles(theme => ({ /* ... */ });**

**mapStateToProps is a function that you would use to provide the store data to your component, whereas mapDispatchToProps is something that you will use to provide the action
creators as props to your component.**

**createStore(reducer,[preloadedState], [enhancer]) Creates a Redux store that holds the complete state tree of your app. There should only be a single store in your app.
React provides ref to get a reference to the rendered DOM element.**
