# Hi, I'm Omni 👋

🔨 用 AI Agent 造工具的人：投研框架、情报监控站、数据看板、小而美的 Web 组件。
🔨 I build things with AI agents — investment research frameworks, intel dashboards, data pipelines, and small web tools.

---

## 🚀 精选项目 / Featured

- **[serenity-skill](https://github.com/haskaomni/serenity-skill)** · ![stars](https://img.shields.io/github/stars/haskaomni/serenity-skill?style=flat-square)
  把市场信息翻译成可验证投研框架的 Codex 技能库：alpha 假设、贝叶斯内生增长估值、TAM 调整 PEG、DMA 健康指数、买方研报自动生成。
  *Codex skills that translate market information into testable investment research frameworks — alpha hypotheses, Bayesian intrinsic-growth valuation, TAM-adjusted PEG, DMA health index, buy-side memo generation.*

- **[serenity](https://github.com/haskaomni/serenity)** · ![stars](https://img.shields.io/github/stars/haskaomni/serenity?style=flat-square)
  Serenity 信号看板：解析 X 帖子中的 `$SYMBOL` 落库 SQLite，联动 Yahoo 日线行情做可视化。
  *Signal dashboard that parses `$SYMBOL` mentions from X posts into SQLite and visualizes them against Yahoo daily prices.*

- **[stockanalysis](https://github.com/haskaomni/stockanalysis)** · ![stars](https://img.shields.io/github/stars/haskaomni/stockanalysis?style=flat-square)
  stockanalysis.com 的 API 爬虫与逆向工程 API 文档。
  *API crawler & reverse-engineered API docs for stockanalysis.com.*

- **[agentic-cpu](https://github.com/haskaomni/agentic-cpu)** · ![stars](https://img.shields.io/github/stars/haskaomni/agentic-cpu?style=flat-square)
  Codex CLI 的 CPU 火焰图分析：AI Agent 真的需要那么多 CPU 吗？
  *CPU flamegraph analysis of Codex CLI — does an AI agent really need that much CPU?*

- **[blueprint](https://github.com/haskaomni/blueprint)** · ![stars](https://img.shields.io/github/stars/haskaomni/blueprint?style=flat-square) · [Demo](https://haskaomni.github.io/blueprint/)
  用 Three.js 构建的交互式工程蓝图风 3D 车辆查看器。
  *Interactive engineering-blueprint-style 3D vehicle viewer built with Three.js.*

- **[sankey-flow](https://github.com/haskaomni/sankey-flow)** · ![stars](https://img.shields.io/github/stars/haskaomni/sankey-flow?style=flat-square)
  自包含的 `<sankey-flow>` 自定义元素：Mermaid Sankey 布局 + 富标签覆盖层。
  *A self-contained `<sankey-flow>` custom element powered by Mermaid Sankey layouts with rich overlay labels.*

---

## 📈 投研与量化 / Investment Research & Quant

- **[a-share-momentum](https://github.com/haskaomni/a-share-momentum)**
  把 S&P 500 Momentum 指数方法论复刻到 A 股全市场的回测：12-2 动量在 A 股没有超额收益，有效的是冷门股溢价 + 小市值 + 过滤后的反转。
  *Backtest porting the S&P 500 Momentum Index methodology to China's A-share market — why momentum fails there and why low-turnover + small-cap + filtered reversal works.*

- **[opencli-plugin-stockanalysis](https://github.com/haskaomni/opencli-plugin-stockanalysis)**
  stockanalysis.com 的 opencli 插件：走公开页面抓取，无需登录，支持搜索/报价/财报/榜单/新闻。
  *An opencli plugin for stockanalysis.com via public-page scraping — search, quotes, financials, rankings and news, no login required.*

- **[etf-dashboard](https://github.com/haskaomni/etf-dashboard)**
  ETF 核心持仓追踪面板（单页静态站）。
  *Single-page dashboard tracking core ETF holdings.*

- **[memory-price-report](https://github.com/haskaomni/memory-price-report)**
  三星 / 美光 / 海力士 LPDDR5/5X & HBM3/3E/4 现货与合约报价完整汇总（2024.10 – 2026.05）。
  *Compiled spot & contract price report for Samsung / Micron / SK Hynix LPDDR5/5X & HBM3/3E/4 (Oct 2024 – May 2026).*

## 📡 情报监控 / Intel & Monitoring

- **[ai-game-intel](https://github.com/haskaomni/ai-game-intel)** · [Site](https://news.ai-game.com)
  AI 游戏生成赛道情报站：单页静态站 + 智能体每日自动检索、去重、部署与 Telegram 通知。
  *AI game-generation intel site — a static single page maintained by an agent that researches, dedupes, deploys and sends Telegram alerts daily.*

- **[traffic-intel](https://github.com/haskaomni/traffic-intel)** · [Site](https://haskaomni.github.io/traffic-intel/)
  监控 traffic.cv 流量榜单的新品情报站：智能体每日逐个调研新跑出来的产品，生成中文报告并用 VitePress 发布。
  *New-product intel from traffic.cv rankings — an agent researches each breakout product daily and publishes Chinese reports via VitePress.*

- **[trend-radar](https://github.com/haskaomni/trend-radar)**
  持续监控 traffic.cv 月榜，为正在起量的产品自动生成「竞品替代 idea + 规划书」（合规的 alternative/平替 SEO 路线）。
  *Watches traffic.cv monthly boards and auto-generates "alternative-product idea + plan" docs for breakout products, following a compliant alternative-SEO strategy.*

## 🛠️ 工具与组件 / Tools & Components

- **[codex-term](https://github.com/haskaomni/codex-term)**
  在浏览器里从任意本地目录运行 Codex CLI。
  *Run Codex CLI in your browser from any local directory.*

- **[pubdir](https://github.com/haskaomni/pubdir)**
  带丰富预览的本地目录分享工具，可选 Cloudflare Tunnel 一键公网访问。
  *Preview-rich local directory sharing with optional Cloudflare Tunnel for public access.*

- **[monopoly-3d](https://github.com/haskaomni/monopoly-3d)**
  中国城市主题的 3D 大富翁网页游戏：Vite + React + TypeScript + three.js，纯 TS 规则引擎与 3D/UI 完全解耦，支持无头 AI 对局模拟。
  *A 3D Monopoly-style web game themed on Chinese cities — Vite + React + TypeScript + three.js, with a pure-TS rule engine fully decoupled from the UI and headless AI match simulation.*

- **[goofish](https://github.com/haskaomni/goofish)**
  基于 opencli 的闲鱼自动化运营：商品上架、擦亮、消息回复、市场调研。
  *Xianyu (Goofish) automation built on opencli — listing, boosting, auto-reply and market research.*

## ✍️ 写作与笔记 / Writing & Notes

- **[atom-joule-bit](https://github.com/haskaomni/atom-joule-bit)**
  《原子、焦耳和比特》：AGI 时代的后稀缺经济学与投资决策，约 10 万字书稿（GitBook）。
  *"Atom, Joule, Bit" — a ~100k-word book on post-scarcity economics and investment decisions in the AGI era.*

- **[cortex](https://github.com/haskaomni/cortex)**
  《前额叶训练手册》：一套系统化认知训练课程，从睡眠/营养/运动的地基，到抑制控制、情绪调节，再到恐惧/兴奋/梦境等极限状态下的头脑主权。
  *"Cortex" — a structured prefrontal-cortex training manual, from sleep/nutrition/exercise fundamentals to emotional regulation and mental sovereignty in extreme states of consciousness.*

- **[my-site](https://github.com/haskaomni/my-site)**
  个人博客「Omni笔记」：AI · Web3 · 前沿科技的精选翻译与笔记（VitePress）。
  *Personal blog "Omni Notes" — curated translations and notes on AI, Web3 and frontier tech (VitePress).*

---

## 📊 GitHub Stats

![Omni's GitHub stats](https://github-readme-stats.vercel.app/api?username=haskaomni&show_icons=true&hide_title=true&theme=default)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=haskaomni&layout=compact)
