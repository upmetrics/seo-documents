# SEO Suggestion Report — Plan vs. Actual Analysis

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/plan-vs-actual-analysis |
| **Post ID** | 69096 |
| **Report Date** | 2026-03-31 |
| **GSC Data Range** | Dec 31, 2025 – Mar 30, 2026 (90 days) |
| **GA4 Data Range** | Mar 1–30, 2026 (30 days) |

---

## Section B: Page Health Score + Action Summary

### Page Health Score: 4 / 10

| Status | Count | Items |
|--------|:-----:|-------|
| 🔴 Critical | 2 | CTA button typo, 0% informational link ratio |
| 🟡 Needs Improvement | 5 | Duplicate link, missing alt texts, CTA type duplication, heading skip, no resource CTA |
| 🟢 Good | 2 | Index status, FAQ + Breadcrumb schema |

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|---|------|:------:|:------:|---------------|------------|---------------|
| 1 | Internal Links | High | Medium | 2 internal links, both to same sales page; docs.google.com links present | Remove duplicate + Google Docs links; add 5 informational links | Approve all |
| 2 | CTAs | High | Medium | 2 identical `cta-template-ai` CTAs, both have button typo "t" | Replace CTA 1 → Type 4; replace CTA 2 → Type 12; add Type 9 after Visualize section | Approve all |
| 3 | Resource CTA | Medium | Quick Win | Not set | Set Sales Forecast Templates | Approve |
| 4 | Related Content | Medium | Quick Win | Not set | 4 items (forecasting-related posts) | Approve all |
| 5 | Meta Title & Desc | High | Quick Win | Likely default title; no meta desc known | Keyword-first title + optimized description | Approve |
| 6 | Image Alt Text | Medium | Quick Win | 2 missing + 6 vague/incorrect alt texts | 8 updates | Approve all |
| 7 | URL Slug | Low | High | `plan-vs-actual-analysis` (clean) | Skip — slug is keyword-matched | Skip |
| 8 | Headings | Medium | Quick Win | H4 used without H3 parent in "Why conduct" section | Change H4 → H3 for 5 sub-headings | Approve |
| 9 | Categories | Low | Quick Win | Forecasting + Managing | Both correct — no change needed | Skip |

---

## Section C: Page Overview

### Basic Info

| Field | Value |
|-------|-------|
| **Post Type** | Blog Post (`post`) |
| **Title** | How to Conduct a Plan vs. Actual Analysis |
| **Categories** | Forecasting, Managing |
| **Tags** | None |
| **Estimated Word Count** | ~2,100 words |
| **Published** | Sep 13, 2024 |
| **Last Modified** | Sep 13, 2024 |
| **Content Freshness** | ⚠️ Never updated since publication (18 months ago) |

### Search Performance (90 days)

| Metric | Value |
|--------|-------|
| **Total Clicks** | ~12 |
| **Total Impressions** | ~6,100 |
| **Avg. CTR** | ~0.2% |
| **Index Status** | ✅ Submitted and Indexed |
| **Last Crawled** | 2026-03-27 |
| **Structured Data** | ✅ FAQ Schema + Breadcrumbs |

**Top Queries:**

| Query | Impressions | Position | Clicks |
|-------|:-----------:|:--------:|:------:|
| actual plan | 247 | 2.0 | 1 |
| plan vs actual | 105 | **15.6** | 1 |
| actual example | 57 | 1.5 | 0 |
| actual analysis | 19 | 8.3 | 0 |
| actual plan meaning | 7 | 4.7 | 0 |

> **Key finding:** The page ranks #2 for "actual plan" — but this is a low-intent, ambiguous query. The money keyword is **"plan vs actual"** at position 15.6 (page 2). That's the target to move to page 1.

**90-Day Impression Trend:**

| Period | Total Impressions | Clicks | Notes |
|--------|:-----------------:|:------:|-------|
| Jan 2026 (first 30 days) | ~2,900 | 7 | Baseline |
| Feb 2026 | ~2,100 | 4 | −28% |
| Mar 2026 | ~1,100 | 1 | −62% vs Jan |

