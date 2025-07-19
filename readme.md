# 星辰博客 - 个人博客系统

一个优雅的现代化个人博客界面，采用React + Tailwind CSS构建，具有响应式设计和丰富的交互效果。

## 功能特点

- 🎨 **现代化UI设计**：渐变色标题、卡片悬停动画、精致阴影效果
- 📱 **响应式布局**：适配手机、平板和桌面设备
- 📝 **博客内容展示**：文章列表、摘要预览、分类标签
- 👤 **作者信息展示**：头像、个人简介
- 📅 **元数据展示**：发布日期、分类标签
- 🔍 **交互效果**：悬停动画、平滑过渡、链接高亮

## 技术栈

- React 18+
- Tailwind CSS 3+
- Lucide React 图标库
- React Hooks 状态管理

## 组件结构
src/
├── components/
│ └── OptimizedPersonalBlog.jsx # 主博客组件
├── assets/
│ └── (未来可添加图片资源)
├── App.js # 应用入口
└── index.js # 渲染入口

## 安装与运行

1. 克隆仓库：
```bash
git clone https://github.com/BuWuZhengYeYangYiNuo/StarBlog.git
```
2. 安装依赖：
```bash
npm install
```
3. 运行开发服务器：
```bash
npm run dev
```
4. 构建生产版本：
```bash
npm run build
```
## 自定义配置
### 修改博客内容
在 index.html 文件中修改以下数组"：
```html
const posts = [
  {
    id: 1,
    title: "文章标题",
    excerpt: "文章摘要...",
    date: "2023-XX-XX",
    category: "分类名称"
  },
  // 更多文章...
];

const categories = ["分类1", "分类2", "分类3"]; // 分类标签
```
## 样式定制
通过修改以下Tailwind CSS变量来自定义主题：
```html
// 在组件中修改这些颜色变量
const colorScheme = {
  primary: 'indigo', // 主色调
  secondary: 'purple' // 辅助色调
};
```
## 浏览器兼容性
Chrome 最新版
Firefox 最新版
Safari 最新版
Edge 最新版
