#### How can we ensure that an effect hook runs only once?
If we pass an empty array [] , it just renders the component only once like componentDidMount . Let's look at this example: import React, { useEffect, useState } from 'react'; function App() { const [count, setCount] = useState(0); useEffect(() => { console. log('Hello from useEffect!

Can useState() update more than one state variable at the same time?
You could combine the loading state and data state into one state object and then you could do one setState call and there will only be one render. Note: Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.

Is useState() synchronous?
useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components. Even though they are asynchronous, the useState and setState functions do not return promises.

State Hook:A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.

Component Lifecycle:
We are born, grow, and then die. Almost everything follows this cycle in its life, and React components do as well. Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.Mar 18, 2019
