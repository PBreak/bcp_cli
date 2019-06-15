# esbutob_cli

> A Vue CLI for esbu_to_b add vux,vuex,axios,JSSDK(later)

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
|-- undefined  author:wangjing（2019-6-25）
    |-- .babelrc
    |-- .editorconfig
    |-- .gitignore //git忽略的文件
    |-- .postcssrc.js
    |-- index.html 
    |-- package-lock.json
    |-- package.json
    |-- README.md
    |-- build
    |   |-- build.js  //npm run build执行的相关webpack配置文件
    |   |-- check-versions.js
    |   |-- logo.png
    |   |-- utils.js
    |   |-- vue-loader.conf.js
    |   |-- webpack.base.conf.js //webpack打包配置文件
    |   |-- webpack.dev.conf.js
    |   |-- webpack.prod.conf.js
    |-- config
    |   |-- dev.env.js
    |   |-- index.js //配置相关如：host和proxy等
    |   |-- prod.env.js
    |-- src
    |   |-- App.vue  //vue单页面入口
    |   |-- main.js //编译执行的js
    |   |-- assets  //请将相关的较小的图片资源放在相关路径上
    |   |   |-- logo.png
    |   |-- components
    |   |-- pages //路由页面
    |   |   |-- HelloWorld.vue
    |   |-- router //路由表配置
    |   |   |-- index.js
    |   |-- service //公共的js
    |   |   |-- getData.js
    |   |-- store  //vuex使用时的变量
    |       |-- store.js
    |-- static
        |-- .gitkeep
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
