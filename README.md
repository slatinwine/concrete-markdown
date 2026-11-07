# 清水混凝土 Markdown

仿 macOS 窗口的所见即所得（WYSIWYG）Markdown 编辑器，清水混凝土墙面风格，零依赖单文件运行，草稿自动保存到本地。

## ✨ 功能特性

- 所见即所得编辑：直接排版，无需分屏预览；内置零依赖的 Markdown ⇄ HTML 双向转换核心
- 工具栏齐全：粗体 / 斜体 / 删除线 / 行内代码、H1–H3、引用、有序 / 无序列表、任务列表、链接、图片（支持本地图片）、分隔线
- 快捷键：`⌘/Ctrl+B` 加粗、`⌘/Ctrl+I` 斜体、`⌘/Ctrl+K` 插入链接、`⌘/Ctrl+S` 导出
- 文件导入：点击导入或把 `.md` 文件直接拖进窗口；导出：下载 `.md` / 独立 `.html`，或一键复制 Markdown / HTML
- 自动保存：草稿与文档名实时写入 localStorage，刷新不丢；标题栏实时显示字数
- 仿 macOS 窗口：红绿灯按钮、可编辑文档名、状态栏提示保存状态

## 🚀 使用方法

纯静态单文件页面，无需构建、无需联网。直接用浏览器打开 `index.html` 即可编辑。

## 🛠️ 技术栈

- 纯 HTML / CSS / JavaScript（单文件，零依赖）
- `contenteditable` 富文本编辑、`localStorage` 持久化、`Blob` 文件下载

## 📁 目录结构

- `index.html` — 窗口界面、Markdown 转换核心与编辑器逻辑