> 🔴 **Alarming decline.** Impressions dropped 62% over 3 months. Likely cause: content freshness + lack of SEO optimization. This page needs immediate attention.

### Engagement (GA4, 30 days)

| Metric | This Page | Site Avg (blog posts) | Status |
|--------|:---------:|:---------------------:|--------|
| Sessions | 32 | ~660 | 🔴 Well below average |
| Active Users | 19 | — | — |
| Engagement Rate | 68.75% | ~57% | 🟢 Above average |
| Bounce Rate | 31.25% | ~43% | 🟢 Below average |
| Avg. Engagement Duration | ~55s | — | — |

> Good engagement when people land on the page — they read it. The problem is almost nobody is finding it via search.

### Internal Link Equity

| Direction | Count | Notes |
|-----------|:-----:|-------|
| Outbound (internal to Upmetrics) | 3 | 2× `/features/financial-forecasting` (duplicate!), 1× `app.upmetrics.co` login |
| Outbound (external) | 4 | 2× Google Docs, LinkedIn, Festoon House |
| Inbound links | Low | Page not in GSC top pages; likely few internal links pointing here |

---

## Section D: Task-by-Task Suggestions

---

## Task 1: Internal Links

### Existing Link Audit

| # | Anchor Text | Target URL | Status | Notes |
|---|-------------|-----------|--------|-------|
| 1 | "log in to Upmetrics" | `app.upmetrics.co/auth/login` | 🟡 Needs Fix | App login page — not a content page; replace with `/features/financial-forecasting` as anchor for a relevant feature mention |
| 2 | "AI financial forecasting tool" | `/features/financial-forecasting` | 🟢 Good | Well-placed, natural mention in Upmetrics section |
| 3 | "Connect to XERO or QuickBooks" | `docs.google.com/document/...` | 🔴 Remove | External internal doc link — not relevant to readers; remove the hyperlink, keep the anchor text |
| 4 | "Enter the actual financial data manually" | `docs.google.com/document/...` | 🔴 Remove | Same issue as #3 — remove hyperlink |
| 5 | "Matt Little" | `linkedin.com/in/matt-little-au/` | 🟢 Good | Proper citation for quote |
| 6 | "Festoon House" | `festoonhouse.com.au` | 🟢 Good | Proper citation for example business |
| 7 | "financial forecasting feature" | `/features/financial-forecasting` | 🔴 Fix | **Duplicate URL** — same page already linked in #2. Remove this link (keep the anchor text as plain text). |

**Current state:** 2 distinct internal links (both to same sales page). Informational link ratio: **0%** — should be 60–70% for a blog post.

---

### New Link Suggestions (5 new informational links)

> **#1** — `future forecasts` → `/blog/what-is-financial-forecasting`
>
> **Section:** Featured Snippet (Introduction)
>
> **In context:** "This analysis helps to identify variances (differences between the two data sets), understand the reasons behind them, and make informed decisions to improve financial strategies and **future forecasts**."
>
> Type: Informational — wraps existing text, zero changes.

---

> **#2** — `create a budget` → `/blog/budgeting-vs-forecasting`
>
> **Section:** Spreadsheet Step 1 (Tip block)
>
> **In context:** "Make sure your sales forecast matches the categories used in your accounting. This makes it easier to **create a budget** and compare your planned numbers with actual results."
>
> Type: Informational — wraps existing text, zero changes.

---

> **#3** — `data-driven decisions` → `/blog/industry-benchmarking`
>
> **Section:** Why Conduct — Enhance Decision-Making
>
> **In context:** "Accurate variance analysis enables business leaders to make informed, **data-driven decisions**. It helps identify areas where strategic adjustments are needed, ensuring the business stays aligned with its goals and objectives."
>
> Type: Informational — wraps existing text, zero changes.

---

