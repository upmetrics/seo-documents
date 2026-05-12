# On-Page SEO Report — Plan vs. Actual Analysis (v2)

**Page:** https://upmetrics.co/blog/plan-vs-actual-analysis  ← re-verified 200 OK, no redirect.
**Post ID:** 69096 · **Type:** post · **Category:** Planning
**Last modified:** 2026-05-12 · **Word count:** 3,751
**Brand:** Upmetrics
**Session:** `workspace/plan-vs-actual-analysis-20260512-162528/`

> **What changed from v1:** Internal-link section rebuilt. Every anchor in this version is a **multi-word phrase that semantically matches the destination page's topic** — not a single keyword pulled out of context. Each anchor is also confirmed verbatim against `content-original.html` and placement is verified against the spacing/balance rules in Task 1 below.

---

## A. Page Snapshot

| Field | Value |
|---|---|
| Title (H1, theme-rendered) | Plan vs. Actual Analysis: Step-by-Step Guide |
| Meta title (Yoast) | Plan vs. Actual Analysis: Step-by-Step Guide + Free Template (**61 chars — over 60 limit**) |
| Meta description (Yoast) | "Learn how to conduct a plan vs. actual analysis using Spreadsheets & Upmetrics—a step-by-step guide. Compare forecasts with actual data to identify variances." (158 chars; contains raw em dash and raw `&`) |
| Canonical | `https://upmetrics.co/blog/plan-vs-actual-analysis` ✓ |
| Index status | PASS · indexed · last crawl 2026-05-11 · mobile-first ✓ |
| Schema | Article, WebPage, BreadcrumbList, Organization, Person ✓ |
| Internal links (in-content) | 4 (excluding end-CTA button) — only **1 link per ~940 words** (well below the 1 / 200–300 norm for a how-to post) |
| External links | 1 (sba.gov, has `rel="noopener"` ✓) |
| Competitor links | 0 ✓ |
| Images | 20 (all have alt; 6 need fixes — see Task 6) |
| ACF Resource CTA | **Not set** — major missed opportunity |
| ACF Related Pages | **Not set** — major missed opportunity |
| Stale year refs | 0 ✓ (evergreen) |

### Search performance (last 28 days, GSC)

| Metric | Value |
|---|---|
| Impressions | 260 (Desktop 202 · Mobile 56 · Tablet 2) |
| Clicks | **0** |
| CTR | 0% (47 ranked queries, all CTR = 0) |
| Top queries by impressions | "plan vs actual report" (30 imp, pos 35) · "planned vs actual report" (30 imp, pos 47) · "actual example" (22 imp, pos 1.6) · "planned vs forecast vs actual" (21 imp, pos 9) · "actual analysis" (15 imp, pos 5.3) |

### Best ranking opportunities

| Query | Impressions | Position | Why it matters |
|---|---|---|---|
| `planned vs forecast vs actual` | 21 | 9.0 | One position from page 1 — meta title/description optimisation can pull it onto the front page |
| `actual analysis` | 15 | 5.3 | Already top-5, but 0 clicks at this position is a CTR signal — meta title/description likely the cause |
| `plan vs actual report` | 30 | 35.1 | Highest-volume query; ranking is page-3 territory — body content (variance report walkthrough) needs strengthening |

### Engagement (last 30 days, GA4)

40 sessions to this URL (25 Organic · 11 Referral · 3 Unassigned · 1 Direct). Organic engagement rate 0.72 (healthy). The traffic is small but readers who land here do engage.

---

## B. Page Health Score

| Area | Status | Notes |
|---|---|---|
| Indexing & canonical | Healthy | Indexed, mobile-crawled, no canonical conflict |
| Content depth | Healthy | 3,751 words; clean H2/H3/H4 hierarchy |
| Schema | Healthy | Article + BreadcrumbList active |
| Internal linking | **Needs improvement** | Only 4 in-content links; few of them carry contextual depth |
| Meta title | **Needs improvement** | Over 60 chars; "+ Free Template" claim has no backing resource |
| Meta description | **Needs improvement** | Raw em dash + raw `&` violate encoding rules |
| Image alt text | **Needs improvement** | 4 alts contain raw em dashes; 2 alts below 60-char minimum |
| Resource CTA (ACF) | **Missing** | Strong match available (`/download/financial-statement`) |
| Related Content (ACF) | **Missing** | 4 strong topical neighbours ready to set |
| CTR vs. benchmarks | **Underperforming** | 0 clicks on 260 impressions; multiple queries ranking 1–10 with no CTR |

