# AI_Romantic_Story_Generator
Generate your tailor-made romantic story
# 命格言情生成器

给两个人配命格，AI 写你们的故事。

## 这是什么

一个用「命理标签组合」驱动的 AI 言情片段生成器。

你选两个角色的命格、关系、职业和触发事件，
AI 生成一段专属的言情故事，输出为可保存分享的好饭。

不需要写一个字。所有维度都是选填的——
哪怕只选了「医生」和「停电」，故事也会自动生成。

## 功能

- **三套命理体系**：天干地支 / MBTI / 星座，三选一
- **命格关系层**：印星（滋养）、七杀（对冲）、比肩（内耗）等，影响两人权力结构
- **25+ 触发事件**：暴雨、末班地铁、多年后重逢、夜里三点的消息……
- **剧情基调自选**：轻甜 / 暧昧 / 虐恋 / BE
- **跳过即随机**：不想选的维度留空，系统随机赋值，卡片标注「命运随机」
- **生成卡片直接保存**：PNG 格式，带二维码，分享即用

## 技术栈

纯前端，单文件 HTML。调用 Claude API 生成故事，Netlify 部署。

## 自部署

1. clone 仓库
2. 在 `index.html` 里把 `YOUR_API_KEY_HERE` 替换成你自己的 Claude API Key
3. 用任意静态托管服务部署即可

## Demo

🔗 [romancegenerator.org](https://romancegenerator.org)
