# gulp自动构建示例项目

本项目用于快速开始宣传类h5静态页面开发

### Start Coding

```
$ npm install
$ npm run dev
```

### 目录结构

```
|-- gulpfile.js
|-- package.json
|-- html/                             // html folder
    |-- aipl.html
|-- images/                           // image folder
|-- js/                               // js folder
|-- less/                             // less folder
    |-- reset.less                    // common reset css, you can add yours
|-- static/                           // compiled files
    |-- css/
        |-- maps/                     // css maps
        |-- reset.css
        |-- swiper.min.css
    |-- js/
        |-- maps/                     // js maps
        |-- jquery.min.js
        |-- sensorsdata.min.js
        |-- swiper.min.js

```

### 说明

* 将需要的文件在相应目录建立好，开始开发即可
* 预置了jquery3.1.0、swiper4.5.0、神策的js
* 使用的插件可以在gulpfile里查看
* 添加的功能
    * browser-sync
    * source map
    * cleancss/uglify
    * autoprefixer
    * babel（默认配置）
    * notify
* 留下了一个移动端示例页面，可以copy相关设置如meta、path
* **开发完后不要忘记按照目标目录结构更改引用path**
