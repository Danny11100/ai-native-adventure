# 🚀 AI Native 冒险 | AI Native Adventure

一个轻量化的 AI 熟练度测试游戏，用 9 道场景化题目评估你的 AI 使用习惯，生成个性化等级报告。

## 🎮 功能特性

- **9 道场景化题目** - 从使用频率到工作流整合，覆盖 AI Native 核心维度
- **5 级评价体系** - AI 难民 → 散户 → 包工头 → 合伙人 → 原住民
- **动态分享海报** - Canvas 生成带二维码的个性化结果图
- **响应式设计** - 移动端优先，适配微信内置浏览器

## 🎨 设计思路

**"星际漫游者的 AI 日记"** - 受《小王子》启发，将测试包装成一场穿越 9 颗星球的冒险。深蓝夜空配色 + 手绘感 UI，区别于传统科技风的冰冷感。

**传播设计：**
- 等级命名使用职场自嘲梗（"包工头"、"合伙人"），降低分享心理门槛
- 结果文案自带社交货币，适合朋友圈传播
- 隐藏成就系统（根据答题路径触发特殊称号）

## 🛠 技术实现

- **纯前端**：HTML5 + CSS3 + Vanilla JS，无后端依赖
- **零成本部署**：Cloudflare Pages / Vercel 静态托管
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
