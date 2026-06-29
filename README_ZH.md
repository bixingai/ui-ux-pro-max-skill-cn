# [UI UX Pro Max](https://uupm.cc)

<p align="center">
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/releases"><img src="https://img.shields.io/github/v/release/nextlevelbuilder/ui-ux-pro-max-skill?style=for-the-badge&color=blue" alt="GitHub Release"></a>
  <img src="https://img.shields.io/badge/reasoning_rules-161-green?style=for-the-badge" alt="161 Reasoning Rules">
  <img src="https://img.shields.io/badge/UI_styles-67-purple?style=for-the-badge" alt="67 UI Styles">
  <img src="https://img.shields.io/badge/python-3.x-yellow?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.x">
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/blob/main/LICENSE"><img src="https://img.shields.io/github/license/nextlevelbuilder/ui-ux-pro-max-skill?style=for-the-badge&color=green" alt="License"></a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/ui-ux-pro-max-cli"><img src="https://img.shields.io/npm/v/ui-ux-pro-max-cli?style=flat-square&logo=npm&label=CLI" alt="npm"></a>
  <a href="https://www.npmjs.com/package/ui-ux-pro-max-cli"><img src="https://img.shields.io/npm/dm/ui-ux-pro-max-cli?style=flat-square&label=downloads" alt="npm downloads"></a>
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/stargazers"><img src="https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat-square&logo=github" alt="GitHub stars"></a>
  <a href="https://paypal.me/uiuxpromax"><img src="https://img.shields.io/badge/PayPal-Support%20Development-00457C?style=flat-square&logo=paypal&logoColor=white" alt="PayPal"></a>
</p>

一款为跨平台和框架构建专业 UI/UX 提供设计智能的 AI 技能。

<p align="center">
  <a href="https://uupm.cc">
    <img src="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/raw/main/screenshots/website.png" alt="UI UX Pro Max" width="800">
  </a>
</p>

<p align="center">
  <b>如果你觉得这个项目有用，欢迎支持项目发展：</b><br><br>
  <a href="https://paypal.me/uiuxpromax"><img src="https://img.shields.io/badge/PayPal-Donate-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal Donate"></a>
</p>

<p align="center">
  <i>其他项目</i><br>
  <a href="https://nextlevelbuilder.io">NextLevelBuilder.io</a> | <a href="https://goclaw.sh">GoClaw.sh</a> | <a href="https://claudekit.cc">ClaudeKit.cc</a> | <a href="https://tose.sh">TOSE.sh</a>
</p>

## v2.0 新特性

### 智能设计系统生成

v2.0 的旗舰功能是 **Design System Generator（设计系统生成器）**——一个由 AI 驱动的推理引擎，可以分析你的项目需求，并在数秒内生成完整且量身定制的设计系统。

```
+----------------------------------------------------------------------------------------+
|  TARGET: Serenity Spa - RECOMMENDED DESIGN SYSTEM                                      |
+----------------------------------------------------------------------------------------+
|                                                                                        |
|  PATTERN: Hero-Centric + Social Proof                                                  |
|     Conversion: Emotion-driven with trust elements                                     |
|     CTA: Above fold, repeated after testimonials                                       |
|     Sections:                                                                          |
|       1. Hero                                                                          |
|       2. Services                                                                      |
|       3. Testimonials                                                                  |
|       4. Booking                                                                       |
|       5. Contact                                                                       |
|                                                                                        |
|  STYLE: Soft UI Evolution                                                              |
|     Keywords: Soft shadows, subtle depth, calming, premium feel, organic shapes        |
|     Best For: Wellness, beauty, lifestyle brands, premium services                     |
|     Performance: Excellent | Accessibility: WCAG AA                                    |
|                                                                                        |
|  COLORS:                                                                               |
|     Primary:    #E8B4B8 (Soft Pink)                                                    |
|     Secondary:  #A8D5BA (Sage Green)                                                   |
|     CTA:        #D4AF37 (Gold)                                                         |
|     Background: #FFF5F5 (Warm White)                                                   |
|     Text:       #2D3436 (Charcoal)                                                     |
|     Notes: Calming palette with gold accents for luxury feel                           |
|                                                                                        |
|  TYPOGRAPHY: Cormorant Garamond / Montserrat                                           |
|     Mood: Elegant, calming, sophisticated                                              |
|     Best For: Luxury brands, wellness, beauty, editorial                               |
|     Google Fonts: https://fonts.google.com/share?selection.family=...                  |
|                                                                                        |
|  KEY EFFECTS:                                                                          |
|     Soft shadows + Smooth transitions (200-300ms) + Gentle hover states                |
|                                                                                        |
|  AVOID (Anti-patterns):                                                                |
|     Bright neon colors + Harsh animations + Dark mode + AI purple/pink gradients       |
|                                                                                        |
|  PRE-DELIVERY CHECKLIST:                                                               |
|     [ ] No emojis as icons (use SVG: Heroicons/Lucide)                                 |
|     [ ] cursor-pointer on all clickable elements                                       |
|     [ ] Hover states with smooth transitions (150-300ms)                               |
|     [ ] Light mode: text contrast 4.5:1 minimum                                        |
|     [ ] Focus states visible for keyboard nav                                          |
|     [ ] prefers-reduced-motion respected                                               |
|     [ ] Responsive: 375px, 768px, 1024px, 1440px                                       |
|                                                                                        |
+----------------------------------------------------------------------------------------+
```