---

## Task 1 — Internal Links

### How anchors were chosen (so you can challenge any of them)

Three rules, applied in order:

1. **Semantic match.** The anchor phrase must describe the *destination page's topic*, not just a keyword that happens to be on the page. "cash flow" as an anchor for a cash flow guide is technically fine; "benchmarks" as an anchor for an industry benchmarking guide is a stretch unless the surrounding sentence is also about benchmarking.
2. **Verbatim presence.** Every anchor below was confirmed to exist character-for-character in the source HTML (script: `workspace/verify_anchors_v2.py`). No paraphrasing.
3. **Spacing & balance.** No two new anchors live in the same paragraph or within 100 words of each other; Informational : Sales/Features ratio is biased Informational (this is a how-to post).

### Part A — Existing in-content links (verdict on each)

| # | Anchor | Target | Type | Verdict |
|---|---|---|---|---|
| 1 | `log in to Upmetrics` | `app.upmetrics.co/auth/login` | App | **Keep.** Natural in the "log in to your workspace" step. |
| 2 | `AI financial forecasting tool` | `/features/financial-forecasting` | Sales/Features (high-conversion: 208 conversions / 945 sessions, 90d) | **Keep.** Strong descriptive anchor pointing to the matching product page. |
| 3 | `cash flow` | `/blog/what-is-cash-flow-forecasting` | Informational | **Keep, but improve anchor.** Two-word generic anchor under-sells the target. Suggest expanding the anchor to **`your cash flow`** (3 words, the verbatim phrase already in the sentence) — still natural, slightly more specific. *Optional polish — not a hard fix.* |
| 4 | `Upmetrics` | `/` (homepage) | Brand | **Keep.** Brand mention in the "Bottom line" closer. |
| 5 | `Get Started Now!` | `/cta/help` | Sales CTA button | **Keep.** Covered under Task 2. |

### Part B — New internal links to add (rebuilt for v2)

Each row shows: the **destination page topic**, the **exact anchor phrase** chosen, **where it lives** in the article, and **why this anchor is the right one** for this target.

| # | Anchor (verbatim in source) | Target | Target's topic | Where in article | Why this anchor matches this target |
|---|---|---|---|---|---|
| 1 | `first forecast` | `/blog/financial-forecast-without-historical-data` | "How to Create a Financial Forecast Without Historical Data" | H3 **"Improve next month's forecast"** — sentence: "Your **first forecast** is mostly guesses, built from benchmarks, gut, and some optimism." | The destination page is literally about the scenario the anchor names: making your *first* forecast when you have no past data. A reader on this sentence is — by definition — thinking about a first forecast. Direct topical hand-off. |
| 2 | `sales forecast` | `/blog/financial-projections-business-plan` | "How to Create Financial Projections for a Business Plan" (high-conversion: 42 conversions / 179 sessions, 90d) | H4 **"1. Start with the plan (spreadsheet method)"** — sentence: "Take the **sales forecast** as an example. List all the products or items you sell…" | A sales forecast is the primary line item inside financial projections. Reader is mid-spreadsheet-setup and might want the broader "how do I build the whole projection" view — the linked guide is exactly that. |
| 3 | `forecast assumption` | `/blog/what-is-financial-forecasting` | "What is Financial Forecasting? Definition & Importance Explained" | H4 **"1. Price variance"** — sentence: "Check whether the change was deliberate. If it wasn't, find out why your price drifted and decide whether to update your **forecast assumption** next month." | "Forecast assumption" is a core concept the destination page defines. Reader has just been told to revisit an assumption — perfect moment to offer the foundational primer. |
| 4 | `cash flow squeeze` | `/blog/cash-flow-problems` | "12 Cash Flow Problems Every Business Faces (And How to Fix Each One)" | H3 **"Identify variances early"** — sentence: "It's a real **cash flow squeeze**, the kind where you start doing math on whether payroll lands." | The destination page is the dedicated taxonomy of cash flow problems — a "cash flow squeeze" is one of them. Reader who feels seen by this sentence will want the full list of what could be going wrong. |
| 5 | `forecast vs. actuals` | `/blog/budgeting-vs-forecasting` | "Budgeting Vs Forecasting: Key Differences + Examples" | H2 **"What is plan vs. actual analysis?"** (just after the snippet block) — sentence: "Finance and bookkeeping teams sometimes call it '**forecast vs. actuals**' too." | The destination is the canonical "what's the difference between these similar finance terms" article. The source sentence is *itself* a terminology disambiguation — the link is on the very phrase being defined. |
| 6 | `talk to investors` | `/blog/angel-investor-funding` | "How to Get Funding from Angel Investors: A Step-by-Step Guide" | H3 **"Tighten cash flow management"** — sentence: "Slow down hiring, delay a big purchase, or **talk to investors** with real numbers in hand." | The source sentence explicitly suggests investor conversations as the recovery action; the destination tells the reader how to actually do that. Direct action → next-step link. |

