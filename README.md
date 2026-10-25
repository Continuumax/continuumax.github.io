# Continuumax Team 官网

Continuumax Team 官方静态网站，纯黑/纯白极简、绝对直角风格，与 Nicing 官网同主题。

## 页面

- `index.html` — 官网首页（品牌理念 + 作品：Nicing / uMax.ai）
- `privacy.html` — 隐私政策
- `terms.html` — 服务条款
- `nicing/` — Nicing 音乐播放器官网（index / privacy / terms）

## 特点

- 纯静态 HTML/CSS/JS，无构建依赖、无后端、无外部资源。
- Cookie 合规：首次进入弹出「本网站使用 Cookie」，可查看 cookie 内容，接受 / 仅必要二选一；仅使用一个偏好 Cookie `continuumax_consent`，无第三方追踪。

## 部署到 GitHub Pages

1. 将本文件夹内容作为仓库根目录，推送到 GitHub（例如 `username.github.io` 或普通仓库）。
2. 仓库设置 → Pages → 部署分支选择 `main`，目录选「根目录 / (root)」，保存。
3. 几分钟后访问 `https://<用户名>.github.io/<仓库名>/`（普通仓库）或 `https://<用户名>.github.io/`（`username.github.io` 仓库）。

> `.nojekyll` 已包含，避免 Jekyll 特殊处理，确保所有页面原样发布。
> 本地预览：`python -m http.server 8000` 后访问 `http://localhost:8000/`。

> AI生成
