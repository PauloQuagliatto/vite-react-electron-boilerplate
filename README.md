## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.

### `npm run electron:start`

Runs the electron in development mode which uses the localhost connection.

### `npm run build`

**SHOULD ALWAYS RUN THIS BEFORE THE NEXT SCRIPTS**<br />

Builds the app for production to the `dist` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

### `npm run make:win`

Builds the electron with the bundled React in `dist` folder outputing it to the `build` folder. <br />

Inside lies an executable to install your app to Windows machines.

### `npm run make:linux`

Builds the electron with the bundled React in `dist` folder outputing it to the `build` folder. <br />

Inside lies executables to install your app to Linux machines.

### `npm run make:mac`

Builds the electron with the bundled React in `dist` folder outputing it to the `build` folder. <br />

Inside lies an executable to install your app to MACOSX machines.