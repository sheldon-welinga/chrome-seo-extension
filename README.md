# SEO Chrome Extension

This application is an extension that extracts main heading from different sites active tab and display them in the extension

The extension can be cloned and extended further if one needs initial setup of such an extension

## Getting Started

- Install `yarn` and `mvm` globally

To ensure you are using the node version used while creating the project run

```
nvm use
```

Install the packages by running

```
yarn install
```

To run the app as an extension. Build the app by running

```
yarn build
```

Then load the extension in your extensions
Visit

```
chrome://extensions/
```

Toggle the `Developer Mode` to enable loading the extension

Now load the `build` folder as an extension by clicking on `load unpacked` and selecting the build directory

To run the extension as a normal application run

```
yarn start
```

## Technologies & packages used in setting up the project

- React (CRA)
- Typescript
- Craco
