## Why do we not need more .html pages in a multi-page React app?

create-react-app provides a great starting point to start a new react app fully configured with webpack, live reloading, etc. But, sadly, it doesn’t provide a way to provide different index files with a different set of entry points. This might not be an issue for many since it is supposed to be a “single page application”, but recently we had a scenario where we needed to provide a different entry point (which differed significantly from the original app) to warrant a separate SPA but had enough shared code too to make setting up a separate project redundant.

If we wanted a component to show up on every page, where would we put it and why?
 `<BrowserRouter>` is a `<Router>` that uses the HTML5 history API (pushState, replaceState and the popstate event) to keep your UI in sync with the URL. For navigation on click of a button you can use Redirect from react-router-dom package.

 What does routing do with the components that were rendered when a new route is requested

What does props.children contain?
props. children does is that it is used to display whatever you include between the opening and closing tags when invoking a component. This component contains an `<img>` that is receiving some props and then it is displaying {props.Apr 7, 2018

How do useState() and this.setState() differ?
The setState function is used to handle the state object in a React class component. This is something you will see a lot of in the examples below. Anytime you see a this.setState() this is how we are setting the state in a class component.

useState() Functional Component
With a functional component, we can use React hooks, specifically the useState() hook. This simplifies the creation of a state component and the function that updates it.

setState() Class Component
Since state in a class component is already an object, it's business as usual. Use setState to populate the values of the state object.

State Hook
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.

Mounting and Un-Mounting
The mount command mounts a storage device or filesystem, making it accessible and attaching it to an existing directory structure. The umount command "unmounts" a mounted filesystem, informing the system to complete any pending read or write operations, and safely detaching it.