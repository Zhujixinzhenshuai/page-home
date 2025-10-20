
# 风流の导航 v4 (PWA + 动画)

说明：
- PWA 支持（manifest.json + service-worker.js），支持离线缓存基础页面
- 暗色模式：星空流星动画；亮色模式：樱花树与飘落花瓣
- 搜索栏位于网站标题下方，按钮切换分组（Home/邮箱/开发工具等）
- BGM：内置 WebAudio 合成（樱花清风风格），页面会尝试自动播放；若被浏览器阻止，用户首次交互后将恢复
- 点击卡片会播放电音提示
- Telegram 按钮位于右下角，点击会提示跳转到 t.me/mrfengliu

部署：将文件上传到 GitHub 仓库根目录并在 Cloudflare Pages 连接，输出目录 `/`，无需构建命令
