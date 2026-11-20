# Publish your saber guides with GitHub Pages · 发布佩剑学习指南

This package is ready to upload. It needs no build command, Python installation, or server application.

## Files

- `index.html` — bilingual home page with four separate entrances / 中英双语首页，四个独立入口
- `saber-explorer.html` — English kids’ guide / 英文孩子指南
- `saber-explorer-zh.html` — Simplified Chinese kids’ guide / 简体中文孩子指南
- `saber-parent-guide.html` — English parent guide / 英文家长指南
- `saber-parent-guide-zh.html` — Simplified Chinese parent guide / 简体中文家长指南
- `README.md` — these instructions

Keep the five HTML files together at the top level of the repository. Their names are case-sensitive. Every guide includes its complete reading view.

## Set up the website

1. Unzip `saber-guides-github-pages.zip` on a computer.
2. Sign in to GitHub and create a repository named `saber-guides`. With GitHub Free, use a **Public** repository for Pages. If you already have a suitable repository, you can use it instead.
3. Upload the extracted files to the repository’s top level and commit them to the `main` branch. If you see an **Add file** menu, choose **Upload files**. In a new empty repository, use its link to upload an existing file.
4. Open the repository’s **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch** as the source.
6. Select the **main** branch and **/(root)** folder, then **Save**.
7. Wait for the deployment to finish. GitHub says publication can take up to 10 minutes. The Pages settings will show a **Visit site** link.
8. Open that published link in Safari on your iPhone. The home page lets you choose the audience and language.

For a repository called `saber-guides`, the address normally looks like:

`https://YOUR-USERNAME.github.io/saber-guides/`

Replace `YOUR-USERNAME` with your GitHub username. Use the actual **Visit site** address shown by GitHub. The GitHub repository page and a downloaded file preview are different from this published website address.

## Updating the website

Upload the newer HTML files to the same repository using the same filenames, and commit the replacements. GitHub Pages will republish the site. Reopen or reload the published website after the deployment completes.

## Notes and videos

- The published guide content is public. This package contains curriculum and resources, not your family’s saved notes or learner profiles.
- Notes and progress remain in the browser where they were entered. English and Chinese editions of the same guide share saved progress when opened in the same browser at the same website address. They do not automatically sync between devices, between file previews and the hosted site, or between kids’ and parents’ guides. Existing notes are not automatically translated.
- Export a backup from the guide before changing where you use it, then import that backup at the new website address. Keep personal backup files out of the public repository.
- YouTube and other providers can still block an individual embedded video or require sign-in. Each viewing page retains an external source link.
- Guide text is translated into Simplified Chinese. Videos retain their original audio; availability of Chinese subtitles depends on their publisher.
- In file previews that cannot run scripts, the guides now show a complete reading view with source links. Interactive quizzes, saved notes, and embedded-player controls require an active browser page.

## If the site does not open

- Check that `index.html` is at the top level of the branch/folder selected in Pages settings.
- Check that the deployment completed successfully in the repository’s Actions tab.
- Use **Visit site** in Pages settings to obtain the exact address.
- For a project repository, retain the repository-name part of the address.

## Official GitHub instructions

- [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 中文发布说明

这个压缩包已经包含完整网页，不需要安装 Python，也不需要构建命令。

1. 在电脑上解压 `saber-guides-github-pages.zip`。
2. 登录 GitHub，建立名为 `saber-guides` 的仓库；使用 GitHub Free 时，请选择 Public（公开）。已有合适的仓库也可以继续使用。
3. 把解压后的五个 HTML 文件和 README 上传到仓库最外层，提交到 `main` 分支。不要只上传 ZIP，也不要额外套一层文件夹。
4. 打开仓库的 **Settings → Pages**。
5. 在 **Build and deployment** 中选择 **Deploy from a branch**，再选择 **main** 与 **/(root)**，点击 **Save**。
6. 等待部署完成，使用页面上的 **Visit site** 打开网站。发布可能需要约 10 分钟。
7. 在 iPhone 的 Safari 中打开这个已发布的网址。首页可以分别进入孩子／家长的中文或英文指南。

更新已有网站时，上传新版文件并覆盖同名文件，提交后等待重新部署，再刷新网站。保留全部文件名和它们之间的相对位置。

### 中文使用说明

- 孩子指南保留紫色、玫瑰色系；家长指南保留青绿色系。
- 同一指南的中英文版在同一浏览器、同一网站地址下共用进度和笔记；已有笔记不会自动翻译。孩子和家长指南各自保存记录。
- 笔记不会自动跨设备同步。更换使用地址前，请先导出备份，再到新地址导入。不要把包含私人笔记的备份文件上传到公开仓库。
- 中文版翻译了指南文字和视频观看提示；原视频音频不变，中文字幕是否可用由发布者决定。
- 内嵌播放仍可能受到视频提供方限制；每个观看页面都保留外部来源链接。
- 如果 iPhone 文件预览无法运行互动功能，完整阅读版仍可显示。互动小测、进度记录和内嵌播放请使用已发布的网页。

Prepared November 20, 2026 / 更新于 2026 年 11 月 20 日。This package has not been published on your behalf / 本压缩包尚未代你发布到网站。
