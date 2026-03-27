# 个人网站项目

这是一个包含个人博客和公司产品展示的网站，使用HTML和Jekyll构建。

## 网站结构

- **首页**：纯HTML格式，网站概览和快速链接
- **个人博客**：Jekyll格式，技术分享和生活感悟
- **公司产品**：
  - 产品主页：HTML格式
  - 灵气手：HTML格式，智能手势控制产品
  - 智能家居：Jekyll格式，智能家庭解决方案

## 项目结构

```
.github.io/
├── index.html          # 网站首页（纯HTML）
├── css/                # 样式文件
│   └── style.css       # 主样式文件
├── blog/               # 个人博客（Jekyll格式）
│   ├── _config.yml     # 博客配置
│   ├── _layouts/       # 博客布局
│   │   └── default.html # 默认布局
│   └── index.md        # 博客首页
├── zdzb/               # 公司产品
│   ├── index.html      # 产品主页（HTML）
│   ├── 灵气手.html     # 灵气手产品页面（HTML）
│   └── smart-home/     # 智能家居（Jekyll格式）
│       ├── _config.yml # 智能家居配置
│       ├── _layouts/   # 智能家居布局
│       │   └── default.html # 默认布局
│       └── index.md    # 智能家居首页
└── README.md           # 项目说明和需求文档
```

## 本地运行

### HTML页面
直接在浏览器中打开HTML文件即可预览。

### Jekyll部分
要在本地运行Jekyll部分，您需要安装：
1. Ruby
2. Jekyll

#### 安装步骤

1. 安装Ruby：
   - Windows：从 https://rubyinstaller.org/ 下载并安装
   - macOS：使用 Homebrew `brew install ruby`
   - Linux：使用包管理器，例如 `apt-get install ruby`

2. 安装Jekyll：
   ```bash
   gem install jekyll bundler
   ```

3. 运行Jekyll服务器：
   - 博客部分：`cd blog && bundle exec jekyll serve`
   - 智能家居部分：`cd zdzb/smart-home && bundle exec jekyll serve`

4. 在浏览器中访问：
   - 博客：`http://localhost:4000`
   - 智能家居：`http://localhost:4000`

## 部署

要部署到GitHub Pages：

1. 将代码推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择主分支作为源
4. 等待几分钟，网站将在 `https://<username>.github.io` 上可用

## 自定义

### 内容修改
- **首页**：编辑 `index.html`
- **个人博客**：编辑 `blog/index.md`，可以添加更多Markdown文件作为博客文章
- **公司产品**：
  - 产品主页：编辑 `zdzb/index.html`
  - 灵气手：编辑 `zdzb/灵气手.html`
  - 智能家居：编辑 `zdzb/smart-home/index.md`

### 样式修改
- 编辑 `css/style.css` 文件修改全局样式

### 布局修改
- **博客布局**：编辑 `blog/_layouts/default.html`
- **智能家居布局**：编辑 `zdzb/smart-home/_layouts/default.html`

### 配置修改
- **博客配置**：编辑 `blog/_config.yml`
- **智能家居配置**：编辑 `zdzb/smart-home/_config.yml`

## 需求文档

本README.md文件可作为项目的需求文档，后续如需修改或扩展功能，请在此文件中更新需求，然后根据需求修改项目代码。

### 现有功能
- [x] 网站首页（HTML）
- [x] 个人博客（Jekyll）
- [x] 公司产品主页（HTML）
- [x] 灵气手产品页面（HTML）
- [x] 智能家居页面（Jekyll）
- [x] 响应式设计

### 未来扩展
- [ ] 博客文章分类和标签
- [ ] 产品详情页
- [ ] 联系表单功能
- [ ] 多语言支持
- [ ] 网站搜索功能