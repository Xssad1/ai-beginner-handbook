# AI 入门手册

面向零基础学习者的中文 AI 学习网页，支持电脑和手机阅读。

- 32 个知识页：基础概念、大模型、提示词、工具、开源、编程与项目实践。
- 57 个术语，附中文释义和例子。
- 30 天行动计划、16 周学习路线、12 道自测与解析。
- 翻页、全文搜索、收藏和本机进度保存。

在线阅读：[GitHub Pages](https://xssad1.github.io/ai-beginner-handbook/)

国内备用入口：[上码阅读版](https://iris-accq.upma.page/)。

## 发布到 GitHub Pages

1. 在自己的 GitHub 账号创建公开仓库，例如 `ai-beginner-handbook`。
2. 将本目录内的文件上传到仓库根目录，确保 `index.html` 直接位于根目录。
3. 打开 **Settings → Pages**。
4. 在 **Build and deployment → Source** 选择 **Deploy from a branch**。
5. 选择 **main** 分支和 **/(root)** 文件夹，点击 **Save**。
6. 等待部署完成，在 Pages 设置页点击 **Visit site** 获取实际网址。

项目网站通常使用 `https://你的用户名.github.io/ai-beginner-handbook/`。
`用户名.github.io` 是域名格式说明，实际网址以 GitHub Pages 显示为准。

[GitHub Pages 官方发布说明](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

## 文件说明

| 文件 | 作用 |
| --- | --- |
| `index.html` | 网页入口与阅读界面 |
| `style.css` | 排版与手机适配 |
| `data.js` | 课程、词典、工具、学习路线与测验内容 |
| `app.js` | 翻页、搜索、收藏、打卡和自测逻辑 |
| `favicon.svg` | 网页图标 |
| `.nojekyll` | 让 GitHub Pages 直接发布静态资源 |

页面不依赖外部脚本、字体或在线 AI 接口。外部工具和参考资料在读者点击时打开。
阅读记录只保存在当前浏览器，不会上传到 GitHub，也不会跨设备同步。

## 内容来源

基于用户提供的 2026-11-20 对话导出重新整理。原导出缺失的词典、每日任务与测验已重新编写，网页中有明确说明。仓库不包含原始 PDF、会话标识、账户信息或托管平台凭据。

## 本地预览与维护

在此目录运行 `python3 -m http.server 8000`，然后在浏览器打开 `http://localhost:8000`。
编辑 `data.js` 可修改学习内容；修改后提交到发布分支会触发网站更新。
