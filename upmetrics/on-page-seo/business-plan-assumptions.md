# On-Page SEO Report — Business Plan Assumptions

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/business-plan-assumptions |
| **Post ID** | 109705 |
| **Post Type** | `post` (Blog Post) |
| **Published** | 2026-08-27 (4 days old) |
| **Last Modified** | 2026-08-27 16:53 |
| **Word Count** | 1,922 |
| **Report Date** | 2026-08-31 |
| **GSC Range** | 2026-06-02 to 2026-08-28 |
| **GA4 Range** | 30 days (engagement), 90 days (conversions) |

> **Read this first.** The page went live 4 days ago and has **11 impressions, 0 clicks, avg position 19.3** — all from a single day (2026-08-28). It is already ranking **position 6 for "business plan assumptions"**. There is not enough data for CTR-based decisions yet, so this report deliberately avoids rewriting anything that is performing. The wins here are **additive**: two empty ACF slots and a set of internal links.

**Index status (URL Inspection API):** `PASS` — *Submitted and indexed*. Robots `ALLOWED`, indexing `ALLOWED`, fetch `SUCCESSFUL`, last crawled **2026-08-27 21:34 UTC** as **MOBILE**. Google's canonical matches the declared canonical exactly. Nothing to fix here.

---

## Section B — Page Health Score & Action Summary

### Page Health Score: 9 / 10

| Status | Count | Items |
|--------|:--:|-------|
| Critical | 0 | — |
| Needs Improvement | 1 | Meta title is identical to the H1 (-1) |
| Good | 9 | Indexing, canonical, OG tags, meta lengths, heading hierarchy, image alt text, end CTA, no stale year references, no competitor outlinks |

This is a well-built new post. The score is high because there are no defects — but note that **Resource CTA and Related Content are both completely empty**, which is lost real estate rather than a scored fault.

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|--------------|---------------|
| 1 | Internal Links | High | Medium | 4 body links, all Informational, 0 Sales | Add 5 links (4 informational + 1 sales) | — | Add #1-#5 |
| 2 | CTA Placements | Medium | Medium | 1 (end CTA, canonical & correct) | Add 1 light Yellow Tip mid-content | — | Add #1 |
| 3 | Resource CTA | High | Quick Win | **Empty** | Set Sales Forecast Templates | — | Approve |
| 4 | Related Content | High | Quick Win | **Empty** | Set 4 related items | After Tasks 1-3 | Approve #1-#4 |
| 5 | Meta Title / Desc | Medium | Quick Win | Title = H1 (52ch); desc 145ch OK | Differentiate title only; keep desc | — | Approve title |
| 6 | Image Alt Text | Low | Quick Win | 1 content image, good alt | No action needed | — | Skip |
| 7 | URL Slug | — | — | `business-plan-assumptions` | Do not touch — pos 6 for primary kw | — | Skip (risky) |
| 8 | Heading Structure | Low | Quick Win | Clean: 4 H2, 6 H3, no skips | No action needed | — | Skip |
| 9 | Categories | Medium | Quick Win | `Planning` only | Add `Forecasting` | — | Approve |
| 10 | Incoming Links | Medium | Manual | Not measured | 8 source pages that already rank for the topic | Manual | Noted |

---

## Section C — Task-by-Task Suggestions

### TASK 1 — Internal Linking

#### Part A: Existing Link Audit

| # | Anchor Text | Target URL | Type | Status |
|:--:|-------------|-----------|------|--------|
| 1 | pricing strategy | `/blog/pricing-strategy-business-plan` | Informational | **Good** |
| 2 | how much funding you expect | `/blog/how-much-funding-do-you-need` | Informational | **Good** |
| 3 | market analysis | `/blog/market-analysis-in-business-plan` | Informational | **Good** |
| 4 | financial plan section | `/blog/write-financial-section-startup-business-plan` | Informational | **Good** |
| 5 | Upmetrics | `/` (homepage) | Branded | **Good** — branded homepage link in conclusion, standard practice |

**External links:** 3 outbound (census.gov, ibisworld.com, bls.gov). All authoritative government/industry sources, none on the competitor list. **Keep all three.**

**One minor note:** all three external links carry `rel="noopener"` but have no `target="_blank"`. `noopener` does nothing without a new-tab target — harmless, but the intent was probably to open them in a new tab.

