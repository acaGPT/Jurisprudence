# Jurisprudence 法理学

《法理学》课程教学资料

## Wiki 指引

课程大纲已迁出 Code 页面，改由本仓库的 GitHub Wiki 作为唯一维护位置：

- [Wiki 首页](https://github.com/acaGPT/Jurisprudence/wiki) — 页面导航入口
- [课程大纲](https://github.com/acaGPT/Jurisprudence/wiki/%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2) — 中英双语完整大纲，含课程说明、学习成果、授课与考核方式，以及各讲核心议题、延伸阅读与经典文献

在本地编辑并发布 wiki 页面：

```bash
git clone https://github.com/acaGPT/Jurisprudence.wiki.git
cd Jurisprudence.wiki          # wiki 仓库的默认分支是 master
# 编辑页面后提交
git commit -am "docs: 更新课程大纲" && git push origin master
```

注意事项：

- 每个 `.md` 文件对应一个 wiki 页面，文件名即页面名；`Home.md` 是首页。
- `*.wiki.git` 仓库只有在用户在 wiki 页面 UI 创建过第一个页面之后才会生成，
  在此之前 clone 或 push 会报 `Repository not found`。
- 中文页面名的站内链接需百分号编码，例如 `.../wiki/%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2`。

## 版本

- v1.1.0 — 大纲迁出 Code 页面、改由 Wiki 维护；README 增加 Wiki 指引
- v1.0.4 — 重复文献替换为更贴合各讲主题的经典作品（链接均经核验）
- v1.0.3 — 第 25 讲描述改为以形式主义—现实主义论战为主旨
- v1.0.2 — 扩充第 25 讲：重写双语描述，新增 Langdell、Pound《机械法理学》、Grey、Schauer 等 4 条形式主义侧经典文献（链接均已核验）
- v1.0.1 — 补全 4 处未译成英文的中文语句，并补全第 25 讲（法律形式主义对法律现实主义）完整条目
- v1.0.0 — 收录《法理学》双语课程大纲
