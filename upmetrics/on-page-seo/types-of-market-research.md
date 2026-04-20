# SEO Suggestion Report — Types of Market Research

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/types-of-market-research |
| **Post ID** | 106882 |
| **Post Type** | post |
| **Category** | Planning |
| **Published** | 2026-04-18 |
| **Modified** | 2026-04-17 |
| **Word Count** | 3,258 |
| **Report Date** | 2026-04-20 |
| **GSC Data Range** | 2026-03-23 to 2026-04-17 (no impressions — page not yet indexed) |
| **GA4 Data Range** | Last 30 days (Report A) / 90 days (Report E) |

---

## Section B — Page Health Score & Action Summary

### Page Health Score: 5/10

| Status | Count | Notes |
|--------|:-:|-------|
| Critical | 1 | Meta title and description likely not set (Yoast fields empty in API response) — Google will use the H1 (64 chars, gets truncated) and auto-generate or omit description |
| Needs Improvement | 4 | Duplicate internal link, weak anchor text on 1 link, no Resource CTA set, no Related Content set |
| Good | 6 | Heading structure, image alts, slug, categories, content freshness, blog post end CTA |

**Deduction breakdown:** -2 (meta likely unset / Critical) · -1 (duplicate internal link) · -1 (Resource CTA not set) · -1 (Related Content not set)

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:-:|------|:-:|:-:|--------------|------------|--------------|---------------|
| 1 | Internal Links | High | Medium | 11 internal links (1 duplicate) | Fix duplicate, polish 1 anchor, add 4 new contextual links | Approve specific items | **Approve all** |
| 2 | CTAs | Medium | Medium | 3 CTAs (1 end + 2 tips) — well placed | Add 1 mid-content banner CTA after Quantitative section | Optional, page already balanced | **Approve #1** |
| 3 | Resource CTA | High | Quick Win | Not set | Attach `Market Survey Template` (download/market-survey-template) | Approve resource pick | **Approve** |
| 4 | Related Content | High | Quick Win | Not set | Set 4 related items (ChatGPT for research, Industry vs Market Analysis, Marketing Strategy, Industry Analysis) | Approve list | **Approve** |
| 5 | Meta Title & Description | High | Quick Win | Likely not set; default title is 64 chars (truncates) | Set title `Types of Market Research: 10 Methods (+ When to Use Each)` and matching description; set focus keyphrase | Approve | **Approve** |
| 6 | Image Alt Text | Low | N/A | 1 content image with good alt; 1 decorative icon | No changes needed | — | **Skip (N/A)** |
| 7 | URL Slug | Low | N/A | `types-of-market-research` — clean, keyword-focused, 4 words | No change needed | — | **Skip (N/A)** |
| 8 | Heading Structure | Low | N/A | 9 H2 + 9 H3, no skipped levels, primary keyword present | No change needed | — | **Skip (N/A)** |
| 9 | Categories | Low | N/A | "Planning" — appropriate for the topic | No change needed | — | **Skip (N/A)** |
| 10 | Incoming Internal Links | Medium | Manual | New page — needs incoming links to build authority | 6 source pages suggested for SEO team to manually link | SEO team manual implementation | **Noted** |

> **Important context:** The page was published 2 days ago (2026-04-18) and is currently in `Discovered - currently not indexed` state in GSC. There's no historical query data yet, so meta-rewrite decisions are based on title/length/structure rather than CTR vs benchmark. Slug change (Task 7) would be safe at this stage but isn't needed.

---

## Section C — Task-by-Task Suggestions

### TASK 1: Internal Linking

**Current state:** 11 internal links in the editor content (excluding the End CTA button). Word count 3,258 → ideal range 7-10 contextual links. **One duplicate link is present** — `/blog/market-analysis-in-business-plan` is anchored twice with the same anchor text.

#### Existing Internal Link Audit

| # | Anchor | Target | Status | Notes |
|:-:|--------|--------|--------|-------|
| 1 | justifying an idea | /blog/how-to-validate-business-idea | Good | — |
| 2 | market research tools | /blog/top-market-research-tools | Good | — |
| 3 | AI-powered research tools | /blog/ai-tools-for-market-research | Needs improvement | Anchor is generic. Target page title is "Top 10 AI Tools For Market Research" — anchor "AI tools for market research" matches better. |
| 4 | use AI for market research | /blog/how-to-use-ai-for-market-research | Good | — |
| 5 | competitive analysis section of your business plan | /blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively | Good | Long but contextually accurate |
| 6 | competitor analysis generator | /ai-tools/competitor-analysis-generator | Good | Sales/Features link, naturally placed |
| 7 | Upmetrics' AI for market research | /features/industry-research | Good | Sales/Features link, naturally placed |
| 8 | market analysis section of your business plan | /blog/market-analysis-in-business-plan | Good | First occurrence (in "Validating a new idea" bullet area) |
| 9 | market analysis section of your business plan | /blog/market-analysis-in-business-plan | **Remove (duplicate)** | Same URL + same anchor as #8 — second occurrence in "How to use market research..." section. Unwrap the link, keep the text. |
| 10 | AI business plan generator | /features/ai-plan-generator | Good | High-conversion target (GA4: 167 conversions / 90d) |
| 11 | write a business plan with AI | /blog/chatgpt-business-plan | Good | High-traffic target (GA4: 279 sessions / 30d) |

