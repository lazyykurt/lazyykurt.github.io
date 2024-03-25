
---
title: quick start
author: Kurt
date: 2019-08-08 11:33:00 +0800
categories: [JavaScript, Typescript]
pin: true
math: true
mermaid: true
---
# Quick Start
first introduction and develop environment setting
[https://b23.tv/Ow8BKgJ](https://b23.tv/Ow8BKgJ)
## 什么是TS
### 介绍
JavaScript more and more important in webapp
![image.png](https://cdn.nlark.com/yuque/0/2024/png/22787689/1710827018715-523ea62d-9be9-4dc1-a9d7-9d8496b515f5.png#averageHue=%238c8d98&clientId=ub31ce663-3868-4&from=paste&height=145&id=u1c797549&originHeight=709&originWidth=1342&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=275791&status=done&style=none&taskId=uac0c43f0-3654-4217-9190-5cdad54235c&title=&width=273.66668701171875)
JavaScript is so weird
![image.png](https://cdn.nlark.com/yuque/0/2024/png/22787689/1710826960910-b004a992-d48d-4ef0-827b-8b85c54aa556.png#averageHue=%23f9faf8&clientId=ub31ce663-3868-4&from=paste&height=150&id=n484q&originHeight=337&originWidth=669&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=95894&status=done&style=none&taskId=ud09def89-0eb3-443d-b68d-09be63fbf50&title=&width=297)
We need fix the JavaScript made it better. So Typescript is created

1. 更严格的语法
2. 编译运行之前，对他进行错误检查，静态检查
### 简单使用
Let's have a brief experience with typescript in [ts_playground](https://www.typescriptlang.org/play) 
you will see if we type like this
successfully run in js

![image.png](https://cdn.nlark.com/yuque/0/2024/png/22787689/1710827846014-621424d9-162e-4006-a3d6-4ebea6c28f5d.png#averageHue=%23fefefd&clientId=ub31ce663-3868-4&from=paste&height=123&id=EJnTa&originHeight=264&originWidth=603&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=111627&status=done&style=none&taskId=u21f7fb59-cbc5-4943-892a-f47fea3e61f&title=&width=280.16668701171875)
doesn't working in ts

![image.png](https://cdn.nlark.com/yuque/0/2024/png/22787689/1710827852253-2209dd78-03f5-4ffc-b1c9-d59a23119c02.png#averageHue=%23dde2e3&clientId=ub31ce663-3868-4&from=paste&height=51&id=Yuty1&originHeight=60&originWidth=407&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=30753&status=done&style=none&taskId=u785a18a1-c3f1-4567-a71e-af6121d4c27&title=&width=347.3333435058594)
## 安装
[https://www.typescriptlang.org/download](https://www.typescriptlang.org/download)
推荐通过 dependency manager 下载 ts，全局安装

1. 下载最新的 [node.js](https://nodejs.org/en/download/current)
2. 安装 ts

`npm install -g typescript`

3. vscode

下载 [vscode](https://code.visualstudio.com/)，并搜索安装tslint插件

4. compile 你的ts文件

`tsc -w`

## [配置](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
[https://www.typescriptlang.org/tsconfig](https://www.typescriptlang.org/tsconfig)

1. set up _tsconfig.json_ file
- `tsc --init`
2. compile automatically
- `tsc -w`
3. _tsconfig.json_ common options
- `"include": ["src"]` compile ts file that your select folder
- `"exclude": ["src/**.test.ts", "node_module"]` uncompile ts file
- `"outDir": "./dist"` output compile file
- `"noImpliciAny" = true` not allow use any type




