# vue-datav大屏数据可视化 




## 项目运行

 ```sh
 # 安装依赖
1. npm install  ||  yarn install

# 直接运行项目
2.npm run dev  ||  yarn dev  || yarn start

# http://localhost:3000/

```



## 原作者

- [github地址：https://github.com/babybrotherzb](https://github.com/babybrotherzb)
- [博客地址：https://blog.csdn.net/weixin_43648947](https://blog.csdn.net/weixin_43648947)
- [掘金地址：https://juejin.im/user/5d90295cf265da5b5c08f32d/activities](https://juejin.im/user/5d90295cf265da5b5c08f32d/activities)

## 项目启动可能遇到的问题

1.nodejs版本过高
降级 Node.js 版本：

首先，尝试将 Node.js 版本降级到较稳定的版本。您可以使用 nvm（Node Version Manager）来管理 Node.js 版本。安装 nvm 后，您可以执行以下命令来切换到较低版本的 Node.js

```sh
nvm install 14
nvm use 14
```
2.清npm缓存
```sh
npm cache clean --force
```
3.重新安装依赖
```sh
rm -rf node_modules
npm install
```

4.缺少@vue/cli-service 模块,安装 @vue/cli-service：
在项目根目录下执行以下命令安装 @vue/cli-service 模块：
```sh
npm install @vue/cli-service --save-dev
```
全局安装 @vue/cli（可选）：
如果您还没有全局安装 @vue/cli，建议您全局安装以确保 @vue/cli-service 可以正常工作。您可以执行以下命令进行全局安装：
```sh
npm install -g @vue/cli
```

## 启动项目
```sh
npm run dev 
```



