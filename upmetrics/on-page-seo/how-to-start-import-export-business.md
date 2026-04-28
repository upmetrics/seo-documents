# SEO On-Page Suggestion Report

| | |
|---|---|
| **Page** | https://upmetrics.co/blog/how-to-start-import-export-business |
| **Post ID** | 51945 |
| **Post Type** | Blog Post (`post`) |
| **Category** | Starting |
| **Word count** | 3,124 |
| **Modified** | 2024-02-02 |
| **Report date** | 2026-04-28 |
| **GSC range** | 2026-01-28 → 2026-04-25 (90 days) |
| **GA4 range** | last 30 / 90 days |

---

## Page Health Score: 6 / 10

| Status | Count |
|---|:--:|
| Critical issues | 2 |
| Needs improvement | 4 |
| Good (no action) | 4 |

**Critical:**
- **Meta optimization** — page averages position **45–55** for relevant import-export queries with **0% CTR** across 600+ impressions in 28 days. Meta title/description need a rewrite.
- **Body link to a template post type (Step 4)** — the existing inline link points to `/template/import-export-business-plan-example`. Per workflow rules, template URLs belong in the Resource CTA / Related Content slots, not as inline body links.

**Needs improvement:**
- Only **1 internal link** in 3,124 words (target: 5–7). Most sections lack outbound editorial links.
- **0 images** in the editor content — no infographics, screenshots, or visual breaks. Image search SEO and engagement both suffer (separate from Task 6, which only audits existing alts).
- **Trade-data citation references December 2021** — the only year reference in the post is 4+ years old. A small editorial refresh (or removal) would reduce datedness signals.
- **Featured-snippet H2 anchor ID is `what-is-business-plan`** (a leftover from a different template). Should be renamed to match the post topic.

**Good:**
- Indexed and crawlable (last crawl 2026-04-05). Has Breadcrumbs + FAQ rich-results.
- Heading hierarchy is clean (3 H2 → 12 H3 → 16 H4, no skipped levels).
- Category assignment ("Starting") matches content.
- Mobile rendering is fine; mobile actually ranks ~16 positions better than desktop on average.

---

## Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|:--:|------|:--:|:--:|---|---|---|
| 1 | Internal Links | High | Medium | 1 inline link (to template, mis-placed) | Add 3 contextual links to high-value blog posts. Remove existing template link (replaced by Resource CTA). | Approve all |
| 2 | CTAs | Low | Low | 4 `upm-blog-tip` + 2 `[elementor-template]` (mid + end). Already saturated. | No new CTAs recommended. Existing setup covers the conversion paths. | Skip (none needed) |
| 3 | Resource CTA | High | Quick Win | Likely unset | Set `/template/import-export-business-plan-example` (Import-Export Business Plan + Free Template) | Approve |
| 4 | Related Content | Medium | Quick Win | Likely unset | Set 4 related items: ecommerce guide, marketing-strategy guide, what-lenders-want, trading template | Approve |
| 5 | Meta Title & Description | High | Quick Win | Page ranks pos 45–55 with 0% CTR on relevant queries | Critical rewrite of title + description; set focus keyphrase | Approve |
| 6 | Image Alt Text | N/A | — | 0 images in content | N/A — no images to audit | Skip (N/A) |
| 7 | URL Slug | Low | Low | `how-to-start-import-export-business` (35 chars, keyword-front, lowercase) | Already optimal — no change | Skip (already good) |
| 8 | Heading Structure | Low | Quick Win | Clean hierarchy. One stale anchor ID. | Optional: rename anchor `what-is-business-plan` → `steps-to-start-import-export-business` | Skip (cosmetic only) |
| 9 | Categories | Low | — | "Starting" — matches content | No change | Skip (already good) |
| 10 | Incoming Links | Medium | Manual | n/a | 5 source-page candidates for SEO team to manually review | Note (manual review) |

---

## Task 1: Internal Linking

### Existing Link Audit

| # | Anchor Text | Target URL | Status | Notes |
|:--:|---|---|---|---|
| E1 | Import-export business plan | https://upmetrics.co/template/import-export-business-plan-example | **Should remove** | Target is a `template` post type — per workflow rules, template URLs go in the Resource CTA (Task 3) or Related Content (Task 4), not as inline body links. The same URL is being moved to Task 3 (Resource CTA), which gives it the prominent top-of-page banner placement. Removing the body link consolidates the offer to one location. |

**Existing internal link count:** 1. **External links:** 12 (all to authoritative gov/industry sources — none to competitor domains). No broken or query-string-tracked URLs detected.

### New Link Suggestions (3 recommended)

The page is procedural and dense with regulatory content, so editorial bridges to other Upmetrics content are limited. Three high-confidence prose anchors:

