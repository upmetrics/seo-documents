# SEO Suggestion Report — Essential Elements of Strategic Planning

| Field | Value |
|-------|-------|
| **Page URL** | https://upmetrics.co/blog/elements-of-strategic-planning |
| **Post ID** | 63611 |
| **Post Type** | `post` (Blog Post) |
| **Brand** | Upmetrics |
| **Category** | Managing |
| **Published / Modified** | 2024-06-05 / **2026-09-08** (rewritten 3 days ago) |
| **Word Count** | 1,911 |
| **Report Date** | 2026-09-11 |
| **GSC Data Range** | 2026-06-13 to 2026-09-08 (90 days) |
| **GA4 Data Range** | 30-day (engagement) + 90-day (conversions) |

---

## Section B — Page Health Score & Action Summary

### Page Health Score: **5.5 / 10**

**The headline:** the content itself is strong — clean heading hierarchy, good alt text, a well-placed download CTA, the canonical end CTA intact. The problem is everything *around* the content. The meta title is a verbatim copy of the H1 and 10 characters too short, the Resource CTA and Related Content panels are both completely empty, and three of the six core-element sections carry zero internal links. The page earns **0 clicks from 12 impressions** at positions 55-91 — it is indexed but effectively invisible.

| Deduction | Points |
|-----------|:--:|
| Meta title below 50 characters (currently 40) | -1 |
| Meta title identical to H1 | -1 |
| Meta title has no differentiation hook | -1 |
| Meta description below 140 characters (currently 130) | -1 |
| Single-word anchor text on an existing internal link (`vision`) | -0.5 |
| **Final** | **5.5 / 10** |

| Status | Count | Items |
|--------|:--:|-------|
| **Critical** | 0 | — |
| **Needs Improvement** | 5 | Meta title (3 rule breaks), meta description length, Resource CTA unset, Related Content unset, category fit |
| **Minor** | 2 | 1-word `vision` anchor, lead image alt missing primary keyword |
| **Good** | 6 | Indexing, canonical, Blog Post End CTA, heading hierarchy, image alt quality, URL slug |

### Search Performance Context

| Metric | Value |
|--------|-------|
| Clicks (90d) | **0** |
| Impressions (90d) | **12** |
| Distinct queries | 9 |
| Best position | 55.0 (`what are the elements of a strategic plan`) |
| Worst position | 91.0 (`key elements of a strategic plan`) |
| GA4 sessions (90d) | **7** |
| Index status | **Submitted and indexed** — last crawled 2026-09-07 |
| Rich results | Breadcrumbs only (Article + FAQPage markup present on page but not picked up as a rich result) |

> **Note on Task 5:** the standard CTR-vs-position benchmark check does not apply here. Every query sits at position 55-91, far outside the benchmark table (which stops at position 20). This is not a "meta is losing clicks" problem — it is a "page has no ranking to lose clicks from" problem. The meta rewrite below is justified on hard rule violations (length, H1 duplication, no hook), not on CTR underperformance.

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|--------------|---------------|
| 1 | Internal Links | High | Medium | 8 internal links; sections 4, 5, 6 have zero | Add 4 links to the unlinked sections; fix 1 weak anchor | None | **Add #1-#4, fix existing #4** |
| 2 | CTA Placements | Medium | Medium | 2 CTAs (download link + end CTA), both good | Add 1 light Yellow Tip after section 5 | None | **Add #1** |
| 3 | Resource CTA | High | Quick Win | **Not set** | Set to The Market Analysis Kit | None | **Approve** |
| 4 | Related Content | High | Quick Win | **Not set** | Set 4 strategy-focused items | Tasks 1, 3 dedup | **Approve #1-#4** |
| 5 | Meta Title / Desc | High | Quick Win | Title = H1, 40 chars; desc 130 chars | Rewrite both; set focus keyphrase | None | **Approve** |
| 6 | Image Alt Text | Low | Quick Win | Both content images have good alt | Optional keyword add on lead image | None | **Skip (optional only)** |
| 7 | URL Slug | — | — | `elements-of-strategic-planning` — clean | No change needed | None | **Skip** |
| 8 | Heading Structure | Low | Quick Win | Correct hierarchy, no H1 conflict | Optional: rename generic "Conclusion" | None | **Skip (optional only)** |
| 9 | Categories | Medium | Quick Win | Managing | Planning (primary) + Managing | None | **Approve** |
| 10 | Incoming Links | Medium | — | Suggestion only | 5 source pages to link from | Manual | **Noted** |

