# ECOM
## What is ReactJS?
In computing, React (sometimes React.js or ReactJS) is a JavaScript library for building user interfaces.

It is maintained by Facebook and a community of individual developers and corporations.

React can be used as a base in the development of single-page applications and mobile applications. But to create complex applications it is required to use a composition of various libraries. Something for state management (e.g. Redux), something for routing etc.

React is mentioned in the same breath as other Javascript frameworks, but "React vs Angular" doesn't make sense because they aren't directly comparable. Angular is a complete framework (including a view layer), React is not. This is why React is confusing to understand, it's emerging in an ecosystem of complete frameworks, but it's mostly the view.

React gives you a template language and some function hooks to essentially render HTML. That's all React outputs, HTML. Your bundles of HTML / Javascript, called "components," can have their own internal state (such as which tab is selected in a tab view), but in the end you just barf out HTML.

## Example
The following is a rudimentary example of React usage in HTML with JSX and JavaScript.
```
<div id="myReactApp"></div>

<script type="text/babel">
  class Greeter extends React.Component { 
    render() { 
      return <h1>{this.props.greeting}</h1>
    } 
  } 
```
```
  ReactDOM.render(<Greeter greeting="Hello World!" />, document.getElementById('myReactApp'));
</script>
```

The Greeter class is a React component that accepts a property greeting. The ReactDOM.render method creates an instance of the Greeter component, sets the greeting property to 'Hello World' and inserts the rendered component as a child element to the DOM element with id myReactApp.

When displayed in a web browser the result will be
```
<div id="myReactApp">
  <h1>Hello World!</h1>
</div>
```
## Features of ReactJS

### 1. Adaptability
One of the most heartwarming features of React JS is its adaptability. What makes React JS usage a piece of cake is its capacity to get adopted with ease and convenience. Because of the short list of lifecycle approaches this is very easy to understand and use. With the advent of ES2015 and ES2016, a more functional and user friendly programming has become a cyber norm and render function of React JS makes it easy for React JS to comply with a user friendly and functional programming style.

### 2. Usefulness of JSX
The separation of HTML from Java is still a hot debate among programmers. The makers of React JS believe that this separation is indeed a very shallow one as both of them were very well integrated. Thus they introduce JSX and React JS features make it very easy because JSX makes the reasoning of a module easier than ever.

### 3. Free and Open Source
If a software is free and it is open source, there is needless to say that it is going to be the new favorite of programmers and relevant community. React JS usage is although subject to the curation by Facebook’s developers, it is still free and open source, which gives you a chance to get codes developed by elite and most enthusiastic developers.

### 4. SCMAScript
Programmer community believes that React JS feautres will touch new heights because of the availability of ECMAScipt6 and 7. While the latter is still in progress, its features are being used by big-shot libraries. With help of any good ES transpiler, you can use these stunning features.

### 5. Decorators from ES7
As it has been mentioned before, you do not need to wait for the ES7 features being supported by the Internet Explorer; you can use a transpiler for that. Decorators are one of the most useful features of React JS and they allow you to augment a function’s behavior by simply wrapping that in a different function.

### 6. Server-side Communication
One of the main reasons why people expect a mass use of React JS is because of React JS features like server-side communication. The library of React JS empowers the programmers by giving them lifecycle “hooks” to enable the serve requests. With help of this feature you understand the mechanism of XHR requests and thus easily update your library to use them.

### 7. Light Railing for Applications
React JS is being used by different companies, developers and programmers, but one reason why every IT company should consider React JS features, is its lifecycle methods, state and props’ capacity to provide enough railing to create useful apps. This railing, however, would not smother the free use of different libraries.

### 8. Asynchronous Functions & Generators
One of the main reasons for the immense React JS usage is the asynchronous functions and generators offered by ES6. The freedom to pause and resume the execution of a JavaScript function makes these generators popular among developers and programmers.

### 9. Flux Library
Like it has been said, React JS is actually a library made of Java scripts. Flux is one of the best libraries that complement React JS and make it very easy for the programmers to manage data across the whole application.

### 10. Destructuring Assignments
In ES6, Destructuring Assignments were introduced to the programmers. They allow the programmers to bring a compound object on the left side of assignment. Having such an amazing feature, one can save some keystrokes and also load only a subset of a required module.
Out verdict goes in favor of React JS and considering very useful features that React JS introduces to the community, we can predict that React JS features will only make it skyrocket in the coming years.

## About This Project
This is just a Basic Ecommerce site I developed while playing with ReactJS.
