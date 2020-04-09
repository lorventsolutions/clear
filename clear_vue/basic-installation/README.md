# Basic Installation

The Clear package comes with compiled assets. To view the project place the package contents in the root directory of your server or point a virtual host to the project directory and every thing should be working out of the box.

**Note:** To setup a virtual host follow this [guide](https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-14-04-lts).

And once you are ready to customize the project follow the below steps.

Follow below steps before you start customizing clear VueJS version.

**Note :** 

Make sure you have [nodejs](https://nodejs.org) installed in your system with minimum version `6.10.0`,

you can check installed version by running `node -v` command in terminal.

If you are having older version, please install latest version from [nodejs.org](http://nodejs.org/)

### 1\) Install Dependencies

Run the below command to get all the dependencies from package.json

`npm install`

### 2\) Install Assets

Run the below command to get the plugins from bower.json

`bower install`

Note 1: If you logged in as `root` user you may need to run `bower install --allow-root`

Note2: We have removed bower in 4.2 version , so if you are using 4.2 or above version please ignore this step.

### 3\) File Compilation

Run the following command to compile all the files.

`npm run dev`

now your vuejs version is ready.

## Development tips

You need to run `npm run dev` everytime you want your changes to be applied but you can follow below tips to save time

### File Compilation with watchers

Run the following command to set watchers for files so that they compile as soon as you save any changes

`npm run watch`

### serve with hot reload at localhost:8080

The following command will create a local server at localhost:8080 with hot-module-replacement enabled, to reflect your changes without effecting the state of your application.

`npm run hot`

### File compilation for production

Run the following command to compile all files with minification for production.

`npm run production`

**Note**: when using "dev" "watch" or "production" make sure that your application is in the root directory of the server.

If your files are being server from a sub folder in the server like `localhost/vue` then consider using the laravel-mix `mix.setResourceRoot('/');` option.

if you are serving the files like `localhost/vue` then set `mix.setResourceRoot('/vue/');`

Eventhough you can run `npm install` we suggest you to run `yarn install` since the package contains `yarn.lock` file which lets you get the exact version of packages that we have used.

