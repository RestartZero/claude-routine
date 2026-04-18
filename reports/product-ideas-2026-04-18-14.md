# AI Product Ideas for Solo Developer — 2026-04-18

> Researched across Product Hunt, Indie Hackers, Zhihu, Xiaohongshu, DEV Community, and micro-SaaS trackers.
> Stack assumed: Python, TypeScript, Claude API, MCP servers, AI automation.
> Priority: ship in 1–3 days, revenue-positive fast.

---

## Top Priority Ideas (Ship in 1–2 Days)

---

### 1. XiaoNote Compliance Checker
**What it does:** Chrome extension that scans a draft 小红书 post before publishing and flags words/patterns likely to trigger shadowban or content moderation.

| Field | Value |
|---|---|
| Target market | Chinese |
| Dev time | 16 hours |
| Monetization | Freemium — 10 checks/day free, ¥29/month unlimited |
| Selling platform | 闲鱼 + 小红书 private traffic (微信群) |
| Competition | Low |
| Revenue potential | $800–2,500/month |

**Why now:** 76.3% of 小红书 creators report content violations causing throttling (Zhihu survey 2026). Zero dedicated compliance tools exist. MV: simple keyword + Claude API pattern analysis in a popup.

---

### 2. Xianyu AutoReply Bot
**What it does:** Python daemon that uses Claude API to auto-respond to buyer inquiries on 闲鱼 listings 24/7, matching seller's tone and item details.

| Field | Value |
|---|---|
| Target market | Chinese |
| Dev time | 20 hours |
| Monetization | ¥39/month subscription |
| Selling platform | 闲鱼 listing + 小红书 promo posts |
| Competition | Very low |
| Revenue potential | $1,000–4,000/month |

**Why now:** Open-source Xianyu AutoAgent shows demand; no polished paid product exists. 闲鱼 power sellers are actively paying for customer service automation (multiple Zhihu threads confirm). Sell the tool itself on 闲鱼 as a virtual product.

---

### 3. Instant MCP Server Generator
**What it does:** Takes any REST API's OpenAPI/Swagger docs URL → generates a fully deployable MCP server (TypeScript) in under 60 seconds.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 20 hours |
| Monetization | $19/month or $5/generation credits |
| Selling platform | Paddle + MCP server directories |
| Competition | Low |
| Revenue potential | $500–3,500/month |

**Why now:** 500+ public MCP servers built since late 2024; 21st.dev hit $10K MRR in 6 weeks with an MCP-adjacent tool (no marketing). Every developer with a REST API wants an MCP server — no generator exists yet. DEV Community article confirms "MCP servers are the new SaaS."

---

### 4. AI Meeting → CRM Auto-Mapper (MCP Server)
**What it does:** MCP server that reads a meeting transcript (Otter/Fathom/plain text), extracts deal details, contacts, action items, and writes them to HubSpot or Notion.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 18 hours |
| Monetization | $29/month subscription |
| Selling platform | Paddle |
| Competition | Medium |
| Revenue potential | $2,000–6,000/month |

**Why now:** AI meeting assistants market growing from $3.24B to $7.33B by 2035. The transcription tools are commoditized — the painful last mile (pushing structured data into CRM) has no clean MCP solution. Integrates with Claude's existing Notion/HubSpot MCP servers.

---

### 5. Legal Doc Risk Highlighter (Chrome Extension)
**What it does:** Sidebar extension that uses Claude API to summarize any contract/legal doc on screen, highlight risky clauses, and suggest plain-English rewrites.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 18 hours |
| Monetization | $9.99/month — subscription via ExtensionPay |
| Selling platform | Chrome Web Store + Paddle |
| Competition | Low–Medium |
| Revenue potential | $1,000–5,000/month |

**Why now:** Legaltech SaaS growing 28% YoY. Generic "summarize this page" extensions are saturated but a legally-focused, risk-aware tool with clear output format is not. Low CAC via organic search ("chrome extension contract review").

---

## Strong Ideas (Ship in 2–3 Days)

---

### 6. Multi-Platform Content Repurposer
**What it does:** Web app — paste one long-form piece; Claude API generates optimized versions for Twitter/X thread, LinkedIn post, 小红书 note, Zhihu answer, and WeChat article simultaneously.