### 设计系统生成的工作原理

```
┌─────────────────────────────────────────────────────────────────┐
│  1. USER REQUEST                                                │
│     "Build a landing page for my beauty spa"                    │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  2. MULTI-DOMAIN SEARCH (5 parallel searches)                   │
│     • Product type matching (161 categories)                    │
│     • Style recommendations (67 styles)                         │
│     • Color palette selection (161 palettes)                    │
│     • Landing page patterns (24 patterns)                       │
│     • Typography pairing (57 font combinations)                 │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  3. REASONING ENGINE                                            │
│     • Match product → UI category rules                         │
│     • Apply style priorities (BM25 ranking)                     │
│     • Filter anti-patterns for industry                         │
│     • Process decision rules (JSON conditions)                  │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  4. COMPLETE DESIGN SYSTEM OUTPUT                               │
│     Pattern + Style + Colors + Typography + Effects             │
│     + Anti-patterns to avoid + Pre-delivery checklist           │
└─────────────────────────────────────────────────────────────────┘
```

### 161 条行业专属推理规则

推理引擎包含以下领域的专门规则：

| 分类 | 示例 |
|----------|----------|
| **科技与 SaaS** | SaaS、Micro SaaS、B2B 服务、开发者工具 / IDE、AI/聊天机器人平台、网络安全平台 |
| **金融** | 金融科技/加密货币、银行、保险、个人财务追踪、发票与账单工具 |
| **医疗健康** | 诊所、药房、牙科、兽医、心理健康、用药提醒 |
| **电子商务** | 通用电商、奢侈品、P2P 市场、订阅盒、外卖配送 |
| **服务业** | 美容/水疗、餐厅、酒店、法律、家政服务、预约与排期 |
| **创意** | 作品集、代理机构、摄影、游戏、音乐流媒体、图片/视频编辑器 |
| **生活方式** | 习惯追踪、食谱与烹饪、冥想、天气、日记、情绪追踪 |
| **新兴技术** | Web3/NFT、空间计算、量子计算、自主无人机队 |

每条规则包含：
- **推荐模式** - 着陆页结构
- **风格优先级** - 最匹配的 UI 风格
- **色彩氛围** - 适合行业的配色方案
- **排版氛围** - 字体个性匹配
- **关键效果** - 动画与交互
- **反模式** - 不应该做什么（例如，银行产品不要使用“AI 紫/粉渐变”）

## 特性

- **67 种 UI 风格** - 玻璃拟态 (Glassmorphism)、粘土拟态 (Claymorphism)、极简主义 (Minimalism)、野兽派 (Brutalism)、新拟态 (Neumorphism)、Bento Grid、深色模式、AI-Native UI 等
- **161 种配色方案** - 与 161 种产品类型一一对应的行业专属色板
- **57 种字体配对** - 精选排版组合，包含 Google Fonts 导入
- **25 种图表类型** - 用于仪表板和分析的建议
- **22 种技术栈** - React、Next.js、Astro、Vue、Nuxt.js、Nuxt UI、Svelte、SwiftUI、React Native、Flutter、HTML+Tailwind、shadcn/ui、Jetpack Compose、Angular、Laravel、Three.js、JavaFX、WPF、WinUI 3、UWP、Avalonia、Uno Platform
- **99 条 UX 指南** - 最佳实践、反模式和无障碍规则
- **161 条推理规则** - 行业专属设计系统生成（v2.0 新增）

