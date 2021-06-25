# Component-Based Architecture

## What is a Component?

### A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

## Views of a Component

- Object-oriented view

- Conventional view

- Process-related view

## Characteristics of Components

- Reusability.
- Replaceable.
- Not context specific.
- Extensible.
- Encapsulated.
- Independent

## What are the advantages of using component based architecture?

- Ease of deployment
- Reduced cost
- Ease of development
- Reusable
- Modification of technical complexity
- Reliability
- System maintenance and evolution
- Independent

![img](https://www.tutorialspoint.com/software_architecture_design/images/principles_of_component_based_design.jpg)

![img](https://miro.medium.com/max/2276/1*27LtOtFyJe7MguQkNcZQjQ.png)

## What is Props?

### React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props

### “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child) Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components

## How are props used in React?

- Firstly, define an attribute and its value(data)
- Then pass it to child component(s) by using Props
- Finally, render the Props Data

![img](https://i.stack.imgur.com/L7izb.png)

![img](https://i.stack.imgur.com/GhqlP.png)

## What is the flow of props?

## Recap:

- Props stand for properties and is a special keyword in React
- Props are being passed to components like function arguments
- Props can only be passed to components in one-way (parent to child)
- Props data is immutable (read-only)
