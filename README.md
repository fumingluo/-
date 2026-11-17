# 龙华周六读书会活动页

面向微信群分享的单页活动网站，使用纯 HTML、CSS 和 JavaScript，无外部依赖。

## 本地预览

直接打开 `dist/index.html`，或在 `dist` 目录启动任意静态文件服务器。

## 更新活动信息

页面文案、时间、地点、费用和报名口令均集中在 `dist/index.html`。替换 `dist/assets/` 内的图片时，请保持文件名不变，或同步修改 HTML 中的路径。

## 部署

仓库已包含 Sites 静态托管配置 `.openai/hosting.json`。由于没有依赖和构建步骤，也可以直接部署到腾讯云 EdgeOne Pages、COS、阿里云 OSS 等国内静态托管服务。

仓库还包含 `.github/workflows/pages.yml`。推送到 GitHub 的 `main` 分支后，会自动尝试启用并发布 GitHub Pages。若仓库命名为 `longhua-reading-club`，发布地址通常为 `https://fumingluo.github.io/longhua-reading-club/`。

