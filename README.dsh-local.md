# obra-superpowers

DSH 技能分组仓：**obra-superpowers**

- **上游**：https://github.com/obra/superpowers
- **结构**：本仓的树 = **上游最新树**（2026-09-13 起对齐），上游的目录层级原样保留。
  本地改动叠在对应文件上（改中文、平台分节、改 frontmatter 的 `name:` 等）——
  `git diff upstream/main` 就是「本机改了什么」的权威答案。
- **本文件**（`README.dsh-local.md`）是本地附加的说明，上游没有；上游的 `README.md` 原样保留。

## 本机改写过的技能

（无——自建技能已全部移入自建仓 `self-dsh`；上游那 14 个技能未做本地改写）

由 `dsh-extensions/install-skill.sh` 软链进 `~/.dsh/skills/`。
