# 开发者个人简历网站 (Developer Portfolio)

基于 Vue 3 + TypeScript + Vite 构建的现代化个人简历网站(。

## ✨ 特性

- **现代设计**：深色主题 + 玻璃态 (Glassmorphism) 风格
- **交互体验**：平滑滚动、进入动画、响应式交互
- **主题切换**：内置深色/浅色模式切换
- **项目展示**：支持简略/详细两种展示模式，突出技术栈
- **完全响应式**：完美适配桌面、平板和移动设备
- **高性能**：基于 Vite 构建，极为轻量

## 🛠️ 技术栈

- **前端框架**: Vue 3 (Composition API)
- **开发语言**: TypeScript
- **构建工具**: Vite
- **样式**: CSS3 Variables + Flexbox/Grid
- **字体**: Inter (Google Fonts)

## 🚀 快速开始

### 1. 安装依赖

```bash
npm install
```

### 2. 本地开发

```bash
npm run dev
```

### 3. 构建生产版本

```bash
npm run build
```

## 📝 配置个人信息

所有数据均在 `src/App.vue` 中配置，您可以轻松修改：

- **个人信息**: 修改 `personalInfo` 对象
- **项目经历**: 修改 `projects` 数组
- **技能列表**: 修改 `skillCategories` 数组

## 📦 部署

本项目是一个纯静态站点，可以轻松部署到任何静态托管服务：

- **GitHub Pages**
- **Cloudflare Pages**
- **Vercel**
- **Netlify**

只需要将 `dist` 目录上传即可。
