# 雨中祈愿地图工坊

[打开地图工坊](https://ctrlcctrlvisthebest.github.io/BeforeTheRainStopMap/)

独立的地图编辑与单人试玩网站，支持 40 张关卡模板、多份本机草稿、完整组件编辑、JSON 导入导出及真实 3D 试玩。无需登录。

原游戏：[雨中祈愿](https://ctrlcctrlvisthebest.github.io/BeforeTheRainStop/)。本项目使用独立草稿存储，不读取或覆盖原游戏的进度、房间和排行榜。

## 发布

本仓库保存可直接运行的单文件发布包，GitHub Pages 使用 **Deploy from a branch → main → /(root)**。`index.html` 内含样式、图标、40 张地图和压缩后的游戏代码；需要支持 DecompressionStream 的现代浏览器。

开发源码单独保存在 BeforeTheRainStopMap 源码项目及其备份压缩包。更新时在源码项目运行 `npm run check` 与 `npm run build:pages`，然后用生成的 `dist-pages/index.html` 替换此处的 `index.html`。请勿用源码项目的开发入口覆盖发布文件。

地图只保存在当前浏览器，建议通过导出 JSON 备份和分享。试玩为单人模式；导入地图不会自动加入原游戏的正式关卡。

来源：2026-09-21 的 BeforeTheRainStop 本地地图编辑器、地图与游戏引擎快照。