---

## Section C — Task-by-Task Suggestions

### TASK 1: Internal Linking

**Part A — Existing Link Audit**

8 internal links across 1,911 words (~1 per 240 words) — already slightly denser than the 1-per-300-500 ideal, so new links are kept deliberately tight and placed only in sections that currently have none.

| # | Anchor Text | Target URL | Status |
|:--:|-------------|-----------|--------|
| 1 | Strategic planning | `/blog/strategic-business-planning` | **Good** |
| 2 | &rarr; Download Now: Strategic Planning Templates | `/strategic-planning-templates` | **Good** (Type 1 CTA, see Task 2) |
| 3 | mission statement | `/blog/mission-statement-business-plan` | **Good** |
| 4 | vision | `/blog/vision-statement-business-plan` | **Needs Fix** — single-word anchor; trailing space sits inside the tag |
| 5 | SWOT analysis | `/blog/how-to-do-a-swot-analysis` | **Good** |
| 6 | PESTLE analysis | `/blog/pestle-analysis` | **Good** |
| 7 | SMART goals framework | `/blog/write-smart-goals` | **Good** |
| 8 | Upmetrics' strategic planning tools | `/features/strategic-planning` | **Good** (only Sales/Features link) |

No broken links, no competitor outbound links, no query strings, no links inside headings. Target URL stays the same for #4 — only the anchor text changes.

---

**Fix to existing link #4**

> **Existing #4** — `vision` &rarr; `/blog/vision-statement-business-plan`
>
> **Section:** 1. Mission, vision, and values
>
> **Original:** "Your mission statement explains what the business does, who it serves, and why it exists today. Your **vision** describes where you want the business to be in the future. Your values set the principles you want to follow when making important decisions."
>
> **Modified:** "Your mission statement explains what the business does, who it serves, and why it exists today. Your **vision statement** describes where you want the business to be in the future. Your values set the principles you want to follow when making important decisions."
>
> **Note:** Expands a 1-word anchor to 2 words and makes it parallel with "mission statement" in the preceding sentence. Also removes the stray space currently trapped inside the `<a>` tag. Meaning preserved.

---

**Part B — New Link Suggestions**

Link distribution today: intro 0, "What is strategic planning?" 1, element 1 has 2, element 2 has 2, element 3 has 1, **elements 4, 5, 6 have 0**, "How to keep your plan useful" 0, conclusion 1. All four recommendations below land in the unlinked half of the article.

**Recommended (4)**

> **#1** — `key performance indicators` &rarr; `/blog/critical-business-kpis`
>
> **Section:** 6. KPIs and review cadence
>
> **In context:** "Finally, decide how you will measure progress and how often you will check it. Select a set of important KPIs (**key performance indicators**) that are directly tied to your objectives and strategies. These might be revenue, customer retention, sales leads, profit margin, capacity, or any metric that is strong and clearly demonstrates progress towards the goal."
>
> **Note:** Wraps existing text, zero edits. The target page is a dedicated KPI explainer, so the anchor promise matches the destination exactly.

---

> **#2** — `your financial forecast` &rarr; `/blog/what-is-financial-forecasting`
>
> **Section:** 5. Action plan and resource allocation
>
> **In context:** "You do not need to add detailed financial projections here. Those calculations can stay in **your financial forecast**. In the strategic plan, you only need enough detail to show what the strategy will cost and whether the business can support it."
>
> **Note:** Wraps existing text, zero edits. The article explicitly hands the reader off to "your financial forecast" and then leaves them there — this gives them somewhere to go.

