# darion.yaphet's blog

这是一个使用 [Hugo](https://gohugo.io/) 和 [hugo-narrow](https://github.com/tom2almighty/hugo-narrow.git) 主题构建的博客网站。

## 本地开发

要本地运行此站点，请执行以下命令：

```bash
# 安装 Hugo (如果您还没有安装)
# macOS
brew install hugo

# 或者使用其他方式安装，请参见 https://gohugo.io/getting-started/installing/

# 克隆仓库 (包括子模块)
git clone --recurse-submodules https://github.com/darion-yaphet/darion-yaphet.github.io.git

# 进入目录
cd darion-yaphet.github.io

# 启动本地服务器
hugo server
```

您的站点将在 `http://localhost:1313` 上可用。

## 部署

此站点通过 GitHub Actions 自动部署。每次向 `main` 分支推送更改时，都会自动构建并部署到 GitHub Pages。

工作流程定义在 `.github/workflows/hugo-deploy.yml` 中。