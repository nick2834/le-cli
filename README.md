# le-cli
前端工程化：创建项目，自动开发生成脚手架、webpack配置文件；开发完成后构建项目，进行压缩合并，并行生产环境和开发环境。


## 安装
`npm install le-cli -g`

## 使用
直接cd 到自己的文件目录（需要自己创建一个文件夹， 程序在这里不会给你创建文件夹的）：
没有动图， 参考下面的命令行执行流程：
`mkdir test` --> `cd test` --> `le -s`                      
![01](./static/img/01.png)


## 已添加的项目构建
- 多页jquery程序+handlebars模板引擎
- 基于TypeScript+webpack多页打包的前台程序
- react+redux+antd+jsonServerMockjs
- react+redux+antd+next服务端渲染
- koa程序+MySql连接数据库
- koa程序+基于TypeScript+MySql
- 基于TypeScript+react+saga项目

## 版本升级说明
- 0.0.10
    - 添加了 基于TypeScript+react+saga项目
    - TypeScript-multipage 项目添加了 live-server 启动项目
    - TypeScript-multipage 添加了handlebars-loader

- 0.0.8                                                                 
    添加基于next 的react 服务端渲染项目模板。 内置redux+antd， 作为前台程序使用。
