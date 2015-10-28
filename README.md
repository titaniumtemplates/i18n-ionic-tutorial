# i18n Ionic Tutorial
This project is the source code of a tutorial on how to internationalize and Localize your Ionic application by making use of Angular Translate, Angular Dynamic Locale and Cordova Globalization Plugin.

## Where to find the tutorial
The complete tutorial is published on [Medium](https://medium.com/titanium-templates/display-song-title-and-cover-by-utilizing-shoutcast-s-meta-data-fb00011cb086).

## Dependecies, Run and Build
### Install NodeJS dependencies

Run `npm install` to install all needed dependencies

### Install Javascript dependencies

Run `bower install` to install all needed dependencies.

### Run the app
Use `grunt serve -l` to run the app in browser and watch for changes in code

or

use `grunt serve` to just run the app for a browser preview

or

use `grunt serve --lab` to run the app in a browser on two platforms at the same time.

### Add a platform

```bash
$ grunt platform:add:<platform>
```

Supported Cordova platforms:

```bash
$ grunt platform:add:ios
$ grunt platform:add:android
```

### Build the app

```bash
$ grunt build
```

### Emulate the app on simulator
iOS:

```bash
$ grunt emulate:ios
```

Android:

```bash
$ grunt emulate:android
```

For more information, see [Ionic Framework Generator's instructions](https://github.com/diegonetto/generator-ionic).

### Angular localization files

Localization files can be found in [Angular's directory](https://code.angularjs.org/1.3.6/i18n/). Any downloaded locale should be included in the `app/locales` folder.

### Plugins installation

Use the following commands and install the plugin required by the app:
```bash
$ cordova plugin add com.keosu.cordova.stream
```
or
```bash
$ cordova plugin add https://github.com/keosuofficial/cordova-audio-stream-plugin.git
```

#### Used Cordova plugins
In case that the required Cordova plugins are not installed while installing NodeJS dependencies, Cordova's command mentioned previously can be used to install the following plugins:

* **cordova-plugin-globalization** - It obtains information and performs operations specific to the user's locale and timezone.

## Further information and help
A production ready [i18n Ionic](http://codecanyon.net/item/i18n-ionic-full-application/12337533?ref=skounis) application which demonstrates and extends everything that is described in this tutorial is available in [Codecanyon](http://codecanyon.net/item/i18n-ionic-full-application/12337533?ref=skounis). [i18n Ionic](http://codecanyon.net/item/i18n-ionic-full-application/12337533?ref=skounis) is ideal as a point of reference to give your applications the internationalized boost they need.

## Third Party Licences
* [Apache License](http://www.apache.org/licenses/)
* [MIT License](https://opensource.org/licenses/MIT)
