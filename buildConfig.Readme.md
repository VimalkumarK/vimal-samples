# Configuration

Customize the build process with the configurartion file.

## MFBuild

### LintExclude

Exclude the files/folders from the liniting process.

* JS
* HTML

### Build

Build process for the JavaScript files with ES6.

* src - Array of file/folder path.
* dest - Path to save the converted files.
* babelify - True/False - Flag to do bable conversion from ES6 to ES5.

### Clean

* string - Array of folder path to clean all the exist files.

### IsReleaseBuild

* Boolean - The flag to minify the files or not.

## FilesToCopy

Other files such as icons, css, html and library files to copy to the destination folder without babelify process.

* Array - Files path collection.