> **#4** — `ChatGPT` → `/blog/chatgpt-prompts-for-business`
>
> **Section:** Why Conduct — Enhance Decision-Making
>
> **In context:** "Even **ChatGPT** can help you understand the impact of the variances on your business resulting in effective decision-making."
>
> Type: Informational — wraps existing text, zero changes.

---

> **#5** — `adjust their strategies` → `/blog/business-growth-plan`
>
> **Section:** Why Conduct — Adjusting Business Strategies
>
> **In context:** "The analysis enables businesses to **adjust their strategies** in response to market changes or unforeseen events, maintaining agility and flexibility."
>
> Type: Informational — wraps existing text, zero changes.

---

**After changes:** 7 total internal links — 5 informational (71%), 2 sales/features (29%). Ratio: ~2.5:1 ✅

---

## Task 2: CTA Placements

### Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|---|----------|-----------|--------|-------|
| 1 | `cta-template-ai` | After "2. Put actual results in your spreadsheet" | 🔴 Replace | Same type as CTA 2 (violates variety rule); button has stray `t` character (visible UI bug); uses old CTA format |
| 2 | `cta-template-ai` | After "1. Start with the plan (Upmetrics)" | 🔴 Replace | Same type as CTA 1; no eyebrow text; stray `t` character bug; too close to CTA 1 (~250 words gap — may appear on same screen) |

> **Bug note:** Both CTAs have `<a ...> Start Your Analysis</a>t` — the trailing `t` renders as visible text on the frontend. Fix urgently.

---

### New CTA Suggestions

> **#1** — Type 4: Financial Forecasting (Image Right) | **Replace** CTA 1 — after "2. Put actual results in your spreadsheet"
>
> **Placed after:** "...Proper alignment and accuracy at this stage will enhance the reliability of your plan vs. actual analysis."
>
> **CTA Preview:**
> ```
> ┌──────────────────────────────────────────────────────────┐
> │  Spreadsheets are exhausting & time-consuming            │
> │                                                          │
> │  Compare actual vs. plan without copying data by hand   │
> │                                                          │
> │  [ Try Upmetrics ]                         🖼 Forecasting│
> └──────────────────────────────────────────────────────────┘
> ```

---

> **#2** — Type 12: Yellow Tip Alert | **Replace** CTA 2 — after "1. Start with the plan (Upmetrics)"
>
> **Placed after:** "Finally! Your forecasts are ready. You can save and alter it at any time."
>
> **CTA Preview:**
> ```
> ┌──────────────────────────────────────────────────────────┐
> │ 💡 Tip: Want AI to build your forecasts automatically?   │
> │ Use Upmetrics' AI financial forecasting →                │
> └──────────────────────────────────────────────────────────┘
> ```
>
> This lightweight tip CTA avoids two full banners appearing close together.

---

> **#3 (NEW)** — Type 9: Financial Dashboards (Image Right) | **Add** — after "Visualize the data with the Upmetrics dashboard"
>
> **Placed after:** "...Asset charts present the value and distribution of your business's assets over time, helping you track growth or depreciation by comparing actual and forecasted data."
>
> **CTA Preview:**
> ```
> ┌──────────────────────────────────────────────────────────┐
> │  Stop squinting at spreadsheet cells                     │
> │                                                          │
> │  See your plan vs. actual data in visual dashboards      │
> │                                                          │
> │  [ Start Free Trial ]              🖼 Financial Dashboard│
> └──────────────────────────────────────────────────────────┘
> ```
>
> Well-spaced: ~600 words after CTA 1, ~800 words before Elementor end-of-post CTA.

---

## Task 3: Downloadable Resource CTA

**Recommendation:** Set **Sales Forecast Templates** as the downloadable resource.

| Field | Value |
|-------|-------|
| Resource URL | `https://upmetrics.co/download/sales-forecast-templates` |
| Resource Link Text | `Download Template` |
| Heading | `Sales Forecast Templates` |
| Combined Display | "Download Template: Sales Forecast Templates" (44 chars ✅) |

