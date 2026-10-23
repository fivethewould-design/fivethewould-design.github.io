# fivethewould-design.github.io

个人开发者站点，托管于 GitHub Pages。

- 访问地址（Pages 默认）：https://fivethewould-design.github.io
- 自定义域名：https://laoli.is-a.dev （is-a.dev 免费子域名，注册文件见 `../laoli.json`，需在 `is-a-dev/register` 提 PR 合并后生效）

## 本地修改

直接编辑 `index.html`（单文件，样式内联，无构建步骤），提交即自动部署。

```bash
git add index.html
git commit -m "update site"
git push
```

## 绑定自定义域名

is-a.dev 的 PR 合并后：

1. 本仓库 `Settings → Pages → Custom domain` 填 `laoli.is-a.dev`，Save。
2. 等 GitHub 校验 DNS（is-a.dev 侧已把 CNAME 指到 `fivethewould-design.github.io`）。
3. 勾选 `Enforce HTTPS`，等证书签发。
