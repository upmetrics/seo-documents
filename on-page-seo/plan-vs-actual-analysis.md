# On-Page SEO Report — Plan vs. Actual Analysis

**Page:** https://upmetrics.co/blog/plan-vs-actual-analysis
**Post ID:** 69096 · **Type:** post · **Category:** Planning
**Last modified:** 2026-05-12 · **Word count:** 3,751
**Brand:** Upmetrics
**Session:** `workspace/plan-vs-actual-analysis-20260512-162528/`

---

## A. Page Snapshot

| Field | Value |
|---|---|
| Title (H1, theme-rendered) | Plan vs. Actual Analysis: Step-by-Step Guide |
| Meta title (Yoast) | Plan vs. Actual Analysis: Step-by-Step Guide + Free Template (**61 chars — over 60**) |
| Meta description (Yoast) | "Learn how to conduct a plan vs. actual analysis using Spreadsheets & Upmetrics—a step-by-step guide. Compare forecasts with actual data to identify variances." (158 chars · contains raw em dash) |
| Canonical | `https://upmetrics.co/blog/plan-vs-actual-analysis` ✓ |
| Index status | PASS · indexed · last crawl 2026-05-11 ✓ |
| Schema | Article, WebPage, BreadcrumbList, Organization, Person ✓ (FAQ schema also detected by Google but is not in Yoast graph — likely cached) |
| Internal links | 5 (4 in-content + 1 in end CTA) |
| External links | 1 (SBA.gov, `rel="noopener"` ✓) |
| Competitor links | 0 ✓ |
| Images | 20 (all have alt text — quality fixes needed; see Task 6) |
| Existing ACF Resource CTA | **Not set** — opportunity |
| Existing ACF Related Pages | **Not set** — opportunity |
| Stale year refs | 0 ✓ (evergreen) |

### Search performance (last 28 days)

| Metric | Value |
|---|---|
| Impressions | 260 (Desktop 202 · Mobile 56 · Tablet 2) |
| Clicks | **0** |
| CTR | 0% |
| Top queries (by impressions) | "plan vs actual report" (30, pos 35) · "planned vs actual report" (30, pos 47) · "actual example" (22, pos 1.6) · "planned vs forecast vs actual" (21, pos 9) · "how to find gaps between planned vs actual sales execution" (19, pos 78) |
| Mobile vs desktop | Mobile avg pos 19 · Desktop avg pos 28 — mobile ranks **better** on average |

### Engagement (last 30 days, GA4)

| Channel | Sessions | Engagement rate |
|---|---|---|
| Organic Search | 25 | 0.72 |
| Referral | 11 | 0.82 |
| Unassigned | 3 | 0.67 |
| Direct | 1 | 0.00 |
| **Total** | **40** | **0.73** |

---

## B. Page Health Score

| Area | Status | Notes |
|---|---|---|
| Indexing & canonical | Healthy | Indexed, mobile-crawled, no canonical conflict |
| Content depth | Healthy | 3,751 words; H2/H3/H4 hierarchy strong |
| Image accessibility | Needs improvement | 4 alts contain raw em dashes; 1 alt is too short; 1 decorative icon labelled |
| Meta title | Needs improvement | 61 chars (over 60 limit); "+ Free Template" promise has no matching on-page download |
| Meta description | Needs improvement | Contains raw em dash + raw "&" |
| Internal linking | Needs improvement | Only 4 in-content internal links for 3,751 words (~1 per 940 words) |
| Resource CTA | Missing | ACF "Resources Hero CTA" not configured |
| Related pages | Missing | ACF Related Posts not configured |
| CTR vs. position | Underperforming | 0 clicks on 260 impressions across 47 ranked queries |

---

## Task 1 — Internal Links

### Part A — Existing in-content links (review)

