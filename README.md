# 把酒话宋 · 第15页互动课件（背钱买酒·算一算）

七个年级下册历史第12课《辽宋夏金元时期经济的繁荣》配套互动页。

- 单文件：`index.html`（零依赖、不联网也能用）
- 内容：①猜一猜 → ②算一算 → ③比一比 → ④想一想

## 部署到 GitHub Pages（网页拖拽法，不用命令行）

1. 打开 https://github.com/new
   - Repository name 填：`bajiu-p15`
   - 选 **Public**（Pages 免费版必须公开）
   - 点 `Create repository`
2. 在仓库页点 **uploading an existing file**（或 Add file → Upload files）
   - 把本文件夹里的 `index.html` 与 `.nojekyll` 一起拖进去
   - 点 `Commit changes`
3. 仓库页 → `Settings` → 左侧 `Pages`
   - Source 选 **Deploy from a branch**
   - Branch 选 `main`，目录选 `/ (root)` → `Save`
4. 等 1–2 分钟，刷新 Settings → Pages，顶部会出现你的网址：
   `https://<你的用户名>.github.io/bajiu-p15/`

## 部署到 GitHub Pages（命令行法）

```bash
git init
git add .
git commit -m "add P15 interactive page"
git branch -M main
git remote add origin https://github.com/<你的用户名>/bajiu-p15.git
git push -u origin main
```

推送后在 Settings → Pages 里开启 main 分支即可。

## 更新内容

改完 `index.html` 重新上传（Web 端：Add file → Upload files 覆盖；命令行：commit 后 push），
Pages 会在 1 分钟内自动更新，**网址不变**。

## 注意

- 国内访问 `github.io` 有时较慢或被拦截，课堂请务必同时保留本地 HTML 文件做备份；
  如需国内更稳，可把同一份 `index.html` 拖到 Cloudflare Pages（同样免费、不休眠）。
- 本页无外部依赖，断网时用本地文件双击打开即可，功能完全一致。
