Why choose Redux instead of the Context API for global state?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity.Jun 12, 2020

What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.Oct 24, 2019


What does an action contain?
Actions are the only source of information for the store as per Redux official documentation. It carries a payload of information from your application to store. As discussed earlier, actions are plain JavaScript object that must have a type attribute to indicate the type of action performed.


Why do we need to copy the state in a reducer?
If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part.
immutable state: Immutable state means its value cannot be changed once it’s created.

time travel in redux: Time travel is the ability to move back and forth among the previous states of an application and view the results in real time.

action creator: An action creator is merely a function that returns an action object.Calling an action creator does nothing but return an object, so you have to either bind it to the store beforehand, or dispatch the result of calling your action creator.

reducer: A reducer is a function that determines changes to an application’s state. It uses the action it receives to determine this change.

dispatch: dispatch is a function of the Redux store. You call store. dispatch to dispatch an action.