| # | Anchor | Target | Classification | Verdict |
|---|---|---|---|---|
| 1 | log in to Upmetrics | `https://app.upmetrics.co/auth/login` | App | **Keep** — relevant to the walkthrough step |
| 2 | AI financial forecasting tool | `/features/financial-forecasting` | Sales/Features · high-conversion | **Keep** — strong anchor, contextually accurate |
| 3 | cash flow | `/blog/what-is-cash-flow-forecasting` | Informational | **Keep** (anchor is short but accurate) |
| 4 | Upmetrics | `/` (homepage) | Brand | **Keep** — brand mention in "Bottom line" closer |
| 5 | Get Started Now! | `/cta/help` | Sales (CTA button) | **Keep** — covered under Task 2 |

### Part B — New internal links to add

All anchors verified verbatim in `content-original.html`. Target pages verified against the Target Page Repository.

| # | Anchor (exact phrase in source) | Target URL | Section | Rationale |
|---|---|---|---|---|
| 1 | **benchmarks** | `/blog/industry-benchmarking` | H3 "Improve next month's forecast" | Source sentence references benchmarks as the basis for first-draft forecasts — directly relevant. |
| 2 | **sales forecast** (use the occurrence inside "Take the sales forecast as an example") | `/blog/financial-projections-business-plan` | H4 "1. Start with the plan (spreadsheet method)" | High-conversion target. Anchor sits in the spreadsheet walkthrough where readers are mid-setup. |
| 3 | **forecast assumption** | `/blog/what-is-financial-forecasting` | H4 "1. Price variance" | Reader is being told to revisit a forecast assumption — natural moment to link the deeper "what is forecasting" primer. |
| 4 | **cash flow squeeze** | `/blog/cash-flow-problems` | H3 "Identify variances early" | Source paragraph already invokes the cash-flow-squeeze framing; deepens it to the dedicated problems guide. |
| 5 | **forecast vs. actuals** | `/blog/common-financial-projections-mistakes` | H2 "What is plan vs. actual analysis?" | High-conversion target. Anchor is the alt-name footnote — sends curiosity-driven readers to the broader projections-mistakes piece. |

**Balance check:** New links are 5 Informational · 0 Sales. Combined with existing (2 Sales + 2 Informational + 1 Brand), total in-content internal links become **9** (1 per ~417 words). Informational:Sales ratio = 7:2 (78% / 22%) — healthy for a how-to blog post.

**Spacing check:** Each suggestion lives in a different H2/H3 section; no two new anchors are within 100 words of each other.

---

## Task 2 — CTA Placements

### Existing
- **End-of-content `delivery-block`** → `/cta/help` ("Get Started Now!"). Keep as-is.

### New
- **Mid-content CTA** after the closing line of section *"How to conduct a plan vs. actual analysis (Example)?"* and before the H2 *"Variances"* — i.e. after the line "The same logic flips. Under plan is good because you spent less than expected." Wait — that's inside Variances. The actual insertion point is the paragraph ending "Same process we walked through, just without the spreadsheet work." → place the CTA **between the H3 "Plan vs. actual analysis using Upmetrics" wrap-up and the H2 "Variances"**.

  **Suggested CTA HTML (uses the standard `delivery-block` pattern already used on the page):**

  ```html
  <div class="delivery-block text-center">
    <p class="delivery-text h2">Stop reconciling spreadsheets every month.</p>
    <p class="delivery-tegline">Connect QuickBooks or Xero and let Upmetrics calculate variance for you.</p>
    <div><a class="cta-btn cta-btn-bg-blue" href="https://upmetrics.co/features/financial-forecasting">See How It Works</a></div>
  </div>
  ```

  **Why this destination, this placement:** Reader has just finished the spreadsheet walkthrough and is in software-evaluation mindset; `/features/financial-forecasting` is the matching product page (high-conversion target — 208 conversions / 945 sessions in last 90 days). Keeps the two CTAs visually distinct (mid = product page, end = generic help redirect).

