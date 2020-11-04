# Node.js package installation

To convert a compressed JavaScript file into a pretty, readable format, you have to install the **[pretty-js](https://www.npmjs.com/package/pretty-js)** package.

## Install Node.js packages

The dependencies are stored in `package.json` file. Hence you can install all dependencies by typing:
```
$ npm i --save-dev
```

## Using `pretty-js`

```
$ node_modules/pretty-js/bin/pretty-js.js file_to_read.js > file_to_write.js
```
Replace `file_to_read.js` and `file_to_write.js` to whatever files you want to read from and write to.
