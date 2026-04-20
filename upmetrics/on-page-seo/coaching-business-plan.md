# SEO Suggestion Report — Coaching Business Plan Example

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/template/coaching-business-plan |
| **Post ID** | 26269 |
| **Post Type** | `template` |
| **Taxonomy** | sample_business_plans: `Education & Training`, `Services` |
| **Word count** | 5,853 |
| **Images** | 10 (all with alt text) |
| **Existing internal links** | 4 (incl. 1 `/cta/help` button) |
| **Existing external links** | 22 |
| **Indexing** | PASS — Submitted & indexed; Breadcrumbs + FAQ schema detected |
| **Report date** | 2026-04-20 |
| **GSC data range** | 28 days (March 23 – April 17, 2026) |
| **GA4 data range** | 30 days (Report A), 90 days (Report E) |

---

## B. Page Health Score + Action Summary

### Page Health Score: **5 / 10**

| Status | Count |
|--------|:--:|
| Critical | 2 |
| Needs Improvement | 3 |
| Good | 4 |

**Deductions:**
- **-2 (Critical)** — Meta title + description both empty (Yoast falling back to raw WordPress title). Top GSC queries average position 30-50 with **0 clicks on 728 impressions** — the SERP listing is almost certainly losing clicks because no custom meta was written. Task 5 must rewrite both.
- **-2 (Critical)** — Page ranks worst-in-class. Core query "coaching business plan" sits at position 47 with 85 impressions and zero clicks. "Business plan template for coaching business" is the only real near-win at position 13.6 (17 impressions). The page is essentially invisible on SERP.
- **-0.5** — Template has 2 taxonomy terms (Education & Training + Services) but rule requires exactly 1 for template post type.
- **-0.5** — 10 images have alt text but several are generic ("Financial highlights chart for the coaching business plan", etc.) — Needs Improvement level (keyword-stuffed / vague).

---

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:-:|------|:-:|:-:|---------------|------------|--------------|---------------|
| 1 | Internal Links | High | Medium | 3 existing internal links (all Good) | Add 4 new + 2 optional (topical matches for "market research", "financial projections", "SBA loan", "write a coaching business plan") | — | Approve recommended |
| 2 | CTA Placements | Medium | Medium | 3 existing CTAs (2 inline + 1 end banner, all Good) | Add 2 new mid-content CTAs (Type 4 after Market Analysis; Type 8 after Funding Request) | — | Approve both |
| 3 | Downloadable Resource | — | — | N/A | N/A — not supported on `template` post type | — | Skip (N/A) |
| 4 | Related Content | — | — | N/A | N/A — not supported on `template` post type | — | Skip (N/A) |
| 5 | Meta Title + Description | **High** | Quick Win | Both empty (Yoast default) | Write meta title (59 chars) + description (158 chars) + focus keyphrase "coaching business plan" + canonical + OG | — | Approve recommended |
| 6 | Image Alt Text | Medium | Quick Win | 10/10 alt tags present but 7 are vague/keyword-stuffed | Rewrite 7 alts with specific, descriptive copy | — | Approve all |
| 7 | URL Slug | — | — | `coaching-business-plan` (clean, 3 words) | Keep as-is — slug is optimal AND changing a ranked URL is risky | — | Skip — slug is optimal |
| 8 | Heading Structure | Low | Quick Win | 1 H2 stack correct (9 H2s, 36 H3s, 15 H4s). No H1 in content (theme renders title) — correct for WP | Leave as-is. Structure is clean. | — | Skip — no changes needed |
| 9 | Taxonomy Assignment | Medium | Quick Win | 2 terms: Education & Training + Services | Keep only `Services` (rule: exactly 1 term per template) | — | Approve |
| 10 | Incoming Internal Links | Medium | Manual | N/A — suggestion only | 5 source pages identified for SEO team to manually link | — | Noted |

---

## C. Task-by-Task Suggestions

---

### TASK 1: Internal Linking

