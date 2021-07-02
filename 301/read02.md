# React: Component Lifecycle Events

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
render

What is the very first thing to happen in the lifecycle of React?
Mounting
When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
1.constructor
2.render
3.componentDidMount
4.componentWillUnmount

What does componentDidMount do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().
setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.
Here we use componentDidMount() to connect to the YouTube API and get videos when the components is rendered.

What types of things can you pass in the props?
like arguments to a function you create a component inside react and you want to render it you pass it to the props you want to give to it 
What is the big difference between props and state?
state is something inside a component but props you pass into a component and state is handlded indside  the component 
props is out side the comp
When do we re-render our application?
when something has done by the user and we want to update it 
What are some examples of things that we could store in state?
when we want to update somwthing that is inside the component 
like in the form whether its box checkbox so we use state to store what is updated by the user 
