# Clear 1.7 installation

**If you are using version 1.7 of clear, Run the below commands**

## 1\) Install Dependencies

Run the below command to get all the dependencies from package.json

`yarn install`

## 2\) Install Assets

Run the below command to get the plugins from bower.json

`bower install`

## 3\) serve with hot reload at localhost:8000

The following command will launch a browser window with localhost:8000 with hot module replacement. To change the default port , edit the port in `config.index.js`

`npm run dev`

## 4\) build for production with minification

The following command will build the project into the `dist` folder. Built files are meant to be served over an HTTP server.

Opening index.html over file:// won't work.

```text
`npm run build`
```

