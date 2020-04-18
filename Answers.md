1. What problem does the context API help solve?
We can share values throughout components without having to pass props through every level of the tree.
1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
Actions are kinda describes how the reducer should take the old version of state and create a new version of state.Reducers is a function and the job is the return a new state.Store contains the state of the app and changes everything in the app by calling store.
1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
Component state is local and applciation state is global.
1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
Make the flow asynchronous in order to make API called from the action creators. Redux middleware cuts off the normal redux flow to make a call before actions make it to the reducer.
1. What is your favorite state management system you've learned and this sprint? Please explain why!
 Context API because I feel like thats easier than using redux