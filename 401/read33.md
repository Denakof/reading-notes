Why is the Context API useful?
The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

Can a component outside of a provider get its context?
To access a React context outside of the render function, we can use the useContext hook. We create the UserContext by calling the React. createContext method with a default context value. Then in the Users component, we call the useContext hook with UserContext to accxess the current value of UserContext .

What are some common use cases for using the Context API?
Some sample use cases where the Context API proves helpful are: Theming — Pass down app theme. i18n — Pass down translation messages. Authentication — Pass down current authenticated user.


Describe “Context Hell”
Like the callback hell, usual when jQuery was used for everything, the React Context hell is the nasty code you get taking advantage of the React Context API.

global state
In the causal domain, a global state is a set of local states which are all concurrent with each other. ... A global state in the time domain is also a global state in the causal domain; if two states occur simultaneously, then they cannot have any cause-effect relationship.

global context
This global context is about how concerned we are worldwide, how we make decisions about global issues and how we can act in a responsible way to make the world a better place. ... The opportunities and tensions provided by world- interconnectedness; The impact of decision- making on humankind and the environment.Apr 29, 2021

provider
Overview. The `<Provider>` component makes the Redux store available to any nested components that need to access the Redux store. Since any React component in a React Redux app can be connected to the store, most applications will render a `<Provider>` at the top level, with the entire app's component tree inside of it.


consumerA React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. Requires a function as a child. The function receives the current context value and returns a React node.

