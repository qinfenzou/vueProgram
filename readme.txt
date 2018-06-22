src 文件结构

├── App.vue                         // APP入口文件
├── api                             // 接口调用工具文件夹
│   └── index.js                    // 接口调用工具
├── components                      // 组件文件夹，目前为空
├── config                          // 项目配置文件夹
│   └── index.js                    // 项目配置文件
├── frame                           // 子路由文件夹
│   └── frame.vue                   // 默认子路由文件
├── main.js                         // 项目配置文件
├── page                                // 我们的页面组件文件夹
│   ├── content.vue             // 准备些 cnodejs 的内容页面
│   └── index.vue                   // 准备些 cnodejs 的列表页面
├── router                          // 路由配置文件夹
│   └── index.js                    // 路由配置文件
├── style                           // scss 样式存放目录
│   ├── base                        // 基础样式存放目录
│   │   ├── _base.scss          // 基础样式文件
│   │   ├── _color.scss     // 项目颜色配置变量文件
│   │   ├── _mixin.scss     // scss 混入文件
│   │   └── _reset.scss     // 浏览器初始化文件
│   ├── scss                        // 页面样式文件夹
│   │   ├── _content.scss       // 内容页面样式文件
│   │   └── _index.scss     // 列表样式文件
│   └── style.scss              // 主样式文件
└── utils                           // 常用工具文件夹
    └── index.js                    // 常用工具文件

初识化 结构文件


├── README.md                       // 项目说明文档
├── node_modules                    // 项目依赖包文件夹
├── build                           // 编译配置文件，一般不用管
│   ├── build.js
│   ├── check-versions.js
│   ├── dev-client.js
│   ├── dev-server.js
│   ├── utils.js
│   ├── vue-loader.conf.js
│   ├── webpack.base.conf.js
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
├── config                          // 项目基本设置文件夹
│   ├── dev.env.js              // 开发配置文件
│   ├── index.js                    // 配置主文件
│   └── prod.env.js             // 编译配置文件
├── index.html                      // 项目入口文件
├── package-lock.json           // npm5 新增文件，优化性能
├── package.json                    // 项目依赖包配置文件
├── src                             // 我们的项目的源码编写文件
│   ├── App.vue                 // APP入口文件
│   ├── assets                      // 初始项目资源目录，回头删掉
│   │   └── logo.png
│   ├── components              // 组件目录
│   │   └── Hello.vue           // 测试组件，回头删除
│   ├── main.js                 // 主配置文件
│   └── router                      // 路由配置文件夹
│       └── index.js            // 路由配置文件
└── static                          // 资源放置目录