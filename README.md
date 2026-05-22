<div align="center">

# 📝 Article Optimizer

**AI 驱动的文档优化工具 | AI-Powered Document Optimizer**

[![Deploy to GitHub Pages](https://github.com/hexiongjiu/article-optimizer/actions/workflows/pages.yml/badge.svg)](https://github.com/hexiongjiu/article-optimizer/actions/workflows/pages.yml)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/demo-live-green.svg)](https://hexiongjiu.github.io/article-optimizer/)

[🇨🇳 中文](#-中文说明) · [🇺🇸 English](#-english)

</div>

---

## 🇨🇳 中文说明

### 这是什么？

Article Optimizer 是一个纯前端的 AI 文档优化工具，上传 Word 文档后，可以逐段调用 DeepSeek AI 进行文字润色，同时完美保留原文档的格式（标题、加粗、表格等），支持差异对比预览，确认后再替换。

### ✨ 功能特性

- 📄 **上传 DOCX** — 基于 mammoth.js 解析，保留标题、列表、表格等格式
- ✨ **段落级 AI 优化** — 悬停任意段落，点击「AI优化此段」即可润色
- 🔍 **差异高亮预览** — 绿色新增、红色删除，改动一目了然
- ✅ **确认替换** — 满意才替换，不满意直接取消
- 🔎 **全文检测** — 一键扫描所有段落，发现表达不当之处并高亮标记
- 💾 **导出 DOCX** — 优化完成后一键导出新的 Word 文档
- 🔑 **隐私安全** — API Key 存储在浏览器本地，不上传任何服务器

### 🚀 在线使用

👉 **[https://hexiongjiu.github.io/article-optimizer/](https://hexiongjiu.github.io/article-optimizer/)**

打开即用，无需安装。

### 🔧 API 配置

本工具使用 [DeepSeek API](https://platform.deepseek.com/) 提供AI能力：

1. 前往 [platform.deepseek.com](https://platform.deepseek.com/) 注册账号
2. 创建 API Key（以 `sk-` 开头）
3. 在页面左上角输入框填入 Key 即可

> API Key 仅保存在你的浏览器 localStorage 中，不会被发送到任何第三方服务器。

### 🛠️ 技术栈

| 功能 | 技术 |
|------|------|
| DOCX 解析 | [mammoth.js](https://github.com/mwilliamson/mammoth.js) |
| 差异对比 | [jsdiff](https://github.com/kpdecker/jsdiff) |
| DOCX 导出 | [html-docx-js](https://github.com/evidenceprime/html-docx-js) + [FileSaver.js](https://github.com/nickelc/FileSaver.js) |
| AI 能力 | [DeepSeek API](https://platform.deepseek.com/) (deepseek-v4-flash) |
| 部署 | GitHub Pages |

### 💻 本地运行

无需构建工具，直接打开即可：

```bash
# 克隆仓库
git clone https://github.com/hexiongjiu/article-optimizer.git
cd article-optimizer

# 方式一：直接用浏览器打开 index.html

# 方式二：本地服务器（推荐，避免跨域问题）
npx serve .
# 或
python -m http.server 8080
```

### 📸 截图

> 📌 截图待补充 — 将使用截图放在 `docs/screenshot.png`

### 🤝 贡献

欢迎提交 Issue 和 Pull Request！

### 📄 许可证

[MIT License](LICENSE) © 2026 hexiongjiu

---

## 🇺🇸 English

### What is this?

Article Optimizer is a browser-based AI document polishing tool. Upload a Word (.docx) file, hover over any paragraph, and let DeepSeek AI rewrite it — all while preserving the original formatting (headings, bold, tables, etc.). Review the diff, confirm, and export.

### ✨ Features

- 📄 **Upload DOCX** — Parsed via mammoth.js with formatting intact
- ✨ **Paragraph-level AI polish** — Hover and click "AI Optimize" to refine any paragraph
- 🔍 **Diff preview** — Green = added, Red = removed; see changes at a glance
- ✅ **Confirm before apply** — Replace only if you're satisfied; cancel otherwise
- 🔎 **Full-text scan** — Detect expression issues across all paragraphs with one click
- 💾 **Export DOCX** — Download the optimized document as a new .docx file
- 🔑 **Privacy-first** — API Key stays in your browser's localStorage, never sent to any server

### 🚀 Live Demo

👉 **[https://hexiongjiu.github.io/article-optimizer/](https://hexiongjiu.github.io/article-optimizer/)**

No installation needed.

### 🔧 API Setup

This tool uses the [DeepSeek API](https://platform.deepseek.com/):

1. Sign up at [platform.deepseek.com](https://platform.deepseek.com/)
2. Create an API Key (starts with `sk-`)
3. Paste it into the input field at the top-left of the page

> Your API Key is stored only in your browser's localStorage and is never sent to any third-party server.

### 🛠️ Tech Stack

| Feature | Technology |
|---------|------------|
| DOCX Parsing | [mammoth.js](https://github.com/mwilliamson/mammoth.js) |
| Diff View | [jsdiff](https://github.com/kpdecker/jsdiff) |
| DOCX Export | [html-docx-js](https://github.com/evidenceprime/html-docx-js) + [FileSaver.js](https://github.com/nickelc/FileSaver.js) |
| AI Engine | [DeepSeek API](https://platform.deepseek.com/) (deepseek-v4-flash) |
| Hosting | GitHub Pages |

### 💻 Run Locally

No build tools required:

```bash
# Clone the repo
git clone https://github.com/hexiongjiu/article-optimizer.git
cd article-optimizer

# Option 1: Just open index.html in your browser

# Option 2: Local server (recommended to avoid CORS issues)
npx serve .
# or
python -m http.server 8080
```

### 📸 Screenshots

> 📌 Screenshots coming soon — place them in `docs/screenshot.png`

### 🤝 Contributing

Issues and Pull Requests are welcome!

### 📄 License

[MIT License](LICENSE) © 2026 hexiongjiu
