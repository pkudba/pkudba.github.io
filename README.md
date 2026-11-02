# 杜毕安（Bi'an Du）的个人学术主页

**[访问杜毕安的个人主页 · Bi'an Du's Academic Homepage](https://pkudba.github.io/)**

杜毕安（Bi'an Du）是北京大学王选计算机研究所博士生，研究计算机视觉、三维/四维生成与重建、世界模型及物理交互资产生成。主页介绍研究论文、开源项目、教育经历、学术荣誉与联系方式。

Bi'an Du is a Ph.D. student at the Wangxuan Institute of Computer Technology, Peking University. His academic homepage features publications, projects, education, honors, and contact information.

- [Google Scholar](https://scholar.google.com/citations?user=YDvr07IAAAAJ&hl=en)
- [GitHub](https://github.com/pkudba)

## 网站文件

- `index.html`：主页内容、样式、个人资料结构化数据与 Google 网站所有权验证标记。
- `assets/`：个人照片和论文配图。
- `robots.txt`：爬虫访问规则与站点地图地址。
- `sitemap.xml`：主页的规范网址及最近一次重要内容更新日期。

## 发布与维护

网站通过 GitHub Pages 发布，来源为 `main` 分支的仓库根目录。

修改内容后提交并推送，待仓库 Actions 中的 Pages 发布完成，再检查 [正式主页](https://pkudba.github.io/)。

更新正文或结构化数据时，将 `sitemap.xml` 中的 `lastmod` 更新为实际修改日期。更新个人资料时，同时维护 `ProfilePage.dateModified`，使用带时区的 ISO 8601 日期时间。不要仅为了触发抓取而每天刷新日期。

Google Search Console 使用网址前缀 `https://pkudba.github.io/`，站点地图为 `https://pkudba.github.io/sitemap.xml`。保留主页 `<head>` 内已有的 `google-site-verification` 标记，以维持所有权验证。
