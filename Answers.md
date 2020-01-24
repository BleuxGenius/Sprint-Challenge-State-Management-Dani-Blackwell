Questions answered MVP Completed 

1. What problem does the context API help solve?

It lets you avoid prop drilling and lets you pass data upstream.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

The store holds the state and it the only place your app will be getting state. Actions handle axios and send dispatches to the reducer, that handles the state changes.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

Component state is good for forms or things that are only used once. Application state reached more components and should hold things that will be needed or modified often.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

It's an interupting function. It lets us make asyncronus api calls

1. What is your favorite state management system you've learned and this sprint? Please explain why!


I like context becuse I don't have to bring in another library and I feel like it's easier to set up