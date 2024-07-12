# Typescript React Storybook Starter

A template repository for quickly getting started with creating
React component libraries.

- Uses Vite for example builds + Storybook
- Uses Jest for tests
- Includes sample Storybook setup

## Getting Started

Once you've cloned the repo, run the following commands to
force all packages to the latest versions before installing:

```sh
npx npm-check-updates -u
npm install
```

Now you can open up a dev server with:

```sh
npm start
```

Have fun coding!

## Deploying Storybook to Github Pages

Uncomment the lines in `.github/workflows/deploy.yaml` to deploy
a Storybook instance to Github Pages. You will also need to enable
Github Pages for your repository in the Settings tab.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

**Note**: This runs the App files in example/ as the dev environment.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Runs tests in Jest

### `npm run build`

Builds the example for production to the `example/build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run storybook`

Starts up a Storybook server on [http://localhost:6006](http://localhost:6006)

### `npm run build-storybook`

Builds a static web app version of Storybook to `/storybook-static`

