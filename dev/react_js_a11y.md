# Explorations in the Virtual DOM: How React.js Impacts Accessibility

Marcy Sutton, Deque Systems - 3/3/2017

## Wuts Good?
- Virtual DOM
- Component lifecycle
- one way data flow
- well timed
- developer ergonomics, package everything within JS

## a11y in react apps
- virtual dom
- html in js
- user input events
- focus management
- user testing

## virtual dom
- in-memory representation of the DOM tree
- diffs against real dom
- when there's a change, push it to the real dom

## HTML in JS
- https://github.com/davidtheclark/react-aria-menubutton
- built in type checking
- JSX <3
- User Input event handling
- handle navigation keypress events
- Once again, https://github.com/evcohen/eslint-plugin-jsx-a11y
- https://github.com/reactjs/react-a11y: flags issues on command line
- https://github.com/dylanb/react-axe: same deal but with axe rules

## User input events
- dynamic HTML
- event handler garbage collection
- multiple contexts - handles stuff like iframes
- synthetic event delegation (???) wrapper around native DOM events, follows w3c spec
- watch this https://www.youtube.com/watch?v=dRo_egw7tBc

## Focus Management
- https://www.smashingmagazine.com/2015/05/client-rendered-accessibility/
- timeouts: has focus moved? https://github.com/facebook/react/issues/1791#issuecomment-82987932
- make sure not to redraw or reorder an element that currently has focus
- check for document.activeElement (does this work across browsers???)
- input event/focus on refs
- assign via component state
- focus on mount/update
- **focus layer system**

## Testing
- unit tests
- integration tests
- tools
- Angular hides lots of relevant data
- isolated tests vs integration tests
- shallow vs mounted dom

### Unit tests
- render with specific props/state
- handling interactions
- snapshot testing

### Tools
- react test utils
- enzyme (it's cool.)
- jest
- simulate events, shallow render, mount components into dom

### Shallow rendering
- render without mounting into DOM
- renders one level deep without worrying about child components
- test in isolation, no need for mock
- good for unit tests
- check out react aria menubutton for examples

### A11y tests requiring more than shallow DOM
- computed name, role
- color contrast
- visible focus state
- focus mgmt with refs
- aria support
- https://gist.github.com/marcysutton/835c2fd90fadb631414b39523d5bda61

### Integration tests
- Unit tests won't catch everything
- test components together
- slower, more processor heavy
- real browser, accurate results

### #Blessed components
- react modal
- react autocomplete
- react tabs
- react aria menubutton
