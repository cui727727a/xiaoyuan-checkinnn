# 校园打卡指南

> 探索校园最美角落，记录青春美好时光

![Campus Check-in Guide](https://img.shields.io/badge/version-3.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-GitHub%20Pages-orange.svg)

## 📖 项目介绍

校园打卡指南是一个面向师生的校园景点推荐平台，收录了校园内各类值得打卡的地点，包括学习场所、风景圣地、运动设施、美食天地、艺术空间等。旨在帮助新生快速熟悉校园环境，让老生发现身边的美好。

### 核心特性

- 🏫 14+ 校园打卡点详细介绍
- 🔍 智能搜索与分类筛选
- ⭐ 点赞、收藏、评分互动系统
- 💬 留言板互动功能
- 📱 完美的移动端适配

## ✨ 功能列表

### 交互与数据
- [x] 关键词搜索打卡点名称和描述
- [x] 标签分类筛选（学习/风景/运动/美食/艺术/生活）
- [x] 多维度排序（默认/名称/点赞/评分）
- [x] 点赞功能，数据持久化存储
- [x] 收藏功能，状态保存到 localStorage
- [x] 五星评分系统

### 视觉与动效
- [x] 页面加载动画
- [x] 滚动进度条指示器
- [x] 卡片滚动渐入效果（IntersectionObserver）
- [x] 卡片悬浮交互（放大、变色、上浮）
- [x] 点赞脉冲动画
- [x] 图片 Lightbox 画廊
- [x] 图片懒加载优化

### 用户体验
- [x] 返回顶部按钮
- [x] 分享功能（系统分享 API + 复制链接）
- [x] Toast 消息提示
- [x] 留言板系统（数据持久化）
- [x] 响应式布局，完美适配手机/平板/桌面

### 附加页面
- [x] 关于站长简历页面
- [x] 页脚导航入口

## 🖼️ AI 生成图片说明

本项目中的校园图片来自真实校园摄影，如需使用 AI 生成与主题相关的图片，可以使用以下提示词：

### 校园风景类
```
A beautiful university campus in spring with cherry blossoms along the main avenue, soft morning light, peaceful atmosphere, photorealistic style, 4K quality
（春日校园樱花大道，柔和晨光，和谐氛围，写实风格）
```

### 校园建筑类
```
Modern university library with large glass windows, sunlight streaming through, cozy reading corners, minimalist design, warm interior lighting, photorealistic
（现代大学图书馆，大玻璃窗，阳光透入，舒适阅读角，极简设计）
```

### 校园生活类
```
University cafeteria with diverse food options, warm lighting, students chatting, cozy atmosphere, photorealistic style
（大学食堂，多样美食选择，温馨灯光，学生交流）
```

## 📂 项目结构

```
xiaoyuan-checkinnn/
├── index.html          # 主页面（打卡点展示、搜索、筛选、留言板）
├── about.html          # 关于站长简历页面
├── images/             # 校园图片资源
│   ├── library.jpg
│   ├── cherry_blossom.jpg
│   ├── lake_pavilion.jpg
│   ├── gymnasium.jpg
│   ├── teaching_building.jpg
│   ├── canteen.jpg
│   ├── sports_field.jpg
│   └── art_center.jpg
└── README.md           # 项目说明文档
```

## 🚀 使用说明

### 本地运行

1. 克隆项目到本地
```bash
git clone https://github.com/cui727727a/xiaoyuan-checkinnn.git
```

2. 进入项目目录
```bash
cd xiaoyuan-checkinnn
```

3. 直接在浏览器中打开 `index.html` 即可访问

### 在线访问

项目已部署至 GitHub Pages，可直接访问：
**https://cui727727a.github.io/xiaoyuan-checkinnn/**

### 数据存储

- 所有用户数据（点赞、收藏、评分、留言）存储在浏览器 localStorage 中
- 刷新页面后数据不会丢失
- 清除浏览器缓存会导致数据重置

## 🎓 关于站长

| 信息 | 内容 |
|------|------|
| 姓名 | 张小园 |
| 专业 | 计算机科学与技术 |
| 年级 | 大三 |
| 技能 | 前端开发、UI/UX设计、Vue.js、React |
| 邮箱 | xiaoyuan@example.edu.cn |

了解更多 → [关于站长](about.html)

## 📝 提交清单

### 第1次提交 - 基础版本
- [x] HTML 结构搭建
- [x] CSS 基础样式
- [x] 8 个校园打卡点展示
- [x] 卡片悬浮效果

### 第2次提交 - 交互扩展
- [x] 搜索/筛选/排序功能
- [x] 滚动渐入动效
- [x] 悬浮交互增强
- [x] 点赞/收藏功能（localStorage）
- [x] Lightbox 画廊

### 第3次提交 - 最终完善
- [x] 「关于站长」简历页面
- [x] 内容扩充至 14 个打卡点
- [x] 新增分类体系（7大类别）
- [x] 留言板/评论系统
- [x] 五星评分功能
- [x] 图片懒加载
- [x] 分享功能
- [x] 返回顶部按钮
- [x] 页面进度条
- [x] 加载动画
- [x] 完善的移动端适配
- [x] README.md 文档

## 🛠️ 技术栈

- **HTML5** - 语义化标签
- **CSS3** - Flexbox、Grid、动画、响应式设计
- **JavaScript ES6+** - 原生 JavaScript，无框架依赖
- **localStorage** - 客户端数据持久化
- **IntersectionObserver API** - 滚动视口检测
- **Web Share API** - 系统分享功能

## 📄 许可证

本项目仅供学习交流使用，如需转载或引用请注明出处。

---

**Made with ❤️ by 张小园**
**© 2024 校园打卡指南 | 记录青春美好时光**