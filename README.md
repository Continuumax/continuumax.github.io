# ContinuuMax Team 官网

ContinuuMax Team 官方静态网站。浅色小众简约风格：暖米白底（#F4F1EC）、墨黑文字、细发丝分割线、真实摄影大图、绝对直角。

## 页面

### 公司站（根目录）
- `index.html` — 首页（hero + 品牌 + 三入口卡）
- `beliefs.html` — 品牌理念
- `sustainability.html` — 可持续发展
- `works.html` — 作品（HearthTone / uMax.ai）
- `privacy.html` — 隐私政策
- `terms.html` — 服务条款

### HearthTone 子站（`hearthtone/`）
- `hearthtone/index.html` — 产品首页（hero 大图 + 播放器 UI 互动 + 特性概览）
- `hearthtone/features.html` — 特性页（四大特性 + 真实摄影配图）
- `hearthtone/download.html` — 下载页（版本信息 + 系统要求 + 更新日志 + 百度盘跳转确认）
- `hearthtone/privacy.html` — 隐私政策
- `hearthtone/terms.html` — 服务条款

## 特点

- 纯静态 HTML/CSS/JS，无构建依赖、无后端、无外部资源。
- 多语言：支持 繁體中文（預設）、简体中文、English (US)、English (UK)，右上角可切换并记住选择（localStorage `continuumax_lang`）。
- Cookie 合规：首次进入弹出「本网站使用 Cookie」，可查看 cookie 内容，接受 / 仅必要二选一；仅使用一个偏好 Cookie `continuumax_consent`（有效期 180 天），无第三方追踪。
- 照片全部来自 Unsplash 免费真实摄影（无 AI 生成），本地存放在 `assets/img/` 与 `hearthtone/assets/img/`，页脚注明图源。
- HearthTone 下载跳转百度网盘（`pan.baidu.com`），带跳转确认弹窗。
- 无圆角（绝对直角）、零装饰、发丝分隔线的极简排版。

## 目录结构

```
.
├── index.html            # 公司首页
├── beliefs.html          # 品牌理念
├── sustainability.html   # 可持续发展
├── works.html            # 作品
├── privacy.html          # 隐私政策（公司站）
├── terms.html            # 服务条款（公司站）
├── assets/
│   └── img/              # 公司站照片（Unsplash）
├── hearthtone/
│   ├── index.html        # HearthTone 首页
│   ├── features.html     # HearthTone 特性
│   ├── download.html     # HearthTone 下载
│   ├── privacy.html      # 隐私政策
│   ├── terms.html        # 服务条款
│   └── assets/
│       └── img/          # HearthTone 照片（Unsplash）
├── .nojekyll             # 禁用 GitHub Pages 的 Jekyll 处理
└── README.md
```

## 部署到 GitHub Pages

1. 将本文件夹内容作为仓库根目录，推送到 GitHub（例如 `username.github.io` 或普通仓库）。
2. 仓库设置 → Pages → 部署分支选择 `main`，目录选「根目录 / (root)」，保存。
3. 几分钟后访问 `https://<用户名>.github.io/<仓库名>/`（普通仓库）或 `https://<用户名>.github.io/`（`username.github.io` 仓库）。

> `.nojekyll` 已包含，避免 Jekyll 特殊处理，确保所有页面原样发布。
> 本地预览：`python -m http.server 8000` 后访问 `http://localhost:8000/`。

> AI生成
