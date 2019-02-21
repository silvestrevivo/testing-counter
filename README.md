# testing-counter

Unit-testing/React excercise developed with Jest + Enzyme, following the the Udemy tutorial from @flyrightsister

### app.js
```javascript
import React, { Component } from 'react';
import './App.css';

class App extends Component {
  render() {
    return (
      <div>
        testing-counter
      </div>
    );
  }
}

export default App;
```

### app.test.js
```javascript
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

it('renders without crashing', () => {
  const div = document.createElement('div');
  ReactDOM.render(<App />, div);
  ReactDOM.unmountComponentAtNode(div);
});
s
```