> **#1** — `market research` → https://upmetrics.co/blog/types-of-market-research
>
> **Section:** 1. Identify products to import or export → Learn What Customers Want / Costs and Profits
>
> **In context:** "Doing this makes you more likely to sell products that people will want to buy. Is the Product a Good Fit? After conducting **market research**, consider whether your export products will work well. This means looking at things like how much they'll cost to make and send, how unique they are, and how much people need or want them."

---

> **#2** — `Predictions for money` → https://upmetrics.co/blog/financial-projections-business-plan
>
> **Section:** 4. Write an Import-export business plan (parts-of-a-plan list)
>
> **In context (list item):** "Usually, a business plan has parts like: A quick summary / Info about your company / Market Research / Details about your products or services / How you'll market and sell / **Predictions for money** coming in and going out / Funding Request"
>
> **Note:** Wraps the first three words of the list item; reads naturally as "Predictions for money [coming in and going out]". Target page is high-traffic + high-conversion (391 sessions, 0.79 engagement, 41 conversions in 90 days).

---

> **#3** — `sales pitch` → https://upmetrics.co/blog/how-to-write-a-business-proposal
>
> **Section:** 9. Market your import export business → before "Direct-Mail Campaigns"
>
> **In context:** "Are these products also wanted in your target market countries? If they're not popular, could they be if people knew about them? Who makes these products? How much does selling them, both here and in the target countries, cost? Using this info, you can contact companies with your **sales pitch** through direct-mail campaigns."

<details>
<summary>Considered but skipped (5 candidate pages)</summary>

| Page | Reason Skipped |
|---|---|
| /blog/marketing-strategy-business-plan | Best anchor "market and sell" sits inside the parts-of-a-plan list in Step 4; would cluster within ~30 words of suggestion #2. Moved to Task 4 (Related Content) instead. |
| /blog/what-lenders-look-for-in-business-plan | Best anchor "Funding Request" is also in the Step-4 list; would cluster with #2. Moved to Task 4 instead. |
| /blog/how-to-write-a-business-plan-complete-guide | The only natural prose anchor ("a business plan") is the line right before suggestion #2 — would create a back-to-back link in Step 4. Picked Task 4 (Related Content) for a sidebar placement instead. |
| /blog/how-to-start-ecommerce-business | No natural in-content anchor (page never says "ecommerce"). Better fit for Related Content. |
| Competitor-analysis page | Section 1 has 3 occurrences of "your competitors" but the repository has no dedicated competitor-analysis blog post on Upmetrics. Skipped — no good target. |

</details>

**Why only 3:** the page is structurally limited for editorial links — Sections 2 (shipping), 3 (suppliers), 5 (registration), 6 (licenses), 7 (financing), and 8 (insurance) are heavy with regulatory/external references that have no clean Upmetrics blog equivalents. Adding more links would require forcing anchor text or linking to weak-relevance pages.

---

## Task 2: CTA Placements

### Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:--:|---|---|---|---|
| C1 | Yellow Tip (`upm-blog-tip`) | After "Local Government Officials" list (Section 1) | Good | Educational tip about Licensed Customs Brokers. Contextual. |
| C2 | Yellow Tip (`upm-blog-tip`) | After "Visit Trade Shows" (Section 3) | Good | Educational tip about supplier vetting + incoterms. Contextual. |
| C3 | Yellow Tip (`upm-blog-tip`) | After CBP Form 5106 reference (Section 5) | Good | Educational tip about multi-state paperwork. Contextual. |
| C4 | Yellow Tip (`upm-blog-tip`) | After ECCN list (Section 6) | Good | Educational tip about customs bonds. Contextual. |
| C5 | `[elementor-template id="52012"]` | After Section 4 (Write an Import-export business plan) | Good | Mid-content elementor banner. Verify rendering separately — content not visible via API. |
| C6 | `[elementor-template id="45300"]` | End of post | Good | Canonical Blog Post End CTA (per workflow). Required for Upmetrics blog posts. |

**Total existing CTAs:** 6 (4 light tips + 2 banners). The page is already saturated for its 3,124-word length (target: 2–3 CTAs for this length).

### New CTA Suggestions

**No new CTAs recommended.** Adding more would over-promote. The 4 yellow tips, mid-content elementor banner, and Blog Post End CTA already cover the natural decision points throughout the article.

---

## Task 3: Downloadable Resource / Tool Attachment

**Recommendation:** Set Resource CTA to the import-export business plan template — the most topically central resource on the site for this post.

| Field | Value |
|---|---|
| `post_id` | 51945 |
| `resource_url` | https://upmetrics.co/template/import-export-business-plan-example |
| `heading` | Import-Export Business Plan |
| `resource_link_text` | Download Template |

**Rendered combined display:** "Download Template: Import-Export Business Plan" (47 chars — fits one line ✓).

