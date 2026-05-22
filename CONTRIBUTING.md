# Contributing / 贡献指南

感谢你愿意为 Article Optimizer 贡献代码！Thanks for considering contributing!

## 如何贡献 / How to Contribute

### 🐛 报告 Bug / Report Bugs

通过 [GitHub Issues](https://github.com/hexiongjiu/article-optimizer/issues) 提交,请尽量包含:

- 复现步骤 / Steps to reproduce
- 期望行为 vs 实际行为 / Expected vs actual behavior
- 浏览器版本 / Browser version
- 截图或控制台报错 / Screenshots or console errors

### ✨ 提交 Pull Request

1. Fork 本仓库 / Fork the repo
2. 新建分支 / Create a branch: `git checkout -b feature/your-feature`
3. 提交修改 / Commit: `git commit -m "feat: add xxx"`
4. 推送 / Push: `git push origin feature/your-feature`
5. 发起 Pull Request

### 📝 代码风格 / Code Style

- 保持单文件结构 (`index.html`),除非有充分理由拆分
- HTML/CSS/JS 使用 4 空格缩进
- 中文注释 OK,英文注释也 OK,但请保持一致

### 🧪 本地测试 / Local Testing

```bash
python -m http.server 8080
# 然后访问 http://localhost:8080
```

准备一个测试用的 .docx 文档(包含标题、表格、列表等元素),确保:

- 上传后格式正确显示
- AI 优化按钮可以正常调用
- 差异预览渲染正常
- 导出的 DOCX 可以在 Word 中打开

## License

提交 PR 即表示你同意你的贡献以 [MIT License](LICENSE) 发布。

By submitting a PR, you agree that your contribution will be licensed under the MIT License.
