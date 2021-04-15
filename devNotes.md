# 项目初始化依赖安装

- 初始化项目

```
npm init
```
- 基本依赖安装

```
npm install express

npm install typescript ts-node @types/node @types/express --save-dev
```
- ts配置文件

```
npx tsc --init
```

# 项目依赖信息

|  包名   | 简介  |  细节 |
|  ----  | ----  |  ----  |
| ts-node  | 用于直接运行TypeScript文件 | TypeScript execution and REPL for node.js, with source map support. Works with typescript@>=2.7.|
| @types/node  | 这个包包含Node.js (http://nodejs.org/)的类型定义。 |Global values: Buffer, __dirname, __filename, clearImmediate, clearInterval, clearTimeout, console, exports, global, module, process, queueMicrotask, require, setImmediate, setInterval, setTimeout |
| @types/express  | 这个包包含Express (http://expressjs.com)的类型定义。 | Dependencies: @types/body-parser, @types/serve-static, @types/express-serve-static-core, @types/qs|