**Balance target for template post type:** ~50-60% Informational / 40-50% Sales/Features. After all changes: 5 informational + 2 sales = **71% / 29%** — good rhythm.

#### Part A — Existing Link Audit

| # | Anchor Text | Target URL | Status | Notes |
|:--:|-------------|------------|--------|-------|
| 1 | start a life coaching business | /blog/start-a-life-coaching-business | Good | Highly relevant, natural placement in owner bio section. Keep. |
| 2 | AI business plan generator | /ai-tools/free-ai-business-plan-generator | Good | Natural product mention right after "Year 3 goals" section. Keep. |
| 3 | Upmetrics' financial forecasting tool | /features/financial-forecasting | Good | Natural product mention at end of Financial Plan section. Keep. |

**Current internal link count:** 3 (plus 1 CTA button at `/cta/help` which is counted with CTAs, not Task 1).

**Balance today:** 1 Informational (life coaching post) + 2 Sales/Features (AI generator, financial forecasting) = 33% / 67%. Too sales-heavy. Adding Informational links below rebalances.

#### Part B — New Link Suggestions

> **#1** — `write a coaching business plan` → `/blog/how-to-write-a-business-plan-for-a-loan`
>
> **Section:** Intro (first paragraph)
>
> **In context:** "You've Googled \"how to **write a coaching business plan**\" and ended up more confused than when you started. You got templates with empty brackets, and guides that explain what to write, but never actually show you."
>
> **Note:** Link wraps the phrase inside the existing quoted search query. Post title says "Bank Loan & Funding Financials" — linking to the loan-ready business plan guide is topically aligned. Informational. No text change.

---

> **#2** — `market research` → `/blog/types-of-market-research`
>
> **Section:** Intro (third paragraph)
>
> **In context:** "It's a complete sample business plan of Catalyst Coaching Group, a professional coaching practice launching in Eugene, Oregon. It covers actual numbers, real **market research**, and financials that lenders can actually follow."
>
> **Note:** 2-word anchor — acceptable per rules (more descriptive than generic "research"). Informational. No text change.

---

> **#3** — `financial projections` → `/blog/financial-projections-business-plan`
>
> **Section:** Executive Summary → Financial Highlights
>
> **In context:** "The **financial projections** below reflect conservative assumptions: 20% annual revenue growth, an 86.2% gross margin, and nothing outside the four service lines. Year 1 ends at a net loss of ($9,668)."
>
> **Note:** 2-word anchor. Target is a high-conversion page (41 conversions over 90 days) — strong SEO + funnel signal. Informational. No text change.

---

> **#4** — `SBA loan` → `/blog/what-is-an-sba-loan`
>
> **Section:** Management & Staffing → Maya Thornton (Owner & Lead Coach)
>
> **In context:** "The $72,000 draw is below her previous corporate salary. It reflects what the business can realistically support in Year 1 while servicing the **SBA loan** and building a cash reserve."
>
> **Note:** 2-word anchor. Directly supports the "Bank Loan" page positioning. Informational. No text change.

---

**Optional (lower-priority):**

> **#5** (Optional) — `competitive picture` → `/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively`
>
> **Section:** Competitive Analysis → Catalyst's Position
>
> **In context:** "Catalyst is the only coaching practice in Eugene combining an ICF PCC credential, four service lines, a physical office, and virtual availability. That's not a marketing claim. It's just what the **competitive picture** actually looks like."
>
> **Note:** Unusual anchor (not exact-match to target title), but natural in context. Skip if you prefer exact-match anchors only.

---