### 可用风格（67）

<details>
<summary><b>通用风格（49）</b></summary>

| # | 风格 | 最适合 |
|---|-------|----------|
| 1 | Minimalism & Swiss Style | 企业应用、仪表板、文档 |
| 2 | Neumorphism | 健康/疗愈应用、冥想平台 |
| 3 | Glassmorphism | 现代 SaaS、金融仪表板 |
| 4 | Brutalism | 设计作品集、艺术项目 |
| 5 | 3D & Hyperrealism | 游戏、产品展示、沉浸式体验 |
| 6 | Vibrant & Block-based | 初创公司、创意机构、游戏 |
| 7 | Dark Mode (OLED) | 夜间模式应用、编程平台 |
| 8 | Accessible & Ethical | 政府、医疗、教育 |
| 9 | Claymorphism | 教育应用、儿童应用、SaaS |
| 10 | Aurora UI | 现代 SaaS、创意机构 |
| 11 | Retro-Futurism | 游戏、娱乐、音乐平台 |
| 12 | Flat Design | Web 应用、移动应用、初创 MVP |
| 13 | Skeuomorphism | 旧式应用、游戏、高端产品 |
| 14 | Liquid Glass | 高端 SaaS、高端电商 |
| 15 | Motion-Driven | 作品集网站、叙事平台 |
| 16 | Micro-interactions | 移动应用、触屏 UI |
| 17 | Inclusive Design | 公共服务、教育、医疗 |
| 18 | Zero Interface | 语音助手、AI 平台 |
| 19 | Soft UI Evolution | 现代企业应用、SaaS |
| 20 | Neubrutalism | Z 世代品牌、初创公司、Figma 风格 |
| 21 | Bento Box Grid | 仪表板、产品页、作品集 |
| 22 | Y2K Aesthetic | 时尚品牌、音乐、Z 世代 |
| 23 | Cyberpunk UI | 游戏、科技产品、加密应用 |
| 24 | Organic Biophilic | 疗愈应用、可持续品牌 |
| 25 | AI-Native UI | AI 产品、聊天机器人、Copilot |
| 26 | Memphis Design | 创意机构、音乐、年轻品牌 |
| 27 | Vaporwave | 音乐平台、游戏、作品集 |
| 28 | Dimensional Layering | 仪表板、卡片布局、模态框 |
| 29 | Exaggerated Minimalism | 时尚、建筑、作品集 |
| 30 | Kinetic Typography | Hero 区块、营销网站 |
| 31 | Parallax Storytelling | 品牌叙事、产品发布 |
| 32 | Swiss Modernism 2.0 | 企业网站、建筑、编辑出版 |
| 33 | HUD / Sci-Fi FUI | 科幻游戏、航天科技、网络安全 |
| 34 | Pixel Art | 独立游戏、复古工具、创意项目 |
| 35 | Bento Grids | 产品功能、仪表板、个人网站 |
| 36 | Spatial UI (VisionOS) | 空间计算应用、VR/AR |
| 37 | E-Ink / Paper | 阅读应用、数字报纸 |
| 38 | Gen Z Chaos / Maximalism | Z 世代生活方式、音乐人 |
| 39 | Biomimetic / Organic 2.0 | 可持续科技、生物科技、健康 |
| 40 | Anti-Polish / Raw Aesthetic | 创意作品集、艺术家网站 |
| 41 | Tactile Digital / Deformable UI | 现代移动应用、趣味品牌 |
| 42 | Nature Distilled | 疗愈品牌、可持续产品 |
| 43 | Interactive Cursor Design | 创意作品集、互动体验 |
| 44 | Voice-First Multimodal | 语音助手、无障碍应用 |
| 45 | 3D Product Preview | 电商、家具、时尚 |
| 46 | Gradient Mesh / Aurora Evolved | Hero 区块、背景、创意项目 |
| 47 | Editorial Grid / Magazine | 新闻网站、博客、杂志 |
| 48 | Chromatic Aberration / RGB Split | 音乐平台、游戏、科技 |
| 49 | Vintage Analog / Retro Film | 摄影、音乐/黑胶品牌 |

