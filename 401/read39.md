What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

 The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.


When using a thunk/async action that dispatches the actual action, which do you export from your reducer?


middleware
Middleware is software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network. ... There are many types of middleware. Some, such as message brokers or transaction processing monitors, focus on one type of communication.


thunk
In computer programming, a thunk is a subroutine used to inject a calculation into another subroutine. Thunks are primarily used to delay a calculation until its result is needed, or to insert operations at the beginning or end of the other subroutine.

