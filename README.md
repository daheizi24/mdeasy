# MDEasy - 简洁美观的 Markdown 查看器

![MDEasy Logo](https://img.shields.io/badge/MDEasy-Markdown%20Viewer-blue?style=for-the-badge)

一个现代化、响应式的 Markdown 文件查看器，支持桌面端和移动端，提供优雅的阅读体验。

## ✨ 功能特性

### 🎯 核心功能
- **📁 文件支持**: 支持 `.md`、`.markdown`、`.txt` 格式文件
- **🖱️ 多种输入方式**: 拖拽文件、点击选择文件
- **⚡ 实时渲染**: 基于 marked.js 的高质量 Markdown 渲染
- **🎨 代码高亮**: 使用 highlight.js 支持多种编程语言语法高亮
- **🌓 主题切换**: 支持明暗主题切换，自动保存用户偏好
- **📱 响应式设计**: 完美适配桌面端、平板和手机端

### 🚀 性能优化
- **⚡ 异步加载**: 外部库异步加载，提升首屏渲染速度
- **🔄 多层降级**: 智能降级策略确保在任何环境下都能正常显示
- **📦 预加载优化**: DNS预解析和资源预加载
- **💾 本地存储**: 主题偏好本地持久化

### 📱 移动端优化
- **👆 触摸友好**: 专门的触摸事件处理和反馈
- **📏 适配屏幕**: 响应式布局适配各种屏幕尺寸
- **⚡ 性能优化**: 移动端专门的性能优化策略
- **🎯 触摸目标**: 符合 iOS/Android 设计规范的触摸目标大小

### ⌨️ 快捷键支持
- `Ctrl + O`: 打开文件
- `Ctrl + T`: 切换主题
- `Esc`: 返回主页

## 🛠️ 技术栈

- **前端框架**: 原生 JavaScript (ES6+)
- **Markdown 解析**: [marked.js](https://marked.js.org/)
- **代码高亮**: [highlight.js](https://highlightjs.org/)
- **样式**: 原生 CSS3 (CSS Variables + Flexbox)
- **图标**: 内联 SVG

## 📦 项目结构

```
mdeasy/
├── index.html          # 主应用文件（单文件应用）
└── README.md          # 项目说明文档
```

## 🚀 快速开始

### 方法一：PC端
1.web访问 daheizi24.github.io
2.下载压缩包并解压
### 方法二：安卓
下载安装包即可（打包环节小问题，正在改）

## 📖 使用说明

### 基本使用
1. **打开应用**: 在浏览器中打开 `index.html`
2. **选择文件**: 
   - 点击「选择 Markdown 文件」按钮
   - 或直接拖拽文件到拖拽区域
3. **查看内容**: 文件内容将自动渲染并显示
4. **返回主页**: 点击「返回主页」按钮或按 `Esc` 键

### 主题切换
- 点击右上角的主题切换按钮
- 或使用快捷键 `Ctrl + T`
- 主题偏好会自动保存



## 🔧 浏览器兼容性

| 浏览器 | 版本要求 | 支持状态 |
|--------|----------|----------|
| Chrome | 60+ | ✅ 完全支持 |
| Firefox | 55+ | ✅ 完全支持 |
| Safari | 12+ | ✅ 完全支持 |
| Edge | 79+ | ✅ 完全支持 |
| Mobile Safari | iOS 12+ | ✅ 完全支持 |
| Chrome Mobile | Android 7+ | ✅ 完全支持 |

## 📝 文件限制

- **支持格式**: `.md`, `.markdown`, `.txt`
- **文件大小**: 
  - 桌面端: 最大 10MB
  - 移动端: 最大 5MB
- **编码**: UTF-8 (推荐)

## 🎨 自定义主题

应用使用 CSS Variables 实现主题系统，可以轻松自定义：

```css
:root {
  --primary: #3b82f6;        /* 主色调 */
  --bg-primary: #ffffff;     /* 主背景色 */
  --bg-secondary: #f8fafc;   /* 次背景色 */
  --text-primary: #1e293b;   /* 主文字色 */
  --text-secondary: #64748b; /* 次文字色 */
  --border: #e2e8f0;         /* 边框色 */
}
```

## 🔒 安全性

- **本地处理**: 所有文件处理都在本地进行，不上传到服务器
- **XSS 防护**: 内置 HTML 转义防止 XSS 攻击
- **CSP 兼容**: 兼容内容安全策略
- **无外部依赖**: 除 CDN 资源外无其他外部依赖


## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！


### 提交规范
- `feat`: 新功能
- `fix`: 修复 bug
- `docs`: 文档更新
- `style`: 样式调整
- `refactor`: 代码重构
- `perf`: 性能优化

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 🙏 致谢

- [marked.js](https://marked.js.org/) - Markdown 解析器
- [highlight.js](https://highlightjs.org/) - 代码语法高亮
- [Feather Icons](https://feathericons.com/) - 图标设计灵感


---

**MDEasy** - 让 Markdown 阅读更简单 ✨