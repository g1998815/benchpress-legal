# 练了吗健身 · 支持与隐私政策页

这两个页面用于 App Store Connect 的「支持网址」和「隐私政策网址」：

- 支持：<https://g1998815.github.io/benchpress-legal/>
- 隐私政策：<https://g1998815.github.io/benchpress-legal/privacy.html>

公开仓库：<https://github.com/g1998815/benchpress-legal>

纯静态、零依赖；样式在 `style.css`，浅色/深色跟随系统。

## 联系信息

- 邮箱：espoirgch@outlook.com
- 开发者：espoirg

## 更新

直接改本目录的 `index.html` / `privacy.html` / `style.css`，然后把改动同步到公开仓库
（GitHub 网页上直接编辑也可以，Pages 会自动重新发布）。

公开仓库的默认分支是 `main`，Pages 从 `/ (root)` 发布。

## 首次部署（已完成）

如果以后需要从零再建一次：

```bash
cd appstore/site
git init -b main
git add .
git commit -m "docs: 练了吗健身支持与隐私政策页"
git remote add origin https://github.com/g1998815/benchpress-legal.git
git push -u origin main
```

然后在 GitHub 仓库 → Settings → Pages → Source 选 `Deploy from a branch`，
分支 `main`、目录 `/ (root)`，保存后等 1–2 分钟。

## 注意

- App Store Connect 会真的去访问这两个 URL；不能用需要登录、需要密码或会过期的链接。
- 以后如果加入云同步、统计或推送，记得回来更新隐私政策，再重新发布。
