# SEO On-Page Report — Market Analysis in a Business Plan

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/market-analysis-in-business-plan |
| **Post ID** | 6113 |
| **Post Type** | Blog Post (`post`) |
| **Report Date** | 2026-05-30 |
| **Word Count** | ~3,347 |
| **GSC Data Range** | 2026-03-01 → 2026-05-27 |
| **GA4 Data Range** | Last 30 days (Report A) / 90 days (Report E) |
| **Content Last Modified** | 2026-05-30 (freshly rewritten) |

---

## Section B — Page Health Score & Action Summary

### Page Health Score: 7.5 / 10

| Status | Count | Items |
|--------|:--:|-------|
| Critical | 0 | — |
| Needs Improvement | 4 | Thin internal linking (only 2 contextual links on a 3,347-word post), broken `href="#"` BLS link, no Resource CTA set, 2 image alts under length minimum |
| Good | — | Indexed (FAQ + Breadcrumb schema present), clean heading hierarchy, required Blog Post End CTA present, 19 cited authoritative external sources |

**Context:** The page ranks **position 47–60** for its core queries (`market analysis for business plan`, `analysis for marketing planning`). This is a **ranking/authority problem, not a CTR problem** — top queries are far below the position 4–20 window where a meta rewrite moves the needle. The single highest-leverage fix here is **internal linking** (passing equity from related high-traffic pages and tightening topical relevance), not meta tweaks. Content was rewritten today, so historical GSC positions reflect the older version.

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|---------------|
| 1 | Internal Links | High | Medium | 2 contextual + 1 branded | Add 5 contextual links; fix 1 broken external link | Add #1–#5, Fix BLS link |
| 2 | CTAs | Low | Medium | 1 mid-banner + required End CTA (both good) | Optional: 1 light Yellow Tip after Step 3 | Optional — Skip |
| 3 | Resource CTA | High | Quick Win | None set | Set "The Market Analysis Kit" | Approve |
| 4 | Related Content | Medium | Quick Win | (check sidebar) | Set 4 curated related items | Approve #1–#4 |
| 5 | Meta Title/Desc | Low | Quick Win | Not returned by API | Suggested title/desc provided (optional — ranking, not CTR, is the issue) | Optional |
| 6 | Image Alt Text | Medium | Quick Win | 3 content images, all have alt | Expand 2 short alts | Approve #1–#2 |
| 7 | URL Slug | — | — | `market-analysis-in-business-plan` (clean) | No change | Skip |
| 8 | Headings | — | — | Clean hierarchy, 1 H1, kw in H2s | No change | Skip |
| 9 | Categories | Low | Quick Win | (verify current) | Keep current — no change recommended | Skip |
| 10 | Incoming Links | Medium | — | Suggestion-only | 6 pages should link here | Noted |

---

## Section C — Task-by-Task Suggestions

### Task 1 — Internal Links

**Existing internal link audit:**

| # | Anchor Text | Target URL | Status |
|:--:|-------------|-----------|--------|
| E1 | financial projections | /blog/financial-projections-business-plan | Good |
| E2 | target market | /blog/how-to-find-your-target-market | Good |
| E3 | Upmetrics | / (homepage) | Good (branded) |
| E4 | BLS | `href="#"` (broken placeholder) | **Fix** |

**Current state:** Only 2 contextual internal links on a 3,347-word post — well below the 5–7 recommended for this length. One broken anchor (`href="#"`) sits in the Sunrise Coffee market-size table.

---

**Fix — Broken external link (E4):**

> **Fix** — `BLS` → currently `href="#"`, change to `https://www.bls.gov/news.release/cesan.nr0.htm`
>
> **Section:** Market analysis example → Market size table (SAM row)
>
> **In context:** "17,598 households × ~$590 annual coffee-shop spend (~15% of the $3,945 BLS food-away-from-home, **BLS**)"
>
> **Note:** The same BLS Consumer Expenditure Survey URL is already used correctly earlier in the article (Step 3 table). This restores the citation link.

---

**New internal link suggestions (Recommended):**

> **#1** — `your specific industry category` → `/blog/industry-analysis-in-business-plan`
>
> **Section:** Step 1 — Define and describe your industry
>
> **In context:** "Once you have the industry data, write a short paragraph that explains **your specific industry category**, the current market condition, and one or two trends that directly affect your business."

---

> **#2** — `free industry data` → `/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** Step 1 — Define and describe your industry
>
> **In context:** "Once you have the code, you can pull **free industry data** from a few places. Census Business Builder, Bureau of Labor Statistics Industries at a Glance, and Bureau of Economic Analysis industry-data tables."

