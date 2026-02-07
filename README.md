# 🚀 AI Native 冒险 | AI Native Adventure

> 当面试官问你「有多 AI Native」，你该怎么回答？9 道题测出你的真实段位。

一个轻量化的 AI 熟练度测试游戏，用 9 道互联网职场场景题评估你的 AI 使用习惯，生成个性化等级报告。

## 💡 灵感来源

**招聘市场的「AI Native」焦虑** - 2024 年开始，「AI Native」成为高频词汇。面试官问「你有多 AI Native」，候选人一脸懵。我们决定把抽象的 buzzword 变成可量化的「游戏化测评」。

**「阿里味」的自嘲文化** - 互联网大厂黑话（对齐、抓手、赋能）本身就是一种社交货币。我们把 AI 使用能力包装成「包工头」「合伙人」等职场梗，降低分享门槛，让测试本身成为话题。

## 🎮 功能特性

- **9 道场景化题目** - 从睁眼第一件事到写周报姿势，覆盖真实工作流
- **5 级评价体系** - AI 难民 → 散户 → 包工头 → 合伙人 → 原住民
- **动态分享海报** - Canvas 生成带二维码的个性化结果图
- **响应式设计** - 移动端优先，适配微信内置浏览器

## 🎨 设计思路

**「面试题的反面」** - 不是考察「你知道多少 AI 知识」，而是测「AI 已经渗透到你生活的哪个角落」。题目设计参考了真实的互联网工作场景，让打工人产生「这说的就是我」的共鸣。

**「大厂黑话」包装** - 等级命名使用职场自嘲梗：
- 难民 = 还没入场
- 散户 = 偶尔试试
- 包工头 = 让 AI 干脏活，我数钱
- 合伙人 = 和硅基生物一起搞事情
- 原住民 = 分不清哪些想法是自己的了

这种「阿里味」的表达方式，天然适合在朋友圈/小红书传播。

## 🛠 技术实现

- **纯前端**：HTML5 + CSS3 + Vanilla JS，无后端依赖
- **零成本部署**：Cloudflare Pages 静态托管
- **数据监控**：Google Analytics 4 自定义事件追踪
- **分享优化**：Open Graph 协议 + Canvas 海报生成

## 🚀 快速开始

```bash
git clone https://github.com/Danny11100/ai-native-adventure.git
cd ai-native-adventure
python -m http.server 8000

📦 部署

Cloudflare Pages（推荐）

1. Fork 本仓库 → Connect to Git → Build command 留空 → 自动部署
Vercel

1. Import Git Repository → Framework Preset: Other → 自动部署
📊 数据埋点

已集成 GA4 事件追踪：

• question_view - 题目曝光
• option_select - 选项点击
• test_complete - 测试完成（含分数/等级）
• share_click - 分享按钮点击
📝 License

MIT License - 可自由修改和商用，保留署名即可。

在线体验：https://ainative.pages.dev (https://ainative.pages.dev/)