---

> **#3** — `revisit the plan` &rarr; `/blog/how-to-conduct-a-monthly-business-plan-review-meeting`
>
> **Section:** How to keep your strategic plan useful?
>
> **In context:** "Use it when making important decisions about where to spend time, money, or resources. If a new opportunity comes up, check whether it supports the goals and direction you have already set. At the same time, **revisit the plan** when something important changes, such as:"
>
> **Note:** Wraps existing text, zero edits. Section 6 sets up a review cadence but never explains how to actually run a review — this fills that gap.

---

> **#4** — `a new geographic market` &rarr; `/blog/business-expansion-plan`
>
> **Section:** 4. Strategies
>
> **In context:** "Take Northstar's goal of growing its healthcare business. The company could: *Expand into **a new geographic market*** / *Compete for large hospital contracts* / *Specialize in outpatient clinics within its existing service area*"
>
> **Note:** Wraps existing text in a list item, zero edits. Lowest-ranked of the four (list placement is less ideal than paragraph, and the target has modest traffic), but it is the only natural anchor in an otherwise link-free section.

---

**Optional (2)**

> **#5** — `setting your own goals` &rarr; `/blog/how-to-set-business-goals`
>
> **Section:** 3. Goals and objectives
>
> **In context:** "When **setting your own goals**, focus on a few outcomes that are important enough to shape business decisions. Then make each objective specific and measurable, with a clear target and timeframe. You can use the SMART goals framework as a simple check for this."
>
> **Note:** Excellent topical match, but it sits roughly 30 words before the existing SMART goals link **in the same paragraph**. Two goal-related links that close together reads as over-linking. Optional rather than recommended for that reason.

---

> **#6** — `the resources needed` &rarr; `/blog/allocation-of-funds`
>
> **Section:** 5. Action plan and resource allocation
>
> **In context:** "Here, I'd suggest you check whether you already have **the resources needed** for each action. If something is missing, note what you will need to add, such as another employee, new equipment, more staff time, or additional budget."
>
> **Note:** Sits ~80 words from suggestion #2 in the same section — within the 100-word spacing floor. Take this **or** #2, not both.