**Current state:** 4 contextual internal links across 1,922 words (~1 per 480 words) — on target for length. All 4 are Informational; there are **zero** Sales/Features links, which is why suggestion #5 below is a product page.

**Also on the page:** FAQ #1 (ACF field, renders below the article) already links to `/blog/financial-projections-business-plan`. See the note on suggestion #1.

#### Part B: New Link Suggestions

> **#1 — RECOMMENDED** — `build your financial projections` → `/blog/financial-projections-business-plan`
>
> **Section:** Introduction (paragraph 2)
>
> **In context:** "That becomes especially difficult when you're starting a new business with little or no historical data. You still need reasonable numbers to plan how the business will operate and **build your financial projections**, but those numbers shouldn't be arbitrary guesses."
>
> **Note:** The single highest-value link on the page — the article's whole premise is that assumptions feed projections, and this exact phrase sits unlinked in the intro. **Be aware:** FAQ #1 already links this same URL further down the page. A body link plus an FAQ link to one URL is common and low-risk, but if you want strict one-link-per-URL, skip this and keep the FAQ link.

---

> **#2 — RECOMMENDED** — `lenders or investors` → `/blog/what-lenders-look-for-in-business-plan`
>
> **Section:** How to document assumptions in your business plan (final paragraph)
>
> **In context:** "Focus on the assumptions that have the biggest effect on your sales, costs, operations, cash flow, or funding needs. And these are the numbers **lenders or investors** are most likely to look at, and the ones you'll need to revisit as your business starts generating real results."
>
> **Note:** Exact topical match — the sentence raises the question the target page answers, right at the point the reader is most likely to act.

---

> **#3 — RECOMMENDED** — `revenue and cash` → `/blog/cash-flow-vs-profit`
>
> **Section:** Funding and cash flow assumptions
>
> **In context:** "Cash flow assumptions focus on when money is expected to come in and when it needs to go out. This matters because **revenue and cash** are not always received at the same time. You can use expected customer payment terms, supplier payment terms, deposits, loan repayments, and other payment schedules to estimate that timing."
>
> **Note:** The sentence states the exact distinction the target page explains in full. Target is a strong performer — 411 GA4 sessions, 82% engagement rate, 75 conversions in 90 days.

---

> **#4 — RECOMMENDED** — `operations section` → `/blog/operations-plan-section`
>
> **Section:** How to document assumptions in your business plan (bullet list)
>
> **In context:** "Staffing or capacity assumptions can sit in the **operations section**."
>
> **Note:** Direct match. This is a list item rather than a paragraph — acceptable, and it is the only place the phrase appears. The two other bullets in this list already link out (market analysis, financial plan section), so this completes the set and makes the list internally consistent.

---

> **#5 — RECOMMENDED** — `sales forecast` → `/blog/how-to-forecast-sales-for-business`
>
> **Section:** Operational assumptions
>
> **In context:** "For the salon, the **sales forecast** assumes 18 customers a day. That number only works if the salon has enough stylists, appointment slots, and working hours to serve those customers."
>
> **Note:** "Sales forecast" is a topic noun, so the how-to guide wins over the product page — the target teaches exactly what the anchor names. It is also the stronger page by a wide margin: **3,995 impressions** for sales-forecast queries versus 607 for the feature page.
>
> **Sales/Features alternative for the same anchor:** `/features/sales-forecasting` (post ID 80455). Pick this instead if you want the post to carry one product link in the body. It is a weaker topical match and ranks at position 63, so the how-to page is the better SEO choice — but the call is yours.

**A note on link balance:** with the set above, all five recommended links are Informational and the post carries **zero** Sales/Features body links. That is deliberate. This is an educational explainer, the product already appears three times on the page (the Task 2 Yellow Tip CTA, the branded homepage link in the conclusion, and the end CTA), and forcing more product links into a 1,922-word explainer would read promotional. If you want a body-level product link, take the #5 alternative above.

---

> **#6 — OPTIONAL** — `market you can realistically reach` → `/blog/tam-sam-som-market-size-metrics`
>
> **Section:** Market assumptions
>
> **In context:** "To make these estimates, start with the **market you can realistically reach**. Look at local customer or population data, nearby competitors, customer interviews or surveys, and any early interest you've already seen."
>
> **Note:** Good match on market sizing. Marked optional only because five links is already on target for 1,922 words. If you take this one, consider dropping #4.

