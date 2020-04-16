# React with NPM bootstrap

## [Optional] Uninstall 'create-react-app' to ensure that npx always uses the latest version.
npm uninstall -g create-react-app

## Installing 'create-react-app' globally
npm install -g create-react-app (prefix sudo, in unix env)

## Creating a React app from CLI with npm as package manager (default is yarn) 
npx create-react-app react-w-npm --use-npm

cd react-w-npm

### Adding a template
#### TypeScript
npm install --save typescript @types/node @types/react @types/react-dom @types/jest

### Build the application
npm run build

### Start the application
npm start

Opens [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Running tests
npm test
See the section about [running tests](https://create-react-app.dev/docs/running-tests) for more information.