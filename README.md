# Philip Hopf Landing Page

这是一个为 Philip Hopf 创建的 WhatsApp 群组推广落地页，支持 GitHub 和 Vercel 部署。

## 功能特性

- 📱 响应式设计，支持移动端和桌面端
- 🎯 动态数字更新，增加紧迫感
- 🔗 随机 WhatsApp 群组链接跳转
- 📊 Google Analytics 和 Google Ads 转化跟踪
- ⚡ 快速加载，优化的静态资源

## 项目结构

```
├── index.html          # 主页面文件
├── public/
│   └── images/         # 图片资源
│       ├── 888.jpg     # 头像图片
│       ├── 963.jpg     # 推广图片
│       └── whatsapp.webp # WhatsApp 图标
├── package.json        # 项目配置
├── vercel.json         # Vercel 部署配置
├── .gitignore          # Git 忽略文件
└── README.md           # 项目说明
```

## 部署说明

### GitHub + Vercel 部署

1. **上传到 GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

2. **连接 Vercel**
   - 访问 [Vercel](https://vercel.com)
   - 点击 "New Project"
   - 选择你的 GitHub 仓库
   - 点击 "Deploy"

### 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

## 配置说明

### WhatsApp 群组链接

在 `index.html` 文件中找到以下部分并替换为你的实际群组链接：

```javascript
const links = [
    'https://chat.whatsapp.com/your-group-1',
    'https://chat.whatsapp.com/your-group-2', 
    'https://chat.whatsapp.com/your-group-3',
    'https://chat.whatsapp.com/your-group-4',
    'https://chat.whatsapp.com/your-group-5'
];
```

### Google Analytics 配置

在 `index.html` 文件中找到以下行并替换为你的跟踪 ID：

```javascript
window.ANALYTICS_TRACKING_ID = 'AW-xxx/xxx';
```

### 自定义内容

- 修改 `index.html` 中的文本内容
- 替换 `public/images/` 目录下的图片文件
- 调整 CSS 样式以匹配你的品牌

## 技术栈

- HTML5
- CSS3 (响应式设计)
- JavaScript (ES6+)
- Vercel (部署平台)

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

## 许可证

MIT License

## 支持

如有问题，请创建 Issue 或联系开发者。
