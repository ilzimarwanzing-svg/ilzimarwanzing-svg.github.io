# 个人简历网站

基于 Start Bootstrap Resume 的静态网站，使用模板的预编译样式和导航脚本。打开根目录下的 `index.html` 就可以预览。

## 修改内容

- 在 `index.html` 中替换姓名、简介、经历、教育背景、技能和项目。需要公开联系方式时，再添加你愿意公开的信息。
- 如需更换头像，把图片放进 `assets/`，再修改 `index.html` 中侧栏头像的 `src`。修改页面标题时，同时更新 `<title>` 和手机端导航标题。

## 发布到 GitHub Pages

1. 在 GitHub 新建公开仓库。个人主页的仓库名为 `你的用户名.github.io`。若这个仓库已有内容，可以改用 `resume` 等项目仓库名。
2. 将本目录中的文件和子目录提交到 `main` 的根目录，让 `index.html` 位于仓库顶层。
3. 打开仓库的 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，选中 **main** 和 **/ (root)**，然后点击 **Save**。
4. 等 Pages 部署完成，在同一页点 **Visit site**。修改并提交 `index.html` 后，GitHub Pages 会重新发布。

[GitHub Pages 中文文档](https://docs.github.com/zh/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 许可

[Start Bootstrap Resume](https://github.com/StartBootstrap/startbootstrap-resume) 使用 MIT 许可证，见 `LICENSE`。Bootstrap 许可证信息保留在 CSS 和 JavaScript 文件头部。
