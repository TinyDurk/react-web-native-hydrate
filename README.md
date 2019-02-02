# react-web-native-hydrate

本文会持续总结web app和native app统一融合框架的构建。

## 简介
### 目标
构建以react为基础的web+native统一开发框架



### 语言
主开发语言：javascript，typescript全面兼容

原生语言：Objective-C、Java



### 架构设计拓扑图

framework topo:

![](https://github.com/TinyDurk/react-web-native-hydrate/blob/master/topoImgs/framework-topo.png)


### 项目基础依赖库
- react
- react-dom
- react-native
- react-native-web
- react-art


## 项目初始化
### 安装
- install yarn: ```npm i -g yarn```
- update yarn: ```yarn global add yarn```
- global intsall react-native: ```yarn global add react-native```
- install dependencies: ```yarn install```


### 启动命令
- run in ios platform: ```yarn start:ios```
- run in android platform: ```yarn start:android```
- run in web browser platform: ```yarn start:web```


### 单元测试命令
run Unit Test: ```yarn test```


### 代码检查命令
```yarn lint```


## 核心设计
### 入口设计


### 路由设计


### PageLayout设计


### native web差异基础组建设计


### 公共业务组件设计


## 附录
### VSCode Plugin
- auto format your code: prettier-vscode, and set your vscode setting json: &quot;editor.formatOnSave&quot;: true
- use customize editorconfig: EditConfig for VS Code
- tslint: tslint


### 开发时工具依赖库
- @types/jest
- @types/node
- @types/react
- @types/react-dom
- @types/react-native
- @types/react-test-renderer
- metro-react-native-babel-preset
- prettier
- react-app-rewire-webpack-bundle-analyzer
- react-app-rewired
- react-test-renderer
- ts-jest
- tslint
- tslint-config-airbnb
- tslint-config-prettier
- typescript
- react-scripts
- typescript
