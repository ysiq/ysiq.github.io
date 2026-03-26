# 个人作品集网站

这是一个使用Jekyll构建的个人作品集网站，包含以下页面：
- 首页
- 产品说明书
- 关于我们
- 联系我们

## 项目结构

```
.github.io/
├── _config.yml          # 网站配置文件
├── _includes/           # 可重用的页面组件
│   ├── header.html      # 头部组件
│   └── footer.html      # 页脚组件
├── _layouts/            # 页面布局模板
│   └── default.html     # 默认布局
├── css/                 # 样式文件
│   └── style.css        # 主样式文件
├── index.md             # 首页内容
├── product-manuals.md   # 产品说明书页面
├── about.md             # 关于我们页面
├── contact.md           # 联系我们页面
└── README.md            # 项目说明
```

## 本地运行

要在本地运行此项目，您需要安装：
1. Ruby
2. Jekyll

### 安装步骤

1. 安装Ruby：
   - Windows：从 https://rubyinstaller.org/ 下载并安装
   - macOS：使用 Homebrew `brew install ruby`
   - Linux：使用包管理器，例如 `apt-get install ruby`

2. 安装Jekyll：
   ```bash
   gem install jekyll bundler
   ```

3. 克隆项目并进入目录：
   ```bash
   git clone <repository-url>
   cd github.io
   ```

4. 安装依赖：
   ```bash
   bundle install
   ```

5. 启动本地服务器：
   ```bash
   bundle exec jekyll serve
   ```

6. 在浏览器中访问：`http://localhost:4000`

## 部署

要部署到GitHub Pages：

1. 将代码推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择主分支作为源
4. 等待几分钟，网站将在 `https://<username>.github.io` 上可用

## 自定义

- 编辑 `_config.yml` 文件修改网站配置
- 编辑Markdown文件修改页面内容
- 编辑 `css/style.css` 文件修改样式
- 添加新的Markdown文件创建新页面
