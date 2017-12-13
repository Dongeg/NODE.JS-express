# NODE.JS-express

## install

直接安装express脚手架

```
$ npm install express-generator -g
```
在当前目录新建一个myapp 文件夹创建一个express脚手架，前端模板引擎用ejs

```
$ express -e myapp 

  Usage: express [options] [dir]

  Options:

    -h, --help          output usage information
    -V, --version       output the version number
    -e, --ejs           add ejs engine support (defaults to jade)
        --hbs           add handlebars engine support
    -H, --hogan         add hogan.js engine support
    -c, --css <engine>  add stylesheet <engine> support (less|stylus|compass|sass) (defaults to plain css)
        --git           add .gitignore
    -f, --force         force on non-empty directory
```
然后安装所有依赖包：

```
$ cd myapp 
$ npm install
```
启动

```
npm start
```
