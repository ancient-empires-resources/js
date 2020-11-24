# JavaScript source code for Ancient Empires 1 and 2 (Android versions)

## Ancient Empires 1

The JS source codes are stored in the "**AE1**" directory. They are separated into the tree structure by the original developer, so you can read them directly to understand the internal logics of the game.

## Ancient Empires 2

The JS source codes are stored in the **AE2** directory. They are compressed into one single file called **all.min.js**. Hence you have to convert it to a beautified, readable format. You need to have the NPM module **[js-beautify](https://www.npmjs.com/package/js-beautify)** installed first. You may read the **[js-beautify.md](https://github.com/ancient-empires-resources/js-Android/blob/main/js-beautify.md)** file to find out how to do this. The converted source code is stored in the **[beautified.js](https://github.com/ancient-empires-resources/js-Android/blob/main/AE2/beautified.js)** file.

For your convenience, a Makefile is included in the **AE2** directory. Simply type `make` to have everything done automatically for you. Or you can use it to customize the option flags when generating the beautified JS file.
