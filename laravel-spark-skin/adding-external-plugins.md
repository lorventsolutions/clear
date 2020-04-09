# Adding External Plugins

## Adding External Plugins from Clear

To use plugins used in clear follow the below steps.

we are going with `select2` plugin which is already added to spark skin but we explain the steps here so you can follow it for other plugins aswell.

### Install Plugins

first copy `select2` and `select2BootstrapTheme` packages from clear package.json and paste into spark package.json

Run `yarn install` which will copy those packages into `node_modules` folder

Check if the packages are downloaded to `node_modules` directory

### Copying assets to public

* In `webpack.mix.js` use `mix.copy` to copy the plugins you needed to `public` directory.

  First copy the vendor direcory path in the `paths` object

```javascript
var paths = {
    'select2': vendors + 'select2/dist/',
    'select2BootstrapTheme': vendors + 'select2-bootstrap-theme/dist/'
};
```

* you can copy the path and the `mix.copy` from clear's `gulpfile.js`

```javascript
mix.copy(paths.select2 + 'css/select2.min.css', destVendors + 'select2/css');
```

Also copy the necessary css files to `resources/assets/css` directory and js files to `resources/assets/js/pages`directory.

* then run `npm run dev` to copy the plugin to the `public/vendors` directoy.

## Usage of Plugins

Use the links, HTML, CSS and js from clear HTML version in your view to get the desired plugin or widget.

