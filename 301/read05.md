# Start With A Mock

![img](https://hackernoon.com/hn-images/1*HSisLuifMO6KbLfPOKtLow.jpeg)

## this is our example in the article , details are in the link

![img](https://ar.reactjs.org/static/1071fbcc9eed01fddc115b41e193ec11/d4770/thinking-in-react-mock.png)

## How would you break a mock into a component heirarchy?

1. Break The UI Into A Component Hierarchy : The first thing you’ll want to do is to draw boxes around every componen (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!  But how do you know what should be its own component? Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing If it ends up growing, it should be decomposed into smaller subcomponents.Since you’re often displaying a JSON data model to a user, you’ll find that if your model was built correctly, your UI (and therefore your component structure) will map nicely. That’s because UI and data models tend to adhere to the same information architecture. Separate your UI into components, where each component matches one piece of your data model.



2. Build A Static Version in React: To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

3. Identify The Minimal (but complete) Representation Of UI State

4. Identify Where Your State Should Live:

### React is all about one-way data flow down the component hierarchy. It may not be immediately clear which component should own what state. This is often the most challenging part for newcomers to understand, so follow these steps to figure it out

### For each piece of state in your application

### Identify every component that renders something based on that state

### Find a common owner component (a single component above all the components that need the state in the hierarchy).Either the common owner or another component higher up in the hierarchy should own the state.If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.Let’s run through this strategy for our application

### ProductTable needs to filter the product list based on state and SearchBar needs to display the search text and checked state. The common owner component is FilterableProductTable. It conceptually makes sense for the filter text and checked value to live in FilterableProductTable

#### Finallly  ***Add Inverse Data Flow***

 ## What is the single responsibility principle and how does it apply to components?

## The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part. All of that module, class or function's services should be narrowly aligned with that responsibility

![img](https://slidetodoc.com/presentation_image/f34c26d4d8207e370f8cc39ba6673693/image-41.jpg)

- the three Q's

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

What does it mean to build a ‘static’ version of your application?

 building a static version requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing. We’ll see why.

To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

Once you have a static application, what do you need to add?
How can you identify where state needs to live?
Remember: React is all about one-way data flow down the component hierarchy. It may not be immediately clear which component should own what state. This is often the most challenging part for newcomers to understand, so follow these steps to figure it out:

For each piece of state in your application:

Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

