# competitor-teardown

把一个竞品/对标产品拆成一份带证据的深度拆解报告（HTML artifact）——公开面调研 → 登录态后台逐路由遍历 → 真实付费/生成实测，逐条标注保真度，并给出对自家产品的可行动清单。凡是用户给出一个产品（URL、产品名、"这家"）并说"拆解一下""看看这个产品""分析下竞品""研究一下他们怎么做的""扒一下他们的定价/功能/增长""对标一下我们"，或者贴出竞品官网要求出调研文档时，务必使用本 skill——即使用户没说"竞品"二字。也适用于"帮我看看他们后台长什么样""他们那个功能怎么实现的""他们凭什么收这么贵"。不用于单支视频的拉片（那是 video-lapian）、不用于自家功能的数据复盘（那是 tapvid-feature-analysis）、不用于定义理想产出标准（那是 ideal-state-research）。

一个 Claude Code skill。来自合集 [claude-skills](https://github.com/Minerva67/claude-skills)。

## 安装

```bash
git clone https://github.com/Minerva67/competitor-teardown.git ~/.claude/skills/competitor-teardown
```

装好后在 Claude Code 里输入 `/competitor-teardown`，或者直接描述任务，符合条件时会自动触发。

## 文件

```
SKILL.md
references/evidence-playbook.md
references/report-structure.md
scripts/screenshot-pipeline.js
```