---

> **#3** — `TAM, SAM, and SOM` → `/blog/tam-sam-som-market-size-metrics`
>
> **Section:** What to include → 3. Market size and growth
>
> **In context:** "An estimate of how big the demand is and how much of it you can realistically reach. This is where **TAM, SAM, and SOM** come in, and your SOM sets the limit on what you can earn in year 1."
>
> **Note:** Links to the dedicated market-sizing guide at the first mention, before the deep Step 3 walkthrough.

---

> **#4** — `your marketing plan` → `/blog/marketing-strategy-business-plan`
>
> **Section:** Step 7 — Connect your research to the rest of the business plan
>
> **In context:** "So your target market should match the customers in **your marketing plan**. Your SOM should support your revenue projections."

---

> **#5** — `writing a business plan` → `/blog/how-to-write-a-business-plan-complete-guide`
>
> **Section:** Introduction
>
> **In context:** "If you're **writing a business plan** for an SBA loan, bank financing, investors, or even just to test whether your idea makes sense, the market analysis section is often where you get stuck."
>
> **Note:** Links the pillar guide from the opening line — natural parent-topic reference.

---

<details>
<summary>Considered but skipped (4 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Find Your Target Market | Already linked in existing content (E2) |
| Financial Projections for Business Plan | Already linked in existing content (E1) |
| Competitive Analysis (dedicated page) | No dedicated WordPress page exists — verified empty in search |
| Why is Market Research Important / Types of Market Research | Moved to Related Content (Task 4) to avoid body+sidebar duplication |

</details>

---

### Task 2 — CTAs

**Existing CTA audit:**

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| C1 | Flex Banner (AI writing) | After Step 7, before the example | Good | Relevant, well-spaced |
| C2 | Blog Post End CTA (delivery-block) | End of content | Good | Canonical required end CTA — present and correct |

The post already satisfies the required end-CTA rule and has one mid-content banner. For a 3,347-word post the target is 2–3 CTAs, so the page is adequately covered. One optional light CTA could fill the CTA-free first half (Steps 1–6).

**New CTA suggestion (Optional):**

> **#1** — Yellow Tip (Type 12) | After "Step 3 — Size your market (TAM, SAM, SOM)"
>
> **Placed after:** "New businesses rarely capture more than a few percent of their addressable market that fast. So your SOM should be based on realistic customer reach, spending patterns, and your business operating capacity."
>
> **CTA Preview:**
> ```
> +---------------------------------------------------------+
> | Tip: Not sure how to size your market? Upmetrics' AI    |
> | research assistant pulls real TAM/SAM/SOM data for you. |
> +---------------------------------------------------------+
> ```
>
> **Note:** Well separated from the mid-banner (C1) which sits four sections later. Skip if you prefer to keep the read clean.

---

### Task 3 — Resource CTA

| Field | Value |
|-------|-------|
| **Recommended resource** | The Market Analysis Kit |
| **Resource URL** | https://upmetrics.co/download/market-analysis-kit |
| **resource_link_text** | `Download Kit` |
| **heading** | `Market Analysis Kit` |
| **Combined display** | "Download Kit: Market Analysis Kit" (34 chars) |

Exact-topic match for this article (post_id 7313). No resource CTA is currently set — this is a quick win.

---

### Task 4 — Related Content

Suggested 4 items (replaces existing sidebar). All curated to avoid duplication with body links (Task 1) and the Resource CTA (Task 3).

| # | Related Post | URL | Custom Title (≤50 chars) |
|:--:|-------------|-----|--------------------------|
| 1 | Why is Market Research Important | /blog/why-is-market-research-important | Why Market Research Makes or Breaks a Plan |
| 2 | Types of Market Research | /blog/types-of-market-research | Which Type of Market Research You Need |
| 3 | How to Validate a Business Idea | /blog/how-to-validate-business-idea | Is Your Business Idea Actually Viable? |
| 4 | What Lenders & Investors Look For | /blog/what-lenders-look-for-in-business-plan | What Lenders Want to See in Your Plan |

---

### Task 5 — Meta Title & Description

**Performance context:** The page's top queries rank **position 47–60** — outside the position 4–20 window where meta CTR optimization pays off. This is a ranking problem, so a meta rewrite is **low priority**. The `seo` object was not returned by the WordPress API, so current values could not be confirmed. If you want a freshly optimized meta for the rewritten content, here is a suggestion:

| Field | Suggested | Chars | Notes |
|-------|-----------|:--:|-------|
| Meta Title | How to Write a Market Analysis for a Business Plan (2026) | 56 | Front-loads primary kw; year hook; differs from H1 |
| Meta Description | Write a market analysis that proves real demand — with a 7-step framework, market-sizing math, and a funded coffee-shop example. Free kit inside. | 152 | Primary kw in first 40 chars; soft CTA |
| Focus Keyphrase | market analysis for business plan | — | Top GSC query (95 impressions, pos 53) |

**SERP Preview:**
```
-----------------------------------------------------------
upmetrics.co > blog > market-analysis-in-business-plan
How to Write a Market Analysis for a Business Plan (2026)
Write a market analysis that proves real demand - with a
7-step framework, market-sizing math, and a funded coffee-
shop example. Free kit inside.
-----------------------------------------------------------
```

---

### Task 6 — Image Alt Text

| Status | Count | Action |
|--------|:--:|--------|
| Good | 1 | No action |
| Needs Improvement | 2 | Expand (under 60-char minimum) |
| Decorative (CTA images) | 2 | No action |
| **Total** | **5** | — |

| # | src (filename) | Status | Current Alt | Suggested Alt | Chars |
|:--:|----------------|--------|-------------|---------------|:--:|
| 1 | market-analysis-in-business-plan-target-market-segmentation.png | Needs Improvement | Target market segmentation across four dimensions | Target market segmentation chart breaking buyers into demographic, geographic, behavioral, and psychographic segments | 116 |
| 2 | market-analysis-in-business-plan-competitor-comparison-matrix.png | Needs Improvement | Competitor comparison matrix for market analysis | Competitor comparison matrix scoring direct and indirect rivals on type, strengths, weaknesses, and pricing | 107 |

The seven-components infographic alt (`Seven components of a market analysis section in a business plan`, 61 chars) is Good — no change. The two CTA images (`Market research`, `crossline`) sit inside CTA blocks — leave as-is.

---

### Task 7 — URL Slug

`market-analysis-in-business-plan` is clean, keyword-focused, and 4 words. **No change** — and the page is indexed and ranking, so a slug change would needlessly risk a 301 chain.

---

### Task 8 — Heading Structure

Clean hierarchy: one H1, descriptive H2s for each major section, H3s for the 7 steps and the example sub-sections. Primary keyword "market analysis" appears in multiple H2s. **No change needed.**

---

### Task 9 — Categories

Post appears appropriately categorized for business-planning content. No change recommended without a specific mis-categorization. Skip.

---

### Task 10 — Incoming Internal Link Suggestions (for SEO team)

Pages that should link **to** this market-analysis guide. All verified in WordPress (real post IDs). Excludes Task 1 targets (no reciprocal links).

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|
| 1 | How to Write a Lounge Business Plan | /blog/lounge-business-plan | 102753 | post | Industry plan guide with a market-analysis section | market analysis section | High |
| 2 | How to Write a Franchise Business Plan | /blog/franchise-business-plan | 106325 | post | Industry plan guide covering market research | market analysis | High |
| 3 | How to Write a Nonprofit Business Plan | /blog/nonprofit-business-plan | 106581 | post | Plan guide needing market-demand evidence | market analysis | Medium |
| 4 | How to Validate a Business Idea | /blog/how-to-validate-business-idea | 106793 | post | Validation hinges on market demand | market analysis for a business plan | Medium |
| 5 | Why is Market Research Important | /blog/why-is-market-research-important | 108279 | post | Adjacent topic — natural next step | write a market analysis | Medium |
| 6 | Business Expansion Plan | /blog/business-expansion-plan | 106868 | post | Expansion requires fresh market analysis | market analysis | Low |

> Every source URL above is verified in WordPress (real post_id). Suggested anchor text is a starting search term for the SEO team — confirm the phrase exists in each source page before linking.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1-#5. Fix the broken BLS link.
Task 2 (CTAs): Skip (page already well covered).
Task 3 (Resource CTA): Approve Market Analysis Kit.
Task 4 (Related Content): Approve items #1-#4.
Task 5 (Meta Title/Desc): Skip (ranking issue, not CTR) — or approve suggested title/desc.
Task 6 (Image Alt Text): Approve #1, #2.
Task 7 (URL Slug): Skip.
Task 8 (Headings): Skip.
Task 9 (Categories): Skip.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task 2 and Task 5"**
