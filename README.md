# redux-react-todos

App Description:
- this is a todo list app
- this is the front end, it communicates with "todos-backend"

Tech Stacks:
- it uses React to manipulate DOM, for the UI
- it uses Redux to manage State
- it uses React Router to do page routing
- it uses redux-thunk middleware to delay the state.dispatch

Flow:
- in rootReducer.js we create function of rootReducer()
- in index.js we createStore, declare redux devtool
- in index.js we import the Provider component from react-redux. So we are able to connect React app to Redux store.
- in TodoList.js we import connect function from react-redux. So we are able to grab the Redux state and place it on TodoList component props 
- in TodoList.js we use "mapDispatchToProps" as the 2nd parameter in connect() method to dispatch actions.
- when start using React Router, I move the add todo form into a separate NewTodoForm.js

Bugs: 
- 在c9上面，前后端无法沟通。
- 在local machine上面，当新添一个todo之后，它不会立马显示到页面上，即使点击“see my todos”也不会显示。只有刷新网页才会显示。