---

> **#7 — OPTIONAL** — `market research` → `/blog/types-of-market-research`
>
> **Section:** What are business plan assumptions?
>
> **In context:** "Since these estimates influence other parts of your plan, they shouldn't be random. Important ones should be based on the best information available, such as **market research**, past results, supplier quotes, or comparable businesses."

---

> **#8 — OPTIONAL** — `equipment costs` → `/startup-costs`
>
> **Section:** Introduction (paragraph 1)
>
> **In context:** "When you start building a business plan, some numbers are already known, such as rent, pricing, **equipment costs**, or employee wages."
>
> **Note:** Weakest of the set. It also sits within ~60 words of suggestion #1, so taking both would cluster two links in the intro. Take #1 over this one.

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| `/blog/market-analysis-in-business-plan` | Already linked in existing content |
| `/blog/write-financial-section-startup-business-plan` | Already linked in existing content |
| `/blog/how-to-write-a-business-plan` | No natural unlinked anchor; claimed by Task 4 (Related Content) |
| `/blog/business-model` | "business model" appears once, but the target is a 22-examples listicle, not an explainer — weak anchor-to-content match |
| `/download/operations-plan-template` | Download post type — excluded from body links by rule; belongs in Task 3 instead |

Two glossary pages that looked promising on title alone — a break-even analysis entry and a SWOT analysis entry — were dropped after checking them: both return **410 Gone** on the live site, and neither topic is discussed in this article.

</details>

---

### TASK 2 — CTA Placements

#### Part A: Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Blog Post End CTA (`delivery-block`) | Very last block | **Good** | Headline, subtitle, button text, URL and image all match the canonical registry version exactly. No changes. |

No Elementor shortcode is present; the end CTA is the hardcoded `delivery-block` form. That satisfies the required-end-CTA rule.

#### Part B: New CTA Suggestion

At 1,922 words the target is 1-2 CTAs. There is already one large banner at the end, so the guidance is a **light text CTA** for the mid-content slot rather than a second banner.

> **#1 — RECOMMENDED** — Yellow Tip Alert (Type 12) | After "Funding and cash flow assumptions"
>
> **Placed after:** "Here, I'd say: pay particular attention to timing gaps. If major expenses, such as payroll, rent, or supplier bills, are due before customer payments or funding arrive, the business may need extra cash to cover the gap."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │ Tip: Cash timing is easy to get wrong by hand. Our      │
> │ cash flow forecasting tool lets you test payment terms  │
> │ and see exactly when the gap appears.                   │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Angle:** Specificity (names the exact feature). **Links to:** `/features/cash-flow-forecasting` — 478 GA4 sessions, 79% engagement, 49 conversions.
>
> **Why here:** It follows the one paragraph in the article that names a concrete, painful problem (a timing gap you cannot see without modelling it). Two full sections sit between this and the end CTA, so they never share a screen.

**Optional second CTA:** an Inline Banner (Type 11) after "Cost and expense assumptions" would be defensible, but it pushes the post to 3 CTAs — above target for this length. Recommend skipping unless you want the extra touchpoint.

---

### TASK 3 — Downloadable Resource CTA

**Current state: EMPTY.** `cta_post_heading`, `cta_post_url` and `cta_post_image` are all unset, so the resource banner does not render at all. This is the single biggest quick win in the report.

| Field | Recommended Value |
|-------|------------------|
| `resource_url` | `https://upmetrics.co/download/sales-forecast-templates` |
| `heading` | `Sales Forecast Templates` |
| `resource_link_text` | `Download Template` |
| **Rendered as** | **Download Template: Sales Forecast Templates** (44 chars — under the ~55 limit) |

**Why this one:** the article's longest and most worked section is Sales and revenue assumptions — the salon example that builds up to `18 × $65 × 26 = $30,420`. A reader who just followed that math wants a place to put it. This resource also has demonstrated demand: **2,078 impressions** for sales-forecast queries in the last 90 days, the highest of any downloadable resource in the repository. Verified live (HTTP 200), post ID 7347.

