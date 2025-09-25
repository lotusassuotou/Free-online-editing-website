# 生活实用工具网 🛠️

一个集合多种实用在线工具的现代化网站，帮助用户提高日常工作和生活效率。专注于提供纯净、无广告的用户体验。

中文 | [English](README_EN.md)

## ✨ 功能特色

### 🎯 主要工具
- **二维码生成器** - 支持文本、URL、WiFi、邮箱、电话等多种类型
- **颜色工具** - 颜色选择器、格式转换、调色板管理
- **文本处理** - 字数统计、大小写转换、编码解码等
- **时间工具** - 时间戳转换、倒计时器、世界时钟
- **密码生成器** - 可定制的安全密码生成
- **单位转换器** - 长度、重量、温度、面积、体积、时间转换
- **Base64工具** - 文本、文件、图片的Base64编码解码
- **PDF工具箱** - PDF合并、分割、压缩和转换功能
- **图片编辑器** - 在线图片编辑，支持滤镜、文字、形状等功能

### 🎨 设计特点
- 现代化响应式设计
- 移动端友好
- 直观的用户界面
- 快速加载
- 本地处理，保护隐私

### 💰 特色亮点
- 完全免费使用
- 无广告干扰
- 搜索引擎优化 (SEO)
- 高质量内容和用户体验

## 🚀 快速开始

### 环境要求
- Node.js 16.x 或更高版本
- npm 或 yarn 包管理器

### 安装依赖
```bash
npm install
```

### 开发模式运行
```bash
npm run dev
```
访问 [http://localhost:3000](http://localhost:3000) 查看网站

### 构建生产版本
```bash
npm run build
```

### 预览生产版本
```bash
npm run preview
```

## 📁 项目结构

```
├── public/                 # 静态资源
├── src/
│   ├── components/         # 公共组件
│   │   ├── Header.jsx      # 头部导航
│   │   └── Footer.jsx      # 底部信息
│   ├── pages/              # 页面组件
│   │   ├── Home.jsx        # 首页
│   │   ├── QRGenerator.jsx # 二维码生成器
│   │   ├── ColorTools.jsx  # 颜色工具
│   │   ├── TextTools.jsx   # 文本工具
│   │   ├── TimeTools.jsx   # 时间工具
│   │   ├── PasswordGenerator.jsx # 密码生成器
│   │   ├── UnitConverter.jsx     # 单位转换器
│   │   ├── Base64Tools.jsx       # Base64工具
│   │   ├── PDFTools.jsx          # PDF工具箱
│   │   └── PhotoEditor.jsx       # 图片编辑器
│   ├── App.jsx             # 主应用组件
│   ├── main.jsx            # 应用入口
│   └── index.css           # 全局样式
├── index.html              # HTML模板
├── package.json            # 项目配置
├── vite.config.js          # Vite配置
├── tailwind.config.js      # Tailwind配置
└── README.md               # 项目说明
```

## 🛠️ 技术栈

- **前端框架**: React 18
- **构建工具**: Vite
- **CSS框架**: Tailwind CSS
- **路由**: React Router DOM
- **图标库**: Lucide React
- **二维码**: qrcode.js
- **颜色选择器**: react-color
- **PDF处理**: pdf-lib
- **图片编辑**: Fabric.js
- **文件下载**: file-saver
- **国际化**: react-i18next

## 🌍 语言支持

网站支持中英文双语，具备自动语言检测和手动切换功能：
- **中文 (zh-CN)** - 默认语言
- **英文 (en-US)** - 英文界面
- 语言偏好本地保存
- 实时切换无需刷新页面

## 📈 SEO优化

### 已实现的SEO特性
- 语义化HTML结构
- Meta标签优化
- Open Graph标签
- Twitter Cards
- 结构化数据 (JSON-LD)
- 响应式设计
- 快速加载时间
- 用户友好的URL结构

### 关键词策略
- 在线工具
- 实用工具
- 免费工具
- 二维码生成
- 颜色工具
- 文本处理
- 密码生成器
- PDF工具
- 图片编辑器
- 在线PS
- PDF合并
- PDF分割

## 💻 部署建议

### Vercel部署
1. 推送代码到GitHub
2. 连接Vercel账户
3. 导入项目
4. 自动部署

### Netlify部署
1. 运行 `npm run build`
2. 上传 `dist` 目录到Netlify
3. 配置自定义域名

### 其他平台
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

## 🎯 未来规划

### 功能扩展
- [x] PDF工具箱 - 已完成
- [x] 图片编辑器 - 已完成
- [x] 多语言支持 - 已完成
- [ ] JSON格式化工具
- [ ] Markdown编辑器
- [ ] 正则表达式测试器
- [ ] 哈希值计算工具
- [ ] 网络ping测试
- [ ] OCR文字识别
- [ ] 视频格式转换

### 优化计划
- [ ] PWA支持
- [x] 多语言支持 - 已完成
- [ ] 暗色主题
- [ ] 用户偏好设置
- [ ] 工具使用统计

## 📱 响应式设计

现在拥有9+个实用工具，网站完全支持：
- 桌面端 (1200px+)
- 平板端 (768px-1199px)
- 移动端 (320px-767px)

## 🔒 隐私保护

- 所有工具处理均在本地完成
- 不收集用户个人信息
- 不存储用户输入数据
- 符合GDPR要求

## 🤝 贡献指南

1. Fork项目
2. 创建功能分支
3. 提交更改
4. 推送到分支
5. 创建Pull Request

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。


⭐ 如果这个项目对您有帮助，请给我们一个Star！

