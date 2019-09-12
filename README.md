# admin

> 基于vue框搭建的后台管理平台，包含登录、注册、找回密码页面以及首页内容等

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## vue项目使用sass

1、安装sass相关插件 
npm install node-sass --save-dev
npm install sass-loader --save-dev

2、进入webpack.base.config.js配置scss 
rrules: [
     {
        test: /\.scss$/,
        loaders: ["style", "css", "sass"]
      },
      ......
]

3、在vue文件中声明使用
<style lang="scss" rel="stylesheet/scss"></style>

