# GPDdev.github.io

Gunpowder / Pegasus Bluie 双身份个人主页的纯静态版本。

## 页面

- `/`：身份选择页
- `/gunpowder/`：Gunpowder / 人类主页
- `/skyblue/`：Pegasus Bluie / 小马主页

## 部署到 GitHub Pages

1. 新建 GitHub repository：`GPDdev.github.io`
2. 把本目录中的文件全部上传到仓库根目录。
3. 推送到默认分支（通常是 `main`）。
4. 打开仓库 Settings → Pages，确认从该分支部署。
5. 稍等后访问 `https://gpddev.github.io/`。

## 文件结构

```text
GPDdev.github.io/
├── index.html
├── 404.html
├── .nojekyll
├── gunpowder/
│   └── index.html
├── skyblue/
│   └── index.html
└── assets/
    ├── style.css
    ├── app.js
    └── images/
        ├── gunpowder-avatar.png
        ├── skyblue-avatar.png
        ├── gunpowder-hero.webp
        └── skyblue-hero.webp
```

头像已经处理成带透明背景的圆形 PNG；两张头图转换为 WebP 以减小加载体积。

以后绑定 `hachile.me` 一类独立域名时，不需要重写页面结构。