<details>
<summary>Considered but skipped (6 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| Business Plan Vs Strategic Plan | No matching anchor text in body — "business plan" never appears outside the end CTA. Claimed by Task 4 instead. |
| How to Create a Business Strategy | Section 4 has no phrase that wraps cleanly; would need a new sentence. Claimed by Task 4. |
| Strategic Business Planning | Already linked in existing content (audit #1) |
| What is a Competitive Advantage? | "competitive" does not appear anywhere in the content |
| Industry Benchmarking | "benchmark" does not appear anywhere in the content |
| Startup / Lean / Business Model Canvas | Template post type — excluded from Task 1 by rule; covered by the existing Type 1 CTA |

</details>

> **Balance note:** existing links run 7 Informational : 1 Sales/Features, and all four recommendations are Informational — pushing the ratio further from the 60-70/30-40 blog-post target. This is deliberate. There is no place in this article where a product link reads as editorial rather than promotional, and the new CTA in Task 2 covers the commercial angle more honestly than a forced body link would.

---

### TASK 2: CTA Placements

**Part A — Existing CTA Audit**

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Type 1 — Download Link | After "What is strategic planning?" section | **Good** | Relevant destination, lightweight, well-positioned early |
| 2 | Blog Post End CTA (`delivery-block`) | Last block of content | **Good** | Canonical headline verified verbatim — do not modify |

The required Upmetrics end CTA is present in raw HTML form with the exact canonical copy. No action needed.

**Part B — New CTA Suggestions**

At 1,911 words the target is 2-3 CTAs. There is currently 1 content CTA plus the required end CTA, so exactly one addition is appropriate — and it should be a light text CTA, not a banner, since the end CTA already supplies the page's one large visual block.

**Recommended (1)**

> **#1** — Yellow Tip Alert (Type 12) | After "5. Action plan and resource allocation", before the "6. KPIs and review cadence" heading
>
> **Placed after:** "You do not need to add detailed financial projections here. Those calculations can stay in your financial forecast. In the strategic plan, you only need enough detail to show what the strategy will cost and whether the business can support it."
>
> **CTA Preview:**
> ```
> +---------------------------------------------------------+
> | Tip: If an action needs extra spending, check the        |
> | numbers before you commit. Our financial forecasting     |
> | tool turns rough cost estimates into a budget and cash   |
> | flow view.                                               |
> +---------------------------------------------------------+
> ```
>
> **Destination:** `/features/financial-forecasting` — tagged high-conversion (67 conversions / 90d in GA4 Report E)
>
> **Angle:** Specificity — names the exact capability rather than making a generic pitch. **Spacing:** ~1,100 words after the Type 1 CTA and ~790 words before the end CTA, so no two CTAs share a screen.

---

### TASK 3: Downloadable Resource CTA

**Current state: not set.** The ACF Resources Hero CTA fields are empty — the page renders no resource banner at all. This is the single highest-value quick win in the report.

| Rank | Resource | URL | Sessions (90d) | Engagement | Verdict |
|:--:|----------|-----|:--:|:--:|---------|
| 1 | The Market Analysis Kit | `/download/market-analysis-kit` | 106 | 0.83 | **Recommended** |
| 2 | Free Business Plan Template | `/download/business-plan-template` | 525 | 0.72 | Alternative |
| — | Strategic Planning Templates | `/strategic-planning-templates` | 119 | 0.82 | **Excluded** — already the Type 1 CTA destination in the body; using it here would show the same resource twice |

**Recommended settings:**

| Parameter | Value |
|-----------|-------|
| `resource_url` | `https://upmetrics.co/download/market-analysis-kit` |
| `heading` | `Market Analysis Kit` |
| `resource_link_text` | `Download Template` |
| **Rendered display** | `Download Template: Market Analysis Kit` (38 chars — well under the ~55 limit) |

**Why the Market Analysis Kit over the higher-traffic business plan template:** element 2 (Situational analysis) is the most research-heavy part of this article — SWOT, PESTLE, market and competitor signals — and the Market Analysis Kit is the only download that maps onto it. The business plan template is higher traffic but topically adjacent at best, and the end CTA already pushes business-plan creation. Say the word and I will swap to the template instead.

---

### TASK 4: Related Content

**Current state: not set.** The sidebar renders nothing. All four slots are available.

Selected from the repository after excluding every URL claimed by Tasks 1, 2 and 3.

| # | Post ID | Page | URL | Custom Title (chars) | Sessions (90d) |
|:--:|:--:|------|-----|---------------------|:--:|
| 1 | 60227 | Business Plan Vs Strategic Plan: What's the Difference? | `/blog/business-plan-vs-strategic-plan` | **Strategic Plan or Business Plan?** (32) | 79 |
| 2 | 73286 | How to Create a Business Strategy for Your Startup? | `/blog/how-to-create-a-business-strategy` | **Picking a Strategy That Fits Your Business** (42) | 6 |
| 3 | 108484 | Best AI Strategy Tools for Business Planning | `/blog/ai-strategy-tools` | **AI Tools That Help You Plan Strategy** (36) | 77 |
| 4 | 83417 | How to Create a Business Growth Plan | `/blog/business-growth-plan` | **What a Growth Plan Should Cover** (31) | 34 |

All four titles are under the 50-character sidebar limit and rewritten for curiosity rather than keyword repetition. #1 directly answers the question this page's own FAQ schema already poses. #2 has low traffic but is the natural next step from element 4 (Strategies), which this article deliberately keeps brief.

> `set-related-pages` replaces the entire repeater, so this set is complete and self-contained.

---

### TASK 5: Meta Title & Description

**Part A — Performance context**

| Top Query | Impressions | Position | Current CTR | Benchmark | Status |
|-----------|:--:|:--:|:--:|:--:|:--:|
| 7 important elements of a strategic plan | 3 | 61.3 | 0% | n/a | Out of benchmark range |
| components of strategic planning | 2 | 56.0 | 0% | n/a | Out of benchmark range |
| what are the elements of a strategic plan | 1 | 55.0 | 0% | n/a | Out of benchmark range |
| elements of strategic planning | 1 | 85.0 | 0% | n/a | Out of benchmark range |
| key elements of a strategic plan | 1 | 91.0 | 0% | n/a | Out of benchmark range |

No query reaches position 20, so the CTR benchmark check cannot fire. The rewrite below is justified entirely on rule violations.

**Classification: Critical rewrite** — the title is identical to the H1 *and* falls below the 50-character floor *and* carries no differentiation hook. Three independent hard-rule breaks.

**Part B — Current vs. suggested**

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | Essential Elements of Strategic Planning | 40 | **6 Core Elements of Strategic Planning (With Examples)** | 53 | Number hook + format signal; keyword ends at char 37; no longer mirrors H1 |
| Meta Description | Learn the 6 core elements of strategic planning, what each part should include, and how to put them together with simple examples. | 130 | **The 6 core elements of strategic planning, explained one by one: mission, situational analysis, goals, strategy, action plan, and KPIs. See examples.** | 149 | Names all six elements so the snippet matches more long-tail variants; keyword at char 11 |
| Focus Keyphrase | *(not set)* | — | **elements of strategic planning** | — | Exact-match to slug and a live GSC query |
| Canonical | `/blog/elements-of-strategic-planning` | — | *(unchanged)* | — | Correct — matches Google's chosen canonical |
| OG Title | Essential Elements of Strategic Planning | 40 | *(match new meta title)* | 53 | — |
| OG Description | *(mirrors meta description)* | 130 | *(match new meta description)* | 149 | — |

**SERP Preview**

```
─────────────────────────────────────────────────────────────
upmetrics.co › blog › elements-of-strategic-planning
6 Core Elements of Strategic Planning (With Examples)
The 6 core elements of strategic planning, explained one by
one: mission, situational analysis, goals, strategy, action
plan, and KPIs. See examples.
─────────────────────────────────────────────────────────────
```

**Differentiator:** competing results for "elements of strategic planning" lean on vague authority framings ("Key Elements of...", "Complete Guide to..."). Leading with the explicit count **6** plus **(With Examples)** signals a finite, worked-through list rather than another overview — and it matches the H2 the reader lands on, so the promise holds.

Both strings pass the banned-AI-word scan and use straight ASCII apostrophes only.

---

### TASK 6: Image Alt Text

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty (wrong) | 0 | — |
| Needs Improvement | 0 | — |
| Good | 2 | No action |
| Decorative — Correct | 1 | No action (`crossline.png` inside the end CTA) |
| **Total images in content** | **3** | — |

Both content images already carry specific, well-written alt text within the 60-125 character range, with no banned openers. **Nothing here requires fixing.** One optional refinement only:

| # | src | Status | Current Alt | Suggested Alt | Chars | Notes |
|:--:|-----|--------|-------------|---------------|:--:|-------|
| 1 | `elements-of-strategic-planning-situational-analysis.png` | Good (optional) | Situational analysis framework covering business performance, customers and market, and opportunities and risks | Situational analysis in strategic planning: business performance, customers and market, opportunities and risks | 111 | Adds the primary keyword to the lead in-content image — currently no alt on the page carries it |

> The hero/featured image (`elements-of-strategic-planning-hero.png`) sits outside the editor content and cannot be edited through this workflow. Worth a manual check in the media library.

---

### TASK 7: URL Slug

**No change recommended.**

| Check | Result |
|-------|--------|
| Contains primary keyword | Yes — `elements-of-strategic-planning` |
| Word count / length | 4 words, 30 characters |
| Formatting | Lowercase, hyphens, no stop words, no double hyphens, no parameters |

The slug is already optimal. Changing it would only create redirect overhead for zero gain.

---

### TASK 8: Heading Structure

| Check | Result |
|-------|--------|
| Exactly one H1 | Yes — rendered by the theme from the post title; content correctly contains no H1 |
| H2/H3 nesting | Correct — six H3 elements all sit under the "6 core elements" H2, no skipped levels |
| Primary keyword in an H2 | Yes — "What is strategic planning?" and "6 core elements to include in a strategic plan" |
| Heading length (<70 chars) | Yes — longest is 51 chars |
| Duplicate headings | None |

**Optional (1):**

| Current | Suggested | Reason |
|---------|-----------|--------|
| `Conclusion` (H2) | `Putting the six elements together` | Generic label carrying no keyword or reader value. Low priority — cosmetic. |

---

### TASK 9: Category / Taxonomy Assignment

| Field | Current | Suggested |
|-------|---------|-----------|
| Categories | Managing | **Planning** (primary), **Managing** (secondary) |

The Upmetrics category reference assigns "strategic planning basics" explicitly to **Planning**. Managing is a defensible secondary — the article does cover KPIs and review cadence — but Planning should lead, and this page currently sits outside the blog's main planning cluster entirely.

---

### TASK 10: Incoming Internal Link Suggestions

This page has essentially no internal link equity flowing into it, which is a large part of why it sits at position 55-91 despite solid content. Every source below is a verified WordPress post.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic (90d) | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | Internal Business Plan: What to Include and How to Write It | `/blog/internal-business-plan` | 106714 | post | Internal plans and strategic plans serve the same purpose — direct topical overlap; 0.64 engagement rate | elements of a strategic plan | 64 sessions | High |
| 2 | Business Plan Components: What to Write in Each Section | `/blog/business-plan-components` | 23817 | post | Structurally parallel "what goes in each section" article; highest traffic of any candidate | strategic planning elements | 243 sessions | High |
| 3 | Strategic Marketing Process: A Full Step-by-Step Guide | `/blog/strategic-marketing-process` | 6133 | post | Shares the strategy-process frame; 0.71 engagement rate | strategic planning process | 24 sessions | Medium |
| 4 | What is a Business Plan: Definition, Use Cases, Resources & More | `/blog/what-is-business-plan` | 77811 | post | Broad definitional hub — natural place to branch into strategic planning | strategic planning | 79 sessions | Medium |
| 5 | Complete Guide to Lean Business Planning for Startups | `/blog/lean-business-planning` | 6123 | post | Planning-methodology article; 0.62 engagement rate | elements of strategic planning | 21 sessions | Medium |

> Every source URL above is verified in WordPress (real post_id). Suggested anchor text is a starting term for the SEO team to search within the source page — the actual anchor depends on what text exists in that page's content. Traffic shown is GA4 sessions over 90 days (these pages fall below the GSC top-250 click threshold, so GSC click data is not available for them).

**Excluded as reciprocal:** `/blog/strategic-business-planning` (linked from this page), and the four pages claimed by Task 4.

> **Bigger opportunity spotted:** `help.upmetrics.co/article/112-create-canvas` is pulling **272 impressions for "strategic planning models"** and 181 for "strategic plan models" at positions 50-68. A help-centre article is outranking the blog for core strategic-planning terms. That is a content-strategy question rather than an on-page fix for this URL, but it is worth raising with the team.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2, #3, #4. Fix existing #4 (vision statement). Skip #5, #6.
Task 2 (CTAs): Add #1 Yellow Tip after section 5.
Task 3 (Resource CTA): Approve Market Analysis Kit.
Task 4 (Related Content): Approve items #1-#4.
Task 5 (Meta Title/Desc): Approve title. Approve description. Approve focus keyphrase. Approve OG updates.
Task 6 (Image Alt Text): Skip — no changes needed.
Task 7 (URL Slug): Skip — slug already optimal.
Task 8 (Headings): Skip — structure is correct.
Task 9 (Categories): Approve Planning + Managing.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task X"**