**Note on duplication:** `/features/financial-forecasting` is already linked in the article via the "AI financial forecasting tool" anchor (inside the Upmetrics walkthrough). The CTA reuse is acceptable because (a) it lives in a different format (button block vs. inline text link), (b) it's mid-content not in the same paragraph as the inline link, and (c) it targets readers who skim past the inline link.

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

**Why this resource:** A plan-vs-actual analysis is built on monthly P&L / cash flow numbers — i.e. financial statements. The Financial Statements Template gives readers the matching starting artifact, which is the natural lead magnet for this article. The plugin will auto-fetch the resource page's featured image.

---

## Task 4 — Related Content (ACF Related Posts repeater)

**Status:** Not configured.

**Recommendation:** Add 4 related posts. All chosen from the Target Page Repository, none overlap with Task 1 / Task 2 / Task 3 targets.

| # | post_id | Display title (Related Title) | URL |
|---|---|---|---|
| 1 | 6040 | How to Build a Financial Plan for a Startup | `/blog/write-financial-section-startup-business-plan` |
| 2 | 81514 | 8 Cash Flow Forecasting Best Practices | `/blog/cash-flow-forecasting-best-practice` |
| 3 | 89621 | How to Forecast Without Historical Data | `/blog/financial-forecast-without-historical-data` |
| 4 | 88309 | 10 Best Revenue Forecasting Software Solutions | `/blog/revenue-forecasting-software` |

(Display titles are tightened versions of the raw post titles — raw titles like "How to Prepare a Financial Plan for Startup Business" wrap awkwardly in the sidebar widget.)

---

## Task 5 — Meta Title & Meta Description

### Title

**Current:** `Plan vs. Actual Analysis: Step-by-Step Guide + Free Template` (61 chars — fails the 60-char limit)

**Issue:** Over length by 1 char; the "+ Free Template" hook has no corresponding on-page download (Task 3 fixes this — the Financial Statements Template now justifies the promise).

**Proposed:** `Plan vs. Actual Analysis: Formula, Variance + Template` (**54 chars**)

- Focus keyphrase `plan vs actual analysis` — first 24 chars ✓
- Hooks: "Formula" (format signal) + "Template" (resource hook) ✓
- Differentiates from H1 ("Step-by-Step Guide") ✓
- No banned AI words ✓
- Straight ASCII apostrophes, no em dash, no curly quotes ✓

### Description

**Current:** `Learn how to conduct a plan vs. actual analysis using Spreadsheets & Upmetrics—a step-by-step guide. Compare forecasts with actual data to identify variances.` (158 chars — contains raw em dash and raw `&`)

**Proposed:** `Learn how to run a plan vs. actual analysis using spreadsheets and Upmetrics. Compare forecasts with actuals, calculate variance, and act on the gaps.` (**149 chars**)

- Length within 140–160 ✓
- Focus keyphrase `plan vs actual analysis` at chars 18–41 (well within first 100) ✓
- No em dash, no `&`, no curly quotes ✓
- No banned AI words ✓

**Focus keyphrase consistency:** `plan vs actual analysis` appears verbatim in both the new title and the new description ✓.

---

## Task 6 — Image Alt Text

20 images, all have alt text. **6 alts need fixes** (encoding + length). All updates preserve the descriptive intent of the original alt.