**Rationale:** The post uses sales forecast examples throughout (cafe business walkthrough). This is the most directly relevant downloadable on the site.

**Deduplication check:** `/download/sales-forecast-templates` is not used as an internal link in Task 1. ✅

---

## Task 4: Related Content

**Recommendation:** Set 4 related posts (all forecasting/financial analysis topics).

| # | Post | ID | URL |
|---|------|:--:|-----|
| 1 | What is Financial Forecasting? | 77435 | `/blog/what-is-financial-forecasting` |
| 2 | What is Cash Flow Forecasting | 81537 | `/blog/what-is-cash-flow-forecasting` |
| 3 | Financial Forecast Without Historical Data | 89621 | `/blog/financial-forecast-without-historical-data` |
| 4 | How to Prepare a Financial Plan for Startup | 6040 | `/blog/write-financial-section-startup-business-plan` |

**Deduplication check:**
- #1 `/blog/what-is-financial-forecasting` — used as internal link in Task 1 ⚠️ **CONFLICT**
  - Per deduplication rule, Task 1 wins. Replace with an alternative.
  - **Alternative:** `10 Best Revenue Forecasting Software` (ID 88309) → `/blog/revenue-forecasting-software`

**Revised Related Content:**

| # | Post | ID | URL |
|---|------|:--:|-----|
| 1 | What is Cash Flow Forecasting | 81537 | `/blog/what-is-cash-flow-forecasting` |
| 2 | Financial Forecast Without Historical Data | 89621 | `/blog/financial-forecast-without-historical-data` |
| 3 | How to Prepare a Financial Plan for Startup | 6040 | `/blog/write-financial-section-startup-business-plan` |
| 4 | 10 Best Revenue Forecasting Software | 88309 | `/blog/revenue-forecasting-software` |

None of these URLs conflict with Task 1 internal links or Task 3 resource CTA. ✅

---

## Task 5: Meta Title & Description

### Current State
*Note: SEO fields not returned by API. Current meta title assumed to match post title.*

| Field | Current (assumed) | Chars |
|-------|-------------------|:-----:|
| Meta Title | How to Conduct a Plan vs. Actual Analysis | 43 |
| Meta Description | Unknown / likely not set | — |
| Focus Keyphrase | Unknown | — |

### Suggested

| Field | Suggested | Chars |
|-------|-----------|:-----:|
| Meta Title | Plan vs. Actual Analysis: Step-by-Step Guide [2026] | 51 |
| Meta Description | Learn how to compare your financial plan against actual results, spot variances early, and improve future forecasting accuracy — with spreadsheet and Upmetrics examples. | 168 → trim |
| Meta Description (trimmed) | Compare your financial plan against actual results, find variances, and fix your forecasting. Step-by-step guide with spreadsheet and Upmetrics walkthroughs. | 158 ✅ |
| Focus Keyphrase | plan vs actual analysis | — |
| Canonical URL | `https://upmetrics.co/blog/plan-vs-actual-analysis` (already set ✅) | — |

**SERP Preview:**
```
Plan vs. Actual Analysis: Step-by-Step Guide [2026]
upmetrics.co › blog › plan-vs-actual-analysis
Compare your financial plan against actual results, find variances, and fix your
forecasting. Step-by-step guide with spreadsheet and Upmetrics walkthroughs.
```

**Rationale:**
- Starting with the keyword "Plan vs. Actual Analysis" helps CTR for users searching that term
- "[2026]" signals fresh content — important given the page's declining impressions
- Current title "How to Conduct" is buried deeper, keyword appears after 15 chars
- Focus keyphrase "plan vs actual analysis" targets the #1 opportunity query (105 impr, pos 15.6)

---

## Task 6: Image Alt Text

