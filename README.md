# @vyg/react-scripts
This is "forked" from Facebook's `react-scripts` v2.0.4 to customize our version of `create-react-app`. It contains the following changes:

- Add `sass-mq`
- Remove service-worker
- Add support for babel-plugin-react-css-modules
- Add support for decorators
- Add module resolver to resolve `~` to base `src` directory


# Usage
`npx create-react-app --scripts-version=@vyg/react-scripts APP_NAME`

## How to make changes
* Makes changes
* Bump package.json version
* `npm publish`

# Original react-scripts package

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://github.com/facebook/create-react-app/blob/master/README.md#getting-started) – How to create a new app.
- [User Guide](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.
