# vue-template

> vue开发模板


## 框架工具
    vue-cli
    vue2.5
    vue-router
    vuex
    axios
    express
    mysql

## 后台目录
	server
	index.js   入口文件
	
	
## 目录结构
  <pre>
  ├── build           
  ├── config               	
  ├── static         		    // 静态文件存放
  ├── index.html         		// 项目入口文件
  ├── package.json       		// 项目配置文件
  ├── server     		        // 后端接口目录
  │   └── index.js          // 后端入口文件
  ├── src                		// 生产目录
  │   ├── api               // 后端接口配置
  │   ├── assets         		// css js 和图片资源
  │   ├── components     		// 各种Vue组件
  │   │   └── Hello.vue     // 
  │   ├── utils     		    // 公用处理方法
  │   │   └── ajax.js       //   
  │   ├── router            // 路由配置
  │   ├── vuex          		// vuex状态管理器
  │   ├── App.vue        		// 项目中全局Vue
  │   ├── main.js        		// Webpack 预编译入口
  │   └── routers.js        // vue路由配置文件
  </pre>

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

