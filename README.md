# Seed Brand Site

ByteDance Seed 品牌与设计系统静态预览站。

## 页面

- `index.html` — 入口落地页
- `homepage.html` — Seed 主页布局（通用智能研究）
- `brand-system.html` — 完整品牌与设计系统规范

## 资源

- `seed-logo.svg` — 品牌 logo（运行时通过 fetch 注入到 `[data-seed-logo]` 槽位）
- `deck-stage.js` — Brand & Design System 页面的演示舞台脚本
- `tweaks-panel.jsx` — 配套调参面板（参考代码）
- `uploads/` — 设计参考图

## 本地预览

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

注：因为 `seed-logo.svg` 是通过 `fetch()` 加载的，必须用 HTTP server 而不是直接 `file://` 打开。
