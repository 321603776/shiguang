

Based on the project structure and code map provided, I can see this is a Progressive Web App (PWA) focused on time-based content. Let me write a comprehensive README.md file:

```markdown
# 时光 (Shiguang)

一个基于时间线的渐进式Web应用。

## 项目简介

时光是一个专注于时间线展示的Web应用，采用现代PWA架构设计，支持离线访问和原生应用般的用户体验。

## 主要功能

- 📅 **时间线展示** - 以时间线的形式展示内容
- ⏰ **时间标记** - 通过圆形按钮进行时间交互
- 📱 **PWA支持** - 可安装到主屏幕，离线访问
- 💧 **水印功能** - 保护内容版权

## 技术特点

- 渐进式Web应用 (PWA)
- Service Worker 缓存策略
- 响应式设计
- 离线访问支持

## 快速开始

### 环境要求

- 现代浏览器（Chrome、Firefox、Edge等）
- 本地服务器（用于PWA功能测试）

### 安装部署

1. 克隆项目到本地：
```bash
git clone https://gitee.com/dlin321603776/shiguang.git
```

2. 使用本地服务器运行：
```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx http-server -p 8000
```

3. 在浏览器中访问：`http://localhost:8000`

### PWA安装

- 在支持的浏览器中访问网站
- 点击"添加到主屏幕"按钮
- 即可像原生应用一样使用

## 项目结构

```
shiguang/
├── index.html      # 主页面
├── manifest.json    # PWA配置文件
├── sw.js           # Service Worker
├── LICENSE         # 许可证
└── .gitignore      # Git忽略配置
```

## 许可证

本项目采用 MIT 许可证开源。
```

This README provides a comprehensive overview of the project based on its structure. The project appears to be a timeline-focused PWA with time-based interactions and offline capabilities.