# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

---

## [Unreleased]

- 初始化仓库：README 说明游戏以 fiction 为原型，创始人已授权给公司。
- 新增 `docs/forms.md`：五种候选形态（互动视觉小说、事业经营数值、舆论场模拟、重生循环、LLM 对手戏）逐条对照三条准入条件；README 文档表与意图仓链接同步。
- `docs/forms.md` 定形态 1 + 2（分支叙事 × 事业经营数值）为首选组合：心理与情感的变化推动事业的变化，这条因果是剧情暗线。
- 部署上线：新增 `.github/workflows/deploy-site.yml`，push main 即发布 `src/` 静态页到 https://love.game.quanttide.com/（OSS 桶 `qtgame-love-site` + CDN `love.game.quanttide.com`，照 qtgame 部署惯例）。