| Field | Value |
|---|---|
| Target market | Both |
| Dev time | 24 hours |
| Monetization | Freemium — 3 repurposes/day free, $15/month or ¥99/month unlimited |
| Selling platform | Paddle (global) + 小程序 (China) |
| Competition | Medium |
| Revenue potential | $1,500–5,000/month |

**Why now:** 小红书 content demand is exploding but creators hate reformatting. Zhihu threads explicitly ask for cross-platform automation. The Chinese-to-English bilingual angle (中英双语) is an untapped differentiator.

---

### 7. 小红书 Account Automation Suite
**What it does:** Python + Claude API tool that manages up to 50 小红书 accounts: schedules posts, generates caption variations, auto-likes/follows within safe rate limits, tracks analytics.

| Field | Value |
|---|---|
| Target market | Chinese |
| Dev time | 36 hours |
| Monetization | ¥299/month (up to 10 accounts), ¥599/month (50 accounts) |
| Selling platform | 微信私域 + 小红书 promo |
| Competition | Low (polished paid tools) |
| Revenue potential | $3,000–10,000/month |

**Why now:** Zhihu article "1 person managing 50 小红书 accounts" viral — proving demand. Most existing tools are fragile scrapers. A stable, Claude-AI-powered suite with natural variation is defensible.

---

### 8. AI Shopify Product Description Optimizer (MCP Server)
**What it does:** MCP server that connects to a Shopify store, reads all product listings, and rewrites descriptions for SEO + conversion using Claude API, with A/B variant generation.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 20 hours |
| Monetization | $29/month |
| Selling platform | Paddle + Shopify App Store (later) |
| Competition | Medium |
| Revenue potential | $1,000–4,000/month |

**Why now:** DEV Community article explicitly calls out Shopify MCP as high-demand. Shopify has 4.8M+ stores. Description quality directly impacts revenue, so merchants pay quickly. Initial distribution: Claude/Cursor MCP directories.

---

### 9. AI Competitor Intelligence Briefer
**What it does:** SaaS that monitors competitor websites, pricing pages, and job postings weekly; Claude API synthesizes changes into a short "what changed and why it matters" briefing delivered via email.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 28 hours |
| Monetization | $49/month (5 competitors), $99/month (20 competitors) |
| Selling platform | Paddle |
| Competition | Low (in this specific format) |
| Revenue potential | $2,000–7,000/month |

**Why now:** Market gap identified in research — businesses need structured competitive intelligence but existing tools (Crayon, Klue) are expensive enterprise plays ($500+/month). A $49 solo-dev tier is wide open.

---

### 10. Resume Tailorer for Job Applications
**What it does:** Paste a job description → Claude rewrites your resume bullet points and generates a custom cover letter optimized for that specific role and ATS keywords.

| Field | Value |
|---|---|
| Target market | Both |
| Dev time | 20 hours |
| Monetization | $4.99/job (pay-per-use) or $29/month unlimited via Paddle |
| Selling platform | Paddle + Payhip |
| Competition | Medium–High |
| Revenue potential | $1,000–4,000/month |

**Why now:** Job market remains turbulent in 2026. Pay-per-use lowers barrier to first purchase. Differentiate on Chinese market (外企 job applications, bilingual CVs) where competition is much lower.

---

## Niche / Longer-Tail Ideas (Still Shippable in 3 Days)

---

### 11. AI Code Review Chrome Extension
**What it does:** Chrome extension that adds a "Review with Claude" button to GitHub PR pages — posts inline comments with Claude's analysis of logic, security, and style.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 24 hours |
| Monetization | $12/month subscription |
| Selling platform | Chrome Web Store + Paddle |
| Competition | Medium |
| Revenue potential | $500–2,500/month |

---

### 12. Chinese Business Email / WeChat Reply Generator
**What it does:** TypeScript web app — describe the situation in plain Chinese, get 3 professionally-worded email or WeChat reply options appropriate for Chinese business culture (正式/商务).

| Field | Value |
|---|---|
| Target market | Chinese |
| Dev time | 16 hours |
| Monetization | ¥39/month or ¥9.9 per 20 credits — 小程序 |
| Selling platform | 微信小程序 + 闲鱼 |
| Competition | Low |
| Revenue potential | $600–2,500/month |

---

### 13. AI PPT Template Generator for 闲鱼 Sellers
**What it does:** Enter a topic → Claude generates a complete structured PPT outline + slide text, then exports to PowerPoint. Sellers resell the output as "虚拟资料" on 闲鱼.

