<h1 align="center">Obsidian VSCode Editor</h1>

<p align="center">
    <img alt="Release version" src="https://img.shields.io/github/v/release/lz-migra/obsidian-vscode-editor?style=for-the-badge">
    <img alt="Download count" src="https://img.shields.io/github/downloads/lz-migra/obsidian-vscode-editor/total?style=for-the-badge">
    <img alt="License" src="https://img.shields.io/github/license/lz-migra/obsidian-vscode-editor?style=for-the-badge">
</p>

<p align="center">
    <span>一个 Obsidian 插件，可以用 VSCode 的体验来查看和编辑代码文件，持续维护并带来新功能。</span>
    <br/>
    <a href="/README.md">English</a>
    ·
    <a href="/README_es.md">Español</a>
    ·
    <a href="/README_cn.md">中文</a>
</p>

---

## 🚀 项目状态

这是原始项目 [`sunxvming/obsidian-vscode-editor`](https://github.com/sunxvming/obsidian-vscode-editor) 的一个维护分支，该项目已超过 3 年未更新。  
在这里你会找到一个**活跃且改进的版本**，包含修复和新功能：

- 📝 **全新上下文菜单** — 完全重写，不再依赖 Monaco Editor，并与 Obsidian 更好地集成。  
- 🌍 **西班牙语支持** — 为西语用户提供完整的本地化。  
- 📋 **粘贴修复** — `Ctrl+V` 和右键菜单粘贴行为一致。  
- ⚡ **兼容性** — 对新版 Obsidian 提供更好支持，编辑器更稳定。  

---

## 📖 插件介绍

Obsidian 默认不支持编辑许多代码文件类型。  
该插件通过将 VSCode 编辑器核心（基于 [Monaco Editor](https://microsoft.github.io/monaco-editor/)）直接集成到 Obsidian 来解决这个问题。  

它支持查看和编辑多种编程语言：  
`C`, `C++`, `C#`, `CSS`, `Go`, `HTML`, `Java`, `JavaScript`, `JSON`, `Python`, `Ruby`, `Rust`, `Shell`, `XML`, `YAML`, `INI` 等。  

无需再打开外部编辑器：一切都在 Obsidian 内完成。  

---

## ✨ 主要特性

- **无需依赖外部服务**：即使离线也可使用。  
- 支持多种语言的完整代码编辑，体验如同 VSCode。  
- 可自定义颜色、明/暗主题和字体大小（`Ctrl + 鼠标滚轮`）。  
- 编辑 Markdown 文档中的代码块。  
- 快速预览代码文件的内部链接。  
- 自动换行（`Alt+Z`）。  
- 可显示/隐藏行号、缩进线和迷你地图。  
- 为 VSCode 用户提供熟悉的快捷键。  
- 提供按钮和命令创建新代码文件。  

---

## ⌨️ 支持的快捷键

大部分与 VSCode 保持一致。示例：

| 分类         | 快捷键                  | 动作                     |
|--------------|-------------------------|--------------------------|
| Ctrl         | `ctrl + c`              | 复制                     |
|              | `ctrl + x`              | 剪切                     |
|              | `ctrl + v`              | 粘贴                     |
|              | `ctrl + s`              | 保存                     |
|              | `ctrl + f`              | 查找                     |
|              | `ctrl + h`              | 替换                     |
|              | `ctrl + z`              | 撤销                     |
|              | `ctrl + y`              | 重做                     |
|              | `ctrl + /`              | 注释/取消注释一行        |
|              | `ctrl + d`              | 复制一行                 |
|              | `ctrl + [`              | 减少缩进                 |
|              | `ctrl + ]`              | 增加缩进                 |
|              | `ctrl + ↑`              | 向上移动一行             |
|              | `ctrl + ↓`              | 向下移动一行             |
| Ctrl+Shift   | `ctrl + shift + k`      | 删除当前行               |
|              | `ctrl + shift + [`      | 折叠代码块               |
|              | `ctrl + shift + ]`      | 展开代码块               |
| Alt          | `alt + z`               | 自动换行                 |

---

## 🔧 安装

### 从 Obsidian 社区插件安装  
🚫 **尚未在官方插件商店上架。**

### 手动安装  
1. 从 [Releases](https://github.com/lz-migra/obsidian-vscode-editor/releases/latest) 下载最新版本。  
2. 解压文件并将文件夹复制到：
`<你的-vault>/.obsidian/plugins/`
3. 打开 Obsidian，进入 **设置 > 社区插件**。  
4. 启用 **社区插件**。  
5. 在下方列表中找到 **Obsidian VSCode Editor** 并开启。  

---

## 📬 联系方式

任何建议、问题或 Bug，都可以在这里提交 issue：  
👉 [GitHub Issues](https://github.com/lz-migra/obsidian-vscode-editor/issues)
