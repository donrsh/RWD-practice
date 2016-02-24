# This is an RWD practice. 

##Tools

I use `breakpoint` ( via `node-sass`) and `autoprefixer` ( via `postcss`) here.

`Webpack` is used to bundle files. 

## Structures of Directory and Files

All files for developing are in `/dev`. `/dev/styles` contains all the scss files, and `/dev/include_styles.js` is used to include all the scss files to be loaded via Webpack.

There's no javascript files is included in the main page. 

## Enter Developing
```
npm install
webpack --watch --color  --progress
```
 