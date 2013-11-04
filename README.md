angular-phonegap-seed
=====================

## Disclaimer

This repo is no longer under active development. Instead, there's now a shiny new Yeoman generator. Check it out! https://github.com/thewildpendulum/gaps

## About

A barebones seed project for getting started with [PhoneGap](http://phonegap.com/) and [AngularJS](http://angularjs.org/) (with routing!)

Built using [PhoneGap-CLI](https://github.com/phonegap/phonegap-cli):
* Cordova: 3.1.0
* Angular: 1.2.0-rc.3

This project also includes a service for wrapping calls to Cordova APIs as presented by Brian Ford in [this awesome blog post](http://briantford.com/blog/angular-phonegap.html).

## Install

You just need to get these files into YourPhoneGapProject/www/, so either `git clone <url> www` or download the zip and move 'em in there.

A Yeoman generator is on the way.

Directory structure:

Note: As of Angular 1.2, the routing service has been removed from core. It is now included explicitly in `/lib`.

```
/angular-phonegap-seed
    /css
        - index.css
    /img
        - logo.png
    /js
        - app.js
        - controllers.js
        - index.js
        - services.js
    /lib
        - angular-1.2.0-rc3.js
        - angular-1.2.0-rc3.min.js
        - angular-route.js
        - angular-route.min.js
    /partials
        - main.html
        - view.html
    /res
        // app and cordova images
    /spec
        // tests
```

Build and run your project, and you should be good to go.

## MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
