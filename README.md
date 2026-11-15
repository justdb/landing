# justdb/landing

JustDB 品牌占位页（landing page）— 部署于 GitHub Pages，绑定自定义域名 **justdb.ai**。

- 线上地址：https://justdb.ai （www.justdb.ai → justdb.ai）
- 部署方式：GitHub Pages，`main` 分支根目录，纯静态单文件（`index.html`）
- DNS：Cloudflare 托管，灰云直连 GitHub Pages（apex 4×A 185.199.108-111.153，www CNAME justdb.github.io）
- HTTPS：GitHub Pages 自动签发/续期 Let's Encrypt 证书

## 相关仓库规划

| 仓库 | 用途 | 域名 |
|------|------|------|
| `justdb/landing`（本仓） | justdb.ai 占位页（Coming Soon） | justdb.ai / www.justdb.ai |
| `justdb/justdb-docs` | VuePress 文档站（开发中） | blog.justdb.ai（原规划，Pages 暂未启用） |
| `justdb/justdb.github.io` | org 主页（2019 年旧站） | justdb.github.io |

## 本地预览

直接用浏览器打开 `index.html` 即可，无构建步骤、无外部依赖。
