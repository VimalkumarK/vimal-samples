# Preiview UIExt Application

An UIExt application to show preview the documents in PDFTron plugin or browser default plugin fo MFiles.

## Getting Started

The application js files are implemented in ES6 standard. The build process converts the ES6 standard files into ES5 standard.


### Installing

Install all the node modules to setup the environment.

```
npm install
```

### PDFTron - Minification

Minify the PDFtron plugin separately using the gulp task

```
gulp Build_Pdftron
```

### Build

Build the application using the gulp task without PDFTron minification process

```
gulp Build
```

Build the application and minify the PDFTon library with the gulp task

```
gulp Build:FullApp
```

## Deployment

Once the build process is done, the application is converted to zip file and it will be saved in dest folder.

## Authors

* **Vimalkumar K** - *Initial work*.
