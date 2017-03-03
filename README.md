# Albums

to run your app on Android:
- open the emulator
- select the project folder
- react-native run-android

## React-Native Basic
- There are two types of components, the functional component and class baesd component
- state is a feature that only avaliable to class based components, state is used to record and react user interactions.
- prop is any type of data we pass from a parent to a child component.
- we can define reusable components with JSX and props, by passing a prop allow a component to be reconfigured on the fly with some new or different data.

## Rules of State

- Definition of state: a plain javascript object used to record and respond to user-triggered events.
- When we need to update what a component shows, call 'this.setState'
- Only change state with 'setState', do not do 'this.state'