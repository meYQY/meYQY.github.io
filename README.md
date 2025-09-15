# meYQY.github.io

一个无需构建的纯静态个人主页，适配 GitHub Pages（用户主页仓库）。

## 使用

- 首页：直接编辑 `index.html` 的文案，比如“关于我”“项目”“联系”。
- 样式：在 `assets/style.css` 调整配色、间距或排版（已适配系统深浅色）。
- 404：可在 `404.html` 自定义未找到页面。

## 本地预览

双击打开 `index.html` 用浏览器查看，或启动一个本地静态服务器：

```bash
python3 -m http.server 3000
# 打开 http://localhost:3000
```

## 发布

这是用户主页仓库（仓库名为 `<用户名>.github.io`），推送到 `main` 或 `master` 分支后，GitHub Pages 会自动从仓库根目录发布。

如有自定义域名，可在仓库根目录添加 `CNAME` 文件并填入你的域名。
