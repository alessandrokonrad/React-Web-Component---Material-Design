### Web Component Material Design (Table)

```
Install React-CLI:

	npm install -g create-react-app

Create project:

	create-react-app table-component

Install dependencies:

	npm install @material-ui/core
	npm install @material-ui/icons

	(for Web Component)
	npm install react-custom-element webcomponents.js

Register App:
	
	create App.js and make your table-component with Material-UI
	import App.js in index.js and register your component via:
		
		registerCustomElement(App, "table-comp")

	go into public and add your component to index.html


```

```
Reference to: https://github.com/bspaulding/react-custom-element
```


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
