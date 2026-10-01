[README.md](https://github.com/user-attachments/files/32921966/README.md)
# -# 风信紫的个人主页

一个纯前端、单文件的个人主页,液态玻璃(Liquid Glass)风格,支持:

- 圆润的毛玻璃卡片(可调模糊度/圆角)
- 动态漂浮光斑背景 + 缓慢色调流转动画
- 鼠标跟随光晕(悬浮玻璃上下呈现不同颜色)
- 图标按钮 Q 弹动效,点击玻璃卡片有果冻回弹效果
- 社交链接:GitHub / X / Bluesky / Telegram

## 使用方法

直接用浏览器打开 `index.html` 即可,无需构建、无需依赖。

## 部署到 GitHub Pages

1. 新建一个仓库,把 `index.html` 放进去(仓库根目录)
2. 进入仓库 Settings → Pages
3. Source 选择 `main` 分支 / `root` 目录,保存
4. 稍等片刻,即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问

## 自定义

打开 `index.html`,可以直接修改:

- 名字 / 简介文字(`<h1>` 和 `<p class="tagline">`)
- 头像图片(`<div class="avatar">` 里的 base64 图片,建议自己换成图床外链以减小文件体积)
- 社交链接地址(`.links` 里各个 `<a href="...">`)
- 配色 / 圆角 / 模糊强度等(`:root` 和 `.glass-panel` 相关 CSS 变量)
