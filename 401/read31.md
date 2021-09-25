Describe use cases useState() vs useReducer()
useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

Why do custom hooks need the use prefix?
Custom Hooks
This is mainly to have an extra option for sharing state and logic between components. ... Custom hooks are normal JS functions, named with the prefix 'use', that can use hooks inside of it and contain a common stateful logic to be reused in other components.

What do custom hooks usually do?
Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks

Using any list of custom hooks, research and name one that you think will be useful in your applications
Custom React Hooks allow us to extract component logic into reusable functions. Custom Hooks look very much like normal helper functions, except they can maintain component state and perform effects. ... So if you find yourself using a lot of these Hooks, you might as well import the package.

Describe how a hook that fetches API data might work
Put the fetchData function above in the useEffect hook and call it, like so: useEffect(() => { const url = "https://api.adviceslip.com/advice"; const fetchData = async () => { try { const response = await fetch(url); const json = await response. json(); console. log(json); } catch (error) { console.

reducer:Definitions of reducer. a substance capable of bringing about the reduction of another substance as it itself is oxidized; used in photography to lessen the density of a negative or print by oxidizing some of the loose silver. synonyms: reducing agent, reductant. types: hydrazine.