| Field | Value |
|---|---|
| Target market | Chinese |
| Dev time | 18 hours |
| Monetization | ¥19.9/month unlimited (target 闲鱼 resellers) |
| Selling platform | 闲鱼 + 知乎 |
| Competition | Low |
| Revenue potential | $500–2,000/month |

**Why now:** 闲鱼 PPT sellers earning ¥5,000+/month confirmed in Zhihu case studies. A B2B-to-reseller model means your users are motivated power users who promote the tool for you.

---

### 14. AEO (Answer Engine Optimization) Audit Tool
**What it does:** Enter your website URL → Claude + web scraping analyzes how well your content answers questions in AI search engines (Perplexity, ChatGPT, Claude.ai) and gives a prioritized fix list.

| Field | Value |
|---|---|
| Target market | Global |
| Dev time | 24 hours |
| Monetization | $29/one-time audit or $49/month for weekly monitoring |
| Selling platform | Paddle + Payhip |
| Competition | Very low (HubSpot AEO Grader is free but shallow) |
| Revenue potential | $1,000–4,000/month |

**Why now:** "AEO" (Answer Engine Optimization) is the 2026 SEO equivalent. HubSpot launched a free surface-level grader — a paid deep-audit tool is the obvious next step.

---

### 15. Batch Claude API Request Scheduler
**What it does:** Web UI for non-technical users to upload a CSV of prompts, schedule batch runs (using Anthropic's Batch API for 50% cost discount), download results — no code required.

| Field | Value |
|---|---|
| Target market | Both |
| Dev time | 20 hours |
| Monetization | Freemium — 100 requests/month free; $19/month for 10K requests; pass through Claude API costs + 30% margin |
| Selling platform | Paddle |
| Competition | Low |
| Revenue potential | $500–3,000/month |

**Why now:** Anthropic's Message Batches API gives 50% cost reduction but requires coding knowledge. Non-technical marketers and researchers want this as a UI. Claude API usage growing 1,400% YoY (Sacra 2026 data).

---

## Execution Ranking (Best ROI for Time Invested)

| Rank | Product | Dev Hours | Revenue Potential | Why Top |
|---|---|---|---|---|
| 1 | Xianyu AutoReply Bot | 20h | $1K–4K/mo | Untapped Chinese niche, sells itself on 闲鱼 |
| 2 | XiaoNote Compliance Checker | 16h | $800–2.5K/mo | Clear pain, zero competition, viral distribution |
| 3 | Instant MCP Server Generator | 20h | $500–3.5K/mo | Organic developer discovery, fast MRR |
| 4 | AI Meeting → CRM Mapper | 18h | $2K–6K/mo | Real B2B pain, integrates existing MCP ecosystem |
| 5 | AEO Audit Tool | 24h | $1K–4K/mo | 2026's hottest SEO trend, near-zero competition |

---

## Platform Quick Reference

| Platform | Best For | Payment |
|---|---|---|
| Paddle | Global SaaS subscriptions | Credit card / PayPal |
| Payhip | One-time digital product sales | Credit card |
| 微信小程序 | Chinese mobile apps | WeChat Pay |
| 闲鱼 | Chinese virtual product sales (B2C) | Alipay |
| Chrome Web Store + ExtensionPay | Browser extension subscriptions | Stripe via ExtensionPay |

---

## Key Market Signals (Research Summary)

- AI micro-SaaS: 70% earn <$1K/month — **niche focus is the differentiator**
- Chrome AI extensions: market hit $2.3B in 2025; 442 extensions with 1K+ users (↑86% YoY)
- MCP servers: 500+ public servers; 21st.dev $10K MRR in 6 weeks with zero marketing
- 小红书: 82.7% creators struggle with typesetting; 76.3% hit by content violations — both solvable with Claude
- 闲鱼: virtual AI products form complete supply chains within 48h of tool release; students earning ¥3K+/day selling AI tool access
- AEO: HubSpot's AEO Grader launched April 2026 — market validation with no deep paid alternative yet

---

*Report generated: 2026-04-18 | Sources: Zhihu, 小红书, Lovable, NxCode, MicroSaaSHQ, DEV Community, ChromeGoldmine, Sacra, EgoistAI, hunted.space*
