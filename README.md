# VUE JAVASCRIPT TEMPLATE FOR IONIC
Hi! This template the true is that is for me and for my personal projects, but if someone want to use be free. The true is that is a very easy template.
Probably the only thing that can grow with the time is this README.md for add all the "things" or tricks with IONIC and VUE or some links of interest.

## Pre-requisites
- You need to install Node.js with NPM
- You need to install ionic
- [Only for Android] Installing Android Studio

## First run
You want to check that all is OK? It is easy, run this command in your shell:
``` bash
ionic serve
```
With this command you will have a localhost web app to have a preview of your changes before to build for a mobile platform.
# Android build
Hi again! This is a mini-guide to deploy your VUE app to your Android device.

First of all you need to build the app to production (dist folder).
``` bash
ionic build
```
Next you need to add the platform for android, in this guide we are going to use capacitator, but you can find in the documentation how to change to cordova.
``` bash
ionic cap add android
ionic cap open android
```
With this, you are going to look that ionic is going to use capacitator to create an android project.
Now, is moment to copy de build or to sync the project. You can use one of the next comandos:

``` bash
ionic cap copy
ionic cap sync
```

The first is usend when you only want to copy the data. The second is when you have add new changes of the configuration. For example, if you add a new npm package.