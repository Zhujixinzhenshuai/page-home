# 风流の导航 — 最终版 🌗

包含：
- 暗色流星背景（Canvas 动画）
- 亮色樱花飘落背景（Canvas 动画）
- 中英切换、主题切换、BGM（可开/关）、电音点击音效
- 鼠标粒子尾迹、卡片居中显示（紧凑尺寸）
- 联系方式：Telegram @mrfengliu

部署：
- 将整个文件夹上传到 GitHub 仓库根目录（index.html, links.json）
- 在 Cloudflare Pages 新建项目，连接该仓库，输出目录 `/`，无需构建命令
- 可在仓库根目录放入 `bg-light.jpg` 来替换亮色模式的默认绘制背景（示例中绘制为向左飘落的樱花）

修改：
- 编辑 `links.json` 添加/删除/修改链接
- 图标：在 `links.json` 的 `icon` 字段中填写完整图片 URL（或 data URL），例如你现有的未开发站点已使用内嵌 SVG data URLs

版权与注意：
- 页面中使用的音效为 WebAudio 合成（无版权问题）
