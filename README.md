# vue-template

由 [https://github.com/vuejs/vue-cli](https://github.com/vuejs/vue-cli) 下的 [webpack](https://github.com/vuejs-templates/webpack) 模板改编而成，更加符合自己VUE开发的脚手架。

## 修改的地方

安装了 less less-loader 在 vue 模板里

    $npm install --save-dev less less-loader

<hr/>

build/webpack.prod.conf.js 下的 `extract` 属性都改为 `false`

<hr/>

config/index.js 下的 `build` 的属性 `assetsPublicPath` 改为 `'./'` ，执行 `npm run build` 以后 `html` 文件引用的 `css`和`js` 文件是相对路径，可以在 `file://` 下运行

## 使用方法

    # install vue-template
    npm install vue-template

    # install dependencies
    cd vue-template && npm install

    # serve with hot reload at localhost:8080
    npm run dev

    # build for production with minification
    npm run build

