---
layout: post
category : react
tagline: "the new Web Stack"
tags : [intro, react, JavaScript]
---
{% include JB/setup %}

## What is React?

React.JS is a JavaScript library for building _awesome_ web UI.
* Functional programming paradigms with Immutable data and pure functions
* Declarative (what) vs imperative (how) UI style
* React maintains a Virtual DOM which diffs with actual browser DOM and render minimally on state changes
* JSX - JS extension for HTML. Pre-parsing HTML-like tags to JavaScript

Core Concepts
* Component are building blocks of an app UI.
* Two types of data handling __props__ and __state__
* Use props to pass data b/w Component hierarchy.
* Use state to maintains data within Component
* State is data owned by one Component (init and setState)
* Props define what a Component "is"
* State defines what a Component "knows"
* initialize state in constructor
* Always use __setState__ to modify the state and re-render the App
* Render fn declare the new UI declaratively for every prop and state changes
* [Lifecycle hooks](https://facebook.github.io/react/docs/react-component.html) enable imperative code
* *   Component Mounting -> Updating -> Unmounting


Overview
- [Quick start](https://github.com/ericvicenti/intro-to-react)
- [React Component search @ JS Coach ](https://js.coach/react)

## Checkout my [React Scaffold project](https://github.com/chalam/react-scaffhold) with following integration

Base
- [Create React App](https://github.com/facebookincubator/create-react-app)

UI/UX

- [react-bootstrap](https://react-bootstrap.github.io)
- [Intro to Grid System](https://getbootstrap.com/css/#grid-intro)
- [Bootstrap themes](https://bootswatch.com/)

Routing
- [React Router](https://reacttraining.com/react-router/)

#### Future Roadmap

Next-Gen
- [Fiber - React 2.0](https://github.com/acdlite/react-fiber-architecture)

State management client-side-only, transient.
- [MobX](https://mobx.js.org/getting-started.html)
- [Redux](http://redux.js.org/)
- [Facebook Flux](https://facebook.github.io/flux/)


State management backed by Server
- [GraphQL](graphql.org)
- [ReactQL](https://reactql.org/)
- [Facebook Relay](https://facebook.github.io/relay/)
- [Netflix Falcor](https://netflix.github.io/falcor/starter/what-is-falcor.html)


Charting
- [HighCharts](www.highcharts.com)
- [Victory](http://formidable.com/open-source/victory/guides/custom-charts/)

DataGrid
- [HandsOnTable](https://handsontable.com/)
- [Pivot Table](http://orbjs.net/)


Data-Viz / WebGL / svg
- [D3.js](https://d3js.org/)
- [deck.gl](https://uber.github.io/deck.gl/#/)
- [three.js](https://threejs.org/)
