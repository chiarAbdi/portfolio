---
title: React Components
date: 2019-10-27T07:20:01.630Z
draft: true
---
## React.Component
React lets you define components as classes or functions. Components defined as classes currently provide more features which are described in detail on this page. To define a React component class, you need to extend React.Component:

````js
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
````