**Balance check:** 8 informational + 3 sales/features = ~73/27 split. Target for blog post is ~60-70 / 30-40 → currently slightly under-indexed on Sales. New suggestions add 4 more informational, keeping the post in the right zone after the planned dedup of #9.

---

#### New Internal Link Suggestions

> **#1** — `total addressable market (TAM)` → `/blog/tam-sam-som-market-size-metrics`
>
> **Section:** 4) Quantitative research (paragraph after the bullet list)
>
> **In context:** "Based on industry reports and census data, you can approximate your **total addressable market (TAM)**, the entire size of the market you are entering, your serviceable addressable market (SAM), the portion you can practically serve, and your serviceable obtainable market (SOM), the portion you can capture in the short term."

---

> **#2** — `industry reports` → `/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** 4) Quantitative research (same paragraph as #1, earlier in the sentence)
>
> **In context:** "Based on **industry reports** and census data, you can approximate your total addressable market (TAM), the entire size of the market you are entering..."
>
> **Note:** Direct topical match — target page is literally a list of industry report sources, which is what the reader would want next.

---

> **#3** — `target market` → `/blog/how-to-find-your-target-market`
>
> **Section:** 1) Primary research (opening paragraph)
>
> **In context:** "Primary research means going directly to your **target market** to collect information yourself. You decide what to ask, who to ask, and how to interpret the answers."
>
> **Note:** Anchor exists verbatim 3 times in the post; linking the first occurrence in the most relevant section.

---

> **#4** — `industry trends` → `/blog/industry-benchmarking`
>
> **Section:** 2) Secondary research (paragraph 2)
>
> **In context:** "Within minutes, you can get demographic information, **industry trends**, and competitor benchmarks. It also narrows down your main research, meaning that you are left with only gathering information that is not available in the existing sources."
>
> **Note:** Industry Benchmarking page covers what to track + where to get the data — natural deeper-dive for readers learning about secondary research.

---

> **#5 (Optional)** — `industry analysis` related text → `/blog/industry-analysis-vs-market-analysis`
>
> **Section:** Would require small text addition — exact phrase "industry analysis" doesn't appear in the post.
>
> **Recommendation:** Skip in Task 1 — reserve this page for Task 4 (Related Content) sidebar instead. No good anchor exists in body without forcing a sentence rewrite.

---

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Use AI for Market Research | Already linked in body |
| 10 Best Market Research Tools | Already linked in body |
| Top 10 AI Tools For Market Research | Already linked in body |
| How To Use ChatGPT for Market Research | No matching anchor text in body — moved to Task 4 |
| Industry Analysis vs Market Analysis | No matching anchor text in body — moved to Task 4 |

</details>

---

### TASK 2: CTA Placements

**Current state:** 3 CTAs — 1 canonical Blog Post End CTA (mandatory, present, do not modify) + 2 yellow `upm-blog-tip` blocks (educational tips, well placed). The post also has 4 inline product mentions (links to `/features/industry-research`, `/ai-tools/competitor-analysis-generator`, `/features/ai-plan-generator`, plus the End CTA button).

#### Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:-:|----------|-----------|--------|-------|
| 1 | `upm-blog-tip` (Yellow tip) | After "How to choose the right type of market research" section bullets | Good | Editorial tip, naturally placed |
| 2 | `upm-blog-tip` (Yellow tip) | After "How to use market research in your business plan" final paragraph | Good | Editorial tip, naturally placed |
| 3 | `delivery-block` (Blog Post End CTA — canonical) | Very last block | Good | Mandatory, fixed copy, do not modify |

**Spacing check:** CTAs #2 and #3 are close (only the closing tip then the End CTA), but they are different visual styles (yellow text tip vs full banner) so they don't compete on screen. Acceptable.

---

#### New CTA Suggestions

