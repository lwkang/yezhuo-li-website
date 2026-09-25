# Yezhuo Li — Academic Website

一个纯静态的单页学术主页，无需任何构建工具，可直接用 GitHub Pages 免费托管。

## 文件说明

- `index.html` — 网页全部内容
- `style.css` — 样式
- `assets/Yezhuo_Li_CV.pdf` — CV 下载文件（页面上的 "Download CV" 按钮指向它）

## 用 GitHub Pages 部署（免费，约 5 分钟）

1. 在 GitHub 上新建一个仓库（Repository）。
   - 如果想要 `https://你的用户名.github.io` 这种根域名，仓库名必须精确写成 `你的GitHub用户名.github.io`。
   - 如果只是想要一个子路径网址（如 `https://你的用户名.github.io/yezhuo-li`），仓库名随意即可，比如 `yezhuo-li-website`。
2. 把本文件夹里的三个文件/文件夹（`index.html`、`style.css`、`assets/`）上传到该仓库的根目录：
   - 网页端操作：打开仓库 → "Add file" → "Upload files" → 把文件拖进去 → Commit。
   - 或者本地命令行：
     ```bash
     git init
     git add .
     git commit -m "Initial site"
     git branch -M main
     git remote add origin https://github.com/你的用户名/仓库名.git
     git push -u origin main
     ```
3. 打开仓库的 **Settings → Pages**。
4. 在 "Build and deployment" 下，Source 选择 **Deploy from a branch**，Branch 选择 **main / (root)**，保存。
5. 等 1-2 分钟，页面顶部会出现你的网址（形如 `https://你的用户名.github.io/仓库名/`），点开即可访问。

## 之后如何更新内容

以后有新论文、新奖项，直接编辑 `index.html` 里对应的 `<section>`（比如 `id="publications"` 或 `id="awards"`），保存后 push 到 GitHub，网站几分钟内自动更新。也可以把新的 CV 文件替换 `assets/Yezhuo_Li_CV.pdf`（保持文件名一致，或改文件名后同步修改 `index.html` 里的链接）。

## 内容来源说明

所有内容均来自你提供的 CV（2026年9月更新版）。个人网页公开展示，出于隐私考虑，联系方式部分只保留了工作邮箱和院系办公电话，未展示 CV 顶部的个人手机号；如需展示，可自行在 `index.html` 的 `#contact` 区块添加。