**Alternatives, both verified live:**
- `/download/financial-statement` (post ID 7281) — heading `Financial Statements`, renders as "Download Template: Financial Statements" (38 chars). Broader fit if you would rather cover the whole financial section than the sales piece.
- `/download/startup-costs-worksheet` (post ID 7339) — heading `Startup Costs Worksheet`, renders as "Download Template: Startup Costs Worksheet" (42 chars). Pick this for a cost angle.

---

### TASK 4 — Related Content

**Current state: EMPTY.** `related_posts` is `false` and `related_blogs` is unset — the sidebar renders nothing.

All four below are excluded from Tasks 1-3 to avoid duplicate placements.

| # | Post ID | Target URL | Custom Related Title | Chars |
|:--:|:--:|-----------|---------------------|:--:|
| 1 | 6056 | `/blog/how-to-write-a-business-plan` | The Complete Business Plan Walkthrough | 38 |
| 2 | 97893 | `/blog/free-and-paid-sources-of-industry-reports` | 21 Places to Find Real Industry Data | 36 |
| 3 | 98143 | `/blog/industry-benchmarking` | What Numbers Should You Benchmark? | 34 |
| 4 | 108758 | `/blog/how-to-calculate-cash-runway` | Know Exactly How Long Your Cash Lasts | 37 |

Titles are written for curiosity rather than as raw post titles, all under 50 characters, and use four different formats (statement, number, question, imperative) so the sidebar does not read as a list of clones.

**Swap option:** if you want post-type variety, replace #4 with post ID 63685 `/template/pro-forma-business-plan` — "See a Pro Forma Statement in Action" (35).

---

### TASK 5 — Meta Title & Description

#### Performance context

| Top Query | Impressions | Clicks | Position | CTR | Benchmark | Status |
|-----------|:--:|:--:|:--:|:--:|:--:|:--:|
| business plan assumptions | 1 | 0 | 6.0 | 0% | 5% | Sample too small |
| realistic business plan assumptions | 1 | 0 | 16.0 | 0% | 1.5% | Sample too small |
| business assumptions template | 1 | 0 | 26.0 | 0% | — | Sample too small |
| **Page total** | **11** | **0** | **19.3** | **0%** | — | **Too new to judge** |

**No CTR-driven rewrite is justified.** 11 impressions across one day cannot support a CTR conclusion. The only actionable finding is structural: the meta title is a character-for-character duplicate of the H1, which wastes the chance to say something different on the SERP.

#### Current vs. suggested

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | What Are Business Plan Assumptions? Types & Examples | 52 | Business Plan Assumptions: 6 Types With Real Examples | 53 | Keyword moved to position 0; adds a number hook; no longer duplicates H1 |
| Meta Description | Learn what business plan assumptions are, which ones to include, how to make reasonable estimates, and how to document them clearly in your plan. | 145 | *(no change)* | 145 | In range, keyword at char 11, active verb, no banned words |
| Focus Keyphrase | *(not exposed by the API)* | — | business plan assumptions | — | Already ranking position 6 — keep or set to this |
| Canonical | `/blog/business-plan-assumptions` | — | *(no change)* | — | Correct |
| OG Title | *(mirrors meta title)* | — | *(let it follow the new title)* | — | — |
| OG Description | *(mirrors meta description)* | — | *(no change)* | — | — |

The suggested title drops the ampersand entirely, so there is no `&` vs `&amp;` encoding risk in the Yoast field.

#### SERP preview

```
─────────────────────────────────────────────────────
upmetrics.co › blog › business-plan-assumptions
Business Plan Assumptions: 6 Types With Real Examples
Learn what business plan assumptions are, which ones to include,
how to make reasonable estimates, and how to document them
clearly in your plan.
─────────────────────────────────────────────────────
```

**Differentiator:** the H1 already asks the "what are…?" question, so the meta title now answers with scope instead — "6 Types With Real Examples" promises a countable, concrete payload that a question-form title does not.

**Caveat worth weighing:** the page is at position 6 for the primary keyword with the current title. The change is low-risk (keyword still front-loaded, length still in range), but if you would rather hold everything steady until there is 30 days of data, skipping this is entirely reasonable.

---