> **#1 (Recommended)** — Type 8 (Investor-Ready Plan, image right) | After Section "4) Quantitative research"
>
> **Placed after:** "For most small businesses, that is a realistic target without needing a large budget or a research firm. You can also use AI-powered research tools to help analyze responses once you have them."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  Got the numbers? Now turn them into a plan.            │
> │                                                         │
> │  Build an investor-ready business plan from your        │
> │  market research                                        │
> │                                                         │
> │  [ Start Planning Now ]                                 │
> │                                       🖼 AI Business Plan │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **HTML to insert:**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> Got the numbers? Now turn them into a plan.
> <p class="title h2">Build an investor-ready business plan from your market research</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Start Planning Now</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-business-plan.svg" alt="AI Business Plan" width="200" height="170" /></div>
> </div>
> ```
>
> **Note:** Section just covered TAM/SAM/SOM and AI research tools — natural moment to nudge toward turning research into a finished plan. Sits ~8 paragraphs before next CTA (the Yellow Tip in "How to choose"), so spacing is clean.

---

### TASK 3: Downloadable Resource / Tool Attachment

**Current state:** No Resource CTA set on the post (Resources Hero CTA ACF fields are empty).

**Recommendation:** Attach **Market Survey Template** — most directly relevant, primary research tool that readers can use immediately after reading.

| Field | Value |
|-------|-------|
| **Resource URL** | `https://upmetrics.co/download/market-survey-template` |
| **Post ID (resource)** | 7321 |
| **Heading** | `Market Survey Template` |
| **Resource link text** | `Download Template` |
| **Combined display** | `Download Template: Market Survey Template` (43 chars ✓ under 55) |

**Why this resource:** Surveys are mentioned as "the most accessible way to collect primary data at scale" — the template is the actionable artifact a reader would download to start. Two strong runner-ups (`Market Analysis Kit`, `Customer Persona Template`) cover broader/related topics; `Market Survey Template` is the most action-aligned with the post's first major section.

---

### TASK 4: Related Content

**Current state:** No Related Content items set (ACF Related Posts repeater is empty).

**Recommendation:** Set 4 related items below. All are repository-verified, NOT used by Tasks 1 or 3, and topically aligned. Custom titles written to be short and click-worthy (under 50 chars each).

| # | Post ID | Display Title | Linked Post | Why |
|:-:|:--:|--------------|-------------|-----|
| 1 | 98033 | Use ChatGPT to Speed Up Your Research | /blog/how-to-use-chatgpt-for-market-research | Direct topic match — practical AI angle reader will want next |
| 2 | 96105 | Market Analysis vs Industry Analysis | /blog/industry-analysis-vs-market-analysis | Clarifies a key concept the post mentions but doesn't fully unpack |
| 3 | 83092 | Marketing Strategy in Your Business Plan | /blog/marketing-strategy-business-plan | Natural next step — research feeds strategy |
| 4 | 69079 | Industry Analysis: What to Include | /blog/industry-analysis-in-business-plan | Closely related deliverable — uses similar research inputs |

---

### TASK 5: Meta Title & Description Optimization

**Current state assessment:** The `get-post` API response did not return any `seo` (Yoast) fields, indicating the meta title, meta description, focus keyphrase, canonical URL, and OG fields are likely **not set**. Without them, Google will:
- Use the H1 (`Types of Market Research: A Practical Guide for Business Owners` — 64 chars) as the SERP title, which **truncates** at ~60 chars
- Auto-generate or omit the meta description, costing CTR

The page has zero GSC impressions yet (published 2026-04-18, status: `Discovered - currently not indexed`), so there is no CTR-vs-benchmark data — recommendation is based on length, structure, and front-loaded keyword placement.

#### Current vs. Suggested

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | (defaults to H1) `Types of Market Research: A Practical Guide for Business Owners` | 64 (truncates) | `Types of Market Research: 10 Methods (+ When to Use Each)` | 57 ✓ | Primary kw in first 24 chars; hook = number "10" + benefit "When to Use Each"; different from H1 |
| Meta Description | (unset) | 0 | `Learn the 10 types of market research, when to use each, and what each one costs. A practical decision framework for startups and small businesses.` | 148 ✓ | Primary kw in first 24 chars; 3-part structure (what + value + soft CTA via "decision framework") |
| Focus Keyphrase | (unset) | — | `types of market research` | — | 4 words; appears verbatim in suggested title and description |
| Canonical URL | (unset) | — | `https://upmetrics.co/blog/types-of-market-research` | — | Self-canonical — required |
| OG Title | (unset) | — | (matches Meta Title) | — | Inherit |
| OG Description | (unset) | — | (matches Meta Description) | — | Inherit |

#### SERP Preview

```
─────────────────────────────────────────────────────
upmetrics.co › blog › types-of-market-research
Types of Market Research: 10 Methods (+ When to Use Each)
Learn the 10 types of market research, when to use each, and
what each one costs. A practical decision framework for
startups and small businesses.
─────────────────────────────────────────────────────
```

**Differentiator note:** Most competitors for "types of market research" use generic titles like "X Types of Market Research" or "A Complete Guide to Market Research". The suggested title differentiates with both a count (`10 Methods`) AND a benefit hook (`When to Use Each`) — the second hook is the rare one that signals decision support, not just enumeration.