| # | Filename | Current alt | Issue | Proposed alt | Length |
|---|---|---|---|---|---|
| 1 | `plan-vs-actual-analysis-spreadsheet-plan.png` | "Spreadsheet method — initial financial plan numbers laid out by month" | Raw em dash | `Spreadsheet method: initial financial plan numbers laid out by month for a cafe business` | 88 |
| 2 | `plan-vs-actual-analysis-spreadsheet-actuals.png` | "Spreadsheet method — actual results entered alongside the planned numbers" | Raw em dash | `Spreadsheet method: actual results entered alongside the planned numbers in the same sheet` | 90 |
| 3 | `plan-vs-actual-analysis-spreadsheet-comparison.png` | "Spreadsheet method — plan and actual data side-by-side for comparison" | Raw em dash | `Spreadsheet method: plan and actual data shown side-by-side with variance for each line` | 87 |
| 4 | `plan-vs-actual-analysis-upmetrics-plan-1.png` | "Starting the plan inside Upmetrics — opening the forecast workspace" | Raw em dash | `Starting the plan inside Upmetrics: opening the financial forecasting workspace for a new project` | 97 |
| 5 | `plan-vs-actual-analysis-upmetrics-actuals-5.png` | "Detailed actuals view with planned figures inside Upmetrics" | 59 chars (below 60) | `Detailed actuals view in Upmetrics with mapped Xero categories alongside the plan figures` | 89 |
| 6 | `plan-vs-actual-analysis-upmetrics-actuals-6.png` | "Upmetrics comparison summary with variance percentages" | 53 chars (below 60) | `Upmetrics comparison summary showing variance percentages across revenue and expense lines` | 90 |

**Optional but recommended (decorative):**

| # | Filename | Current alt | Proposed alt | Reason |
|---|---|---|---|---|
| 7 | `crossline.png` (inside end CTA button) | "crossline" | `` (empty) | Decorative icon — should have `alt=""` so screen readers skip it. |

**Other 13 images:** alts are within 60–125 chars, descriptive, no banned words, no encoding issues — **leave alone**.

**Quality gate checks:**
- Critical coverage: 0 missing/empty alts (other than the decorative crossline) ✓
- Banned openers: none of the proposed alts start with "Image of / Picture of / Photo of / Screenshot of / Graphic showing" ✓
- Banned AI words: none ✓
- Keyword stuffing: primary keyphrase ("plan vs actual analysis") appears in 0 proposed alts (it's already in many filenames) ✓
- Duplicate check: no two proposed alts are identical ✓
- Encoding: straight ASCII, no em dashes, no curly quotes ✓

---

## Task 7 — Headings & Structure

**Verdict:** No critical issues.

- 0 in-content H1 (theme renders the post title as the page H1 — correct for the Upmetrics blog template).
- 7 × H2, 12 × H3, 10 × H4. Hierarchy is well-formed (no H4 without a parent H3).
- The H2 "Variances" is terse compared to the others. **Optional polish:** rename to `Reading variance: favorable vs. unfavorable` (matches the actual subsection content and adds keyword surface area). Not required for SEO — purely a clarity tune-up.

---

## Summary of Proposed Changes

| Group | Task | Item | Count |
|---|---|---|---|
| **A** | 1 | New internal links | 5 |
| **A** | 5 | Meta title rewrite | 1 |
| **A** | 5 | Meta description rewrite | 1 |
| **A** | 6 | Image alt text updates | 6 (+1 optional decorative) |
| **A** | 7 | Heading rename (optional) | 0–1 |
| **B** | 2 | Mid-content CTA insertion | 1 |
| **C** | 3 | Resource CTA (ACF) | 1 |
| **C** | 4 | Related Posts (ACF, 4 entries) | 1 set |

**Execution groups (CLAUDE.md convention):**
- **Group A** = WordPress `update-post` (content body + SEO fields + alt text edits inside HTML).
- **Group B** = WordPress `update-post` (content body — same call as Group A; the CTA block is just another HTML edit).
- **Group C** = WordPress `set-resource-cta` + `set-related-pages` (ACF-only, no content rewrite).

Group A and Group B can be bundled into a single `update-post` call (one content rewrite covering links + CTA insertion + alt text + meta).

---

## Approval needed

Reply with which suggestions you'd like to apply:

1. **All** — apply everything above (recommended).
2. **Group A only** — content + meta + alt text edits, no CTA insertion, no ACF changes.
3. **Skip task N** — name any task numbers to drop.
4. **Edit before applying** — suggest changes to specific items (anchors, CTA copy, alt wording, etc.).

Nothing has been written to WordPress yet. Once you approve, I'll bundle the edits and apply them via MCP.