</details>

<details>
<summary><b>着陆页风格（8）</b></summary>

| # | 风格 | 最适合 |
|---|-------|----------|
| 1 | Hero-Centric Design | 具有强视觉识别的产品 |
| 2 | Conversion-Optimized | 潜客获取、销售页 |
| 3 | Feature-Rich Showcase | SaaS、复杂产品 |
| 4 | Minimal & Direct | 简单产品、应用 |
| 5 | Social Proof-Focused | 服务、B2C 产品 |
| 6 | Interactive Product Demo | 软件、工具 |
| 7 | Trust & Authority | B2B、企业、咨询 |
| 8 | Storytelling-Driven | 品牌、代理机构、非营利组织 |

</details>

<details>
<summary><b>BI/分析仪表板风格（10）</b></summary>

| # | 风格 | 最适合 |
|---|-------|----------|
| 1 | Data-Dense Dashboard | 复杂数据分析 |
| 2 | Heat Map & Heatmap Style | 地理/行为数据 |
| 3 | Executive Dashboard | 高管摘要 |
| 4 | Real-Time Monitoring | 运营、DevOps |
| 5 | Drill-Down Analytics | 详细探索 |
| 6 | Comparative Analysis Dashboard | 并排对比 |
| 7 | Predictive Analytics | 预测、机器学习洞察 |
| 8 | User Behavior Analytics | UX 研究、产品分析 |
| 9 | Financial Dashboard | 金融、会计 |
| 10 | Sales Intelligence Dashboard | 销售团队、CRM |

</details>

## 安装

### 使用 Claude Marketplace（Claude Code）

在 Claude Code 中用两条命令直接安装：

```
/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```

### 使用 CLI（推荐）

```bash
# 全局安装 CLI
npm install -g ui-ux-pro-max-cli

# 进入你的项目目录
cd /path/to/your/project

# 为你的 AI 助手安装
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

npm 包名是 `ui-ux-pro-max-cli`；它仍然会安装 `uipro` 命令。旧的 `uipro-cli` 版本已经过时，不应再用于当前资源。

### 全局安装（对所有项目可用）

```bash
uipro init --ai claude --global   # 安装到 ~/.claude/skills/
uipro init --ai cursor --global   # 安装到 ~/.cursor/skills/
```

### 其他 CLI 命令

```bash
uipro versions              # 列出可用版本
uipro update                # 从已安装的 CLI 包刷新技能文件
uipro init --offline        # 兼容性标志；安装内置模板
uipro uninstall             # 卸载技能（自动检测平台）
uipro uninstall --ai claude # 卸载指定平台
uipro uninstall --global    # 删除全局安装
```

## 前置条件

搜索脚本需要 Python 3.x。

```bash
# 检查 Python 是否已安装
python3 --version

# macOS
brew install python3

# Ubuntu/Debian
sudo apt update && sudo apt install python3

# Windows
winget install Python.Python.3.12
```

## 使用方法

### 技能模式（自动激活）

**支持：** Claude Code、Cursor、Windsurf、Antigravity、Codex CLI、Continue、Gemini CLI、OpenCode、Qoder、CodeBuddy、Droid (Factory)、KiloCode、Warp、Augment

当你请求 UI/UX 工作时，该技能会自动激活。只需自然对话：

```
Build a landing page for my SaaS product
```

> **Trae**：请先切换到 **SOLO** 模式。该技能会在 UI/UX 请求中自动激活。

### 工作流模式（斜杠命令）

**支持：** Kiro、GitHub Copilot、Roo Code、KiloCode

使用斜杠命令调用该技能：

```
/ui-ux-pro-max Build a landing page for my SaaS product
```

### 示例提示词

```
Build a landing page for my SaaS product

Create a dashboard for healthcare analytics

