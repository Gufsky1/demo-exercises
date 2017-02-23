# Micro Exercise: React, codepen

#### Objective
Introduction to codepen REPL and React components

#### Description
instructor will walk classroom through creating their first react component using codepen.

### Student instructions
Step 1. go to codepen
[react starter codepen url]

Step 2. paste into HTML box:  
```
<div id="app"></div>
```

Step 3. paste into into JS Box
```JavaScript
// our first component is App, it is a parent component
const App = () => {
  return null
}
```

Step 4. follow along with instructor, we will create and compose more components

#### Trainer instructions & notes
1. walk classroom through creating their first component 
2. explain differences between state-ful & stateless components
3. point out the use of ES6 arrow functions (comparing & contrast differneces from functions learned in previous lessons)
4. Show example of multiple component instances
5. Show example of passing props, explain & describe
6. Begin to describe state management to (prep for next lesson - react state)
7. Begin a deeper explanation on JSX (prep for upcoming lesson)
8. describe how rendering works

#### Observe & Assess
- ensure students understand how props work
- ensure students understand JSX vs HTML
- ask for questions

##### trainer Code snippets
```JavaScript
// render our App component to the DOM
React.render(<App />, document.getElementById('app'))


// stateless components
const Button = () => {
  return (<button>My Button</button>)
}

const H2 = (props) => {
  return (<h2>{props.name}</h2>)
}

const Card = () => {
  return (
  <div>
      <H2 name='Example Title' />
      <H2 name='Example asdasdf' />
      Hello World
      <Button />
      <Button />
    </div>

  )
}

const App = () => {
  return (
  <div>
    <Card />
  </div>
  )
}
// stateful components
export class App extends Component {

    shouldComponentUpdate(nextProps) {
        return this.props.actions !== nextProps.actions;
    }

    render() {
      return (<div>hello</div>);
    }

}
```
