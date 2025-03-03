# NaviHub - 您的网络导航门户

## 项目介绍

NaviHub是一个简洁、美观且功能强大的网站导航平台，旨在为用户提供便捷的网络资源访问体验。通过分类整理各类优质网站和工具，帮助用户快速找到所需资源，提高网络冲浪效率。

## 功能特点

- **分类导航**：按照搜索引擎、社交媒体、生产力工具和学习资源等类别整理网站
- **响应式设计**：完美适配各种设备屏幕尺寸，包括桌面、平板和手机
- **搜索功能**：快速查找收录的网站和资源
- **美观界面**：简洁现代的UI设计，提供舒适的视觉体验
- **易于扩展**：简单的代码结构，方便添加新的网站类别和链接

## 技术栈

- HTML5
- CSS3 (包含Flexbox和Grid布局)
- 响应式设计
- Font Awesome图标库 (v6.7.2)

## 项目结构

```
navihub/
├── index.html        # 主页面
└── README.md         # 项目文档
```

## 本地运行

使用任意HTTP服务器启动项目，例如：

```bash
# 使用Python内置HTTP服务器
python -m http.server

# 或使用Node.js的http-server
npx http-server .
```

然后在浏览器中访问 `http://localhost:8000` 或对应端口

## 自定义与扩展

### 添加新的网站类别

在`index.html`文件中，复制现有的类别部分并修改内容：

```html
<section class="category">
  <div class="category-header">
    <h2 class="category-title">新类别名称</h2>
    <p class="category-description">
      类别描述文本
    </p>
  </div>
  <div class="site-grid">
    <!-- 网站项目 -->
  </div>
</section>
```

### 添加新的网站链接

在对应类别的`site-grid`div中添加新的网站链接：

```html
<a href="https://example.com" class="site-item">
  <i class="fas fa-icon-name site-icon" style="font-size: 24px; color: #颜色代码;"></i>
  <div class="site-info">
    <div class="site-name">网站名称</div>
  </div>
</a>
```

## 联系方式

- 作者：您的名字
- 邮箱：your.email@example.com

---

如果您觉得这个项目有帮助，请给它一个⭐️！