# 服务器部署

本分支为服务器部署文件，需要服务器在 Node.js 环境中运行

将 master 分支中的 `.nuxt`、`static`、`package.json`、`nuxt.config.js` 文件拷贝至服务器

初始化依赖

```
yarn install --production
```

开启服务

```
yarn start
```

> 注：服务器端口配置在 package.json 中的 `config.nuxt` 中