# SEO On-Page Report — Business Acquisition Plan for Buying an Existing Business

| Field | Value |
|-------|-------|
| **Page URL** | https://upmetrics.co/blog/business-plan-for-buying-an-existing-business |
| **Post ID** | 69012 |
| **Post Type** | `post` (Blog Post) |
| **Category** | Planning |
| **Published / Last Modified** | 2024-09-10 / 2026-07-30 |
| **Word Count** | 3,264 |
| **Report Date** | 2026-08-10 |
| **GSC Data Range** | 2026-05-12 → 2026-08-07 (90 days) |
| **GA4 Data Range** | Last 30 days (engagement) / Last 90 days (conversions) |
| **Index Status** | Submitted and indexed (last crawl 2026-07-31, mobile-first) |

---

## Section B — Page Health Score & Action Summary

### Page Health Score: **4.0 / 10**

| Status | Count | Items |
|--------|:--:|-------|
| **Critical** | 1 | Meta title/description losing every click at position 17-25 (0% CTR across 1,516 impressions) |
| **Needs Improvement** | 4 | Meta title identical to H1 · Meta title has no differentiation hook · Meta description 169 chars (over 160 cap) · Zero in-content CTAs across 3,264 words |
| **Minor** | 2 | Split anchor tag on the organizational-structure link · Generic alt text on the ten-sections diagram |
| **Good** | 6 | Indexed & crawled clean · Correct canonical · Heading hierarchy valid (no skips, one H1) · Blog Post End CTA present and canonical · No outdated year references · Breadcrumb schema detected |

**Score breakdown:** 10 &minus; 2 (top query 0% CTR vs 1.5% benchmark at position 19.3) &minus; 1 (title = H1) &minus; 1 (title has no hook) &minus; 1 (description over character limit) &minus; 0.5 (alt text quality) &minus; 0.5 (existing anchor quality) = **4.0**

### The headline problem

This page collected **1,516 impressions and 3 clicks in 90 days** (0.20% CTR, average position 30.5). It is indexed, ranking, and getting shown &mdash; but the SERP listing is not earning clicks. The five highest-impression queries all returned **zero clicks**:

- `business acquisition business plan` &mdash; 358 impressions, position 19.3
- `merger and acquisition business plan` &mdash; 230 impressions, position 44.0
- `acquisition business plan` &mdash; 143 impressions, position 17.7
- `merger and acquisition business plans` &mdash; 118 impressions, position 39.9
- `business acquisition plan` &mdash; 116 impressions, position 25.5

Notice that **none of them contain the phrase the page is optimised for**. The page's own keyword (`business plan for buying an existing business`) draws only 20 impressions but converts at 10% CTR &mdash; it works, there is just no volume behind it. The real demand sits on `acquisition business plan` variants, and the meta title does not lead with that phrase.

Secondary note: **desktop carries 92% of impressions** (1,398 vs 118 mobile), so the meta title has room for the full 60 characters without mobile truncation being the primary constraint.

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|--------------|---------------|
| 1 | Internal Links | Medium | Medium | 5 internal links (4 unique targets + homepage). One is a split anchor tag. | Add 4 links; fix the split anchor | None | **Add #1-#4, fix split anchor** |
| 2 | CTA Placements | High | Medium | 0 in-content CTAs. End CTA present and correct. | Add 3 CTAs (2 light + 1 banner) | None | **Add #1-#3** |
| 3 | Resource CTA | Low | Quick Win | Set to Free Business Plan Template, link text defaults to "Download Now" | Keep resource, set link text to "Download Template" | None | **Approve** |
| 4 | Related Content | Medium | Quick Win | 5 items; 2 only loosely related to acquisitions | Replace with 4 acquisition-relevant items | None | **Approve #1-#4** |
| 5 | Meta Title & Description | **High** | Quick Win | Title = H1, no hook. Description 169 chars. Top query 0% CTR. | Rewrite both; set focus keyphrase | None | **Approve both** |
| 6 | Image Alt Text | Low | Quick Win | 2 content images, both have alt. 0 missing. | Sharpen alt on the ten-sections diagram | None | **Approve #1** |
| 7 | URL Slug | &mdash; | High | `business-plan-for-buying-an-existing-business` (7 words) | No change | Would need 301 | **Skip &mdash; ranks pos 12.9 on its exact term** |
| 8 | Heading Structure | Low | Quick Win | Valid hierarchy. One awkward H3. | Optional H3 rewording | None | **Optional &mdash; your call** |
| 9 | Categories | Low | Quick Win | Planning | Add Forecasting as second category | None | **Approve** |
| 10 | Incoming Links | Medium | &mdash; | Suggestion only | 5 source pages identified | Manual | **Noted &mdash; review manually** |

