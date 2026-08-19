# 服装设计笔记 · Fashion Design Notes

一个参考 Claude Docs 阅读体验的纯网页知识库。

## 当前能力

- 左侧笔记导航、顶部搜索、正文与右侧本页目录
- Markdown 风格标题、引用、列表、标签
- 新建、编辑、删除笔记
- Markdown 导入与导出
- 通过 GitHub Contents API 读取和提交 `data/notes.json`

## 使用

直接打开 `index.html` 即可预览。点击“连接 GitHub”，填写用户名、仓库名和具有仓库内容读写权限的 token。token 只保存在当前页面内存，不会写入仓库。

生产环境建议下一步接入 GitHub OAuth 或服务端代理，避免让用户直接输入长期 token。