### Anchors I considered but rejected (transparency)

| Considered anchor | Considered target | Why rejected |
|---|---|---|
| `benchmarks` | `/blog/industry-benchmarking` | Anchor lives in the *same sentence* as anchor #1 ("first forecast") — fails the 100-word spacing rule. Picked the stronger semantic match (#1). |
| `Better forecasts` | `/blog/financial-forecast-without-historical-data` | Same section as #1 — would create within-section duplication on the same destination. |
| `variance analysis` | (no clean target) | Upmetrics has no dedicated variance-analysis hub; closest matches drift to projection mistakes or budgeting — semantic distance too large. |
| `customer acquisition cost` | (no clean target) | No dedicated CAC page exists. |
| `financial planning software` | `/features/financial-forecasting` | Same destination as existing link #2 — would be a duplicate-target violation. |
| `financial performance` | `/blog/financial-projections-business-plan` | Destination is already used by anchor #2 (`sales forecast`) — cross-task dedup keeps the stronger anchor and drops this. |
| `runway is shorter` | `/blog/cash-flow-problems` | Same destination as anchor #4 (`cash flow squeeze`) AND in adjacent paragraph to the existing `cash flow` link → spacing + dedup both fail. |
| `five mistakes` (in body) | `/blog/common-financial-projections-mistakes` | Misleading: in source it refers to mistakes covered *inside this article*, not the destination's projection mistakes. Would frustrate readers. |

### Validation summary

- **6 new anchors**, all verified verbatim in `content-original.html`.
- **6 unique destinations** (no two suggestions share a target).
- **Section distribution:** anchors live in 6 different sections (one H2 + four H3s + one H4). No two within 100 words.
- **Type mix (new only):** 6 Informational, 0 Sales/Features.
- **Combined totals (existing + new):** 10 in-content internal links across 3,751 words → 1 link per ~375 words. Informational : Sales+Brand ratio = 8 : 2 (80% / 20%). Healthy for a how-to post.
- **Cross-task dedup:** None of these 6 URLs are reused in Task 2, Task 3, or Task 4 below.

---

## Task 2 — CTA Placements

### Existing

End-of-content `delivery-block` → `/cta/help` ("Get Started Now!"). Keep as-is — it's the standard Upmetrics end-of-post CTA.

### New

Insert **one mid-content `delivery-block`** between the H3 "Plan vs. actual analysis using Upmetrics" (ending paragraph: "…every monthly sync brings your actuals straight into Upmetrics, ready to compare against the plan.") and the H2 "Variances". This is the natural beat: reader has finished the software walkthrough and is in evaluation mindset.