### TASK 6 — Image Alt Text

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty | 0 | — |
| Needs Improvement | 0 | — |
| Good | 1 | No action |
| Decorative — Correct | 1 | No action |
| **Total images** | **2** | — |

| # | src | Status | Current Alt | Chars | Verdict |
|:--:|-----|--------|-------------|:--:|---------|
| 1 | `business-plan-assumptions-summary-table.png` | Good | Assumptions summary table listing each assumption, its working value and the basis behind it | 91 | In the 60-125 range, describes what the image actually shows, no banned opener. Leave as is. |
| 2 | `crossline.png` | Decorative | `crossline` | 9 | Sits inside the canonical end CTA block, which must not be edited. Leave as is. |

**No action required for this task.** The single content image is already correctly described.

---

### TASK 7 — URL Slug

| Current Slug | Assessment |
|--------------|-----------|
| `business-plan-assumptions` | 3 words, contains the exact primary keyword, lowercase, hyphenated, 25 characters, no parameters |

**Recommendation: do not change.** The slug is already optimal, and the page ranks **position 6** for the primary keyword. Any change would require a 301 redirect and would put a position-6 ranking at risk for zero gain.

---

### TASK 8 — Heading Structure

| Check | Result |
|-------|--------|
| Exactly one H1 | Yes — rendered from the post title by the theme; no H1 inside the editor content (correct pattern) |
| H2 / H3 hierarchy | 4 H2 and 6 H3, no skipped levels — all six H3s nest correctly under H2 #2 |
| Primary keyword in an H2 | Yes — "What are business plan assumptions?" |
| Heading length under 70 chars | Yes — longest is 54 characters |
| Duplicate headings | None |
| Anchor IDs | Present on all four H2s; absent on H3s — **correct**, because `table_of_contents` is set to `h2`, so only H2s need anchors |

**No changes recommended.** The only cosmetic option is renaming the generic "Conclusion" H2 to something keyword-bearing, but it would appear in the on-page table of contents where "Conclusion" is the clearer label. Recommend leaving it.

---

### TASK 9 — Category Assignment

| Current | Suggested | Reason |
|---------|-----------|--------|
| `Planning` | `Planning`, `Forecasting` | `Planning` stays primary — the article is about a business plan component. `Forecasting` is warranted because the substance is estimating revenue, costs, cash flow and staffing inputs, which is exactly what that category covers per the taxonomy reference. |

Max is 2 categories and primary comes first, so the value to send is `["Planning", "Forecasting"]`.

---

### TASK 10 — Incoming Internal Link Suggestions

Pages that should link **to** this article. Every row is a verified WordPress post with a real post ID.

These are ranked on **query-level GSC data**: for each of the target's linkable topics (`assumption`, `financial projection`, `sales forecast`, `financial plan`), Search Console was asked which pages on the site already earn impressions for that term. Pages Google already associates with the topic are the strongest candidates, because a link from them carries topical context rather than just link equity.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | How to Prepare a Financial Plan for Startup Business | `/blog/write-financial-section-startup-business-plan` | 6040 | post | Ranks for both `assumption` and `financial plan` — 9,602 impressions, 7 clicks | business plan assumptions | 129 GA4 sessions | High |
| 2 | Sales Forecasting Methods: 8 Proven Approaches | `/blog/sales-forecasting-methods` | 6238 | post | Ranks for `sales forecast` — 6,371 impressions. Forecasting methods are meaningless without stated assumptions | forecast assumptions | 6,371 impr | High |
| 3 | Business Plan Components: What to Write in Each Section | `/blog/business-plan-components` | 23817 | post | Ranks for `assumption`. Section-by-section parent guide with a natural slot for this topic | business plan assumptions | 1 impr | High |
| 4 | Plan vs. Actual Analysis: Step-by-Step Guide | `/blog/plan-vs-actual-analysis` | 69096 | post | Ranks for `sales forecast` — 24 impressions. The whole page is about testing assumptions against real results | the assumptions you started with | 24 impr | High |
| 5 | How to Create a Perfect Business Plan Outline | `/blog/business-plan-outline` | 15426 | post | Ranks for `financial plan` at position 8.5 with a 4.6% CTR — an engaged, structurally-minded audience | documenting your assumptions | 22 impr | Medium |
| 6 | What is Cash Flow Forecasting: Type, Examples | `/blog/what-is-cash-flow-forecasting` | 81537 | post | Ranks for `assumption` and `sales forecast` | cash flow assumptions | 7 impr | Medium |
| 7 | How to Perform Break-Even Analysis | `/blog/break-even-analysis-business-plan` | 70006 | post | Ranks for `assumption`. Break-even is entirely assumption-driven | underlying assumptions | 1 impr | Medium |
| 8 | 10 Extremely Persuasive Business Plan Myths | `/blog/business-plan-myths` | 62303 | post | Ranks at **position 1.0** for an `assumption` query — small volume but Google already treats it as authoritative on the term | realistic assumptions | 1 impr | Medium |