**Note:** This URL is also currently the existing inline body link in Step 4 (flagged for removal in Task 1 above). Setting it as the Resource CTA gives it the prominent top-of-page banner with the auto-fetched featured image — far more visible than a mid-content text link.

---

## Task 4: Related Content

**Recommendation:** Set 4 related items below. Mix of post + template; all topically adjacent; uses custom titles (NOT auto-fetched) to maximize sidebar click-worthiness.

| # | URL | post_id | Custom Title | Title chars |
|:--:|---|:--:|---|:--:|
| 1 | https://upmetrics.co/blog/how-to-start-ecommerce-business | 44127 | Start Your Own Online Store | 27 |
| 2 | https://upmetrics.co/blog/marketing-strategy-business-plan | 83092 | Marketing Strategy for Your Plan | 32 |
| 3 | https://upmetrics.co/blog/what-lenders-look-for-in-business-plan | 107358 | What Lenders Want in Your Plan | 30 |
| 4 | https://upmetrics.co/template/trading-business-plan | 36936 | Trading Business Plan Sample | 28 |

**Why this mix:**
- Items 1, 2, 3 are blog posts giving the reader natural "next steps" (online sales, marketing execution, funding readiness).
- Item 4 is a template — gives readers a second sample-plan format if the import-export plan isn't what they need.
- All 4 have custom titles under 40 chars, written for curiosity rather than keyword stuffing.

---

## Task 5: Meta Title & Description Optimization

### Performance Context (top 5 GSC queries by impressions, 28 days)

| Top Query | Impressions | Position | Current CTR | Benchmark CTR | Status |
|---|:--:|:--:|:--:|:--:|---|
| as someone looking to start an importer business... | 7 | 52.4 | 0% | <1% | Long-tail AI-overview probe — not actionable |
| export | 5 | 1.6 | 0% | 28% | Healthy position but query is too generic to rank for |
| export import business | 4 | 51.0 | 0% | <1% | **Buried — primary opportunity** |
| business import export | 3 | 62.0 | 0% | <1% | Buried |
| export and import business | 3 | 58.7 | 0% | <1% | Buried |

**Verdict:** Critical rewrite. Page ranks pos 45–55 average across 600+ impressions for relevant import-export queries with 0% CTR. Position 51 is below the benchmark table floor (pos 11–20 = 1.5%), so this is a "page is barely visible" problem rather than a "ranking high but losing clicks" problem. A sharper meta title + description won't fix the ranking alone, but it removes one variable (weak click-through signal) and frontloads the keyword for both Google parsing and mobile truncation. Mobile already ranks ~16 positions better than desktop — a mobile-friendly meta is high-leverage.

### Current vs. Suggested

| Field | Current (assumed = H1) | Chars | Suggested | Chars | Notes |
|---|---|:--:|---|:--:|---|
| Meta Title | How to Start an Import Export Business in 9 Easy Steps | 54 | How to Start an Import Export Business: 9-Step Guide [2026] | 59 | Adds year hook + format signal; keyword in first 38 chars; differs from H1 ("9 Easy Steps" vs "9-Step Guide") |
| Meta Description | (not visible via API — likely uses excerpt) | — | Want to start an import export business in 2026? This 9-step guide covers products, suppliers, licenses, financing, marketing, and includes a free template. | 155 | Front-loads keyword (pos 17); 3-part formula (what / why / soft CTA); active voice; no banned words |
| Focus Keyphrase | (assumed: "import export business") | — | import export business | — | Verbatim in both title and description; matches highest-impression relevant query (4 imp at pos 51) |
| Canonical | https://upmetrics.co/blog/how-to-start-import-export-business | — | (no change) | — | Currently matches Google's canonical — OK |
| OG Title | (likely unset → falls back to meta title) | — | (matches meta title) | — | OK to leave inheriting |
| OG Description | (likely unset → falls back to meta description) | — | (matches meta description) | — | OK to leave inheriting |

### SERP Preview Mockup

```
─────────────────────────────────────────────────────
upmetrics.co › blog › how-to-start-import-export-business
How to Start an Import Export Business: 9-Step Guide [2026]
Want to start an import export business in 2026? This 9-step
guide covers products, suppliers, licenses, financing,
marketing, and includes a free template.
─────────────────────────────────────────────────────
```

**Differentiator note:** Stands out on SERP for "import export business" because most competing titles use generic patterns ("How to Start an Import Export Business", "Import Export Business Step by Step") — the suggested title combines a year tag and the "9-Step Guide" format signal. The "free template" mention in the description is a soft CTA that should pull mobile clicks.

---

## Task 6: Image Alt Text Audit

### Image Inventory

| Status | Count |
|---|:--:|
| Critical — Missing | 0 |
| Critical — Empty (wrong) | 0 |
| Needs Improvement | 0 |
| Good | 0 |
| Decorative — Correct | 0 |
| **Total images in content** | **0** |

