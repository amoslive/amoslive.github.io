# amoslive.github.io

Amos 的个人学术履历与作品主页，基于 [HugoBlox Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv) 构建。

## 本地预览

需要 Hugo Extended 0.162.0、Go 和 Node.js 22：

```bash
pnpm install
hugo server
```

访问 `http://localhost:1313/`。

## 编辑内容

- 个人资料：`data/authors/me.yaml`
- 首页区块：`content/_index.md`
- 导航菜单：`config/_default/menus.yaml`
- 站点配置：`config/_default/hugo.yaml` 和 `params.yaml`

推送到 `main` 分支后，GitHub Actions 会自动构建并部署到 GitHub Pages。