Design a portfolio website with dark mode

Make a mobile app UI for e-commerce

Build a fintech banking app with dark theme
```

### 工作原理

1. **你提出请求** - 请求任何 UI/UX 任务（构建、设计、创建、实现、审查、修复、改进）
2. **生成设计系统** - AI 自动使用推理引擎生成完整设计系统
3. **智能建议** - 根据你的产品类型和要求，找到最匹配的风格、颜色和排版
4. **代码生成** - 使用正确的颜色、字体、间距和最佳实践实现 UI
5. **交付前检查** - 对常见 UI/UX 反模式进行验证

### 支持的技术栈

该技能为以下技术栈提供特定指南：

| 分类 | 技术栈 |
|----------|--------|
| **Web (HTML)** | HTML + Tailwind（默认） |
| **React 生态** | React、Next.js、shadcn/ui |
| **Vue 生态** | Vue、Nuxt.js、Nuxt UI |
| **Angular** | Angular |
| **PHP** | Laravel（Blade、Livewire、Inertia.js） |
| **其他 Web** | Svelte、Astro、Three.js |
| **桌面端** | JavaFX |
| **iOS** | SwiftUI |
| **Android** | Jetpack Compose |
| **跨平台** | React Native、Flutter |

只需在提示词中提及你偏好的技术栈，或者让其默认使用 HTML + Tailwind。

## 设计系统命令（高级）

如需直接访问设计系统生成器：

> 注意：如果你通过 Continue 安装，请将下面命令中的 `.claude/skills/` 替换为 `.continue/skills/`。对于 Droid (Factory)，请使用 `.factory/skills/`。

```bash
# 生成 ASCII 输出的设计系统
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "beauty spa wellness" --design-system -p "Serenity Spa"

# 生成 Markdown 输出
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fintech banking" --design-system -f markdown

# 按领域搜索
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "glassmorphism" --domain style
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "elegant serif" --domain typography
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "dashboard" --domain chart

# 技术栈专属指南
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "form validation" --stack react
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "responsive layout" --stack html-tailwind
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "tableview binding" --stack javafx
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "atlantafx primer enterprise theme" --stack javafx
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "enterprise tableview density permission" --stack javafx
```

### 持久化设计系统（Master + Overrides 模式）

将你的设计系统保存到文件中，以便在不同会话中进行**分层检索**：

```bash
# 生成并持久化到 design-system/MASTER.md
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp"

# 同时创建页面级覆盖文件
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp" --page "dashboard"
```

这会创建如下 `design-system/` 文件夹结构：

```
design-system/
├── MASTER.md           # 全局事实来源（颜色、排版、间距、组件）
└── pages/
    └── dashboard.md    # 页面级覆盖（只记录与 Master 的差异）
```

**分层检索的工作方式：**
1. 构建特定页面（例如 “Checkout”）时，先检查 `design-system/pages/checkout.md`
2. 如果页面文件存在，它的规则会**覆盖** Master 文件
3. 如果不存在，则只使用 `design-system/MASTER.md`

**上下文感知检索提示词：**
```
I am building the [Page Name] page. Please read design-system/MASTER.md.
Also check if design-system/pages/[page-name].md exists.
If the page file exists, prioritize its rules.
If not, use the Master rules exclusively.
Now, generate the code...
```

## 架构与贡献

### 面向用户

代码库已经重构为使用**基于模板的生成系统**。所有平台专属文件（`.cursor/`、`.windsurf/`、`.kiro/`、`.factory/` 等）现在都由 CLI 动态生成。

**始终使用 CLI 安装：**

```bash
npm install -g ui-ux-pro-max-cli
uipro init --ai <platform>
```

这能确保你获得已安装 CLI 包中内置的最新模板，并为你的 AI 助手生成正确的文件结构。新版本发布时，请先更新 npm 包。

### 面向贡献者

如果你想为本项目做贡献：

```bash
# 1. 克隆仓库
git clone https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.git
cd ui-ux-pro-max-skill

# 2. 理解结构
src/ui-ux-pro-max/           # 单一事实来源（数据、脚本、模板）
cli/                         # CLI 安装器（从模板生成文件）
.claude/                     # Claude Code 技能的本地开发/测试
.factory/                    # Droid (Factory) 技能的本地开发/测试