---

## Section C — Task-by-Task Suggestions

## Task 1 — Internal Linking

### Part A — Existing Link Audit

| # | Anchor Text | Target URL | Status |
|:--:|-------------|------------|--------|
| 1 | `pricing` | `/blog/pricing-strategy-business-plan` | **Needs Fix** (minor) |
| 2 | `organization ` + `structure` | `/blog/organizational-structure-business-plan` | **Needs Fix** |
| 3 | `Working capital ` | `/blog/how-to-calculate-working-capital` | **Good** |
| 4 | `Exit planning` | `/blog/exit-strategies-for-business` | **Good** |
| 5 | `Upmetrics` | `https://upmetrics.co` (homepage) | **Good** &mdash; branded homepage link, standard practice |

**Current state:** 5 internal links across 3,264 words &mdash; below the 7-10 range for this length. No competitor domains linked. No query strings or tracking parameters on any internal link. No broken targets.

---

**Fix #A1 &mdash; split anchor tag (recommended)**

The organizational-structure link is currently rendered as **two adjacent `<a>` tags pointing at the same URL**:

```
<a href="https://upmetrics.co/blog/organizational-structure-business-plan">organization </a><a href="https://upmetrics.co/blog/organizational-structure-business-plan">structure</a>
```

This produces two separate link elements where there should be one. Google treats each anchor independently, so the anchor signal is split into `organization` and `structure` instead of the intended `organization structure`. It also renders with an odd trailing space inside the first link.

> **Fix:** merge into a single anchor.
>
> **Original:** "Then draft the **organization** **structure**: who reports to whom, and how the team is organized once you take over."
>
> **Modified:** "Then draft the **organization structure**: who reports to whom, and how the team is organized once you take over."
>
> **Note:** No visible text change &mdash; only the HTML is corrected. Same target URL.

---

**Fix #A2 &mdash; single-word anchor (optional)**

> **#A2** &mdash; `pricing` → `/blog/pricing-strategy-business-plan`
>
> **Section:** Cover the market and competitive analysis
>
> **In context:** "Start with the business's recent sales, customer retention, **pricing**, and service area. Use this information to see whether demand is growing, stable, seasonal, or declining."
>
> **Note:** One-word anchor. The only clean 2-word expansion in the article is "Current pricing" in the revenue-streams bullet ("**Current pricing** and when prices were last reviewed."). Moving the link there would improve the anchor but costs the link its position in the market-analysis section. Low priority &mdash; leaving it as is, is defensible.

---

### Part B — New Link Suggestions

**Recommended (4)**

> **#1** &mdash; `Buying an existing business` → `/blog/how-to-buy-existing-business`
>
> **Section:** Introduction (first paragraph)
>
> **In context:** "**Buying an existing business** gives you something a startup does not: real customers, operating history, and financial records. But those numbers only show how the business performed under the current owner."
>
> **Note:** Wraps existing text, zero changes. This is the sister pillar &mdash; this page covers the *plan*, that page covers the *process*. The two should be linked.

---

> **#2** &mdash; `a standard business plan` → `/blog/business-plan-components`
>
> **Section:** How to write a business acquisition plan?
>
> **In context:** "A business acquisition plan uses many of the same sections as **a standard business plan**, but the emphasis is different. Since the business is already operating, you can use its financial history, customers, team, and operations to support your plan."
>
> **Note:** Wraps existing text, zero changes. The sentence explicitly references the standard plan structure; the target page is exactly that reference (26,527 impressions, position 29.2 &mdash; it also gains from the link).

---

