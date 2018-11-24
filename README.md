# Web-Content für die "Hallo Cordova!"-App

This repositories contains some web content (two HTML files and one image)
in folder [docs/](docs), which are to be used for building a mobile App
for Android (and maybe also iOS). For this these files are to be copied
into the folder `www/` of a [Cordova](https://cordova.apache.org/) project
(but delete the default content in folder `www/` before doing that).
The file `docs/index.html` from this repository has to be file
`www/index.html` after the copying.
After this the Android app (APK file) can be built by the following two
commands:

    cordova platforms add android
    cordova build

<br>

The web content can be previewed at [this URL](https://mdecker-mobilecomputing.github.io/HTML_HalloCordova/index.html).


----
# License

See the [LICENSE file](LICENSE.md) for license rights and limitations (BSD 3-Clause License)
for the files in this repository.
