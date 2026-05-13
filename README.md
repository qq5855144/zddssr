# 工地记工

> 轻量级工地考勤记工工具，帮助施工团队快速记录和管理工时。

## ✨ 功能特性

- **记工管理**：灵活记录工人每日出勤、工时、工种
- **数据概览**：直观查看项目进度与人力投入
- **响应式界面**：适配 PC、平板、手机端，工地现场也能轻松操作

## 🛠 技术栈

- **前端框架**：React（SPA 单页应用，基于 Vite 构建）
- **语言**：TypeScript / JavaScript
- **样式方案**：CSS（独立样式文件）
- **部署**：静态文件托管，支持任意 HTTP 服务器

## 📁 项目结构

```
zddssr/
├── assets/          # 构建产物（JS、CSS 等静态资源）
├── index.html       # 入口 HTML 文件
└── README.md
```

## 🚀 本地运行

1. 将项目文件部署到任意 HTTP 服务器（如 Nginx、Apache、Live Server 等）
2. 确保 `index.html` 作为入口，`assets/` 目录与 HTML 同位
3. 浏览器打开对应地址即可使用

## 📦 构建与开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 生成生产环境构建
npm run build
```

## 📄 License

MIT

---

如有问题或建议，欢迎提 Issue。
