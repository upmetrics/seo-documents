# SEO Page Audit — How to Conduct a Plan vs. Actual Analysis

**Page:** [https://upmetrics.co/blog/plan-vs-actual-analysis](https://upmetrics.co/blog/plan-vs-actual-analysis)
**Primary keyword:** plan vs actual (US — vol 80, KD 0, traffic potential 10)
**Audit date:** 2026-04-30
**Brand:** Upmetrics
**Geography:** United States

---

## 1. EXECUTIVE DASHBOARD

### Page Snapshot

| Metric | Value | Verdict |
|---|---|---|
| Word count | 2,057 (article body) | ⚠️ Below depth leader (Productive — 3,270) |
| Headings | 32 (1 H1, 6 H2, 5 H3, 11 H4, 1 H5 in article body) | ⚠️ H4-heavy, structurally shallow |
| Meta title | "How To Conduct Plan Vs. Actual Analysis \| Know Everything - Upmetrics" (69 chars) | 🔴 Contains "Know Everything" filler; weak click hook |
| Meta description | 158 chars — describes both spreadsheets and Upmetrics methods | 🟡 Borderline long, generic |
| Canonical | Self-referencing ✅ | ✅ Clean |
| Noindex / nofollow | None | ✅ Clean |
| Schema | Article, FAQPage, Person, Organization, BreadcrumbList, ImageObject, WebPage, WebSite (8 types) | ✅ Complete |
| Author | Vinay Kevadia (Founder/CEO) — in schema, but **no visible on-page bio block** | 🔴 E-E-A-T weak |
| Published / Updated | Sep 13, 2024 / Sep 13, 2024 (never refreshed in 19 months) | 🔴 Stale |
| Images | 21 (2 missing alt) | 🟡 Easy fix |
| Internal links (article body) | ~17 | 🟡 OK |
| External citations | 0 authoritative sources (only customer testimonial link + 2 broken Google Docs internal links) | 🔴 No E-E-A-T citations |
| Backlinks (Ahrefs) | **0 live** (3 all-time, 1 historical refdomain) | 🔴 No external authority |
| GSC clicks (last 6mo, US) | **0 clicks across 105 queries / ~1,800 impressions** | 🔴 Critical |
| Top GSC query | "plan vs actual report" — 221 impressions, pos 24.98, 0 clicks | 🔴 |
| Best-positioned query | "comparing what you planned with the actual performance" — 148 impr, pos 5.6, 0 clicks | 🔴 CTR failure |

### Top 3 Problems (in priority order)

1. **The page generates zero traffic despite measurable demand.** 105 queries / ~1,800 impressions over the last 6 months produced 0 clicks in the US. The average position (~25-40 for the highest-volume queries) means it's stuck on page 3-4 — but even the queries where it ranks page 1 (e.g. "comparing what you planned with the actual performance" — pos 5.6, 148 impressions) still get 0 clicks. That's a **double failure**: low rankings *and* the snippet doesn't earn clicks at the rankings it does have.

2. **Content depth is materially below the SERP leaders, especially Productive.io (pos 5).** Productive runs 3,270 words across 9 H2 sections with 14 visuals and 6 FAQs; Upmetrics runs 2,057 words with only 6 H2s and 3 FAQs. Indeed (pos 2) wins with a tight 1,200-word definitional structure that lifts a worked numerical example. Upmetrics has neither depth nor a tight definitional hook — it's stuck in the middle.

3. **Two external links in the body point to internal Google Docs (`docs.google.com/document/d/...`) — these are leaked internal documentation, not real citations.** Combined with the absence of a single authoritative external citation in a finance article (no IRS, SBA, AICPA, or accounting-textbook reference), this signals weak E-E-A-T to Google and breaks user trust.

### Traffic Opportunity

If this page earned a top-3 position for just its existing top-5 GSC queries (combined ~810 monthly impressions) at a realistic 18% CTR, it would generate **~145 monthly clicks** — vs. the current 0. The keyword universe (`plan vs actual`, `plan vs actual report`, `planned vs actual report`, `planned vs forecast vs actual`, `forecast vs actuals`) has low difficulty (KD 0) but is dominated by high-DR domains; a content overhaul + 1-2 backlinks should be enough to break into the top 5.

---

## 2. MASTER ACTION TABLE

All SEO actions sorted by priority. Content actions live in the **Content Update Brief (.docx)** and are not duplicated here.

| # | P | Action | Section ref | Effort |
|---|---|---|---|---|
| 1 | P1 | **Rewrite meta title** to remove "Know Everything" filler and tighten the click hook (see Title & Meta Copy block below) | §2 copy block | XS |
| 2 | P1 | **Rewrite meta description** to lead with a concrete value prop (variance formula + spreadsheet template offer) — see copy block | §2 copy block | XS |
| 3 | P1 | **Update the published/modified date** in WordPress to refresh the timestamp (currently Sep 13, 2024 — 19 months stale). Pair with the content update so the refresh is real, not cosmetic | §5 | XS |
| 4 | P1 | **Replace the two broken external links** that point to `docs.google.com/document/d/1c7EVYmEwo_kmFv6KdmOrVBkPvSwbNX7a4wB06czkpuY/...` (anchors: "Connect to XERO or QuickBooks", "Enter the actual financial data manually"). These leak internal documentation. Replace with the public Upmetrics help-center articles or remove the link if no public equivalent exists | §7B | S |
| 5 | P1 | **Add a visible author bio block** below the article that includes Vinay Kevadia's photo, role ("Founder & CEO, Upmetrics"), and 2-sentence bio. Schema already references this — the page just doesn't render the block | §8 | S |
| 6 | P1 | Execute the **content update** in the Content Update Brief (.docx) — depth, definitional hook, worked example, expanded FAQs, project-management framing | Update Brief | M |
| 7 | P2 | **Add 2 missing image alt attributes:** `example-of-a-sales-forecast-for-a-cafe-business.webp` and `corresponding-upmetrics-forecast-category.webp` | §5 | XS |
| 8 | P2 | **Add 3-5 authoritative external citations** to the body — SBA, AICPA, Investopedia, or HBR — for the variance/forecasting concept definitions. Specific recommendations live in the Update Brief Section 14E | Update Brief | S |
| 9 | P2 | **Pursue 2-3 backlinks** from finance/SMB blogs (currently 0 live refdomains). Quick-win targets: guest post on LivePlan competitor blogs, HARO finance queries, syndication on Substack finance newsletters | §7E | M |
| 10 | P2 | **Add internal links from 5-7 Upmetrics financial-planning posts** to this page using anchors like "plan vs actual analysis" or "how to compare planned vs actual financials". Specific source URLs in §7C | §7C | S |
| 11 | P3 | **Add a small "Last reviewed: [date]" line** under the H1 (separate from the published date) so readers see freshness even when the date displayed is older | §5 | XS |
| 12 | P3 | **Add HowTo schema** to the spreadsheet method (3 numbered steps) — the FAQPage schema is already present, but a HowTo block on the spreadsheet section could win a SERP feature | §5 | S |

### Title & Meta Copy block

This block is the **authoritative source** for `meta_titles` and `meta_descriptions` in the Update Brief JSON.

**Current meta title (69 chars):**
> How To Conduct Plan Vs. Actual Analysis | Know Everything - Upmetrics

Problem: "Know Everything" is filler, weak hook, no benefit.

**Recommended titles (pick one — A is the recommended primary):**

| # | Title | Length | Why |
|---|---|---|---|
| A | Plan vs. Actual Analysis: Step-by-Step Guide + Free Template | 60 | Leads with keyword, signals depth + asset |
| B | Plan vs. Actual Analysis: How to Compare Forecasts to Real Results | 67 | Definitional + benefit-led |
| C | How to Run a Plan vs. Actual Analysis (With Spreadsheet Example) | 65 | How-to + concrete artifact |

**Current meta description (158 chars):**
> Learn how to conduct a plan vs. actual analysis using Spreadsheets & Upmetrics—a step-by-step guide. Compare forecasts with actual data to identify variances.

Problem: Reads like a header card; no concrete value or hook.

**Recommended meta descriptions (pick one — A is the recommended primary):**

| # | Description | Length |
|---|---|---|
| A | Compare your forecasts to real numbers in 3 steps. Free spreadsheet template, the variance formula every founder should know, and a bike-shop example you can copy. | 158 |
| B | Plan vs. actual analysis in plain English. Includes the variance formula, a downloadable spreadsheet template, and a worked example. Spreadsheet or Upmetrics — both shown. | 156 |

---

## 3. KEYWORD & RANKING ANALYSIS

### 3A. Top 10 Keywords (GSC, US, last 6 months)

GSC returned 105 queries, 0 clicks, ~1,800 total impressions. Trend column noted as "stable 0-click" because no clicks have ever been recorded for any query in the 6-month window.

| # | Query | Impr | Pos | Clicks | CTR | Verdict |
|---|---|---|---|---|---|---|
| 1 | plan vs actual report | 221 | 24.98 | 0 | 0% | 🔴 Page 3 — needs depth + backlinks |
| 2 | planned vs actual report | 217 | 40.98 | 0 | 0% | 🔴 Page 4 — same intent, ranks far worse than #1 |
| 3 | comparing what you planned with the actual performance | 148 | 5.6 | 0 | 0% | 🟡 **Page 1, no clicks → CTR failure** |
| 4 | forecast vs actuals | 103 | 88.21 | 0 | 0% | 🔴 Page 9 — needs heading targeting |
| 5 | planned vs actual chart example | 79 | 27.95 | 0 | 0% | 🔴 Page 3 — visual gap |
| 6 | forecast vs. actual | 69 | 60.86 | 0 | 0% | 🔴 |
| 7 | plan vs actual | 64 | 20.53 | 0 | 0% | 🔴 Page 2-3 on the primary keyword |
| 8 | planned vs forecast vs actual | 57 | 11.51 | 0 | 0% | 🟡 Striking distance |
| 9 | actual vs. last year | 35 | 60.11 | 0 | 0% | 🔴 Tangential intent |
| 10 | planned vs actual chart example (variant — graph) | 13 | 74.77 | 0 | 0% | 🔴 |

**Pattern:** the page ranks for the right *concept cluster* (plan vs actual / planned vs actual / forecast vs actual) but consistently sits 20-40 positions deep — and the one query at position 5.6 (148 impressions) still gets zero clicks, indicating the snippet itself fails to earn the click.

### 3B. Striking Distance (positions 4-15 with ≥30 impressions)

| Query | Impr | Pos | What it needs |
|---|---|---|---|
| comparing what you planned with the actual performance | 148 | 5.6 | **CTR fix only** — title/meta rewrite (see §2). Already on page 1 |
| planned vs forecast vs actual | 57 | 11.5 | Add an explicit H2: "Plan vs. forecast vs. actual: what's the difference?" |
| differences between actual and expected performance are | 28 | 3.93 | Already on page 1 — strengthen meta to capture |
| actual example | 27 | 1.30 | Already #1 — but query is too generic to capture meaningful traffic |
| plan vs actual | 64 | 20.5 | Needs depth + 1-2 backlinks to break top 10 |

### 3C. Cannibalization Check

✅ **No cannibalization.** Across the primary keyword and the top 5 highest-impression queries (`plan vs actual`, `plan vs actual report`, `planned vs actual report`, `comparing what you planned with the actual performance`, `forecast vs actuals`), only the target page ranks. No other Upmetrics URLs surface. Consolidation is not needed; the focus is on lifting this single page.

---

## 4. SERP & INTENT ANALYSIS

### Intent classification

**Mixed informational** — leaning definitional + how-to.

The SERP for "plan vs actual" (US) is dominated by:
- **4 PAA boxes at the top** (definitional: "What is the difference between plan and actual?", "What is planned vs actual plan?", "What does planned and actual mean?", "How do you calculate plan vs actual variance?") — confirms strong definitional intent
- **AI Overview** present — Google is actively summarizing the concept above the fold
- **Indeed (pos 2, DR 92)** — career-advice definitional + worked sales example (1,200 words)
- **LivePlan (pos 3, DR 80)** — long blog guide (2,273 words) with sitelinks deep into it (signals strong topical authority)
- **Reddit r/FPandA (pos 4, DR 95)** — UGC, finance-team focused
- **Productive.io (pos 5, DR 75)** — long how-to guide (3,270 words) with project-management framing
- **CashFlowFrog (pos 6, DR 45)** — short product/blog hybrid (493 words)
- **Ruddr help doc (pos 7, DR 34)** — definitional KB article
- **LinkedIn post (pos 8)** — UGC
- **TargetBoard (pos 9, DR 18)** — product page with PM angle

**Intent mismatch on the target page:** The Upmetrics article jumps directly into "what is plan vs actual analysis" (good) and then into a deep how-to with Spreadsheets vs. Upmetrics methods. It misses two intent signals that Google is rewarding:
1. **A tight, snippet-friendly definition** (the kind Indeed and the AI Overview lift)
2. **A worked numerical example** (the Triumph Bike Shop example Indeed runs through, which makes the abstract concept tangible)

The page also doesn't address the `planned vs forecast vs actual` 3-way comparison — a real query with 57 impressions and a top-12 position that's begging to be captured with one new H2.

### SERP Features Table

| Feature | Present? | Owner / Notes |
|---|---|---|
| AI Overview | ✅ | Defines plan vs. actual; cites Indeed, LivePlan, Productive |
| People Also Ask | ✅ (4 questions at top) | "What is the difference between plan and actual?", "What is planned vs actual plan?", "What does planned and actual mean?", "How do you calculate plan vs actual variance?" |
| Featured Snippet | ❌ (no clear winner) | Snippet opportunity — see §4 below |
| Video pack | ❌ | — |
| Image pack | ❌ | — |
| Knowledge panel | ❌ | — |
| Sitelinks (organic) | ✅ on LivePlan (pos 3) | Multiple deep anchors — Google rewards LivePlan's heading structure |
| Reddit/UGC results | ✅ pos 4 | r/FPandA thread (limited UGC value to scrape) |
| Organic results start at | Position 2 (after PAA stack + AI Overview) | Above-the-fold real estate is largely SERP features |

### Featured snippet opportunities

There is **no current winner** for a featured snippet on "plan vs actual". To win it, the rewrite should include:

- A **definition paragraph (40-55 words)** placed immediately after the H1, formatted as a single block: "Plan vs. actual analysis (also called variance analysis) is the practice of comparing forecasted financial figures — sales, expenses, cash flow — against the actual numbers your business recorded over the same period. The gap between the two is called variance, and tracking it monthly helps founders catch problems before they compound."
- A **3-step ordered list** for "How to calculate plan vs. actual variance" — short, snippet-shaped (Step 1: Pull plan figure. Step 2: Pull actual figure. Step 3: Variance = Actual − Plan; Variance % = (Actual − Plan) / Plan × 100)
- A **comparison table for plan vs. forecast vs. actual** — the 3-column table format Google sometimes lifts as a table snippet

---

## 5. TECHNICAL SEO (Failures Only)

| # | Issue | Severity | Fix |
|---|---|---|---|
| 1 | Meta title contains "Know Everything" filler | P1 | → See §2 (Title & Meta Copy block) |
| 2 | Meta description is generic / unspecific | P1 | → See §2 (Title & Meta Copy block) |
| 3 | Page never updated — Sep 13, 2024 published, Sep 13, 2024 modified (19 months stale) | P1 | Update WordPress modified date when content rewrite ships |
| 4 | 2 of 21 article-body images missing alt text: `example-of-a-sales-forecast-for-a-cafe-business.webp` and `corresponding-upmetrics-forecast-category.webp` | P2 | Add descriptive alt text |
| 5 | No HowTo schema on the spreadsheet 3-step process (FAQPage schema is present and correct) | P3 | Add HowTo block to "Plan vs. analysis using spreadsheets" section |
| 6 | No "Last reviewed" line visible to users | P3 | Add a small "Last reviewed: [date]" line under the H1 |

Everything else passes:
- ✅ Self-referencing canonical
- ✅ No noindex / nofollow
- ✅ Schema is rich (8 types including FAQPage)
- ✅ Open Graph + Twitter cards complete
- ✅ Breadcrumbs (2 BreadcrumbList blocks present — slight redundancy but not harmful)
- ✅ 19/21 images have alt text
- ✅ Mobile-friendly site framework (assumed — full Lighthouse not run as part of this audit)

---

## 6. CONTENT GAPS & COMPETITOR DEPTH

### 6A. Content depth comparison

| Page | DR | Pos | Words | H2s | Visuals | FAQs | External citations |
|---|---|---|---|---|---|---|---|
| **Upmetrics (target)** | — | — | **2,057** | **6** | 21 | 3 | **0 authoritative** |
| Indeed | 92 | 2 | 1,200 | 4 | low | 0 | low |
| LivePlan | 80 | 3 | 2,273 | 9 | 10 | 2 | 3 |
| Productive | 75 | 5 | **3,270** | 9 | 14 | 6 | 0 |
| CashFlowFrog | 45 | 6 | 493 | 4 | 2 | 6 | 0 |
| TargetBoard | 18 | 9 | 1,200 | 7 | low | 0 | 0 |

**Read:** Upmetrics is mid-depth (above the short product pages, well below Productive). The bigger problem isn't word count — it's *which topics* are missing.

### 6B. Competitor heading map (gap analysis)

Topics covered by competitors but missing or under-developed on Upmetrics:

| Topic | On Upmetrics? | Indeed | LivePlan | Productive | TargetBoard | Gap label |
|---|---|---|---|---|---|---|
| Tight 50-word definition (snippet-shaped) | ❌ Definitional intro is 3+ paragraphs of prose | ✅ | ✅ | ✅ | partial | 🆕 NEW |
| Worked numerical example with full P&L (e.g., bike shop sales × price × actual) | ❌ Has cafe images but no fully narrated number walkthrough | ✅ (3-month bike shop) | ✅ | ✅ | partial | 🆕 NEW |
| Variance formula (Actual − Plan; variance %) | ❌ Mentioned in FAQ only | implicit | ✅ | ✅ | ✅ | 🆕 NEW |
| Plan vs. forecast vs. actual (3-way comparison) | ❌ | ❌ | partial | ✅ | ✅ | 🆕 NEW |
| Types of variance (favorable / unfavorable, price / volume / mix) | ❌ | ❌ | ✅ | ✅ | ❌ | 🆕 NEW |
| Cadence guidance (monthly vs. quarterly vs. annual) | ❌ Buried in FAQ #2 | ❌ | ✅ | ✅ | ❌ | 🟡 EDIT (promote out of FAQ) |
| Common mistakes when running plan vs. actual | ❌ | ❌ | ✅ | ✅ | ❌ | 🆕 NEW |
| Variance threshold guidance (when is variance "bad enough to act on"?) | ❌ | ❌ | partial | ✅ | partial | 🆕 NEW |
| Project-management angle (schedule, scope, effort variance — not just finance) | ❌ Finance-only | ❌ | ❌ | ✅ | ✅ | 🆕 NEW (small section) |
| What to do *after* you find a variance (action playbook) | ❌ Mentioned generically | partial | ✅ | ✅ | partial | 🆕 NEW |
| Detailed step-by-step walkthrough for the spreadsheet method | ✅ Has 3 steps | ✅ | ✅ | ✅ | — | ✅ KEEP |
| Upmetrics walkthrough (proprietary advantage) | ✅ | — | — | — | — | ✅ KEEP (only us) |
| Xero/QuickBooks integration | ✅ | — | — | — | — | ✅ KEEP (only us) |
| Visualizing the data (dashboards/charts) | ✅ has 4 chart screenshots | — | partial | partial | ✅ | ✅ KEEP |

### 6C. Topic Gap Detail

The five most impactful gaps to close (full writing instructions live in the Content Update Brief §14E):

1. **Snippet-shaped definition.** A 40-55-word paragraph immediately after the H1. Currently the page meanders for two paragraphs before defining the term. This is the single biggest reason Indeed/LivePlan/Productive are getting cited in the AI Overview and Upmetrics isn't.

2. **A worked numerical example.** Indeed runs a Triumph Bike Shop 3-month walkthrough with units, price, revenue, plan, actual, and variance. Upmetrics shows cafe-business *images* but never narrates the numbers in text. Text wins for snippets and AI overviews.

3. **Variance formula + variance %.** A clean two-line formula block: `Variance = Actual − Plan` and `Variance % = (Actual − Plan) / Plan × 100`. Currently buried in FAQ #3 in long-form prose.

4. **Plan vs. forecast vs. actual (3-way).** Captures `planned vs forecast vs actual` (57 impressions, pos 11.5 — striking distance) and `plan vs forecast vs actual` (30 impressions, pos 13.5). One new H2 + 100-word explainer + a 3-column comparison table.

5. **Common mistakes + variance thresholds.** Most direct competitors have this; it's the section that signals real expertise and turns a definitional article into a "trusted by practitioners" article.

---

## 7. LINKS & BACKLINKS

### 7A. Internal links — issues

The article body has ~17 internal links, most of which are appropriate (CTAs to /signup, links to financial-forecasting feature page, related blog posts). One issue:

- The internal link **anchor "log in to Upmetrics"** is set to `rel="nofollow"`. Either remove the nofollow (it's a first-party link to the app) or remove the link.

### 7B. External links — issues (broken / wrong)

| URL | Anchor | Issue | Fix |
|---|---|---|---|
| `https://docs.google.com/document/d/1c7EVYmEwo_kmFv6KdmOrVBkPvSwbNX7a4wB06czkpuY/edit#heading=h.grebps483qcf` | "Connect to XERO or QuickBooks" | 🔴 Internal Google Doc — not a public resource | Replace with the public Upmetrics help-center article on Xero/QuickBooks integration; remove if no public equivalent |
| `https://docs.google.com/document/d/1c7EVYmEwo_kmFv6KdmOrVBkPvSwbNX7a4wB06czkpuY/edit#heading=h.n5m93nngjesg` | "Enter the actual financial data manually" | 🔴 Same internal doc | Same fix |
| `https://www.linkedin.com/in/matt-little-au/` | "Matt Little" | 🟡 Customer testimonial — fine, but should have `rel="nofollow noopener"` set explicitly (currently does — ✅) | Keep |
| `https://festoonhouse.com.au/` | "Festoon House" | 🟡 Customer link — fine | Keep |

### 7C. Internal links to ADD (incoming — point to this page from other Upmetrics posts)

This page currently lacks contextual internal links from related financial-planning content. Recommend adding **5-7 contextual links** from:

| Source URL (recommended) | Suggested anchor |
|---|---|
| [https://upmetrics.co/blog/what-is-cash-flow-forecasting](https://upmetrics.co/blog/what-is-cash-flow-forecasting) | "plan vs. actual analysis" |
| [https://upmetrics.co/blog/financial-forecast-without-historical-data](https://upmetrics.co/blog/financial-forecast-without-historical-data) | "compare your forecast to actuals" |
| [https://upmetrics.co/blog/write-financial-section-startup-business-plan](https://upmetrics.co/blog/write-financial-section-startup-business-plan) | "track plan vs. actual performance" |
| [https://upmetrics.co/features/financial-forecasting](https://upmetrics.co/features/financial-forecasting) | "run a plan vs. actual analysis" |
| Any "how to write a business plan" pillar | "monitor plan vs. actual variance" |

(The exact source URL list should be verified with the SEO team — these are derived from the related-content links already on the target page.)

### 7D. External citations to ADD

Currently zero authoritative external citations. The Update Brief Section 14E recommends adding 3-5 citations from:
- **U.S. Small Business Administration (SBA)** — for forecasting fundamentals
- **AICPA / Journal of Accountancy** — for variance analysis terminology
- **Investopedia** — for "variance analysis" concept
- **Harvard Business Review** — for budgeting/forecasting cadence research

### 7E. Backlink gap

| Page | Live refdomains (Ahrefs) |
|---|---|
| Upmetrics (target) | **0** (3 all-time backlinks, 1 historical refdomain) |
| Indeed pos 2 | (Ahrefs returned 0 for the URL specifically — but Indeed.com domain is DR 92) |
| LivePlan pos 3 | not reported at URL level |
| Productive pos 5 | **4** refdomains |
| CashFlowFrog pos 6 | 0 |
| TargetBoard pos 9 | 0 |

**Read:** Even Productive (pos 5) only has 4 refdomains at the URL level — this isn't a heavily-contested backlink fight. Upmetrics needs **2-3 referring domains** to plausibly break the top 5.

**Quick-win backlink targets:**
1. **HARO finance queries** — pitch the Upmetrics CEO for "plan vs. actual" / variance / forecasting questions
2. **SMB finance newsletters** — guest contribution on Substack newsletters (e.g., Founder's Journey, CFO Secrets)
3. **Resource-page outreach** — find SBA-affiliate small-business resource pages that link to forecasting guides
4. **Existing backlink reclamation** — the 1 historical refdomain may be reclaimable; check Ahrefs' lost/broken backlinks

---

## 8. E-E-A-T & CITATIONS

### 8A. Signal comparison (gaps only)

| Signal | Upmetrics | Indeed | LivePlan | Productive | Verdict |
|---|---|---|---|---|---|
| Visible author bio block (photo + role + 2-line bio) | ❌ Schema only — no rendered block | ✅ (Indeed Career Guide team) | ❌ | ❌ | 🔴 Add bio block |
| Author has linked profile / external proof | ✅ Schema includes LinkedIn/X/YouTube | ✅ | — | — | ✅ |
| "Last updated" date visible | ✅ "Updated September 13, 2024" — but stale | — | — | ✅ | 🟡 Refresh |
| Authoritative external citations in body | ❌ 0 | low | 3 | 0 | 🔴 Add 3-5 |
| Customer testimonial / case study | ✅ Matt Little / Festoon House | — | — | — | ✅ unique strength |
| Schema (FAQPage, Article, Person) | ✅ Complete | partial | partial | partial | ✅ unique strength |
| First-hand product walkthrough | ✅ Upmetrics walkthrough | — | — | — | ✅ unique strength |

### 8B. Citation audit

The article makes several unsourced factual or quasi-factual claims that should either be cited or rephrased. Examples (full list with exact quotes lives in the Update Brief Section 14E):

| Claim | Where | What it needs |
|---|---|---|
| Statements about variance being "the difference between plan and actual" | Body + FAQ | Cite Investopedia or AICPA glossary |
| Statements about cadence (monthly / quarterly / annual) | FAQ #2 | Cite SBA or HBR forecasting research |
| Mentions of integration with Xero/QuickBooks | "Integration with Xero or QuickBooks" section | Link to public Upmetrics help-center docs (NOT the internal Google Doc currently linked) |

### 8C. E-E-A-T quick wins

1. **Render the author bio block.** Schema says Vinay Kevadia is "Founder & CEO of Upmetrics" — but no on-page block displays this. Add a 2-line bio under the article with photo, role, and a link to his author page (`/author/vinay-kevadia` is already in the schema).
2. **Refresh the "Updated" date** when the content rewrite ships — but only if the rewrite is real, not cosmetic.
3. **Add 3-5 external citations** to authoritative finance sources (SBA, AICPA, Investopedia, HBR).

---

## 9. APPENDIX

### Ahrefs API consumption

| Call | Endpoint | Units |
|---|---|---|
| 0 | subscription-info-limits-and-usage | 0 |
| 1 | site-explorer-organic-keywords (1st attempt — bad `where` syntax) | 0 (errored) |
| 1b | site-explorer-organic-keywords (retry — 0 rows for vol≥100 filter) | 50 |
| 2 | serp-overview (16 rows × 11 units) | 176 |
| 3 | keywords-explorer-overview | 50 |
| 4 | site-explorer-backlinks-stats | 50 |
| **Total** | | **326** |
| Workspace remaining | (as of audit start) | 385,932 / 400,000 |
| Reset | 2026-05-11 | |

### Data sources

- Python scraper (`scrape_page.py`) for target page + 4 of 5 competitors
- WebFetch fallback for Indeed (403 blocked) and TargetBoard (encoding error in scraper)
- Google Search Console — 6-month range 2025-10-30 → 2026-04-27, US filter
- Ahrefs MCP — US country, 4 calls
- WebSearch — SERP feature confirmation for primary keyword

### Notes / caveats

- **GSC trend data (Call 2 — query+date for top 10 queries)** returned a payload exceeding the conversation token limit; a detailed month-over-month trend analysis was not feasible. This is non-blocking because total clicks across all 105 queries = 0, so the trend story is "stable zero".
- **Ahrefs organic keywords** returned 0 rows with volume ≥ 100 for the target URL. The page is too low-ranking for Ahrefs to surface high-volume rankings; GSC data filled the gap.
- **No Reddit/Quora UGC threads** were scraped from the SERP — the one Reddit thread (r/FPandA) is generic FPandA discussion and offers limited signal beyond what's already in the SERP feature analysis.
- **Backlink stats** showed 0 live backlinks. Sanity-checked — the result is plausible for a Sept 2024 blog post that has never been promoted and has 0 GSC clicks.

---

*End of SEO Audit Report. The companion Content Update Brief (.docx) contains all writer-facing content actions.*
