# ShopHub / FreshCo H5

电商 H5 前端静态文件（Vue CLI 构建的 SPA）。

## 目录结构

```
├── index.html      # 入口 HTML
├── css/            # 样式文件（38个）
├── js/             # JS 打包文件（43个，含路由分包）
├── img/            # 站点图片
└── fonts/          # 图标字体
```

## 说明

- 这是前端静态壳子，商品数据等通过 API 动态加载，后期需对接后端接口。
- 路由使用 hash 模式（`#/index`），可直接部署到 GitHub Pages / 任意静态托管。
- 主入口：`index.html` → `js/vendors~app.*.js` + `js/app.*.js`。
