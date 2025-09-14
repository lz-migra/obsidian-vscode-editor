<h1 align="center">Obsidian VSCode Editor</h1>

<p align="center">
    <img alt="Release version" src="https://img.shields.io/github/v/release/lz-migra/obsidian-vscode-editor?style=for-the-badge">
    <img alt="Download count" src="https://img.shields.io/github/downloads/lz-migra/obsidian-vscode-editor/total?style=for-the-badge">
    <img alt="License" src="https://img.shields.io/github/license/lz-migra/obsidian-vscode-editor?style=for-the-badge">
</p>

<p align="center">
    <span>An Obsidian plugin to view and edit code files with the VSCode experience, actively maintained with new improvements.</span>
    <br/>
    <a href="/README.md">English</a>
    ·
    <a href="/README_es.md">Español</a>
</p>

---

## 🚀 Project status

This is a maintained fork of the original project [`sunxvming/obsidian-vscode-editor`](https://github.com/sunxvming/obsidian-vscode-editor), which hasn’t received updates for over 3 years.  
Here you will find an **active and improved version**, with fixes and new features:

- 📝 **Revamped context menu** — fully rewritten, now independent from Monaco Editor and better integrated with Obsidian.  
- 🌍 **Spanish support** — complete localization for Spanish-speaking users.  
- 📋 **Paste fixes** — consistent behavior for both `Ctrl+V` and the context menu.  
- ⚡ **Compatibility** — improved support for recent Obsidian versions and more editor stability.  

---

## 📖 About the plugin

By default, Obsidian doesn’t support editing many types of code files.  
This plugin solves the issue by integrating the core of VSCode’s editor (based on [Monaco Editor](https://microsoft.github.io/monaco-editor/)) directly into Obsidian.  

It allows viewing and editing of multiple programming languages:  
`C`, `C++`, `C#`, `CSS`, `Go`, `HTML`, `Java`, `JavaScript`, `JSON`, `Python`, `Ruby`, `Rust`, `Shell`, `XML`, `YAML`, `INI`, and more.  

No need to open an external editor anymore: everything happens without leaving Obsidian.  

---

## ✨ Key features

- Works **without relying on external services**: usable even offline.  
- Full code editing for multiple languages, just like in VSCode.  
- Customizable colors, light/dark themes, and font size (`Ctrl + mouse wheel`).  
- Code block editing inside Markdown documents.  
- Quick preview of internal links to code files.  
- Automatic line wrapping (`Alt+Z`).  
- Option to show/hide line numbers, indentation guides, and minimap.  
- Familiar keyboard shortcuts for VSCode users.  
- Buttons and commands to create new code files.  

---

## ⌨️ Supported shortcuts

Most are consistent with VSCode. Examples:

| Category     | Shortcut               | Action                   |
|--------------|------------------------|--------------------------|
| Ctrl         | `ctrl + c`             | Copy                     |
|              | `ctrl + x`             | Cut                      |
|              | `ctrl + v`             | Paste                    |
|              | `ctrl + s`             | Save                     |
|              | `ctrl + f`             | Find                     |
|              | `ctrl + h`             | Replace                  |
|              | `ctrl + z`             | Undo                     |
|              | `ctrl + y`             | Redo                     |
|              | `ctrl + /`             | Toggle line comment      |
|              | `ctrl + d`             | Duplicate line           |
|              | `ctrl + [`             | Decrease indentation     |
|              | `ctrl + ]`             | Increase indentation     |
|              | `ctrl + ↑`             | Move line up             |
|              | `ctrl + ↓`             | Move line down           |
| Ctrl+Shift   | `ctrl + shift + k`     | Delete current line      |
|              | `ctrl + shift + [`     | Collapse code block      |
|              | `ctrl + shift + ]`     | Expand code block        |
| Alt          | `alt + z`              | Toggle word wrap         |

---

## 🔧 Installation

### From Obsidian’s community plugins  
🚫 **Not available in the official plugin store yet.**

### Manual installation  
1. Download the latest release from the [Releases](https://github.com/lz-migra/obsidian-vscode-editor/releases/latest) section.  
2. Extract the archive and copy the folder into:
`<your-vault>/.obsidian/plugins/`
3. Open Obsidian and go to **Settings > Community plugins**.  
4. Enable **Community plugins**.  
5. Look for **Obsidian VSCode Editor** in the list below and toggle it on.  

---

## 📬 Contact

For suggestions, bugs, or questions, feel free to open an issue here:  
👉 [GitHub Issues](https://github.com/lz-migra/obsidian-vscode-editor/issues)
