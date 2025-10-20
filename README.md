# 我的未来导航站 v2 🌗

一个带有 **暗色 / 亮色切换** 的未来风导航网站。  
亮色模式为「冰蓝银白」科技感背景，可自定义图片。

---

## 🚀 部署步骤

1. 将本项目上传到你的 GitHub 仓库。
2. 登录 [Cloudflare Pages](https://pages.cloudflare.com/)，点击「创建项目」。
3. 选择连接你的 GitHub 仓库。
4. 构建设置：
   - 构建命令：*(留空)*
   - 输出目录：`/`
5. 部署后，在「自定义域名」中绑定你的域名（例如：`nav.yourdomain.com`）。

---

## 🎨 修改亮色模式背景图片

如果你想换成自己的背景图片：
1. 将图片放在项目根目录。
2. 命名为：`bg-light.jpg`
3. 打开 `index.html`，找到注释：
   ```css
   --bg-light: url('bg-light.jpg');
   ```
4. 保存并提交即可。

---

## 🧊 技术说明

- HTML + Tailwind + JSON 数据源
- 自动 favicon 抓取
- 响应式布局
- 支持搜索 / 分组
- 主题切换保存至 localStorage
