# 🎀 Send Me To A Ciallo Website

> Ciallo～ (∠・ω< )⌒★ 一键传送至柚子社的二次元世界！

## 📡 在线体验

🔗 **[ciallo.yumfish.cn](https://ciallo.yumfish.cn/)**

---

## ✨ 功能

- 🎯 **一键 Ciallo** — 点击中央大按钮，随机跳转至柚子社/Ciallo/綾(宁宁)宁相关网页
- 🔊 **音效播放** — 点击时播放 Ciallo 音效 (res/audio.mp3)
- 🌸 **樱花飘落** — 满屏飘落花瓣，萌系满满
- ✨ **气泡特效** — 星星爱心从底部升起
- 💬 **随机整活文案** — 每次点击显示不同的猛男专属提示
- 📮 **链接投稿** — 收集网友推荐链接（跳转 Bilibili）
- ⏳ **预加载遮罩** — 等音频加载完再显示页面，体验更好

## 🚀 部署

本项目为纯静态页面，可直接部署到 **Cloudflare Pages**：

1. Fork / Clone 本仓库
2. 在 Cloudflare Pages 中连接仓库
3. 构建配置无需设置（纯 HTML）
4. 部署完成！

你也可以使用任何静态托管服务，如 GitHub Pages、Vercel、Netlify 等。

## 🛠️ 自定义

### 添加/修改网址

编辑 `index.html` 中的 `urlList` 数组：

```js
const urlList = [
    'https://www.yuzu-soft.com/',           // 柚子社官网
    'https://zh.moegirl.org.cn/柚子社',       // 萌娘百科
    // ... 在这里继续添加 ...
];
```

### 替换音频

将你的 Ciallo 音效文件替换 `res/audio.mp3` 即可。没有音频文件也不影响使用。

## 📁 项目结构

```
SendMeToCialloWebsite/
├── index.html          # 主页面（HTML + CSS + JS 全内嵌）
├── res/
│   └── audio.mp3       # 音效文件（可选）
├── LICENSE             # MIT 许可证
└── README.md           # 本文件
```
