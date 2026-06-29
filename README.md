# UI/UX Pro Max 中文教程网站

一个基于 [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) 项目的中文教程网站，为 AI 编码助手提供专业级设计智能。本站已同步上游 README 的 v2.0 重大更新。

![UI/UX Pro Max](https://img.shields.io/badge/UI%2FUX-Pro%20Max-v2.0-6366f1?style=for-the-badge)
![Reasoning Rules](https://img.shields.io/badge/reasoning_rules-161-green?style=for-the-badge)
![UI Styles](https://img.shields.io/badge/UI_styles-67-purple?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📖 项目简介

本网站是 UI/UX Pro Max 技能库的中文教程站点，面向中文开发者介绍安装、使用方式和 v2.0 的智能设计系统生成能力。UI/UX Pro Max 是一个面向 AI 编码助手的设计智能技能，可帮助 Claude Code、Cursor、Windsurf、Antigravity、Codex CLI、GitHub Copilot、Kiro 等工具在生成界面时做出更专业的设计决策。

## 🆕 v2.0 重大更新

### 智能设计系统生成器

v2.0 的旗舰能力是 **Design System Generator**：AI 会分析项目需求，并在几秒内输出定制化设计系统，包括：

- 推荐页面结构与转化模式
- 最匹配的 UI 风格
- 行业专属配色方案
- 字体组合与情绪定位
- 关键动效与交互建议
- 需要避免的反模式
- 交付前 UX / Accessibility 检查清单

### 设计系统生成流程

1. **用户请求**：例如“为我的美容水疗中心构建一个着陆页”。
2. **多域检索**：并行匹配产品类型、UI 风格、配色、落地页模式和字体组合。
3. **推理引擎**：结合产品分类规则、BM25 排名、行业反模式与条件规则进行筛选。
4. **完整输出**：生成 Pattern、Style、Colors、Typography、Effects、Anti-patterns 与 Checklist。

### 161 条行业推理规则

推理规则覆盖以下方向：

| 类别 | 示例 |
| --- | --- |
| Tech & SaaS | SaaS、Micro SaaS、B2B Service、Developer Tool、AI/Chatbot Platform、Cybersecurity |
| Finance | Fintech/Crypto、Banking、Insurance、Personal Finance Tracker、Invoice & Billing |
| Healthcare | Medical Clinic、Pharmacy、Dental、Veterinary、Mental Health、Medication Reminder |
| E-commerce | General、Luxury、Marketplace、Subscription Box、Food Delivery |
| Services | Beauty/Spa、Restaurant、Hotel、Legal、Home Services、Booking & Appointment |
| Creative | Portfolio、Agency、Photography、Gaming、Music Streaming、Photo/Video Editor |
| Lifestyle | Habit Tracker、Recipe & Cooking、Meditation、Weather、Diary、Mood Tracker |
| Emerging Tech | Web3/NFT、Spatial Computing、Quantum Computing、Autonomous Drone Fleet |

## 🎯 核心能力

| 特性 | 数量 | 说明 |
| --- | --- | --- |
| UI 风格 | 67 种 | Glassmorphism、Claymorphism、Minimalism、Brutalism、AI-Native UI、Spatial UI 等 |
| 配色方案 | 161 种 | 与 161 个产品类型对齐的行业专属调色板 |
| 字体配对 | 57 种 | 精选 Google Fonts 排版组合 |
| 图表类型 | 25 种 | 仪表盘和数据分析可视化建议 |
| 技术栈 | 22 种 | React、Next.js、Astro、Vue、Nuxt、Angular、Laravel、SwiftUI、Flutter、JavaFX、WinUI 等 |
| UX 准则 | 99 条 | 最佳实践、反模式和无障碍规则 |
| 推理规则 | 161 条 | 用于智能生成行业专属设计系统 |

## 🚀 快速开始

### Claude Marketplace（Claude Code）

```text
/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```

### CLI 安装（推荐）

```bash
# 全局安装 CLI 工具
npm install -g ui-ux-pro-max-cli

# 进入你的项目目录
cd /path/to/your/project

# 为指定 AI 助手安装技能
uipro init --ai claude      # Claude Code
uipro init --ai cursor      # Cursor
uipro init --ai windsurf    # Windsurf
uipro init --ai antigravity # Antigravity
uipro init --ai copilot     # GitHub Copilot
uipro init --ai kiro        # Kiro
uipro init --ai codex       # Codex CLI
uipro init --ai qoder       # Qoder
uipro init --ai roocode     # Roo Code
uipro init --ai gemini      # Gemini CLI
uipro init --ai trae        # Trae
uipro init --ai opencode    # OpenCode
uipro init --ai continue    # Continue
uipro init --ai codebuddy   # CodeBuddy
uipro init --ai droid       # Droid (Factory)
uipro init --ai kilocode    # KiloCode
uipro init --ai warp        # Warp
uipro init --ai augment     # Augment
uipro init --ai all         # 所有助手
```

> 当前 npm 包名是 `ui-ux-pro-max-cli`，安装后仍使用 `uipro` 命令。旧的 `uipro-cli` 已过时，不建议继续使用。

### 全局安装

```bash
uipro init --ai claude --global   # 安装到 ~/.claude/skills/
uipro init --ai cursor --global   # 安装到 ~/.cursor/skills/
```

### 其他 CLI 命令

```bash
uipro versions              # 列出可用版本
uipro update                # 从已安装 CLI 包刷新技能文件
uipro init --offline        # 使用随包模板离线安装
uipro uninstall             # 卸载自动检测到的平台
uipro uninstall --ai claude # 卸载指定平台
uipro uninstall --global    # 移除全局安装
```

## ✅ 前置条件

搜索脚本需要 Python 3.x：

```bash
python3 --version
brew install python3                         # macOS
sudo apt update && sudo apt install python3  # Ubuntu/Debian
winget install Python.Python.3.12            # Windows
```

## 💬 使用方式

### Skill Mode（自动激活）

支持：Claude Code、Cursor、Windsurf、Antigravity、Codex CLI、Continue、Gemini CLI、OpenCode、Qoder、CodeBuddy、Droid (Factory)、KiloCode、Warp、Augment。

直接自然语言描述需求即可：

```text
Build a landing page for my SaaS product
```

> Trae 用户请先切换到 **SOLO** 模式，再提出 UI/UX 请求。

### Workflow Mode（斜杠命令）

支持：Kiro、GitHub Copilot、Roo Code、KiloCode。

```text
/ui-ux-pro-max Build a landing page for my SaaS product
```

### 示例提示词

```text
Build a landing page for my SaaS product
Create a dashboard for healthcare analytics
Design a portfolio website with dark mode
Make a mobile app UI for e-commerce
Build a fintech banking app with dark theme
```

## 🧠 设计系统命令（高级）

```bash
# 生成 ASCII 设计系统输出
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "beauty spa wellness" --design-system -p "Serenity Spa"

# 生成 Markdown 设计系统输出
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fintech banking" --design-system -f markdown

# 按领域检索
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "glassmorphism" --domain style
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "elegant serif" --domain typography
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "dashboard" --domain chart

# 按技术栈检索指南
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "form validation" --stack react
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "responsive layout" --stack html-tailwind
```

### 持久化设计系统

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp"
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp" --page "dashboard"
```

生成结构：

```text
design-system/
├── MASTER.md
└── pages/
    └── dashboard.md
```

## 🛠️ 技术栈

本站本身使用：

- **HTML5**：语义化页面结构
- **CSS3**：Grid、Flexbox、Custom Properties、玻璃拟态和响应式设计
- **JavaScript**：原生 ES6+ 交互逻辑
- **Font Awesome**：图标库
- **Google Fonts**：Inter 与 JetBrains Mono

## 📂 项目结构

```text
ui-ux-pro-max-skill-cn/
├── index.html      # 中文教程主页面
├── style.css       # 样式文件
├── script.js       # 交互脚本
├── README.md       # 中文项目说明
├── README_ZH.md    # 旧版中文说明
├── CNAME           # GitHub Pages 自定义域名
└── LICENSE         # MIT 许可证
```

## ✨ 页面更新内容

- 更新首页文案和统计数据到 v2.0：67 UI 风格、161 配色、57 字体、25 图表、22 技术栈、161 推理规则。
- 新增“智能设计系统生成器”介绍区块。
- 新增 Claude Marketplace 安装方式。
- 将 CLI 包名更新为 `ui-ux-pro-max-cli`。
- 扩展支持平台、技术栈、使用方式和高级设计系统命令。

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

原始 UI/UX Pro Max 项目：[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)

---

<p align="center">
  <strong>为 AI 时代打造的卓越设计技能库</strong>
</p>
