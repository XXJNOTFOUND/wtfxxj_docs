# WTFXXJ 玩家文档

这是基于 VitePress 的 Minecraft 服务器玩家文档。

## 本地开发

```bash
npm install
npm run docs:dev
```

## 构建

```bash
npm run docs:build
```

构建完成后，静态文件会生成到：

```txt
docs/.vitepress/dist
```

将该目录部署到 Nginx、宝塔、1Panel 或其他静态站点服务即可。

## 主要目录

```txt
docs/
├─ index.md              # 首页
├─ guide/                # 新手教程
├─ systems/              # 玩法系统
├─ plugins/              # 插件教程
├─ main/                 # 加入、权限、支持等说明
└─ .vitepress/config.mts # 站点配置
```

## 维护建议

- 每个功能单独写一篇页面。
- 指令一定要配中文说明和示例。
- 价格、冷却、权限上限等服务器配置要单独标注。
- 不要提交 `node_modules/`、`docs/.vitepress/dist/`、`docs/.vitepress/cache/`。