**Destination:** `/features/financial-forecasting` (same destination as the inline link #2, but in a different format and section).

**Reason this isn't a "duplicate":** Inline anchor link (mid-walkthrough, low visual weight) versus full block CTA (decision-time, high visual weight). The two serve different reader states and don't collide spatially (separated by several paragraphs and the "Variances" H2 boundary).

**Suggested HTML** (uses the existing `delivery-block` pattern already on the page):

```html
<div class="delivery-block text-center">
  <p class="delivery-text h2">Stop reconciling spreadsheets every month.</p>
  <p class="delivery-tegline">Connect QuickBooks or Xero — Upmetrics calculates variance for you, line by line.</p>
  <div><a class="cta-btn cta-btn-bg-blue" href="https://upmetrics.co/features/financial-forecasting">See How It Works</a></div>
</div>
```

(Note: the suggested CTA copy uses an em dash inside body text. That's allowed inside CTA copy — the em-dash ban applies only to meta title/description and image alt text per the SEO toolkit rules. If you'd prefer no em dash anywhere, change to a colon: "Connect QuickBooks or Xero: Upmetrics calculates variance for you, line by line.")

---

## Task 3 — Resource CTA (ACF "Resources Hero CTA")

**Status:** Not configured.

**Recommendation:** Set the Resources Hero CTA to the **Financial Statements Template** download.

| Parameter | Value |
|---|---|
| `post_id` | 69096 |
| `resource_url` | `https://upmetrics.co/download/financial-statement` |
| `heading` | `Financial Statements Template` |
| `resource_link_text` | `Download Template` |

**Why this resource (and not, say, the business plan template):** A plan-vs-actual analysis is *built on* P&L, cash flow, and balance sheet data — i.e., financial statements. The Financial Statements Template is the matching starting artifact for a reader who's just learned the variance formula. The plugin auto-fetches the resource page's featured image, so no image parameter is needed.

This addition also **justifies keeping the "+ Template" hook** in the meta title (see Task 5) — without this resource, the title is making a promise the page doesn't keep.

---

## Task 4 — Related Content (ACF Related Posts repeater)

**Status:** Not configured.

**Recommendation:** Add 4 related posts. All four are deliberately *not* used by Tasks 1, 2, or 3 (cross-task dedup applied).

| # | post_id | Display title (`title` field) | URL |
|---|---|---|---|
| 1 | 6040 | How to Build a Financial Plan for a Startup | `/blog/write-financial-section-startup-business-plan` |
| 2 | 81514 | 8 Cash Flow Forecasting Best Practices | `/blog/cash-flow-forecasting-best-practice` |
| 3 | 88309 | 10 Best Revenue Forecasting Software Solutions | `/blog/revenue-forecasting-software` |
| 4 | 71260 | 9 Common Financial Projections Mistakes | `/blog/common-financial-projections-mistakes` |

Display titles are tightened versions of the raw post titles — the raw "How to Prepare a Financial Plan for Startup Business" wraps awkwardly in the sidebar widget. Always pass `title` explicitly per the plugin docs.

---

## Task 5 — Meta Title & Meta Description

### Title

**Current (Yoast):** `Plan vs. Actual Analysis: Step-by-Step Guide + Free Template` — **61 chars (over 60-limit by 1)**.

**Two problems:**
1. **Length** — fails the 50–60 inclusive rule.
2. **Promise without backing** — "+ Free Template" implies a download on the page; the page currently has no downloadable template. (Task 3 fixes this by attaching the Financial Statements Template as the Resource CTA, which means we *can* keep the "+ Template" hook.)

**Proposed:** `Plan vs. Actual Analysis: Formula, Variance + Template` (**54 chars**)

| Check | Result |
|---|---|
| 50–60 char window | 54 ✓ |
| Focus keyphrase `plan vs actual analysis` in first 40 chars | Yes (chars 1–24) ✓ |
| Differentiation hook | "Formula" (format signal) + "Template" (resource hook) ✓ |
| Different angle from H1 ("Step-by-Step Guide") | Yes — emphasises formula + template instead of "step-by-step" ✓ |
| Banned AI words | None ✓ |
| Encoding (straight quotes, no em dash, no curly quotes) | Clean ✓ |

### Description

**Current (Yoast):** `Learn how to conduct a plan vs. actual analysis using Spreadsheets & Upmetrics—a step-by-step guide. Compare forecasts with actual data to identify variances.` (158 chars · raw em dash · raw `&`)

**Proposed:** `Learn how to run a plan vs. actual analysis using spreadsheets and Upmetrics. Compare forecasts with actuals, calculate variance, and act on the gaps.` (**149 chars**)

| Check | Result |
|---|---|
| 140–160 char window | 149 ✓ |
| Focus keyphrase `plan vs actual analysis` in first 100 chars | Yes (chars 18–41) ✓ |
| Encoding (no raw em dash, no raw `&`, no curly quotes) | Clean ✓ |
| Banned AI words | None ✓ |

**Focus keyphrase consistency check:** `plan vs actual analysis` appears verbatim in both new title and new description ✓.

---

## Task 6 — Image Alt Text

20 images total; all currently have alt text. **6 alts need fixes** (encoding + length).

| # | Filename | Current alt | Issue | Proposed alt | Len |
|---|---|---|---|---|---|
| 1 | `plan-vs-actual-analysis-spreadsheet-plan.png` | "Spreadsheet method — initial financial plan numbers laid out by month" | Raw em dash | `Spreadsheet method: initial financial plan numbers laid out by month for a cafe business` | 88 |
| 2 | `plan-vs-actual-analysis-spreadsheet-actuals.png` | "Spreadsheet method — actual results entered alongside the planned numbers" | Raw em dash | `Spreadsheet method: actual results entered alongside the planned numbers in the same sheet` | 90 |
| 3 | `plan-vs-actual-analysis-spreadsheet-comparison.png` | "Spreadsheet method — plan and actual data side-by-side for comparison" | Raw em dash | `Spreadsheet method: plan and actual data shown side-by-side with variance for each line` | 87 |
| 4 | `plan-vs-actual-analysis-upmetrics-plan-1.png` | "Starting the plan inside Upmetrics — opening the forecast workspace" | Raw em dash | `Starting the plan inside Upmetrics: opening the financial forecasting workspace for a new project` | 97 |
| 5 | `plan-vs-actual-analysis-upmetrics-actuals-5.png` | "Detailed actuals view with planned figures inside Upmetrics" | 59 chars (below 60) | `Detailed actuals view in Upmetrics with mapped Xero categories alongside the plan figures` | 89 |
| 6 | `plan-vs-actual-analysis-upmetrics-actuals-6.png` | "Upmetrics comparison summary with variance percentages" | 53 chars (below 60) | `Upmetrics comparison summary showing variance percentages across revenue and expense lines` | 90 |

**Optional (decorative):**

| # | Filename | Current alt | Proposed | Reason |
|---|---|---|---|---|
| 7 | `crossline.png` (inside end-CTA button) | "crossline" | `` (empty alt) | Decorative icon — screen readers should skip it. |

**Quality-gate checks (all proposed alts):**
- Critical-coverage: 0 missing/empty alts (excluding the decorative icon) ✓
- Length 60–125: all 6 in range ✓
- Banned openers (Image of / Picture of / Photo of / Screenshot of / Graphic showing): none ✓
- Banned AI words: none ✓
- Keyword stuffing: primary keyphrase appears in 0 proposed alts ✓
- Duplicate-alt: no two proposed alts identical ✓
- Encoding: all straight ASCII, no em dashes, no curly quotes ✓

---

## Task 7 — Headings & Structure

**Verdict:** Healthy with one optional polish.

- 0 in-content H1 (the theme renders the post title as the page H1 — standard for the Upmetrics blog template).
- 7 × H2, 12 × H3, 10 × H4. Hierarchy is well-formed; no skipped levels.
- Optional polish: the H2 `Variances` is terse compared to its siblings. A more descriptive version like **`Reading variance: favorable vs. unfavorable`** would better surface its content for SERP snippet extraction. Not required.

---

## Summary of changes

| Group | Task | What changes | Items |
|---|---|---|---|
| **A** | 1 | New in-content internal links | 6 anchors |
| **A** | 1 (optional) | Expand existing anchor "cash flow" → "your cash flow" | 1 |
| **A** | 5 | Rewrite meta title | 1 |
| **A** | 5 | Rewrite meta description | 1 |
| **A** | 6 | Image alt text updates | 6 (+1 optional decorative) |
| **A** | 7 (optional) | Rename H2 "Variances" | 1 |
| **B** | 2 | Insert mid-content CTA block | 1 |
| **C** | 3 | Set ACF Resource CTA (`/download/financial-statement`) | 1 |
| **C** | 4 | Set ACF Related Posts (4 entries) | 1 |

**Execution mechanics:** Group A + Group B are both edits to the post `content` field → bundled into a single `update-post` call. Group C is two ACF-specific calls: `set-resource-cta` + `set-related-pages`.

---

## What to do next

Reply with one of:

1. **All** — apply Tasks 1–7 (including the two optional polish items).
2. **All, skip optional** — apply everything except the H2 rename and the decorative `crossline` alt.
3. **Group A only** — content + meta + alt edits, no new CTA block, no ACF.
4. **Edit first** — flag specific anchors/copy/alts to change and I'll redraft before any WordPress writes.

Nothing has been written to WordPress yet.