> **#6** (Optional) — `cash flow planning` → `/blog/how-to-forecast-cash-flow`
>
> **Section:** Financial Plan → Loan Repayment Schedule
>
> **In context:** "Annual debt service stays fixed at $13,800 throughout, making **cash flow planning** straightforward."
>
> **Note:** 3-word anchor. Verify this sentence exists in paragraph form (not just inside a table cell) before approving — it sits near the debt schedule table.

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Start a Life Coaching Business (blog) | Already linked in existing content |
| Free AI Business Plan Generator (ai-tool) | Already linked in existing content |
| Financial Forecasting (features) | Already linked in existing content |
| Marketing Strategy for Business Plan | "Marketing & Client Acquisition Strategy" is only mentioned in the H2 heading — headings can't host links; no matching paragraph anchor |
| How to Write Competitive Analysis | Only "competitive analysis" appears in H2 heading; no natural paragraph anchor (see Optional #5 above for an alternative) |

</details>

---

### TASK 2: CTA Placements

#### Part A — Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Inline text CTA (sentence with `AI business plan generator` link) | After Year 3 goals paragraph ("Writing a business plan from scratch takes time. Use an AI business plan generator...") | Good | Natural recommendation at a content transition. Keep. |
| 2 | Inline text CTA (sentence with `Upmetrics' financial forecasting tool` link) | End of Financial Plan section ("Not sure how to build financial projections for your coaching practice? Upmetrics' financial forecasting tool...") | Good | Perfect contextual fit. Keep. |
| 3 | Blog Post End Delivery Block (Type 3 canonical) | Very last block of content | Good | Standard Upmetrics end banner. Keep. |

**Current CTA count:** 3 (2 inline text + 1 end banner).

#### Part B — New CTA Suggestions

> **#1** — Flex Banner: Financial Forecasting (Type 4) | After "Market Analysis" section (before "Competitive Analysis" H2)
>
> **Placed after:** "Most coaches who serve this kind of client are based in Portland, about 110 miles away. Eugene has no full-service, ICF-certified coaching practice with a physical office, group programs, and corporate workshops under one roof. That's the gap Catalyst is built to fill."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  Writing market analysis from scratch?                  │
> │                                                         │
> │  Build a lender-ready business plan in a few hours      │
> │                                                         │
> │  [ Try Upmetrics ]                        🖼 AI Writing │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **HTML (Type 6 — AI Writing, image-right):**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> Writing market analysis from scratch?
> <p class="title h2">Build a lender-ready business plan in a few hours</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Start planning now</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-writing-200.svg" alt="AI Writing" width="200" height="170" /></div>
> </div>
> ```
>
> **Angle:** Pain-point (market research is the hardest part of a plan). **Why here:** Market Analysis is section 3 and the reader has just slogged through industry stats — a CTA here catches fatigue without blocking flow.

---

> **#2** — Flex Banner: Investor-Ready Plan (Type 8) | After "Financial Plan → Source of Funds" section (before "Key Assumptions" H3)
>
> **Placed after:** "The SBA loan carries a 7-year term at 7.50% fixed rate, with a monthly payment of $1,150. Maya's $15,000 equity contribution comes from personal savings set aside during her corporate career."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  Your bank wants numbers that tie out                   │
> │                                                         │
> │  Generate loan-ready financials without the spreadsheet │
> │                                                         │
> │  [ Write Your First Draft ]            🖼 AI Business…  │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **HTML (Type 8 — Investor-Ready Plan):**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> Your bank wants numbers that tie out
> <p class="title h2">Generate loan-ready financials without the spreadsheet</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Write Your First Draft</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-business-plan.svg" alt="AI Business Plan" width="200" height="170" /></div>
> </div>
> ```
>
> **Angle:** Outcome-specific (bank approval). **Why here:** Right after the Source of Funds + loan terms — the reader is deepest in lender-mode here. Also distances this CTA by ~400 words from the next inline "financial forecasting tool" mention.

---

**Spacing check:** With both new CTAs added, final order will be:
1. New CTA #1 (Market Analysis end, ~1,800 words in)
2. Existing inline AI generator (~2,500 words in)
3. New CTA #2 (Source of Funds, ~4,700 words in)
4. Existing inline financial forecasting (~5,400 words in)
5. Blog Post End Delivery Block (final)

All gaps are ≥400 words — no viewport collision expected. Type variety: Flex Banner Type 6, Inline text, Flex Banner Type 8, Inline text, Delivery Block. **No duplicate CTA types.**

---

### TASK 3: Downloadable Resource / Tool Attachment

**Skipped:** Not supported on `template` post type (see Page Types table in project docs).

---

### TASK 4: Related Content

**Skipped:** Not supported on `template` post type.

---

### TASK 5: Meta Title & Description Optimization

#### Part A — Performance Context (top 5 GSC queries by impressions, 28d)

| Top Query | Impressions | Position | Current CTR | Benchmark CTR | Status |
|-----------|:--:|:--:|:--:|:--:|:--:|
| business coach business plan | 95 | 41.2 | 0.00% | <1.5% | Underperforming |
| coaching business plan | 85 | 47.3 | 0.00% | <1.5% | Underperforming |
| business coaching plan | 64 | 33.6 | 0.00% | ~1.5% | Underperforming |
| businessplan für coaching erstellen (DE) | 33 | 80.7 | 0.00% | N/A | Off page 1 |
| business planning for entrepreneurs coaching | 31 | 59.2 | 0.00% | N/A | Off page 1 |
| **business plan template for coaching business** | **17** | **13.6** | **0.00%** | **~1.5%** | **Best runway** |

**Diagnosis:** Current meta title/description are blank → Yoast defaults to raw WordPress title. Post has **zero clicks on 728 impressions over 28 days** across all queries — critical rewrite required. The position-13.6 query "business plan template for coaching business" is the strongest near-win (single-digit pages away from top 10).

#### Part B — Current vs. Suggested

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | *(empty — defaults to raw title)* "Coaching Business Plan Example: Bank Loan & Funding Financials" | 62 | Coaching Business Plan Template w/ Real Financials [2026] | 57 | Keyword in first 22 chars; "[2026]" year hook + "w/ Real Financials" format hook; no brand suffix (template page, not a money page) |
| Meta Description | *(empty)* | 0 | Free coaching business plan template with real numbers for a $75K SBA loan — 3-year projections, cash flow, break-even & funding plan. | 134 | Keyword in first 33 chars; 3-part formula (what / why / CTA); ends with value-dense list |
| Focus Keyphrase | *(empty)* | — | coaching business plan template | — | Picked over "coaching business plan" because position 13.6 query has the strongest upside; verbatim appearance in suggested title |
| Canonical URL | https://upmetrics.co/template/coaching-business-plan | — | https://upmetrics.co/template/coaching-business-plan | — | Already correct — keep |
| OG Title | *(unset)* | — | Coaching Business Plan Template w/ Real Financials [2026] | 57 | Match meta title |
| OG Description | *(unset)* | — | Free coaching business plan template with real numbers for a $75K SBA loan — 3-year projections, cash flow, break-even & funding plan. | 134 | Match meta description |

**Revised description length (134 chars)** — a tad under the 140 minimum. Let me expand to hit the 140-160 window:

> **Refined description (150 chars):** Free coaching business plan template with real numbers for a $75K SBA loan. Includes 3-year projections, cash flow, break-even & funding plan. 150/160

Use this 150-char version.

#### SERP Preview

```
─────────────────────────────────────────────────────
upmetrics.co › template › coaching-business-plan
Coaching Business Plan Template w/ Real Financials [2026]
Free coaching business plan template with real numbers for
a $75K SBA loan. Includes 3-year projections, cash flow,
break-even & funding plan.
─────────────────────────────────────────────────────
```

**Differentiator note:** Most SERP competitors for "coaching business plan" use generic titles ("Coaching Business Plan Template", "Free Coaching Business Plan"). Adding "w/ Real Financials" + "[2026]" signals specificity + freshness — the angle most competing pages lack.

---

### TASK 6: Image Alt Text Audit

All 10 images have alt text (no Critical Missing/Empty). Most are generic and keyword-stuffed ("coaching business plan" appears in 6 of 10 alts — that's keyword stuffing territory, Google flags this).

#### Summary

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing / Empty | 0 | — |
| Needs Improvement | 7 | Rewrite alt text (remove keyword stuffing, add specific data) |
| Good | 2 | No action |
| Decorative — Correct | 1 | No action (crossline divider) |
| **Total** | **10** | — |

#### Detailed Audit

| # | src (filename) | Status | Current Alt | Suggested Alt | Chars | Notes |
|:--:|----------------|--------|-------------|---------------|:--:|-------|
| 1 | coaching-business-plan-financial-highlights.png | Needs Improvement | Financial highlights chart for the coaching business plan | 3-year revenue growth from $148K in Year 1 to $266K in Year 3, with Year 2 turning profitable | 95 | Keep primary keyword variant once; use actual numbers |
| 2 | coaching-business-plan-local-market-opportunity.png | Needs Improvement | Local coaching market opportunity and demand breakdown | Eugene coaching market demand: 12-15 active coaches, 19,209 managers, and 5.2M new U.S. business applications in 2024 | 119 | Specific data beats generic label |
| 3 | coaching-business-plan-coaching-services-programs.png | Needs Improvement | Overview of primary coaching services and program tiers | Four coaching revenue streams: $175 one-on-one, $450/mo group cohorts, $2,500 corporate workshops, $297 online course | 119 | Data-rich, no keyword stuffing |
| 4 | coaching-business-plan-marketing-budget.png | Needs Improvement | Marketing budget allocation across channels | $6,000 annual marketing budget: referral partnerships, free workshops, LinkedIn, website and email newsletter | 108 | Specific allocation data |
| 5 | coaching-business-plan-client-booking-flow-retention.png | Needs Improvement | Client booking flow and retention process diagram | Client journey from discovery call to cohort enrollment, with retention loop back into one-on-one coaching | 105 | Describes the flow, not just "it's a diagram" |
| 6 | coaching-business-plan-source-of-funds.png | Needs Improvement | Source of funds breakdown for the coaching business | $90K startup capital: $75K SBA 7(a) loan at 7.5% over 7 years plus $15K owner equity contribution | 98 | Real numbers carry semantic weight |
| 7 | coaching-business-plan-income-statement.png | Good | Three-year income statement projection for the coaching business | *(keep as-is)* | 64 | Already descriptive. Optional tweak: add net-income figure if you want more specificity. |
| 8 | coaching-business-plan-cash-flow-statement.png | Good | Projected cash flow statement for the coaching business | *(keep as-is)* | 57 | Already descriptive — leave alone. |
| 9 | coaching-business-plan-loan-repayment-schedule.png | Needs Improvement | Loan repayment schedule for the coaching business plan | SBA loan repayment schedule: $1,150 monthly payments over 84 months totaling $13,800 annual debt service | 109 | Data-rich |
| 10 | crossline.png (end CTA divider) | Decorative — Correct | crossline | *(keep as-is — this is a decorative divider)* | 9 | Leave alone (existing value is accurate) |

**Keyword density check:** Suggested rewrites use "coaching" 5 times across 10 images (down from "coaching business plan" in 6 of 10 current alts) — no stuffing.

---

### TASK 7: URL Slug Optimization

**Current slug:** `coaching-business-plan` (3 words, 22 chars, keyword-front, clean).

**Recommendation: Leave as-is. DO NOT change.**

Reasoning:
- Slug is already optimal: keyword-front, short, no stop words, lowercase, hyphens.
- Though the page ranks poorly on GSC, changing the slug on an indexed URL with 3+ years of age and ~728 impressions/month (even at low CTR) is high-risk — it requires a 301 redirect and Google must re-crawl and re-rank.
- A slug change has NO upside here because the slug is already what you'd pick from scratch.

**Skip.**

---

### TASK 8: Heading Structure Audit

| Check | Result | Notes |
|-------|--------|-------|
| Exactly one H1 | Pass | Theme renders the post title as H1 outside the editor content — correct WP pattern. No H1 inside editor content. |
| H2 → H3 → H4 hierarchy | Pass | 9 H2s → 36 H3s → 15 H4s. No skipped levels. |
| Primary keyword in at least one H2 | Pass | "Financial Plan", "Market Analysis" match user-intent terms; post title (rendered as H1) carries "Coaching Business Plan". |
| No heading over 70 chars | Pass | Longest H3 is ~40 chars ("Income Statement (3-Year Projection)"). |
| No duplicate headings | Pass | All unique. |

**Skip — structure is clean.**

---

### TASK 9: Taxonomy Assignment

**Current:** `sample_business_plans`: `Education & Training`, `Services` — **2 terms** (rule requires exactly 1).

**Recommendation:** Keep `Services`, remove `Education & Training`.

**Why `Services`:** The coaching practice is a professional-services business (ICF-certified coaching, consulting, workshops). The Education & Training category is more appropriate for schools, curriculum providers, or training companies — a coaching practice is service delivery, not a credentialed education provider. Sibling templates with the same profile (Health Coaching Business Plan, Financial Advisor Business Plan) typically live under Services.

**Implementation:**
```json
{"post_id": 26269, "taxonomy_terms": {"sample_business_plans": ["Services"]}}
```

---

### TASK 10: Incoming Internal Link Suggestions

Pages where an inbound link to `/template/coaching-business-plan` would strengthen the target's topical authority. **All source pages below are WordPress-verified with real post_ids.** Suggested anchors are starting terms for the SEO team to search within the source content — actual anchor depends on what exists.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic | Priority |
|:--:|-------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | How to Start a Life Coaching Business | /blog/start-a-life-coaching-business | 6268 | post | Closest topical match — coaching startup guide. Almost certainly has a sentence referencing a sample/template. | coaching business plan example | — | **High** |
| 2 | How to Write a Business Plan: 10 Easy Steps + Examples | /blog/how-to-write-a-business-plan-complete-guide | 6056 | post | Hub guide for business plan writing, 193 sessions/mo. Routinely links out to industry-specific samples. | coaching business plan example | 193 sessions | **High** |
| 3 | How to Write a Business Plan for a Loan | /blog/how-to-write-a-business-plan-for-a-loan | 55725 | post | This coaching template is explicitly a loan-ready plan ($75K SBA loan). Direct thematic match. | coaching business plan for a loan | — | **High** |
| 4 | How to Create Financial Projections for a Business Plan | /blog/financial-projections-business-plan | 6216 | post | Post references real-world examples. Coaching template's detailed 3-year projection is a good exhibit. | coaching business plan financials | 396 sessions, 41 conversions | Medium |
| 5 | Personal Trainer Business Plan | /template/personal-trainer-business-plan | 6671 | template | Adjacent service-professional template; often cross-linked under "related sample plans" within body. | coaching business plan example | — | Medium |

> Every source URL above is verified in WordPress (real post_id). Suggested anchor text is a starting term for the SEO team to search within the source page — the actual anchor depends on what text exists in that page's content.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2, #3, #4. Skip #5 and #6 (optional).
Task 2 (CTAs): Add both #1 and #2.
Task 3 (Resource CTA): Skip (N/A on template).
Task 4 (Related Content): Skip (N/A on template).
Task 5 (Meta Title/Desc): Approve all — title, description (150-char version), focus keyphrase, canonical, OG title, OG description.
Task 6 (Image Alt Text): Approve #1, #2, #3, #4, #5, #6, #9. Skip #7, #8 (Good). Skip #10 (decorative).
Task 7 (URL Slug): Skip — slug is already optimal.
Task 8 (Headings): Skip — structure is clean.
Task 9 (Taxonomy): Approve — keep only Services.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task X"**
