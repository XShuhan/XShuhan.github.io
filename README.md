# Shuhan Xue — Personal Homepage

地址：https://xshuhan.github.io/

纯 HTML/CSS 学术主页，无构建步骤。编辑 `index.html` 更新身份、简介和论文；编辑 `style.css` 调整样式。

## 本地预览

在此目录执行 `python3 -m http.server 8765 --bind 127.0.0.1`，打开 http://127.0.0.1:8765/ 。也可以直接打开 `index.html`。

## GitHub Pages

仓库：`XShuhan/XShuhan.github.io`。使用 `main` 分支根目录发布，`.nojekyll` 让 GitHub 直接托管静态文件。

## 设计与选型

- 推荐本主页的轻量静态实现：目前内容以简介和两篇论文为主，修改直接，无需安装依赖。
- [Jon Barron](https://jonbarron.info/)：参考其简介、联系方式、论文缩略图与论文链接的内容组织。本页从头实现，并未复制其源代码。
- [Academic Pages](https://academicpages.github.io/)：更适合需要教学、报告等多页面分类的主页。
- [al-folio](https://alshedivat.github.io/al-folio/)：更适合同时维护博客、丰富履历和多个项目的主页。
- [GitHub Pages 官方文档](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)：可托管 HTML/CSS，个人站仓库须命名为 `<owner>.github.io`，公共仓库可使用 GitHub Free。

## 信息与素材来源

2026-10-11 核实。身份、邮箱、Scholar 个人页链接由本人提供。研究简介是根据公开论文拟定的文案。

- Scholar：https://scholar.google.com/citations?user=qpQ7JBQAAAAJ&hl=zh-CN （通过浏览器核实论文列表；不在主页展示动态引用指标）
- GitHub：https://github.com/XShuhan
- PhAI Labs：https://phai-labs.com/
- ScienceBuddy：https://arxiv.org/abs/2609.17523
- ScienceBuddy 代码：https://github.com/Gen-Verse/ScienceBuddy
- PAST-Bench：https://arxiv.org/abs/2608.04003
- PAST-Bench 代码：https://github.com/Gen-Verse/PAST-Bench

两篇论文目前按 arXiv 预印本展示，不填写未确认的录用信息。图片来自上述公开项目的原始素材：

- `assets/sciencebuddy-overview.svg`：https://raw.githubusercontent.com/Gen-Verse/ScienceBuddy/main/assets/sciencebuddy-overview.svg
- `assets/past-bench-overview.png`：https://raw.githubusercontent.com/Gen-Verse/PAST-Bench/main/assets/past_bench_overview.png

头像和浏览器标签页图标均使用本人提供的插画原图 `assets/avatar.jpg`。未添加未经本人提供的教育经历、导师、奖项或 CV。
