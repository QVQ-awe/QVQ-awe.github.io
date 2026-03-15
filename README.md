# 我的个人网站

一个使用 Bootstrap 5 构建的现代化个人网站，展示个人作品、数据和介绍。

## 🌐 在线预览

访问 [GitHub Pages](https://your-username.github.io/QVQ-awe.github.io/) 查看效果。

## ✨ 功能特性

- **响应式设计** - 支持桌面、平板和手机等多种设备
- **个人主页** - 展示项目作品和成就
- **个人介绍** - 详细的个人信息、技能、工作经历
- **数据展示** - 可视化数据卡片
- **项目详情** - 展示项目信息和亮点
- **毛玻璃效果** - 现代化的卡片设计风格
- **动画效果** - 流畅的悬停和加载动画

## 📁 页面结构

```
├── index.html          # 首页 - 项目展示
├── About.html          # 个人介绍页面
├── data.html           # 数据展示页面
├── Profile.html        # 项目详情页面
├── public/
│   ├── background.css  # 背景样式
│   ├── site.css        # 全局样式
│   ├── beluga.jpg      # 背景/头像图片
│   └── favicon.ico     # 网站图标
└── src/                # Vue 源码目录（可选）
```

## 🚀 快速开始

### 环境要求

- Node.js 16+
- npm 或 yarn

### 安装依赖

```sh
npm install
```

### 开发模式

```sh
npm run dev
```

启动后访问 http://localhost:5173 预览网站。

### 生产构建

```sh
npm run build
```

### 本地预览生产版本

```sh
npm run preview
```

## 🎨 自定义内容

### 修改个人信息

编辑 `About.html` 文件中的以下内容：

- 姓名、职业、联系方式
- 技能专长和进度条
- 工作经历
- 教育背景
- 兴趣爱好

### 修改项目内容

编辑 `index.html` 和 `Profile.html` 文件：

- 项目名称和描述
- 项目图片
- 技术栈信息

### 修改样式

- `public/site.css` - 全局样式、卡片效果、动画
- `public/background.css` - 背景图片样式

### 更换背景图片

将新的图片替换 `public/beluga.jpg`，或修改 CSS 中的背景图片路径。

## 🛠️ 技术栈

- **HTML5** - 语义化结构
- **Bootstrap 5.3** - UI 框架
- **CSS3** - 自定义样式和动画
- **Vite** - 构建工具
- **Vue 3** - 可选的组件化开发

## 📝 待办事项

- [ ] 添加更多动画效果
- [ ] 集成 Vue 组件化开发
- [ ] 添加深色模式切换
- [ ] 添加联系表单
- [ ] 添加博客功能

## 📄 许可证

MIT License

---

**© 2026 我的个人网站。All Rights Reserved.**
