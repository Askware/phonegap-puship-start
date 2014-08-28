<<<<<<< HEAD
# PhoneGap Build with Push Enabled Starter Application

> A example application to get started with PhoneGap Build and push notifications on Android and iOS.
=======
# Hello World PhoneGap Application

> A Hello World application built with PhoneGap
>>>>>>> upstream/master

## Usage

### Desktop

In your browser, open the file:

    /www/index.html

### PhoneGap CLI

This repository is automatically downloaded by [phonegap-cli][phonegap-cli-url]
when you create a new application.

### PhoneGap Build

Create a new app with the following repository:

    https://github.com/Puship/phonegap-puship-start.git

### Nitrous.io

First [setup nitrous.io][nitrous-url] to use this project.

Then run the following commands in the nitrous.io terminal:

    $ cd ~/workspace/phonegap-start
    $ npm install -g phonegap
    $ phonegap remote build android

The last command requires an Adobe ID and will build your app on PhoneGap Build.

## Contributors

### Updating the Application

The application is based on the [Phonegap phonegap-start][phonegap-start] app.

#### 1. Update the Source

    cp phonegap-start/www www/

__Do not replace `www/config.xml`.__

__Do not replace `www/img/logo.png`.__

#### 2. Update index.html

Replace `<h1>PhoneGap</h1>` with `<h1>Puship Example</h1>`.

#### 3. Update PhoneGap Version

    <preference name="phonegap-version" value="x.x.x" />

#### 4. Commit

    $ git commit -am "Version x.x.x"

#### 5. Tag

    $ git tag x.x.x

<<<<<<< HEAD
[phonegap-start]: http://github.com/phonegap/phonegap-start
=======
[phonegap-cli-url]: http://github.com/phonegap/phonegap-cli
[cordova-app]: http://github.com/apache/cordova-app-hello-world
[nitrous-url]: https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-3cc067e(https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=phonegap%2Fphonegap-start&file_to_open=README.md
>>>>>>> upstream/master

