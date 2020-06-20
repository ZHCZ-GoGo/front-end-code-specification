# 前端 Vue 工程化目录

``` text
--env                   # 存放环境和生产环境配置           @1.env
--node_modules          # 项目依赖
--public                # 静态文件夹
--readme-img            # 存放readme.md文件图片应用
--src                   # 项目源码目录
   |--assets                 # 存放一些项目内置的静态文件   @2.assets
   |--components             # 组件库                   @3.components
   |    |--common               # 存放公共组件
   |    |--[module]             # 存放单独模块的组件
   |--consts                 # 存放静态变量              @4.consts
   |--layout                 # 存放页面模板              @5.layout
   |--libs                   # 存放npm上没有的项目依赖库   @6.libs
   |--mock                   # 模拟数据                 @7.mock
   |--plugins                # 存放插件                 @8.plugins
   |--router                 # 存放路由信息              @9.router
   |--services               # 存放服务层                @10.services
   |--store                  # vuex状态管理             @11.store
   |--styles                 # 存放样式                 @12.styles
   |--utils                  # 存放http等常用工具        @13.utils
   |--views                  # 视图页面                 @14.views
--App.vue               # 入口组件
--main.js               # 项目入口文件
--.browserslistrc       # 指定项目的目标浏览器的范围
--.env.development      # 开发环境变量
--.eslintrc.js          # 配置代码 eslint 规则
--.gitignore            # 配置 git 忽略
--..prettierignore      # prettierrcl 格式化忽略文件
--.prettierrc           # 配置 prettierrcl 代码格式化
--babel.config.js       # 配置 babel 
--package.json          # 项目详细依赖
--README.md             # readme 文件
--vue.config.js         # vue 配置文件
```
