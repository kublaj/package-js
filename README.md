# Package.js

**This project is no longer maintained!**

JavaScript Package Manager and Build Tools for Web App Framework development.

## Installation:

You need install node.js and npm first;See http://nodejs.org/ and http://npmjs.org/ ;
```bash
cd package-js
sudo npm install -g
```

## Getting started:

* Copy ```package-js/src/Package``` directory to your static js directory. For example:```your-project/statics/jslibs/Package```;
* Create your own library,example:```your-project/statics/jslibs/XLib```;
* Create ```XLib/_nsconf_.js```;
* Create ```XLib/init.js```;
* Link ```Package/_xproxy_.html``` to ```XLib/_xproxy_.html``` if you want to load tpl.html or other assets cross domains;
* Create other packages;

For examples,please see package files under `src/Test` directory ,and test page here: http://jexcheng.github.io/package-js/tests/test.html .

For complete references,please see [Package.js Specification](http://jexcheng.github.io/package-js/) .
