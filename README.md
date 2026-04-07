# 静烛

这是一个可直接部署到 GitHub Pages 的静态页面项目。

## 本地结构

- `index.html`：主页面入口
- `.github/workflows/pages.yml`：GitHub Pages 自动部署工作流
- `.nojekyll`：关闭 Jekyll 处理，确保静态文件按原样发布

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 把当前目录内容推到该仓库的 `main` 分支。
3. 打开仓库的 `Settings > Pages`。
4. 将 `Build and deployment` 的 `Source` 设为 `GitHub Actions`。
5. 等待 Actions 跑完，页面就会发布。

发布地址通常是：

`https://你的用户名.github.io/仓库名/`

如果仓库名就是 `你的用户名.github.io`，则地址会是：

`https://你的用户名.github.io/`
