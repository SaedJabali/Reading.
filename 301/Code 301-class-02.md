# React

## React State

React components has a built-in *state* object.

The state object is where we store property values that belongs to the component.

When the state object changes, the component re-renders.

## React Lifecycle

Lifecycle of Components

Each component in React has a lifecycle which we can monitor and manipulate during its three main phases.

### The three phases are:

* Mounting:  Mounting means putting elements into the DOM.

* Updating:  The next phase in the lifecycle is when a component is updated.

   A component is updated whenever there is a change in the component's state or props.

* Unmounting: The next phase in the lifecycle is when a component is removed from the DOM, or unmounting as React likes to call it

1. **Mounting**

React has four built-in methods that gets called, in this order, when mounting a component:

constructor()

getDerivedStateFromProps()

render()

componentDidMount()

2. **Updating**

React has five built-in methods that gets called, in this order, when a component is updated:

getDerivedStateFromProps()

shouldComponentUpdate()

render()

getSnapshotBeforeUpdate()

componentDidUpdate()



3. **Unmounting**

React has only one built-in method that gets called when a component is unmounted:

componentWillUnmount()


## React Events

React has the same events as HTML: click, change, mouseover etc.

**Adding Events**

React events are written in camelCase syntax:

onClick instead of onclick.

React event handlers are written inside curly braces:

onClick={shoot}  instead of onClick="shoot()".

**Bind this**

For methods in **React**, the *this* keyword should represent the component that owns the method.

That is why we should use arrow functions. With arrow functions, *this* will always represent the object that defined the arrow function.

In class components, the this keyword is not defined by default, so with regular functions the this keyword represents the object that called the method, which can be the global window object, a HTML button, or whatever.

**Without the binding, the this keyword would return undefined.**

**Passing Arguments**

If we want to send parameters into an event handler, we have two options:

1. Make an anonymous arrow function.

2. Bind the event handler to this.

**Conditional rendering** in React works the same way conditions work in JavaScript.
Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.