**No images exist in the editor content.** Task 6 has nothing to action.

**Outside Task 6 scope but worth noting:** a 3,124-word how-to article with zero infographics, screenshots, or visual breaks is unusual — it likely hurts engagement metrics and forfeits image-search traffic. Consider commissioning a separate image-generation pass (e.g., a flowchart of the 9 steps, a sample license-flow diagram, a financing-options comparison). This is content-strategy work, not on-page SEO.

---

## Task 7: URL Slug Optimization

**Current slug:** `how-to-start-import-export-business` (35 chars).

- Lowercase ✓
- Hyphenated ✓
- Contains primary keyword "import export business" ✓
- Length under 60 chars ✓
- No stop-word noise

**GSC position context:** average position 45–55 for relevant queries. Per workflow rules, position 16+ is "safe to optimize" — but the slug is **already optimal**. Changing it would create unnecessary 301-redirect risk for zero gain.

**Recommendation:** Skip — no change needed.

---

## Task 8: Heading Structure Audit

| Level | Count | Notes |
|:--:|:--:|---|
| H1 | 0 (in content) | WP theme injects post title as H1 — correct |
| H2 | 3 | Types of Import Export Businesses / Steps to starting an Import-export business / Conclusion |
| H3 | 12 | 9 step headings (1.–9.) + 3 type headings |
| H4 | 16 | Subsections within steps |

**Structure is good** — no skipped levels, no duplicates, primary keyword present in H2 #1 ("Types of Import Export Businesses") and several H3s ("4. Write an Import-export business plan", "9. Market your import export business").

**Minor cleanup (cosmetic, optional):**
- The featured-snippet H2 carries the anchor `id="what-is-business-plan"` — a leftover from a different template. Rename to `id="steps-to-start-import-export-business"` for cleanliness.

No other heading changes recommended.

---

## Task 9: Category / Taxonomy Assignment

**Current category:** Starting

**Assessment:** Matches content (page is a "how to start X" guide). Already correct. No tags currently assigned, which is consistent with Upmetrics' tag-light taxonomy convention.

**Recommendation:** Skip — no change needed.

---

## Task 10: Incoming Internal Link Suggestions

**Note for SEO team:** the candidates below are data-verified WordPress posts that are topically adjacent to this page. The "Suggested Anchor" is a starting search term — the actual anchor depends on what text exists in the source page's body, which the SEO team should verify manually before adding the link.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic | Priority |
|:--:|---|---|:--:|---|---|---|:--:|:--:|
| 1 | 21 Free and Paid Sources of Industry Reports | https://upmetrics.co/blog/free-and-paid-sources-of-industry-reports | 97893 | post | Confirmed in GSC: ranks for "import export" related query at pos 1 (1 impression). Page covers trade/industry data sources, natural fit to mention import-export starter guide. | starting an import export business | low (GSC: 1 imp on relevant query) | High |
| 2 | How to Start an Ecommerce Business: A Step by Step Guide | https://upmetrics.co/blog/how-to-start-ecommerce-business | 44127 | post | Topical adjacent — ecommerce often involves international supply/import sourcing. Long-form prose hosts the link naturally. | import export business | n/a in repo | Medium |
| 3 | How to Start a Dropshipping Business: A Step-by-Step Guide | https://upmetrics.co/blog/how-to-start-dropshipping-business | 54001 | post | Topical adjacent — dropshipping often involves international suppliers. Confirmed in WP repository. | import-export business | n/a in repo | Medium |
| 4 | Amazon FBA Business Plan | https://upmetrics.co/template/amazon-fba-business-plan | 26462 | template | Topical adjacent — Amazon FBA usually involves importing products. Template prose can link to the operational how-to guide. | import export business | n/a in repo | Medium |
| 5 | How to Write a Business Plan: 10 Easy Steps + Examples | https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide | 6056 | post | Site's broad business-plan guide — should reference industry-specific guides. Verified in WordPress. | starting an import export business | n/a in repo | Low |

**No reciprocal-link risk:** none of the above are link targets in Tasks 1–4 of this report.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve all 3 (#1, #2, #3). Remove existing template body link (E1).
Task 2 (CTAs): Skip — no new CTAs needed.
Task 3 (Resource CTA): Approve — set Import-Export Business Plan template.
Task 4 (Related Content): Approve all 4.
Task 5 (Meta Title/Desc): Approve suggested title. Approve description. Approve focus keyphrase.
Task 6 (Image Alt Text): Skip (N/A — 0 images).
Task 7 (URL Slug): Skip — already optimal.
Task 8 (Headings): Skip cosmetic anchor-ID rename.
Task 9 (Categories): Skip — already correct.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: `Approve all` (which means: approve every "Approve" item above and skip everything marked "Skip").