> **#3** &mdash; `SBA 7(a) loan` → `/blog/sba-loan-to-buy-business`
>
> **Section:** Open with the acquisition summary (Executive summary)
>
> **In context:** "The business has run for 14 years and did $500,000 in revenue last year with $120,000 in seller's discretionary earnings. I'm funding it with a $270,000 **SBA 7(a) loan**, a $54,000 seller note, and $36,000 of my own cash."
>
> **Note:** Wraps existing text, zero changes. The phrase also appears in the "Sources and uses of funds" table &mdash; use the paragraph occurrence above, not the table cell. Target page ranks for 15+ "buying a business loan" query variants.

---

> **#4** &mdash; `three-year forecast` → `/blog/financial-projections-business-plan`
>
> **Section:** Post-acquisition projections
>
> **In context:** "Next, use the seller's recent performance and the adjusted earnings as the starting point for a **three-year forecast**. For the first year, reflect what will change after the acquisition. Include new costs such as bookkeeping, your salary, additional staff, and loan payments, along with any expenses that will no longer continue."
>
> **Note:** Wraps existing text, zero changes. Target page has 16,043 impressions at position 48.1 &mdash; the weakest-ranking high-volume page in the cluster, so the link equity has somewhere useful to go.

---

**Optional (3)**

> **#5** &mdash; `cash flow` → `/blog/create-cash-flow-statement`
>
> **Section:** Post-acquisition projections
>
> **In context:** "Then show **cash flow** month by month, not just yearly. A slow winter can leave you short the month a payment is due, and a reader wants to see the business covers its debt even in its weakest stretch."
>
> **Note:** Sits roughly 70 words after suggestion #4 &mdash; inside the 100-word spacing minimum. **Pick #4 or #5, not both.** #4 is the stronger target.

---

> **#6** &mdash; `daily operating process` → `/blog/operations-plan-section`
>
> **Section:** Map out the operations and transition plan
>
> **In context:** "Describe what you're inheriting: The **daily operating process**, how work gets done from enquiry to invoice. Location and facilities, and whether the premises are owned or leased."
>
> **Note:** The anchor sits in a bullet list rather than a paragraph &mdash; acceptable but less ideal. Roughly 70 words from suggestion #7. **Pick #6 or #7, not both.**

---

> **#7** &mdash; `marketing and sales channels` → `/blog/marketing-strategy-business-plan`
>
> **Section:** Plan the customer retention and growth plan
>
> **In context:** "Next, describe how you plan to grow. Begin with the **marketing and sales channels** that already work. Then say how you will keep them running before adding new services, marketing campaigns, or price changes."
>
> **Note:** Wraps existing text, zero changes. Roughly 70 words from suggestion #6. **Pick #6 or #7, not both.**

---

