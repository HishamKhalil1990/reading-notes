# EJS
### EJS stands for Embedded JavaScript templatesis which is used as a simple templating language that let us generate HTML markup with plain JavaScript.
### as express, EJS is a npm module. so to use it, EJS should be installed first using `npm install ejs` . to use EJS, html file is made with EJS extension as `index.ejs` . after that the file can be rendered on browser using EJS render method. however, the html tag can be put as an argument in the render method without a need to construct an `index.ejs` file. 
### to manipulate the `index.ejs` -template html- file, first the places are intended to be manipulated must be determined and replaced with `<%= var %>` where `var` is the decleared variable name in the server.js file. second use assign the needed value in the variable `var` in server.js file. 
### EJS supports arrays and looping, so when sending an array with an object that hold two variables it can loop over them. also it supports if/else statments