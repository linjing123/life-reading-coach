# life-reading-coach

把《高性价比人生指南》《人生进阶指南》《人情世故指南》和《投资入门指南》中的相关内容，组织成每天可以阅读、实践和复盘的个人成长计划。

它适合想改善钱、时间、学习和生活边界，却不想自己翻目录、排计划的人。

## 它会做什么

- 根据你当前想解决的问题选择真实原文；
- 以《高性价比人生指南》为主线，搭配同主题补充阅读；
- 保留原文链接，说明重点、适用条件和来源；
- 设计一个当天可以完成的约5分钟练习；
- 记录已推送内容，根据反馈调整后续阅读；
- 每7期回顾一次，漏读不要求补齐。

## 安装

### 使用 GitHub CLI

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --url https://github.com/linjing123/life-reading-coach/tree/main/life-reading-coach
```

### 手动安装

将 `life-reading-coach/` 文件夹复制到：

```text
~/.agents/skills/
```

项目内使用时，也可以复制到项目目录的 `.agents/skills/`。

## 开始使用

在 Codex 中输入：

```text
使用 life-reading-coach，帮我从钱开始。今天先读什么？给我原文和一个5分钟练习。
```

也可以指定目标：

```text
我最近总是拖延。请以《高性价比人生指南》为主线，搭配《人生进阶指南》，给我今天的阅读和行动练习。
```

## 定时推送

Skill负责选文、练习和阅读进度。它本身不会在后台自动发送消息。每天定时推送需要在使用环境中另行配置自动化任务。

## 来源

- [高性价比人生指南](https://github.com/eternity4719/HowToLiveBetter)
- [人生进阶指南](https://github.com/byoungd/up)
- [人情世故指南](https://github.com/kkk-bot/HowToGetAlong)
- [投资入门指南](https://github.com/xuchonglang/investing-for-beginners)

本仓库只包含自编 Skill 方法、来源链接和空白进度模板，不包含上述项目的正文或用户私人进度。各来源的许可和使用范围以原项目当前说明为准。
