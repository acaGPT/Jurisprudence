# Jurisprudence 法理学

《法理学》课程教学资料 by iLINGBIN

## Wiki 指引

本仓库的 GitHub Wiki 作为唯一维护位置：

- [Wiki 首页](https://github.com/acaGPT/Jurisprudence/wiki) — 页面导航入口
- [课程大纲](https://github.com/acaGPT/Jurisprudence/wiki/%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2) — 中英双语完整大纲，含课程说明、学习成果、授课与考核方式，以及各讲核心议题、延伸阅读与经典文献

在本地编辑并发布 wiki 页面：

```bash
git clone https://github.com/acaGPT/Jurisprudence.wiki.git
cd Jurisprudence.wiki          # wiki 仓库的默认分支是 master
# 编辑页面后提交
git commit -am "docs: 更新课程大纲" && git push origin master
```

## 配套工具仓库

为大纲中附有作者介绍链接的条目自动配设肖像小头像的流水线（取图、核验、插入、署名），
独立维护于：

- [jurisprudence-syllabus-portraits](https://github.com/acaGPT/jurisprudence-syllabus-portraits) — 肖像抓取与插入工具链（Python）

## 许可证

本项目以 MIT 许可证发布，版权归 acaGPT（2026）所有。许可证全文见 [LICENSE](LICENSE)。

## 版本

- v1.2.0 — 新增 MIT 许可证（版权 2026 acaGPT）；README 增加许可证说明

- v1.1.0 — 大纲迁出 Code 页面、改由 Wiki 维护；README 增加 Wiki 指引
- v1.0.4 — 重复文献替换为更贴合各讲主题的经典作品（链接均经核验）
- v1.0.3 — 第 25 讲描述改为以形式主义—现实主义论战为主旨
- v1.0.2 — 扩充第 25 讲：重写双语描述，新增 Langdell、Pound《机械法理学》、Grey、Schauer 等 4 条形式主义侧经典文献（链接均已核验）
- v1.0.1 — 补全 4 处未译成英文的中文语句，并补全第 25 讲（法律形式主义对法律现实主义）完整条目
- v1.0.0 — 收录《法理学》双语课程大纲
