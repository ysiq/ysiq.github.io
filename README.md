# 个人网站项目

一个包含个人博客和公司产品展示的网站，使用 HTML 和 Jekyll 构建，部署于 GitHub Pages。

## 网站概览

| 模块 | 技术栈 | 说明 |
|------|--------|------|
| 首页 | HTML | 网站概览和快速链接 |
| 个人博客 | Jekyll | 技术分享、生活感悟、项目记录 |
| 公司产品 | Jekyll | 智能家居、灵巧手产品展示 |

## 项目结构

```
.github.io/
├── index.html              # 网站首页
├── _config.yml             # Jekyll 全局配置
├── _layouts/               # 布局文件
│   ├── blog.html           # 博客布局
│   └── zdzb.html           # 公司产品布局
├── css/                    # 根目录样式
│   └── style.css
├── blog/                   # 个人博客
│   ├── css/style.css       # 博客样式
│   ├── index.md            # 博客首页
│   ├── 技术分享/index.md
│   ├── 生活感悟/index.md
│   └── 项目记录/index.md
├── zdzb/                   # 公司产品
│   ├── css/style.css       # 产品样式（暗色主题）
│   ├── index.md            # 产品首页
│   ├── smart-home/         # 智能家居
│   │   ├── img/            # 产品图片
│   │   ├── index.md        # 产品总览
│   │   ├── gateway.md      # 智能网关
│   │   ├── wall-switch.md  # 墙面开关
│   │   ├── smart-curtain.md# 智能窗帘
│   │   └── socket.md       # 移动插座
│   ├── dexterous-hand/     # 灵巧手
│   │   ├── img/            # 产品图片
│   │   ├── index.md        # 产品总览
│   │   ├── 1-机械结构与运动性能.md
│   │   ├── 2-感知与交互系统.md
│   │   ├── 3-电气与控制接口.md
│   │   ├── 4-外形尺寸与安装.md
│   │   ├── 5-软件生态与开发.md
│   │   ├── 6-快速上手指南.md
│   │   └── 7-维护保养与故障处理.md
│   └── downloads/          # 下载中心
│       ├── index.md        # 下载页面
│       ├── 灵巧手产品说明书.pdf
│       └── 灵巧手上位机说明书.doc
└── README.md
```

## 布局说明

| 布局文件 | 使用范围 | 特性 |
|---------|---------|------|
| `blog.html` | blog 目录 | 顶部导航（技术分享/生活感悟/项目记录） |
| `zdzb.html` | zdzb 目录 | 顶部导航 + 左侧二级导航 + 回到顶部按钮 |

## 本地运行

### 方式一：直接预览
直接在浏览器中打开 `index.html` 文件。

### 方式二：Jekyll 服务

```bash
# 安装 Jekyll
gem install jekyll bundler

# 运行服务
cd github.io
bundle exec jekyll serve

# 访问地址
# 首页：http://localhost:4000
# 博客：http://localhost:4000/blog/
# 公司产品：http://localhost:4000/zdzb/
```

## 部署

网站自动部署到 GitHub Pages：`https://ysiq.github.io`

## 功能清单

- [x] 网站首页
- [x] 个人博客（技术分享/生活感悟/项目记录）
- [x] 公司产品展示
  - [x] 智能家居（5个产品页面）
  - [x] 灵巧手（8个介绍页面）
  - [x] 下载中心
- [x] 响应式设计
- [x] 暗色主题（公司产品）
- [x] 回到顶部按钮

## 版本

| 版本 | 更新内容 |
|-----|---------|
| V1.0 | 初始版本 |