<details>
<summary>Considered but skipped (6 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Write a Business Plan (complete guide) | Ranks in GSC but returns no post in WordPress &mdash; could not verify a post ID, so not suggested. Replaced with Business Plan Components. |
| Small Business Valuation Calculator | The WordPress post (ID 25774) is in **draft** status. It ranks via the frontend AI-tools route, but there is no published post to link to. |
| Financial Forecasting (feature page) | The natural anchor ("built-in financial forecasting") sits ~25 words from the existing Upmetrics homepage link in the conclusion &mdash; would cluster two sales links in one breath. |
| What Lenders & Investors Look for in a Business Plan | Claimed by Task 4 (Related Content). Linking it inline would need a sentence rewrite; the sidebar slot is cleaner. |
| Business Contingency Plan | "contingency plan" appears only in an H3. Links never go in headings, and no body text carries the phrase. |
| What is a Competitive Analysis | "competitive analysis" appears only in an H3. Same reason. |

</details>

---

## Task 2 — CTA Placements

### Part A — Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Blog Post End CTA (`delivery-block`) | Very last block | **Good** | Headline, subtitle, button text, and `/cta/help` URL all match the canonical registry version. No changes. |

**Current state:** **Zero in-content CTAs across 3,264 words.** The only conversion element in the body is the branded homepage link in the conclusion and the end-of-article banner. For a post this length the guidance is 3-4 CTAs total &mdash; the end CTA counts as one, so there is room for three.

The post also carries a Resources Hero CTA (see Task 3), which renders above the content, not in it.

---

### Part B — New CTA Suggestions

**Recommended (3)** &mdash; one banner + two light text CTAs, matching the light-CTA preference for editorial content.

> **#1** &mdash; Yellow Tip Alert (Type 12) | After "Cover the market and competitive analysis"
>
> **Placed after:** "Then close by saying what all of it means for the purchase. Is the business in a strong spot or starting to fall behind? Name what you'll protect and what you'll improve once it's yours."
>
> **Angle:** Ease
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │ Tip: Need a starting structure for the market and       │
> │ competitor sections? Our AI Business Plan Generator →   │
> │ drafts them from the details you already have.          │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Destination:** `/ai-tools/free-ai-business-plan-generator` &mdash; 1,145 sessions and 257 conversions in the last 90 days (top-10 conversion-starting page).

---

> **#2** &mdash; Download Link (Type 1) | After "Historical financial performance"
>
> **Placed after:** "Three years of steady growth, which is exactly what you want to see. If there'd been a dip or a spike in there instead, you'd leave it in and explain it, because a number you've quietly smoothed over is the first thing someone will ask about."
>
> **Angle:** Specificity
>
> **CTA Preview:**
> ```
>            → Download Now: Financial Statements Template
> ```
>
> **Destination:** `/download/financial-statement` &mdash; 99 sessions, 81.8% engagement rate. The reader has just been told to lay out three years of statements; this hands them the format.

---

> **#3** &mdash; Flex Banner: Financial Forecasting, image left (Type 5) | After "Post-acquisition projections"
>
> **Placed after:** "Then show cash flow month by month, not just yearly. A slow winter can leave you short the month a payment is due, and a reader wants to see the business covers its debt even in its weakest stretch."
>
> **Angle:** Pain point
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  🖼        Building monthly cash flow in a spreadsheet? │
> │ Financial                                               │
> │ Forecast    Change the purchase price once and every    │
> │             projection updates with it.                 │
> │                                                         │
> │             [ Try Upmetrics AI ]                        │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Destination:** `/signup`. Sits ~610 words before the Blog Post End CTA &mdash; clear of the 300-word buffer.

**Spacing check:** #1 → #2 ≈ 950 words · #2 → #3 ≈ 550 words · #3 → End CTA ≈ 610 words. No two CTAs share a screen. Three different CTA types, three different persuasion angles, no shared content words across headlines.

---

## Task 3 — Downloadable Resource CTA

**Currently set:**

| Field | Value |
|-------|-------|
| Resource URL | `https://upmetrics.co/download/business-plan-template` |
| Heading | Free Business Plan Templates |
| Link text | *(not set &mdash; defaults to "Download Now")* |
| Renders as | `Download Now: Free Business Plan Templates` (41 chars) |

**Suggested:**

| Field | Value |
|-------|-------|
| Resource URL | `https://upmetrics.co/download/business-plan-template` *(unchanged)* |
| Heading | `Free Business Plan Template` |
| Link text | `Download Template` |
| Renders as | `Download Template: Free Business Plan Template` (46 chars) |

The resource itself is the right one &mdash; a reader here wants a plan template, and the download page drove 39 conversions in 90 days. The only change is setting `resource_link_text` explicitly so it reads as a template offer rather than a generic "Download Now", and trimming the heading to singular to match the actual resource title.

**Alternative considered:** `/download/financial-statement` (Financial Statements Template) is a closer match to the article's heaviest section, but it is already being used as CTA #2 in Task 2 &mdash; putting it in both places would show the same resource twice.

---

## Task 4 — Related Content

**Currently set (5 items):**

| # | Current Title | Target | Assessment |
|:--:|--------------|--------|------------|
| 1 | Where to Find Industry Reports — Free and Paid Options | `/blog/free-and-paid-sources-of-industry-reports` | Weak fit &mdash; also contains a raw em dash, which is against the encoding rule |
| 2 | How to Do Industry Benchmarking for Better Decisions | `/blog/industry-benchmarking` | Good fit &mdash; keep |
| 3 | How to Write a Business Plan for a Loan: Step-by-Step Guide | `/blog/how-to-write-a-business-plan-for-a-loan` | Good fit &mdash; keep, shorten title |
| 4 | Why and When You Should Update Your Business Plan | `/blog/updating-your-business-plan` | Weak fit for an acquisition reader |
| 5 | How to Plan a Business Expansion Using Your Business Plan | `/blog/business-expansion-plan` | Moderate &mdash; moved to Task 10 instead |

**Suggested set (4 items — replaces all existing):**

| # | Related Title (custom) | Chars | Target URL | Post ID | Why |
|:--:|----------------------|:--:|------------|:--:|-----|
| 1 | What Lenders Check First in Your Plan | 37 | `/blog/what-lenders-look-for-in-business-plan` | 107358 | 536 sessions, 84.9% engagement &mdash; the highest-engagement blog page on the site. Directly answers "who is reading this plan". |
| 2 | Writing a Plan Your Bank Will Approve | 37 | `/blog/how-to-write-a-business-plan-for-a-loan` | 55725 | Acquisition plans are almost always lender-facing. Carried over from the current set with a shorter title. |
| 3 | Benchmark the Business Before You Buy | 37 | `/blog/industry-benchmarking` | 98143 | Already ranks for "industry benchmarking for acquisition targets". Carried over with an acquisition-specific title. |
| 4 | Read the Seller's Income Statement | 34 | `/blog/how-to-read-income-statement` | 74709 | The article tells readers to verify three years of statements; this teaches them how. |

All four are under the 50-character sidebar limit, use straight ASCII apostrophes, and avoid the raw post titles.

---

## Task 5 — Meta Title & Description

### 1. Performance context — why the rewrite is justified

| Top Query | Impressions | Position | Current CTR | Benchmark CTR | Status |
|-----------|:--:|:--:|:--:|:--:|:--:|
| business acquisition business plan | 358 | 19.3 | 0.0% | 1.5% | **Underperforming** |
| merger and acquisition business plan | 230 | 44.0 | 0.0% | &mdash; | Below top 20 |
| acquisition business plan | 143 | 17.7 | 0.0% | 1.5% | **Underperforming** |
| merger and acquisition business plans | 118 | 39.9 | 0.0% | &mdash; | Below top 20 |
| business acquisition plan | 116 | 25.5 | 0.0% | &mdash; | Below top 20 |
| business plan for buying an existing business | 20 | 13.0 | 10.0% | 1.5% | Healthy (but tiny volume) |

Two queries sit inside position 4-20 with **zero** clicks against a 1.5% benchmark. That is a Critical trigger. The pattern is consistent: the phrase driving almost all impressions is `acquisition business plan`, and the current title leads with `Business Acquisition Plan for Buying an Existing Business` &mdash; which reads as a near-duplicate of the H1 and offers no reason to click over a competitor.

### 2. Current vs. suggested

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | Business Acquisition Plan for Buying an Existing Business | 57 | Acquisition Business Plan: 10 Sections + Free Template | 54 | Focus keyphrase at char 0. Two hooks (number + free template). No longer identical to H1. |
| Meta Description | Learn how to write a business acquisition plan for buying an existing business. Cover valuation, due diligence, financing, and ownership transition with a free template. | 169 | Write an acquisition business plan for buying an existing business: what to get from the seller, how to normalize earnings, and a free template inside. | 151 | Was 9 chars over the hard cap. Keyphrase at chars 9-34. Adds "normalize earnings" &mdash; a detail no competitor title carries. |
| Focus Keyphrase | *(not exposed via API &mdash; confirm in Yoast)* | &mdash; | acquisition business plan | &mdash; | 143 impressions at position 17.7 &mdash; the best runway among top queries. 3 words. |
| Canonical | /blog/business-plan-for-buying-an-existing-business | &mdash; | *(unchanged)* | &mdash; | Correct. Google canonical matches user canonical. |
| OG Title | Business Acquisition Plan for Buying an Existing Business | 57 | *(match new meta title)* | 54 | Currently mirrors the old meta title. |
| OG Description | *(matches meta description)* | 169 | *(match new meta description)* | 151 | Same. |

### 3. SERP preview

```
─────────────────────────────────────────────────────
upmetrics.co › blog › business-plan-for-buying-an-existing-business
Acquisition Business Plan: 10 Sections + Free Template
Write an acquisition business plan for buying an existing
business: what to get from the seller, how to normalize
earnings, and a free template inside.
─────────────────────────────────────────────────────
```

### 4. Differentiator

Competing results for `acquisition business plan` lean on "Guide", "Template", and "How to Write". This title leads with a **concrete section count (10)** that matches the article's actual structure, plus the free-template signal. The number is the differentiator &mdash; it promises a checkable, finite deliverable rather than another guide.

**Note on the keyphrase choice:** `business acquisition business plan` has more impressions (358 vs 143) and also sits in the 4-20 band, but it is a duplicated-word phrase that reads badly in a title. `acquisition business plan` is a clean 3-word substring that also appears inside the higher-volume query, so a title leading with it stays relevant to both.

---

## Task 6 — Image Alt Text

### Audit summary

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | &mdash; |
| Critical — Empty (wrong) | 0 | &mdash; |
| Needs Improvement | 1 | Rewrite alt text |
| Good | 1 | No action |
| Decorative — Correct | 1 | No action |
| **Total images** | **3** | &mdash; |

No accessibility failures. Both content images already carry alt text.

### Detailed audit

| # | src (filename) | Status | Current Alt | Suggested Alt | Chars | Notes |
|:--:|----------------|--------|-------------|---------------|:--:|-------|
| 1 | `business-plan-for-buying-an-existing-business-ten-sections.png` | Needs Improvement | Ten sections of a business plan for buying an existing business | Ten sections of an acquisition business plan, from executive summary and financials through risk analysis and appendix | 118 | Current alt states the count but not what the sections are. New alt names the endpoints and carries the new focus keyphrase. |

**No action (listed for completeness):**

| # | src (filename) | Status | Current Alt |
|:--:|----------------|--------|-------------|
| 2 | `business-plan-for-buying-an-existing-business-transition-timeline.png` | **Good** | Operations and transition plan timeline from before closing to day 90 (69 chars &mdash; specific, in range, no banned openers) |
| 3 | `crossline.png` | **Decorative — Correct** | `crossline` &mdash; accent graphic inside the end CTA button. Leave as is. |

Keyword usage after the change: the primary keyword appears in exactly 1 of 2 content alts. No duplicates, no banned openers, no banned AI words.

---

## Task 7 — URL Slug

**Current:** `business-plan-for-buying-an-existing-business` (44 chars, 7 words)

**Recommendation: no change.**

The slug is one word over the 3-6 word guideline, but the risk assessment is decisive against touching it:

- The page ranks **position 12.9** for `business plan for buying an existing business` &mdash; an exact slug match &mdash; and that query is the only one converting (10% CTR).
- Google has indexed three **section-anchor URLs** from the pre-July structure (`#how-to-plan-for-buying-an-existing-business`, `#mistakes-to-avoid-while-writing-a-business-plan-for-buying-a-business`, `#why-do-you-need-a-plan-for-purchasing-a-business`), all still drawing impressions at positions 7-11. Those anchors no longer exist in the rewritten content, and a slug change on top of that would compound the disruption.
- A slug change would require a 301 redirect and reset whatever equity the page has accumulated since 2024.

The `acquisition business plan` targeting is better handled through the meta title (Task 5) than through the URL.

---

## Task 8 — Heading Structure

| Check | Result |
|-------|--------|
| Exactly one H1 | Pass &mdash; theme renders the H1; content contains none |
| H2 → H3 → H4, no skipped levels | Pass |
| Primary keyword in at least one H2 | Pass &mdash; "How to write a business acquisition plan?" |
| Headings under 70 characters | Pass &mdash; longest is 61 chars |
| No duplicate headings | Pass |
| Section count matches the claim | Pass &mdash; the article promises ten sections and delivers ten H3s |

**One optional polish:**

| Current H3 | Issue | Suggested |
|-----------|-------|-----------|
| Plan the customer retention and growth plan | "Plan…plan" repeats within a 7-word heading | Protect customer retention and plan for growth |

Note: the new focus keyphrase `acquisition business plan` does not appear verbatim in any H2 &mdash; only the word-order variant `business acquisition plan` does. Forcing the exact phrase into a heading would read awkwardly and the semantic variant is already there. No change recommended.

---

## Task 9 — Category / Taxonomy

**Current:** `Planning`

**Suggested:** `Planning`, `Forecasting`

Planning stays as primary &mdash; the article is fundamentally about writing a business plan. Forecasting is warranted as secondary because the financial plan is the article's largest section by a wide margin: historical financial performance, normalized earnings and add-backs, sources and uses of funds, and post-acquisition projections, with three of the article's four data tables. That maps directly to the Forecasting definition (financial projections, cash flow, income statements, financial plan).

`Funding` was considered &mdash; the SBA 7(a) loan and seller-note content supports it &mdash; but the financing material is one part of one section, whereas the forecasting material spans four subsections.

---

## Task 10 — Incoming Internal Link Suggestions

Pages that should link **to** this article. Suggestion only &mdash; the SEO team implements manually.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic (90d) | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | How to Write an SBA Business Plan + Template | `/blog/sba-business-plan` | 6125 | post | Highest-impression plan-format guide in the cluster; SBA 7(a) is the standard route for funding an acquisition | acquisition business plan | 18 clicks / 21,644 imp | High |
| 2 | Top SBA Lenders | `/blog/best-sba-lenders` | 89179 | post | Ranks **position 1** for "how to get a loan to buy an existing business" and position 17 for "top business acquisition loans for startups 2026" | business acquisition plan | 14 clicks / 16,867 imp | High |
| 3 | How to Get Funding for a Business | `/blog/how-to-get-funding-for-a-business` | 82946 | post | Ranks for "how to get funding to buy an existing business" (11 imp) and "funding to buy an existing business" (6 imp) &mdash; both at position 74+, so it needs the topical reinforcement too | business plan for buying a business | 18 clicks / 9,461 imp | High |
| 4 | Allocation of Funds: What It Is and Why It Matters | `/blog/allocation-of-funds` | 83630 | post | "Sources and uses of funds" is a named section in this article; the source page covers the same concept at position 12.8 | sources and uses of funds | 17 clicks / 16,761 imp | Medium |
| 5 | Business Plan Table of Contents: Sample + Free Template | `/blog/business-plan-table-of-contents` | 6149 | post | Ranks **position 1** for "business plan for existing business"; strongest position of any candidate | acquisition business plan sections | 51 clicks / 7,559 imp | Medium |

> Every source URL above is verified in WordPress with a real post ID and carries real GSC traffic. Suggested anchor text is a starting search term for the SEO team &mdash; the actual anchor depends on what phrasing already exists in each source page's content.

**Excluded from this list:**

- `/blog/how-to-buy-existing-business`, `/blog/sba-loan-to-buy-business`, `/blog/business-plan-components`, `/blog/financial-projections-business-plan` &mdash; all receive outbound links from this page under Task 1. Reciprocal links avoided.
- `/blog/how-to-get-a-business-loan-with-bad-credit` (81933) &mdash; ranks for "business acquisition loans bad credit" (16 imp) and "bad credit business acquisition loans" (15 imp), but sits under 10 clicks in 90 days, below the traffic floor for a useful equity source.
- `/blog/industry-benchmarking`, `/blog/what-lenders-look-for-in-business-plan`, `/blog/how-to-write-a-business-plan-for-a-loan` &mdash; assigned to Task 4 (Related Content).

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2, #3, #4. Fix the split anchor (#A1). Skip #A2, #5, #6, #7.
Task 2 (CTAs): Add #1, #2, #3.
Task 3 (Resource CTA): Approve — keep business-plan-template, set link text to "Download Template".
Task 4 (Related Content): Approve items #1-#4 (replaces all 5 current items).
Task 5 (Meta Title/Desc): Approve title. Approve description. Set focus keyphrase to "acquisition business plan". Update OG fields to match.
Task 6 (Image Alt Text): Approve #1.
Task 7 (URL Slug): Skip — ranks position 12.9 on the exact-match term.
Task 8 (Headings): Approve the H3 reword. (or: Skip)
Task 9 (Categories): Approve Planning + Forecasting.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task 8"**
