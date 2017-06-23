# Notes
## Three items that react components are focused on
1. state
2. lifecycle events
3. UI

## Getting a React app started
1. `npm install --save react react-dom`
2. `npm install --save-dev babel-core babel-loader babel-preset-env babel-preset-react css-loader style-loader html-webpack-plugin webpack webpack-dev-server
`
3. create index.css, index.js
4. create webpack.config.js


Or use `npm install -g create-react-app`

## this keyword

**Implicit Binding** - Find where the function was invoked and look to the left of the dot

**Explicit Binding** - Setting this with .call, .apply, or .bind.
- `.call`: first argument is the this and each other argument is passed one by one
- `.apply`: same as `.call` but second argument is a list
- `.bind`: same as `.call` but returns a function that can be used later
