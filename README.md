# create-desktop-react-app
Implementation of CRA + NW.js.
This is a simple implementation of [create-react-app](https://create-react-app.dev/) with [Typescript template](https://github.com/facebook/create-react-app/tree/main/packages/cra-template-typescript) and packed with [NW.js](https://nwjs.io/)

<img src="https://nwjs.io/img/logo.png" width="150"/>
<img src="https://create-react-app.dev/img/logo.svg" width="150"/>



## DEV
The entry point is the `index.js` file.
You can edit it to add your own code like any other React app.

To start developement you need to install the dependencies:

```sh
npm install
```

Then you can start the development server:

On Windows:
```sh
npm run dev-on-win
```

On Linux:
```sh
npm run dev-on-linux
```

And then you can start develpment!

## BUILD (production executable)
To create a production executable, run:

For Windows:
```sh
npm run build-for-win
```
For Linux:
```sh
npm run build-for-linux
```
For MacOS:
```sh
npm run build-for-mac
```
For all:
```sh
npm run build-for-all
```

This will create a `dist` folder with the executable.
To publish the executable you have to distribute it with all the files included in the executable folder.