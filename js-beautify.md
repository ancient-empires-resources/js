# Node.js package installation

To convert a compressed JavaScript file into a beautified, readable format, you have to install the **[js-beautify](https://www.npmjs.com/package/js-beautify)** package.

## Install Node.js packages

The dependencies are stored in `package.json` file. Hence you can install all dependencies by typing:
```
$ npm i --save-dev
```

## Using `js-beautify`
```
$ nodejs node_modules/js-beautify/js/bin/js-beautify.js <option-flags> file_to_read.js > file_to_write.js
```
Replace `file_to_read.js` and `file_to_write.js` to whatever files you want to read from and write to.

To see a list of option flags available, type:
```
$ nodejs node_modules/js-beautify/js/bin/js-beautify.js --help
```
