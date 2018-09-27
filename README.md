# redux-react-todos

App Description:
- this is a todo list app

Tech Stacks:
- it uses React to manipulate DOM, for the UI
- it uses Redux to manage State

Flow:
- in rootReducer.js we create function of rootReducer()
- in index.js we createStore, declare redux devtool
- in index.js we import the Provider component from react-redux. So we are able to connect React app to Redux store.
- in TodoList.js we import connect function from react-redux. So we are able to grab the Redux state and place it on TodoList component props 
- in TodoList.js we use "mapDispatchToProps" as the 2nd parameter in connect() method to dispatch actions.