| # | Image | Current Alt | Suggested Alt | Issue |
|---|-------|-------------|---------------|-------|
| 1 | example-of-a-sales-forecast-for-a-cafe-business.webp | `""` (empty) | `sales forecast spreadsheet example for a cafe business` | Missing alt text |
| 2 | example-of-a-actual-sales-forecast-for-a-cafe-business-1.webp | `"example of a actual sales forecast for a cafe business"` | `example of an actual sales forecast for a cafe business` | Grammar: "a actual" → "an actual" |
| 3 | example-of-a-cafe-business.webp | `"example of cafe business"` | `plan vs actual comparison table for a cafe business` | Too vague, doesn't describe the variance comparison shown |
| 4 | start-with-the-plan.webp | `"start with the plan"` | `Upmetrics financial forecasting module showing revenue and expense streams` | Vague — describes UI shown in screenshot |
| 5 | forecast-with-ai-button.webp | `"forecast with ai button"` | `Forecast with AI button in Upmetrics financial forecasting tool` | Lowercase, incomplete description |
| 6 | revenue-stream.webp | `"revenue stream"` | `Upmetrics revenue stream forecast form with amount and percentage fields` | Too vague |
| 7 | actual-data.webp | `"actual data"` | `Upmetrics actual data tab showing import options for financial data` | Too vague |
| 8 | corresponding-upmetrics-forecast-category.webp | `""` (empty) | `mapping Xero chart of accounts to Upmetrics forecast categories` | Missing alt text |

**Note:** The "ai assistant blog" image in both CTAs is the old CTA image — alt text will be replaced automatically when CTAs are replaced with new templates (Type 4 / Type 9).

---

## Task 7: URL Slug

**Current slug:** `plan-vs-actual-analysis`

✅ **Skip.** The slug is clean, 4 words, and matches the target keyword. The top impression query "plan vs actual" maps naturally. No change needed.

---

## Task 8: Heading Structure

### Issue: H4 used without H3 parent

In the "Why conduct a plan vs. actual analysis" section, the content jumps directly from H2 → H4, skipping H3.

**Fix:** Change all 5 H4s in this section to H3:

| # | Current (H4) | Suggested (H3) |
|---|-------------|----------------|
| 1 | `<h4>Identify variances</h4>` | `<h3>Identify variances</h3>` |
| 2 | `<h4>Improve forecasting accuracy</h4>` | `<h3>Improve forecasting accuracy</h3>` |
| 3 | `<h4>Enhance decision-making</h4>` | `<h3>Enhance decision-making</h3>` |
| 4 | `<h4>Financial control and accountability</h4>` | `<h3>Financial control and accountability</h3>` |
| 5 | `<h4>Adjusting business strategies</h4>` | `<h3>Adjusting business strategies</h3>` |

**Note:** The duplicate H4 `"1. Start with the plan"` appearing in both the Spreadsheet and Upmetrics method sections is intentional (parallel structure) — not a real duplicate issue. No change needed there.

---

## Task 9: Categories

**Current:** Forecasting, Managing

✅ **Skip.** Both are appropriate:
- **Forecasting** — primary (financial projections, variance analysis)
- **Managing** — secondary (financial control, performance tracking, accountability)

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve all. Fix #1 (replace app login link anchor). Remove #3, #4 (Google Docs links). Fix #7 (remove duplicate link). Add #1–#5 new links.
Task 2 (CTAs): Replace CTA 1 → Type 4. Replace CTA 2 → Type 12. Add CTA 3 (Type 9) after Visualize section.
Task 3 (Resource CTA): Approve Sales Forecast Templates.
Task 4 (Related Content): Approve revised items #1–#4.
Task 5 (Meta Title/Desc): Approve suggested title. Approve description. Set keyphrase "plan vs actual analysis".
Task 6 (Image Alt Text): Approve all 8 updates.
Task 7 (URL Slug): Skip.
Task 8 (Headings): Approve H4 → H3 changes for all 5 headings.
Task 9 (Categories): Skip — no change needed.

Or simply: "Approve all except Task 7 and Task 9"
```
