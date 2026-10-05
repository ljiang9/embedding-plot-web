# embedding-plot-web

**单 HTML 文件、零依赖、双击即用** 的向量二维可视化小工具。粘贴 `label, x, y` 向量点或只写文本（内置 FNV-1a 哈希映射到二维），Canvas 散点 + 纯 JS k-means 聚类着色 + 悬停详情。

## 快速开始

直接用浏览器打开 `index.html` 即可。

## 无 API Key 如何运行

完全离线。所有功能（哈希向量化、k-means、Canvas 渲染）都在浏览器里完成，不调用任何网络服务，不需要任何 Key。

## 运行 Node 断言

```bash
node test/assert.mjs
# ✓ embedding-plot-web 全部 Node 断言通过
```

## License

MIT © ljiang9