> Every source URL above is verified in WordPress with a real post ID and returns HTTP 200. The suggested anchor text is a **starting search term** for the SEO team — the actual anchor depends on what phrasing already exists in each source page's content. No content scraping of source pages was performed.

**Note on #1:** this article already links *out* to page 6040. Adding a link back makes it reciprocal. Given how tightly the two topics are coupled (a financial plan is assumptions plus arithmetic) that is defensible, but skip it if you keep links strictly one-directional.

**Excluded on purpose:** `/blog/financial-projections-business-plan` (6216) is the single strongest candidate by data — 7,233 impressions across `assumption`, `financial projection` and `sales forecast` — but Task 1 suggestion #1 points *at* it, and the FAQ already links it too. Listing it here would make a three-way loop. Same reasoning excludes `/blog/how-to-forecast-sales-for-business` (76107), now claimed by Task 1 #5.

---

## Data Coverage Note

**All planned data pulls completed.** GSC access from this machine was severely degraded during the run — roughly 96 seconds just to open a connection to `searchconsole.googleapis.com`, and the GSC MCP server timed out on every attempt. A direct service-account client was used instead, and the full set eventually returned: top queries, device split, 90-day trend, page totals, site top pages, per-topic ranking queries, and URL Inspection. Everything above is real data.

The per-topic queries arrived late and were worth waiting for — they surfaced pages that keyword search alone had missed, including `/blog/sales-forecasting-methods` (6,371 impressions) and `/download/sales-forecast-templates` (2,078 impressions). Task 1 #5, Task 3 and Task 10 were all revised on the strength of that data.

**One observation from URL Inspection worth noting.** Rich-result detection reports **Breadcrumbs only**. The page's source does contain valid `FAQPage` JSON-LD alongside `Article`, `WebPage` and `BreadcrumbList` — that was confirmed by fetching the live page directly. The FAQ markup simply is not producing a rich result, which is expected: Google restricted FAQ rich results to government and health sites in August 2023. **No action needed** — keep the FAQ schema (it still helps with entity understanding and AI overviews), just do not expect FAQ snippets in the SERP.

| Data source | Status |
|-------------|--------|
| WordPress (posts, ACF, FAQs, taxonomy) | Complete — via direct JSON-RPC after the MCP connector returned 401/handshake errors |
| GSC — page queries, device, trend, totals | Complete |
| GSC — per-topic ranking queries | Complete |
| GSC — URL Inspection | Complete (`PASS`, Submitted and indexed) |
| GA4 — Report A (engagement, 30d) | Complete |
| GA4 — Report E (conversions, 90d) | Complete |
| Live page fetch (meta, H1, schema) | Complete |
| Target URL verification (HTTP status) | Complete — every cited URL returns 200; two 410-Gone glossary pages were caught and dropped |

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2, #3, #4, #5. Skip #6-#8.
   (For #5, use the how-to page. Say "use the features page for #5" if you want the product link instead.)
Task 2 (CTAs): Add #1 Yellow Tip after "Funding and cash flow assumptions". Skip optional.
Task 3 (Resource CTA): Approve Sales Forecast Templates.
Task 4 (Related Content): Approve items #1-#4.
Task 5 (Meta Title/Desc): Approve suggested title. Keep description. Keep keyphrase.
Task 6 (Image Alt Text): Skip - no action needed.
Task 7 (URL Slug): Skip - ranks position 6, do not touch.
Task 8 (Headings): Skip - structure is clean.
Task 9 (Categories): Approve Planning + Forecasting.
Task 10 (Incoming Links): Noted - will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task 5"**
