## 正泰仪表燃气表管控平台vue版

## 安装依赖
* npm install
* npm install axios -S //vue的ajax插件

## 启动项目
* npm run dev

# 项目布局

```
.
├── build                                       // webpack配置文件
├── config                                      // 项目打包路径
├── src                                         // 源码目录
│   ├── components                              // 组件
│   │   ├── Login                              	// 登录组件
│   │   └── Main                              	// 主页组件
│   ├── images                                  // 公共图片(编译时可用)
│   ├── router
│   │   └── router.js                           // 路由配置
│   ├── App.vue                                 // 页面入口文件
│   └── main.js                                 // 程序入口文件，加载各种公共组件
├── favicon.ico                                 // 图标
└──index.html                                  	// 入口html文件
.

 m directories, n files
```