# Web-Content für die "Hallo Cordova!"-App

This repository contains some web content (two HTML files and one image)
in folder [docs/](docs), which is to be used for building a mobile app
for Android (and maybe also iOS). 

----
## Steps to build the app

**Prerequisites:** 
[Apache Cordova](https://cordova.apache.org/) must be installed.


Create Cordova project:

    cordova create HalloCordova de.mide.hallocordova "Hallo Cordova"

A project structure should be created. Go to folder `www/` of this folder structure
and delete the default content in it. After this you copy the files from folder
[docs/](docs) in this repository into the `www/` folder.
Then the following commands have to be entered to build the app for
Android:

    cordova platforms add android
    cordova build

The build command should print out a message telling at which path the created installation file 
(APK file for Android) can be found.

<br>

----
## Preview of web content

The web content in this repository can be previewed at [this URL](https://mdecker-mobilecomputing.github.io/HTML_HalloCordova/index.html).

<br>

----
## License

See the [LICENSE file](LICENSE.md) for license rights and limitations (BSD 3-Clause License)
for the files in this repository.