# 3. 在 src/ui-ux-pro-max/ 中修改
# - data/*.csv              → 数据库文件
# - scripts/*.py            → 搜索引擎与设计系统
# - templates/              → 平台专属模板

# 4. 同步到 CLI 并本地测试
cd cli
npm run sync:assets
npm run check:assets

# 5. 构建并测试 CLI
bun run build
node dist/index.js init --ai claude --offline  # 在临时文件夹中测试

# 6. 创建 PR（不要直接推送到 main）
git checkout -b feat/your-feature
git commit -m "feat: description"
git push -u origin feat/your-feature
gh pr create
```

详见 [CLAUDE.md](CLAUDE.md) 中的开发指南。

## 自动发布

本仓库使用 semantic-release 和 Conventional Commits 自动创建 GitHub Release：

- `dev` 分支会创建 beta GitHub 预发布，例如 `2.6.0-beta.1`。
- `main` 分支会创建正式稳定版 GitHub Release，例如 `2.6.0`。

Release notes 和 `CHANGELOG.md` 会根据 Conventional Commit 消息生成。发布准备阶段会同步 `skill.json`、`.claude-plugin/plugin.json`、`.claude-plugin/marketplace.json`、`cli/package.json` 和 `cli/package-lock.json` 中的版本号。

使用以下提交类型以获得正确的版本递增：

- `fix:` -> patch release
- `feat:` -> minor release
- `feat!:` 或 `BREAKING CHANGE:` -> major release

发布工作流使用默认的 `GITHUB_TOKEN` 创建 GitHub Release，并使用仓库中的 `NPM_TOKEN` secret 将 `ui-ux-pro-max-cli` 发布到 npm。

## 故障排查

### `uipro: unknown command 'uninstall'` 或 `unknown command 'update'`

你安装的 `ui-ux-pro-max-cli` 版本过旧。请更新后重试：

```bash
npm install -g ui-ux-pro-max-cli@latest
uipro uninstall
```

### `uipro uninstall` 提示 “No installed AI skill directories detected”

该技能安装在与你当前运行命令不同的目录中。你可以：

```bash
# 方案 A — 进入最初安装技能的项目根目录
cd /path/to/your/project
uipro uninstall

# 方案 B — 删除全局安装
uipro uninstall --global

# 方案 C — 手动删除
rm -rf .claude/skills/ui-ux-pro-max   # Claude Code
rm -rf .cursor/skills/ui-ux-pro-max   # Cursor
rm -rf .windsurf/skills/ui-ux-pro-max # Windsurf
rm -rf .agents/skills/ui-ux-pro-max   # Antigravity
```

### Claude Marketplace 安装失败并提示 “Zip file contains a symbolic link”

这是 v2.5.1 之前版本中的已知问题。仓库内部曾使用符号链接，某些安装工具无法处理。**解决方法：** 改用 CLI 安装器：

```bash
npm install -g ui-ux-pro-max-cli
uipro init --ai claude
```

或者等待下一个修复该问题的版本发布。

### `npm install -g ui-ux-pro-max-cli` 因权限错误失败

```bash
# macOS/Linux — 使用 Node 版本管理器（推荐）或 sudo
sudo npm install -g ui-ux-pro-max-cli

# 或者使用 npx，无需全局安装
npx ui-ux-pro-max-cli init --ai claude
```

### 运行设计系统命令时找不到 Python

搜索脚本需要 Python 3.x。请根据你的操作系统安装：

```bash
brew install python3        # macOS
sudo apt install python3    # Ubuntu/Debian
winget install Python.Python.3.12  # Windows
```

### 设计系统输出被截断 / 字段不完整

使用 `--max-length` 标志增加（或取消）截断限制：

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS" --domain style --max-length 0
#                                                                               ^ 0 = unlimited
```

---

## 星标历史

[![星标历史图表](https://api.star-history.com/svg?repos=nextlevelbuilder/ui-ux-pro-max-skill&type=Date)](https://star-history.com/#nextlevelbuilder/ui-ux-pro-max-skill&Date)

## 许可证

该项目根据 [MIT 许可证](LICENSE) 获得许可。
