# 牛逼导航

基于 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 构建的常用网站与效率工具导航站。

## 本地构建

在仓库根目录执行：

```sh
hugo --source exampleSite --themesDir themes --destination public --baseURL https://nbdh.top/
```

生成的静态文件位于 `exampleSite/public/`。

## 部署

站点静态文件由 Cloudflare Pages 托管，自定义域为 `nbdh.top`。
