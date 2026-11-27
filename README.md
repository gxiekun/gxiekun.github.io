# kungeai.com

爱折腾的昆哥的个人主页，GitHub Pages 部署，自定义域名 kungeai.com。

- `index.html` — 单文件站点（样式内联，无构建步骤）
- `avatar.jpg` — 头像（昆哥卡通头像）
- `CNAME` — 自定义域名声明，内容固定为 `kungeai.com`，不要删

## 域名 DNS（在域名注册商处设置）
- A 记录 ×4：主机记录 `@` → 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
- CNAME：主机记录 `www` → `gxiekun.github.io`
- DNS 生效后，在仓库 Settings → Pages 里确认 Custom domain 为 kungeai.com，并勾选 Enforce HTTPS。
