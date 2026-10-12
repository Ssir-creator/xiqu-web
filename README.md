# 戏境

传统演艺多模态体验网站，包含智能导赏、沉浸展演、跨媒介叙事与虚实互动。

## 在线发布

推送到 `main` 后，GitHub Actions 自动发布到 GitHub Pages。
默认站点地址为 `https://ssir-creator.github.io/xiqu-web/`，以成功部署输出的地址为准。

首次发布如提示 Pages 尚未启用，在仓库 Settings → Pages 中选择 **GitHub Actions**，然后重新运行 `Publish Xijing website` 工作流。

后续更新同一仓库的 `index.html`，推送到 `main` 即可更新固定网址。部署完成后刷新网页；如果看到缓存内容，可用 Ctrl+F5 强制刷新。

## 离线使用

下载 `index.html` 后用 Chrome 或 Edge 打开。所有图片、语音、样式与脚本均内嵌，无需安装依赖。
摄像头和麦克风由用户主动授权；功能介绍和按钮、触控体验无需联网。

## 本地预览

在仓库目录运行 `python3 -m http.server 8080`，在浏览器访问本地服务器。线上部署使用 HTTPS，有利于浏览器的摄像头与麦克风权限支持。
