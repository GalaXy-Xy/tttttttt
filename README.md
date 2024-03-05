# 企业官网展示页面

一个现代化、响应式的企业官网展示页面，采用纯前端技术实现。

## 项目特性

- 🎨 现代化设计风格，简约商务感
- 📱 完全响应式设计，适配PC、平板、手机
- ⚡ 原生JavaScript实现，无框架依赖
- 🎯 平滑滚动和动画效果
- 🖼️ 自动轮播图功能
- 📝 静态表单展示

## 技术栈

- **HTML5** - 语义化标签结构
- **CSS3** - 现代样式和动画
- **JavaScript** - 原生JS实现交互功能
- **Google Fonts** - Inter和Roboto字体
- **Font Awesome** - 图标库

## 页面结构

- **首页** - 轮播图展示、公司简介
- **关于我们** - 公司背景、使命愿景
- **产品中心** - 产品展示卡片
- **联系我们** - 联系信息和表单

## 快速开始

1. 克隆项目到本地
```bash
git clone https://github.com/GalaXy-Xy/tttttttt.git
cd tttttttt
```

2. 直接在浏览器中打开 `index.html` 文件

3. 或者使用本地服务器（推荐）
```bash
# 使用Python
python -m http.server 8000

# 使用Node.js
npx serve .

# 使用Live Server（VS Code插件）
```

## 浏览器支持

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 项目结构

```
├── index.html          # 主页面文件
├── styles.css          # 样式文件
├── script.js           # JavaScript功能
├── README.md           # 项目说明
└── .gitignore          # Git忽略文件
```

## 功能说明

### 导航栏
- 固定顶部导航
- 移动端汉堡菜单
- 平滑滚动到对应区域

### 轮播图
- 自动轮播（5秒间隔）
- 手动切换（按钮和指示点）
- 键盘和触摸支持
- 鼠标悬停暂停

### 响应式设计
- 移动端优先设计
- 三个断点：手机(<768px)、平板(768px-1024px)、PC(>1024px)
- 灵活的网格布局

### 动画效果
- 页面加载动画
- 滚动触发动画
- 悬停效果
- 平滑过渡

## 自定义配置

### 修改主题色
在 `styles.css` 中修改CSS变量：
```css
:root {
    --primary-color: #1E88E5;
    --secondary-color: #1976D2;
}
```

### 修改轮播图
在 `index.html` 中修改轮播图内容，在 `script.js` 中调整自动播放间隔。

### 修改联系信息
在 `index.html` 的联系我们部分修改联系信息。

## 部署说明

项目为纯静态文件，可以部署到任何静态网站托管服务：

- GitHub Pages
- Netlify
- Vercel
- 阿里云OSS
- 腾讯云COS

## 许可证

MIT License

## 联系方式

如有问题或建议，请联系：
- 邮箱：contact@company.com
- 电话：+86 010-12345678