---

### TASK 6: Image Alt Text Audit

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty (wrong) | 0 | — |
| Needs Improvement | 0 | — |
| Good | 1 | No action |
| Decorative — Correct | 1 | No action (part of canonical End CTA — do not modify) |
| **Total images** | **2** | — |

The single content image (`types-of-market-research-primary-research-methods.png`) has a clear, descriptive alt: `Overview of primary market research methods including surveys interviews focus groups and observation` (99 chars, no banned openers, no AI words). The decorative `crossline.png` is part of the canonical Blog Post End CTA template and must be left as-is. **No changes needed.**

---

### TASK 7: URL Slug Optimization

Current slug: `types-of-market-research` (24 chars, lowercase, hyphens, primary keyword present, 4 words). Already optimal — **no change recommended**.

Note: Page is not yet indexed, so a slug change would be technically safe at this point. However, there is no improvement to make.

---

### TASK 8: Heading Structure Audit

| Check | Result |
|-------|--------|
| Single H1 in body | ✓ (0 in body — title rendered by theme as H1 outside the editor content) |
| H2 count | 9 — well-distributed |
| H3 count | 9 — only nested under H2s, no skipped levels |
| Primary keyword in H2s | ✓ — appears in multiple H2s ("market research" appears in 4 of 9 H2s) |
| Heading length | All under 70 chars |
| Duplicate headings | None |

**No changes needed.** Optional style note: H2s use `1)`, `2)`, etc. as numeric prefixes (`1) Primary research`). This is a style choice; removing the prefixes would make headings cleaner but is not an SEO concern.

---

### TASK 9: Category / Taxonomy Assignment

Current: `["Planning"]`. Market research is a foundational planning activity (the post explicitly frames research as "where your market analysis comes from"). The Planning category is correct. **No change needed.**

A second category like "Statistics" was considered but rejected — that category is reserved for posts that ARE statistics roundups, not posts that USE statistical methods.

---

### TASK 10: Incoming Internal Link Suggestions

**Why this matters:** This page is brand new (2 days old) and not yet indexed. Building incoming internal links from established, traffic-receiving site pages will accelerate indexation and help Google understand the page's importance.

All source pages below are verified WordPress posts (confirmed via `list-posts` slug lookup), and pages already linking TO this post via Task 1 are excluded to avoid reciprocal link suggestions.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor (search term for SEO team) | Traffic | Priority |
|:-:|------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | How To Use ChatGPT for Market Research | /blog/how-to-use-chatgpt-for-market-research | 98033 | post | Direct topical sibling — should reference research types | types of market research | — | High |
| 2 | How to Write a Marketing Strategy for Business Plan | /blog/marketing-strategy-business-plan | 83092 | post | Marketing strategy depends on research inputs — natural place to link | market research methods | — | High |
| 3 | How to Write a Business Concept (Step-by-Step Guide + Examples) | /blog/business-concept-guide | 92056 | post | Business concept validation requires research | types of market research | — | Medium |
| 4 | How to Write an Industry Analysis in Your Business Plan | /blog/industry-analysis-in-business-plan | 69079 | post | Industry analysis uses similar research types — natural cross-link | market research types | — | Medium |
| 5 | 42+ ChatGPT Prompts for Business | /blog/chatgpt-prompts-for-business | 105437 | post | Has prompts for research workflows; high traffic (346 sessions/30d) | market research | 346 sessions | Medium |
| 6 | How to Write a Business Plan for Investors | /blog/business-plan-for-investors | 64304 | post | Investor plans require strong market research evidence | market research | — | Low |

> Every source URL above is verified in WordPress (real post_id). Suggested anchor text is a starting term for the SEO team to search within the source page — the actual anchor depends on what text exists in that page's content.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Fix duplicate #9 (unwrap second market-analysis link). Update #3 anchor. Add #1, #2, #3, #4. Skip #5.
Task 2 (CTAs): Add #1 (Type 8 Investor-Ready) after Quantitative section.
Task 3 (Resource CTA): Approve Market Survey Template.
Task 4 (Related Content): Approve all 4 items with the suggested custom titles.
Task 5 (Meta Title/Desc): Approve title, description, focus keyphrase, canonical, OG fields.
Task 6 (Image Alt Text): Skip — no action needed.
Task 7 (URL Slug): Skip — already optimal.
Task 8 (Headings): Skip — already good.
Task 9 (Categories): Skip — Planning is correct.
Task 10 (Incoming Links): Noted — SEO team will review and implement manually.
```

Or simply: **"Approve all"** (executes Tasks 1, 2, 3, 4, 5; skips 6, 7, 8, 9; Task 10 is suggestion-only)
