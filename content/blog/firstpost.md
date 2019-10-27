---
title: React Components
date: 2019-07-09
menu: main
image: img/profile.png
---
## React Components
Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions,but work in isolation and returns HTML via a render function.

Components come in two types, Class components and Function components, in this tutorial we will concentrate on Class components.

### Create a Class Component
When creating a React component, the component's name must start with an upper case letter.

The component has to include the extends React.Component statement, this statement creates an inheritance to React.Component, and gives your component access to React.Component's functions.

The component also requires a render() method, this method returns HTML.
```js
class Car extends React.Component {
  render() {
    return <h2>Hi, I am a Car!</h2>;
  }
}
```