# SEO Page Audit — How to Write a Company Overview

**URL:** [https://upmetrics.co/blog/how-to-write-an-effective-business-overview-for-your-business-plan](https://upmetrics.co/blog/how-to-write-an-effective-business-overview-for-your-business-plan)
**Primary keyword:** `how to write company overview`
**Secondary keyword (co-equal):** `company overview example`
**Brand:** Upmetrics
**Audit date:** 2026-05-22
**Manual competitors:** Liveplan, Indeed, Joorney *(Ahrefs SERP competitors skipped per user input)*

---

## 1. Executive Dashboard

### Page Snapshot

| Metric | Value |
|--------|-------|
| URL | [https://upmetrics.co/blog/how-to-write-an-effective-business-overview-for-your-business-plan](https://upmetrics.co/blog/how-to-write-an-effective-business-overview-for-your-business-plan) |
| Primary Keyword | how to write company overview |
| Primary KW — US Search Volume | 40 (low-volume head term — see note below) |
| Primary KW — Current Position (Ahrefs) | 9 |
| Primary KW — Keyword Difficulty | Not returned by Ahrefs (likely KD ≤ 5; backlink-poor SERP) |
| Secondary KW — Volume / KD / Traffic Potential | `company overview example` — vol 200, KD 1, TP 700 |
| Whole-page footprint (GSC, last 6 mo) | **500 queries, 20,606 impressions, 16 clicks (CTR 0.08%)** |
| Title Tag | "How to Write a Company Overview for a Business Plan?" (52 chars) |
| Meta Description | "Wondering what to include in a company overview section and how to write one? This blog post covers all those details and also offers examples for you to write your own company overview." (**186 chars — over limit**) |
| H1 | "How to Write a Company Overview for a Business Plan?" (matches title exactly — should differ) |
| Word Count (article body only) | 2,320 words (from `.blog-content-area`) |
| Headings | 1 H1, 7 H2, 18 H3 |
| Internal Links (in-content / nav-share) | 11 in-content blog links / 16 nav-share / 4 template / 42 other = 73 total |
| External Links (in-content) | **0** (the 4 detected external links are footer social icons — no in-content citations) |
| Content Images (with alt / without alt) | 3 / 0 (all 3 have alt text — good) |
| Schema Markup | Article + WebPage + BreadcrumbList + FAQPage + Organization + Person (verified) — comprehensive |
| Canonical Tag | Self-referencing (clean) |
| Page Type | Blog article |
| Content Freshness | Published date visible; date appears in meta as well. No "last updated" date visible. |
| Author Attribution | "Upmetrics" — generic byline. No author bio, no photo, no person credentials. |
| Downloadable Templates/Freebies | 2 found ("Download Now: Free Company Profile Templates" + AI Business Plan CTA). |

### Top 3 Problems

1. **Catastrophic CTR collapse.** Page generates 20,606 impressions across 500 queries in 6 months but only **16 clicks (0.08% CTR)** — well below the ~2-5% expected at positions 3-9. The title is a question, the meta description is 186 chars (gets truncated), and neither mentions the "example" hook that the secondary keyword (vol 200, position 3.2, 782 impressions, 0 clicks) clearly wants. The clicks are sitting there; the SERP listing isn't earning them.
2. **Backlink and example depth keep the page out of the top 5.** Only 2 live referring domains vs. SERP average of ~14 (Indeed 13, NerdWallet 13, Visme 10, bplans 35). Combined with the existing examples (ice cream company, solar company — both short snippets), the page can't match Indeed's sustained Deep Harbor narrative or Liveplan's 290+ word Botanical Bounty / 480+ word Bright House examples that anchor the top 3 results.
3. **Content depth gaps + zero external citations.** The page is missing every other competitor's coverage of legal structure types (LLC/C-corp/S-corp/sole prop/partnership), ownership breakdown, locations/facilities, dedicated vision + core values sections, board of advisors, market opportunity callout, and pre-launch startup guidance. It also has **0 external citations** to authoritative sources (SBA.gov, Census, expert quotes) — a clear E-E-A-T gap that the top-ranking pages exploit.

### Traffic Opportunity

> Page already commands 20,606 impressions / 6 months at avg position 5-7 for the keyword cluster. Lifting CTR from 0.08% to a position-appropriate ~3-5% would move clicks from ~3/month to **170-350/month** with no ranking change. Adding the missing content + 8-10 quality backlinks could push primary clusters ("company overview" at 6,171 impressions, "business overview" at 2,233) from pos 5-6 into top 3, where CTR doubles again — potential **500-800 clicks/month**.

---

## 2. Master Action Table

All SEO actions, sorted by priority. **Content actions (fixes, additions, rewrites) live in the [Content Update Brief .docx](#)** — they are NOT duplicated here.

| # | Priority | Category | Action | Assignee | Details | Section Ref |
|---|----------|----------|--------|----------|---------|-------------|
| 1 | **P1** | Meta | Rewrite title tag (current 52 chars → new 53 chars) to mirror Indeed's top-ranking formula and capture the secondary "example" keyword | Dev | See Title & Meta Copy block below | §5 |
| 2 | **P1** | Meta | Rewrite meta description (current 186 chars — over Google's truncation limit) | Dev | See Title & Meta Copy block below | §5 |
| 3 | **P1** | Technical | Differentiate H1 from title tag — currently identical (same text in both) | Dev | Keep H1 as "How to Write a Company Overview for a Business Plan" (drop the question mark); set title tag per below | §5 |
| 4 | **P1** | Technical | Add `last_updated` date display on page + update schema `dateModified` to today | Dev | Article schema has the data but page shows no "last updated" label — visible recency boosts CTR and is what users see on competitor pages (LivePlan: "May 13, 2026"; Indeed: "Updated December 15, 2025") | §5 |
| 5 | **P1** | E-E-A-T | Replace generic "Upmetrics" byline with a named author + bio + photo | Dev + Content | Author block exists but author_has_bio=false, author_has_photo=false. Use a real product/business-plan expert at Upmetrics (e.g., Vinay or a founder), add 2-3 sentence bio mentioning relevant credentials, link author archive. | §8 |
| 6 | **P1** | Video Asset | Embed Upmetrics' own YouTube video "Write a Company Overview in Minutes (Framework + Example)" (1 month old, 5:10) into the article body | Dev + Content | Upmetrics already has this video in the Google video pack for the primary keyword. Embedding it captures video-intent clicks, reinforces E-E-A-T, and increases dwell time. Place near the "What to include" H2. | §8 |
| 7 | **P2** | Internal Link (incoming) | Add link FROM `/blog/business-plan-outline` TO target page | SEO Team | Cannibalization check: `business-plan-outline` ranks at position 1 for "company overview" but with only 119 impressions — it's a chapter heading on that page. Add a "For a deep dive, see our [company overview guide]" link after the company overview section in business-plan-outline. | §7 |
| 8 | **P2** | Internal Link (incoming) | Add link FROM `/blog/business-plan-components` TO target page | SEO Team | `business-plan-components` ranks pos 1 for "company overview" (21 impr) — minor cannibalization. Add an internal link from its company overview subsection pointing to the target page as the definitive guide. | §7 |
| 9 | **P2** | Internal Link (incoming) | Add link FROM `/blog/executive-summary-example-for-a-business-plan` TO target page | SEO Team | Executive summary and company overview are sister sections of a business plan — Google already ranks this page for "company overview" (8 impr at pos 1, likely an anchor link). Cross-link to consolidate authority. | §7 |
| 10 | **P2** | Internal Link (in-content) | Audit existing 11 in-content blog links — verify all are still 200 OK and remove any that link to deprecated content | SEO Team | Particularly check `/blog/legal-structure-of-business`, `/blog/products-and-services-section`, `/blog/complete-guide-to-write-mission-statement-for-your-business` | §7 |
| 11 | **P2** | E-E-A-T Schema | Add `dateModified` to Article schema (alongside existing `datePublished`) | Dev | Article schema is present but page lacks visible last-updated date; updating schema + adding visible date together signals freshness | §5 |
| 12 | **P2** | Performance | Confirm largest content image (`what-to-include-in-an-effective-company-overview.webp`, served from 2020 build) has explicit width/height attributes + is lazy-loaded | Dev | webp format is good; verify CLS-safe rendering | §5 |
| 13 | **P3** | Backlinks | Outreach campaign — 8-10 referring domains needed to close gap to SERP average | Link Builder | Target: SBA Resource Partners, regional SBDCs, university entrepreneurship programs, .edu syllabi for small business management courses. Pitch the downloadable templates + 2 worked examples as a free teaching resource. | §7E |
| 14 | **P3** | Backlinks (digital PR) | Submit the article + Upmetrics YouTube video as a citation candidate to Liveplan's competitor link roundups and bplans.com/business-planning resources | Link Builder | These domains already link out to peer how-to guides; pitch is a peer recommendation, not a competitor steal. | §7E |
| 15 | **P3** | Backlinks (broken-link reclamation) | Identify decayed referring domains (all-time refdomains = 20, live = 2 — 18 have decayed) and contact site owners to restore the link | Link Builder | 18 lost backlinks is a fast win; use Ahrefs "broken backlinks" report (out-of-budget for this audit — schedule for next sprint) | §7E |

### Title & Meta Copy (ready to copy-paste)

```
Title Tag (OLD): How to Write a Company Overview for a Business Plan? (52 chars)
Title Tag (NEW): How to Write a Company Overview (Examples + Template) (53 chars)

Meta Description (OLD): Wondering what to include in a company overview section and how to write one? This blog post covers all those details and also offers examples for you to write your own company overview. (186 chars — over limit, truncates)
Meta Description (NEW): Learn how to write a company overview for your business plan — what to include (6 sections), expert writing tips, and 2 full examples to copy. (140 chars)
```

**Why this title/meta combo:**
- New title mirrors Indeed's top-ranking formula ("How To Write a Company Overview (With Example and Tips)") but tightens it and adds "Template" — capturing both the `company overview example` keyword (vol 200, page is at pos 3 with 0 clicks) AND the "template" / "PDF" intent visible in Google's "People also search for" panel.
- Drops the question mark — questions in titles slightly underperform statements in commercial-intent SERPs and the question is implied by "How to."
- New meta is 140 chars (well within Google's ~155 char display), opens with the action verb "Learn," names the article's 3 deliverables (6 sections, tips, 2 examples), and ends with a benefit ("to copy").

**Content actions are NOT included here.** Title/meta fixes, technical fixes, link changes, and backlink work live in this table. Content fixes (filler removal, vague sentence rewrites, citation additions), content additions (new sections from Section 6), and content rewrites (any section flagged 🟡 EDIT or 🔴 REWRITE) live in the **Content Update Brief .docx** (Section 14 — annotated outline). The writer should never need to read this audit report.

---

## 3. Keyword & Ranking Analysis (US Focused)

**Data window:** GSC US data 2025-11-20 → 2026-05-19 (6 months). Ahrefs US data 2026-05-22.
**Note on GSC trend data:** GSC Call 2 returned 2,000 rows (at row-limit cap). Trend data is reliable for queries with ≥40 days of daily rows; some lower-impression queries have partial trend coverage and are marked accordingly.

### Top 10 Keywords (by impressions)

| # | Keyword | Impressions | Clicks | CTR | Avg Position | Trend (6mo) |
|---|---------|-------------|--------|-----|--------------|-------------|
| 1 | company overview | 6,171 | 4 | 0.06% | 5.2 | ↑ +221% (rising — 245 → 787) |
| 2 | business overview | 2,233 | 1 | 0.04% | 6.4 | ↑ +99% (rising — 140 → 279) |
| 3 | company overview example | 782 | 0 | 0.00% | **3.2** | (limited trend data — under 2k row cap) |
| 4 | what is a business overview | 608 | 0 | 0.00% | 8.5 | (limited trend data) |
| 5 | plan overview | 561 | 0 | 0.00% | 32.8 | (limited trend data) |
| 6 | how to write company overview ⭐ | 462 | 0 | 0.00% | 6.4 | (limited trend data) |
| 7 | business overview example | 366 | 2 | 0.55% | **2.5** | ↑ +5400% (rising — 1 → 55) |
| 8 | how to write a company description | 302 | 0 | 0.00% | 23.7 | (limited trend data) |
| 9 | overview company | 281 | 0 | 0.00% | 13.6 | (limited trend data) |
| 10 | how to write a business description | 271 | 0 | 0.00% | 24.6 | (limited trend data) |

⭐ = primary keyword

**Key observation:** All three rising-trend queries (company overview, business overview, business overview example) are gaining impressions month-over-month — search demand is increasing. The page is on page 1 for 7 of 10 top queries but converts essentially zero clicks. This is a **SERP listing problem, not a ranking problem.**

**Position vs CTR — what the data says:**
- Position 2.5-3.2 (queries #3, #7): expected CTR ≈ 10-15%. Actual: 0-0.55%. Gap: **~20-30× below benchmark.**
- Position 5-6 (queries #1, #2, #6): expected CTR ≈ 4-6%. Actual: 0.04-0.06%. Gap: **~80-100× below benchmark.**

**Diagnosis:** Title tag is a question (slight underperform), meta description is 186 chars (truncates), and neither title nor meta mentions "example" — the word that drives clicks for query #3 (782 impr at pos 3.2). The title/meta rewrite in Section 2 directly targets this gap.

### Ahrefs Organic Keywords (target page, US, vol ≥10)

| Keyword | Volume | Best Position | Note |
|---------|--------|---------------|------|
| company description | 1,400 | 29 | **Striking-distance miss** — high-volume term, page 3. Adjacent intent to "company overview." Adding a brief disambiguation section ("Company overview vs. company description") could lift this. |
| company overview | 900 | 8 | Matches GSC head term — Ahrefs sees it at pos 8 (slightly worse than GSC's 5.2 avg, likely due to date snapshot). |
| general overview | 150 | 2 | Already top 2 — low effort to defend, low priority. |
| corporate overview | 60 | 1 | Already #1 — defend. |
| company overview sample | 20 | 12 | Striking distance, but low volume. |
| company overviews | 20 | 1 | Already #1. |
| how to write a business overview | 20 | 3 | Already top 3. |
| example of a company overview | 10 | 3 | Already top 3. |
| company outline | 10 | 1 | Already #1. |
| business overview sample | 10 | 3 | Already top 3. |

### Striking Distance Opportunities (positions 4-20 with ≥200 impressions)

| Keyword | Impressions | Clicks | Position | Opportunity |
|---------|-------------|--------|----------|-------------|
| company overview | 6,171 | 4 | 5.2 | Push to pos 3 via depth + backlinks → ~600 clicks/mo at 10% CTR (vs current ~0.7) |
| business overview | 2,233 | 1 | 6.4 | Push to pos 4 via same fixes → ~220 clicks/mo at 10% CTR |
| company overview example | 782 | 0 | 3.2 | **Title fix alone unlocks this — already top 3, just needs "Example" in SERP listing copy.** Potential ~80 clicks/mo at 10% CTR |
| what is a business overview | 608 | 0 | 8.5 | Page 1 but low CTR — definition optimization (40-50 word intro) could win snippet here |
| how to write company overview | 462 | 0 | 6.4 | Primary kw — title fix + tightening intro should lift to pos 3-5 |
| company description (Ahrefs) | (no GSC) | — | 29 (Ahrefs) | Page 3 for a 1,400-volume head term — adding a "Company overview vs. company description" section could break into top 10 |

### Cannibalization Check (US data)

Checked the primary keyword + top 5 highest-impression queries. Findings:

| Query | Target Page Position | Competing Page URL | Competing Page Position | Impressions on Competing Page | Recommendation |
|-------|---------------------|--------------------|-------------------------|-------------------------------|----------------|
| company overview | 5.2 | [https://upmetrics.co/blog/business-plan-outline](https://upmetrics.co/blog/business-plan-outline) | 1 | 119 | **Mild cannibalization.** Target dominates (6,171 vs 119 impr). The pos 1 entries are likely anchor-link snippets, not full ranking pages. Add internal link from `business-plan-outline` → target (already in Action Table #7). |
| company overview | 5.2 | [https://upmetrics.co/blog/business-plan-components](https://upmetrics.co/blog/business-plan-components) | 1 | 21 | Negligible — 21 impressions vs target's 6,171. Add internal link (Action #8). |
| company overview | 5.2 | [https://upmetrics.co/blog/executive-summary-example-for-a-business-plan](https://upmetrics.co/blog/executive-summary-example-for-a-business-plan) | 1 | 8 | Negligible. Add internal link (Action #9). |
| company overview | 5.2 | [https://upmetrics.co/template/graphic-design-business-plan-example](https://upmetrics.co/template/graphic-design-business-plan-example) | 10 | 1 | Truly negligible. No action needed. |
| business overview | 6.4 | [https://upmetrics.co/blog/what-is-business-plan](https://upmetrics.co/blog/what-is-business-plan) | 53.3 | 3 | Not ranking — no cannibalization. |
| business overview | 6.4 | [https://upmetrics.co/sample-business-plans](https://upmetrics.co/sample-business-plans) | 1 | 4 | Trivial. |
| company overview example | 3.2 | [https://upmetrics.co/sample-business-plans](https://upmetrics.co/sample-business-plans) | 77 | 1 | Not ranking. |

**Verdict:** No real cannibalization. The "position 1" entries for competing URLs are anchor-link snippets that Google awards when a page has strong heading structure — not separate ranking pages. The target page is the clear winner for this keyword family on the domain.

**Important nuance:** GSC also splits target-page impressions across anchor URL variants (e.g., the target URL + `#tips-to-write-an-effective-company-overview`, + `#what-to-include-...`, etc.). For "how to write company overview" alone, 3 anchor variants contributed 462 + 453 + 453 = **1,368 combined impressions on the same page** — but GSC reports them as separate rows. The target page's true total impression count is likely closer to ~22,000-23,000, not 20,606. This is a positive signal (Google awards jump-to-section snippets), not a problem to fix.

---

## 4. SERP & Intent Analysis

### What Google is rewarding

- **Dominant intent:** Informational how-to guide with a strong example-driven component. Every top-10 organic result is a long-form guide (1,200-2,300 words) on a major content site (Indeed DR 92, NerdWallet DR 90, The Balance DR 90, SBA.gov DR 93, Visme DR 87, bplans DR 78, LivePlan DR 72, Upmetrics DR 73).
- **Content types ranking (live SERP, May 2026):** Position 1 = Indeed (with featured snippet). Positions 3-10 = a mix of how-to guides; SBA.gov has appeared as a new top-5 entrant via the .gov authority lane. LivePlan refreshed their article on **2026-05-13** and re-entered position 10. Two Reddit discussion threads appear in the SERP's discussions block.
- **What this means:** Google strongly favors educational guides that include worked examples. The page that wins is the one that combines (a) clear structure with what-to-include + how-to-write phases, (b) at least one fully written example narrative the reader can mimic, and (c) recent freshness signals.

### Intent match/mismatch

- **Current page type:** Blog article — guide format ✅ matches dominant intent
- **Match status:** ✅ **Format match — content gap is the problem, not intent**
- **Where the target falls short:** The page covers the right intent (informational + examples) but the examples are shallow snippets. Indeed wins position 1 with the sustained "Deep Harbor Technology" narrative; Liveplan wins position 10 (despite recent re-entry) with 290+ and 480+ word worked examples ("Botanical Bounty" agriculture farm, "Bright House" nursing home). The target's "ice cream cones" and "solar" examples read as illustrative paragraphs rather than full models a reader can copy.

### SERP Features

| Feature | Present? | Who Owns It | Can We Win? | Action |
|---------|----------|-------------|-------------|--------|
| AI Overview | **No** (confirmed via live SERP scrape) | — | n/a | Monitor — Google may add later for this query |
| Featured Snippet | **Yes** (paragraph format) | [Indeed](https://www.indeed.com/career-advice/career-development/company-overview-example) (live SERP position 1) | **Yes — winnable** | Add a 40-50 word definition paragraph at the top of "What is a company overview?" + a 6-item bulleted list immediately below "What to include" H2. Indeed's snippet is generic; Upmetrics' DR 73 + brand can leapfrog with tighter copy. |
| PAA (People Also Ask) | **Yes** (4 questions, live SERP) | Various | **Yes — winnable for 2-3 questions** | PAA questions captured: "What is a company overview example?", "How to write a good company overview?", "What is an example of an overview?", "What is an overview of the company?" — add direct answer paragraphs (40-60 words each) inside the FAQ schema block. See Update Brief Section 14E. |
| Video pack | **Yes** (3 videos) | Upmetrics, LivePlan, HubSpot | **Already in — but not embedded** | Upmetrics' own YouTube video ("Write a Company Overview in Minutes," 5:10, 1 month old) is in the Google video pack but is NOT embedded on this blog page. Embedding it captures video-intent clicks + reinforces E-E-A-T. See Action #6. |
| Image pack | Uncertain (position 1 has image_th flag) | — | Low priority | The featured snippet has an image thumbnail. Target page's 3 in-content images have alt text but may not be optimized for image search. Audit image filenames + alt text for keyword inclusion. |
| Knowledge panel | No | — | n/a | Not applicable to this query type |
| Discussions block (Reddit) | **Yes** (live SERP) | r/resumes, r/smallbusiness | n/a (UGC) | The Ahrefs SERP snapshot showed Quora threads at position 4; live SERP shows Reddit instead. UGC drift confirms the SERP is actively evolving. |

### Featured Snippet Optimization

| Query | Snippet Type | Current Owner | What Target Page Needs | Where to Place |
|-------|--------------|---------------|------------------------|----------------|
| how to write company overview | Paragraph | Indeed | A 40-50 word definition that opens "A company overview is..." and immediately answers the query. Currently the target page opens with a 2-sentence rhetorical hook ("If you were to invest in a business, what would be the first thing you'd like to know?") — beautiful for engagement, terrible for snippet capture. | Restructure "What is a company overview?" H2 to lead with the definition before the hook (or replace the hook with the definition). |
| what to include in a company overview | List (likely) | Indeed | A clean numbered list of 6 components in the H2 directly under "What to include" — the target page already has this structure but the list items contain prose explanations. Google's snippet harvester prefers `<ol>` with short items. | "What to include in an effective company overview" — keep the 6 H3s but add a tight bulleted list summary BEFORE the deep-dive H3s. |
| how do you start a company overview | Paragraph | Open (no clear winner in live SERP) | A short 30-40 word answer paragraph starting "Start your company overview by..." | Add as a new H3 inside "Tips to write..." or open the existing "Add a structure" tip with this exact sentence. |

**Important:** Featured snippet optimization recommendations live in Update Brief Section 14E (annotated outline). The SEO actions listed above are content changes — they belong in the writer's brief, not in this report's action table.

---

## 5. Technical SEO (Failures Only)

Only issues requiring action are shown. Passing checks are omitted.

| # | Issue | Current | Fix | SEO Impact |
|---|-------|---------|-----|------------|
| 1 | Meta description too long (186 chars — exceeds Google's ~155 char display window) | "Wondering what to include in a company overview section and how to write one? This blog post covers all those details and also offers examples for you to write your own company overview." | → See §2 Title & Meta Copy for rewrite (140 chars) | SERP listing truncates mid-sentence, hurting CTR |
| 2 | Title tag is identical to H1 (best practice: differentiate the two) | Both are: "How to Write a Company Overview for a Business Plan?" | Title → "How to Write a Company Overview (Examples + Template)"; H1 stays as the longer, more contextual version (drop question mark) | Two slots to target keyword variants and SERP-vs-on-page intent |
| 3 | Title ends with a question mark (slight CTR underperform on commercial-intent SERPs) | "How to Write a Company Overview for a Business Plan?" | → See §2 (new title is a statement, not a question) | Marginal CTR lift |
| 4 | No visible "Last Updated" date on page | Article schema has `datePublished`; no visible updated label | Add visible "Last updated: [date]" near the byline + update Article schema with `dateModified` | Freshness signal; competitors (LivePlan, Indeed) display update dates prominently |
| 5 | Article schema present but `dateModified` may be stale | Schema has Article type (verified) but no confirmed `dateModified` field | Refresh `dateModified` to today (2026-05-22) on republish, and on every future content update | Indexable freshness signal |
| 6 | Zero in-content external citation links | externalLinks = 4, all footer social icons (YouTube, Facebook, Twitter, LinkedIn — brand profiles, not citations) | Add 3-5 outbound citations to authoritative sources within the body (SBA.gov, Census, named expert quotes). Specific suggestions in Update Brief Section 14E. | E-E-A-T signal; competitor avg is 0-5 citations but the top ranker (SBA.gov entry) earns rank from being .gov authority |

**Passing checks (not listed above — confirmed clean):**
- Canonical tag self-referencing ✅
- No noindex / no nofollow on page ✅
- 1 H1, no duplicates ✅
- OG tags + Twitter cards present ✅
- All 3 content images have alt text ✅
- BreadcrumbList + FAQPage + Article + Organization schema all present ✅
- HTTPS, mobile viewport, valid URL structure ✅

**No critical blocker found.** All §5 issues are addressed by Section 2 actions (rewrites + schema update). The page is fundamentally healthy from a technical standpoint — the rankings are held back by content depth (§6), backlinks (§7E), and SERP CTR (§2 / §3), not technical defects.

---

## 6. Content Gaps & Competitor Depth

### 6A. Content Depth Comparison

| Page | URL | Content Type | Word Count | H2s | H3s | Images | FAQs | External Citations | Downloads |
|------|-----|--------------|------------|-----|-----|--------|------|---------------------|-----------|
| **Upmetrics (target)** | [link](https://upmetrics.co/blog/how-to-write-an-effective-business-overview-for-your-business-plan) | Blog article | **2,320** | 7 | 18 | 3 | 4 (FAQPage schema) | **0** | 2 templates |
| Liveplan | [link](https://www.liveplan.com/blog/planning/company-overview) | Blog article | 2,154 | 8 | 6+ | 7 (tables/visuals) | 1 | 5 | Sample business plan library (550+) |
| Indeed | [link](https://www.indeed.com/career-advice/career-development/company-overview-example) | Guide with one sustained example | ~1,500 | 4 | 12 | 0 | 0 | 0 | — |
| Joorney | [link](https://www.joorney.com/news/what-should-in-company-overview-of-business-plan/) | Blog article | ~1,200 | 3 | 15 (sub-elements) | 0 | 0 | 0 | — |

**Word count methodology:** Target page uses brand-specific selector `.blog-content-area`. Competitors use universal content-area detector. Indeed and Joorney are WebFetch estimates (Python scraper was blocked by 403). Treat as directionally comparable.

**Verdict:** Target page is the **longest of the four** but ranks last (position 9). Length is not the problem — depth-per-topic and example quality are.

### 6B. Competitor Heading Map

Topics covered on each page. ✅ = covers the topic / ✗ = does not cover. **C1=Liveplan, C2=Indeed, C3=Joorney.**

| Topic / Section | C1 (Liveplan) | C2 (Indeed) | C3 (Joorney) | OURS (Target) | Action |
|-----------------|:---:|:---:|:---:|:---:|--------|
| What is a company overview (definition) | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| Why a company overview matters (purpose / audience) | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| What to include — overall components | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| **Legal structure types (LLC / Corp / Sole Prop / Partnership)** | ✅ (5 types + tax/liability detail) | ✅ (LLC, Sole Prop, Partnership, Corp) | ✅ (LLC, Corp, Sole Prop) | ✗ | **✗ GAP — must add. 3/3 competitors cover. Currently only linked out to a separate page.** |
| **Ownership / equity split** | ✅ (dedicated section) | ✅ (in legal structure) | ✅ (Ownership and Management Team) | ✗ | **✗ GAP — must add.** |
| **Locations / facilities** | ✅ (dedicated section) | ✅ (dedicated section with example) | ✅ (Business Location incl. online profiles) | ✗ | **✗ GAP — must add.** |
| Company history / background | ✅ (with Botanical Bounty example) | ✅ (with Deep Harbor example) | ✅ | ✅ (H3: 3. Business history) | ✅ table stakes; **go deeper** with a fuller worked example |
| Management team / leadership | ✅ (Management team + Professional gaps + Board of advisors) | ✗ | ✅ (Ownership and Management Team) | ✅ (H3: 2. Teams and partners) | ✅ go deeper — add team bio guidance + planned hires |
| **Board of advisors** | ✅ (H4 — mentors, advisors, lawyers, accountants) | ✗ | ✗ | ✗ | **✗ GAP** (1 competitor only — Low priority) |
| Mission statement | ✅ | ✅ (with example) | ✅ (with example) | ✅ (H3: 5. Company mission statement) | ✅ table stakes |
| **Vision statement** (as distinct from mission) | ✗ | ✗ | ✅ (dedicated section with example) | ✗ | **✗ GAP — Medium priority.** Joorney is alone but treats it well. |
| **Core values** | ✗ | ✗ | ✅ (with example) | ✗ | **✗ GAP — Medium priority.** Frequently referenced in UGC / SERP. |
| **Market opportunity (callout, sets up market analysis)** | ✗ | ✗ | ✅ | ✗ | **✗ GAP — Low priority** (bridges to market analysis section) |
| Future goals / business goals | ✗ | ✗ | ✗ | ✅ (H3: 6. Future goals) | ✅ **UNIQUE EDGE** — Upmetrics is alone in covering this |
| Tips: writing structure / approach | ✅ (3 tips inc. "adjust to your target audience") | ✅ (4 tips) | ✅ (6 V/M/V tips) | ✅ (6 tips) | ✅ go deeper / restructure — currently the tips are generic; competitors are more strategic |
| Tips: write it last | ✅ (Cover the basics, then high points, then adjust) | ✅ ("Write it last" — explicit tip) | ✗ | ✅ (H3: 5. Write it at the end) | ✅ table stakes |
| **Tips: adjust to audience type (investor vs bank vs internal)** | ✅ (sustained worked example of revising the overview for a loan) | ✅ (#1 tip: understand target audience) | ✅ (Align the Message with the Audience) | ✗ (mentioned in "Highlight the basics" but not as a distinct concept) | **✗ GAP — must add.** All 3 competitors treat this as a discrete tip. |
| **Tips: storytelling / narrative structure** | ✅ (uses narrative throughout examples) | ✅ ("Create a narrative" as a tip) | ✅ (Incorporate Storytelling) | ✗ ("Demonstrate passion" is close but doesn't address narrative craft) | **✗ GAP — Medium priority.** |
| Worked example #1 | ✅ (Botanical Bounty — 290+ words, Oregon LLC, 2 years operating) | ✅ (Deep Harbor — sustained across every section, ~700+ words) | ✅ (eco-friendly products — V/M/V written verbatim) | ✅ (Ice cream cones — short snippet, ~100 words) | ✅ **go deeper** — examples are thin compared to competitors |
| Worked example #2 | ✅ (Bright House nursing home nonprofit — 480+ words) | ✗ | ✗ | ✅ (Solar company — short snippet) | ✅ go deeper |
| **Industry diversity in examples** | ✅ (agriculture + nonprofit healthcare — atypical industries) | partial (tech repair only) | partial (sustainable products only) | partial (ice cream + solar — both consumer-facing) | **Recommendation:** Add a service business example (e.g., consulting / SaaS / B2B) to broaden coverage |
| FAQs | partial (1 FAQ) | ✗ | ✗ | ✅ (4 FAQs in FAQPage schema) | ✅ **UNIQUE EDGE** — defend, expand from 4 to 6-8 |
| External citations (.gov / studies / experts) | ✅ (5 — incl. links to peer guides) | ✗ | ✗ | ✗ | **✗ GAP — must add.** Currently 0; competitors avg 1-2. |
| Downloadable templates / freebies | partial (550+ sample library) | ✗ | ✗ | ✅ (2 templates) | ✅ **UNIQUE EDGE** — already has, leverage harder in CTA + intro |
| Author bio / credentials | ✅ (Tim Berry — founder of Palo Alto Software, originator of Lean Business Planning) | ✗ ("Indeed Editorial Team") | ✗ | ✗ (generic "Upmetrics" byline, no bio, no photo) | **✗ GAP — must add.** See Action #5. |
| Embedded video | ✅ (LivePlan video walkthrough) | ✗ | ✗ | ✗ | **✗ GAP — must add.** Upmetrics has the asset (own YouTube video in Google video pack), just needs embedding. Action #6. |
| **Key takeaways / TL;DR at top** | ✅ (bulleted key takeaways block) | ✗ | ✗ | ✗ | **✗ GAP — Medium priority.** Improves snippet eligibility + AI Overview eligibility. |
| **Pre-launch / startup edge case** ("can a startup include this?") | partial (mentioned in audience-adjustment tip) | ✗ | ✗ | ✅ (FAQ: "Can a startup include a company overview...") | ✅ **UNIQUE EDGE** — defend, but expand from FAQ-level to a callout |
| **"Company overview vs. company description vs. executive summary" disambiguation** | partial (implicit) | partial (links to executive summary article) | ✗ | ✗ | **✗ GAP — Medium priority.** UGC (Quora) shows users explicitly confused about terminology — addressing this captures the 1,400-vol "company description" keyword too. |
| **"When to write" guidance (order in the business plan)** | partial (write it last is implied) | ✅ ("Write it last" as explicit tip) | ✗ | ✅ ("Write it at the end" tip) | ✅ table stakes; consider promoting to a dedicated callout |

### 6C. Topic Gap Detail

Every ✗ GAP from the heading map gets a specific recommendation. Listed by priority.

| # | Missing Topic | Covered By | Evidence Source | Priority | Recommended Action |
|---|---------------|------------|-----------------|----------|-------------------|
| 1 | Legal structure types (LLC / C-corp / S-corp / Sole Prop / Partnership) | C1 (5 types w/ tax detail), C2 (4 types w/ Deep Harbor example), C3 (mentioned) | All 3 competitors + UGC users explicitly ask | **High** | Add a dedicated H3 inside "What to include" — "Legal Structure (LLC, Corp, Sole Prop, Partnership)" — covering each type, with a one-sentence tax/liability note. ~250-350 words. |
| 2 | Ownership / equity split | C1 (dedicated H3), C2 (in legal section), C3 (Ownership and Management Team) | All 3 competitors | **High** | Add a brief H3 — "Ownership Breakdown" — guidance on stating who owns what %, day-to-day vs equity-only roles. ~150-200 words. Use Indeed's Deep Harbor co-partner example as a model. |
| 3 | Locations / facilities | C1 (H3), C2 (H3 w/ example), C3 (incl. online profiles) | All 3 competitors | **High** | Add an H3 — "Location(s) and facilities" — covering primary location, additional planned locations, and (for digital/remote businesses) virtual workspace + online profiles. ~200-250 words. |
| 4 | Audience-adjustment guidance (investor vs bank vs internal-use) | C1 (sustained worked example revising for a loan application), C2 (#1 tip), C3 (Align with Audience) | All 3 competitors | **High** | Convert the existing tip "Highlight the basics" into a more explicit tip: "Adjust your overview to your reader" — call out the 3 contexts (investor pitch, bank/SBA loan, internal-use lean plan) and give a one-line guidance for each. |
| 5 | External citations (.gov / studies / experts) | C1 (5 outbound citations) | C1 + ranking patterns (SBA.gov ranking pos 3-5 in live SERP) | **High** | Add 3-5 outbound citations to authoritative sources: SBA.gov (writing a business plan), Census Bureau (business demographics), and 1-2 expert quotes. Strengthens E-E-A-T and matches winning SERP pattern. Specific URLs in Update Brief Section 14E. |
| 6 | Sustained worked example (one full company across all sections) | C2 (Deep Harbor across all sections), C1 (Botanical Bounty across 4 sub-sections) | Top 2 ranking pages | **High** | Replace OR extend the existing ice cream cones + solar examples with one fully written sustained example — show every component (basic info → team → history → customer → mission → goals) for a single fictional business. Target: ~400-500 words for the worked example block. |
| 7 | Vision statement (distinct from mission) | C3 (dedicated section w/ example) | C3 + general business-plan convention | **Medium** | Restructure the "5. Company mission statement" H3 into a unified "5. Mission, Vision, Values" block with three short subsections + an example for each. Joorney's eco-friendly products example is a useful structural template. |
| 8 | Core values | C3 (with example) | C3 + UGC confusion ("what values mean") | **Medium** | Include core values inside the mission/vision/values block from #7. ~100-150 words. |
| 9 | Storytelling / narrative-structure tip | C1, C2, C3 | All 3 competitors | **Medium** | Replace or expand "Demonstrate passion" tip with "Tell a story (narrative structure)" — explain the structure: need → action → outcome. Indeed has the cleanest framing. |
| 10 | Key Takeaways block at top | C1 only | C1 + AI Overview eligibility patterns | **Medium** | Add a bulleted "Key takeaways" / "TL;DR" block immediately after the intro, before the first H2. 4-6 bullets summarizing what the article delivers. Improves snippet + AI Overview eligibility. |
| 11 | Terminology disambiguation (company overview vs. company description vs. executive summary) | C2 (links to executive summary article) | UGC (Quora) + Ahrefs (target ranks pos 29 for "company description", vol 1,400) | **Medium** | Add a brief callout / sidebar inside "What is a company overview?" disambiguating the three terms in 2-3 sentences. Captures the 1,400-vol "company description" keyword. |
| 12 | "When to write" guidance (order in the business plan) | C2 ("Write it last"), C1 (implicit) | Top 2 competitors + UGC ("when should I write the overview?") | **Medium** | Promote the existing "5. Write it at the end" tip into a more prominent callout, with a paragraph on WHY (you need the rest of the plan to know what to summarize). |
| 13 | Pre-launch / startup edge case expansion | own FAQ only | UGC ("how do I write this if I don't have a company yet?") | **Medium** | Expand the existing FAQ "Can a startup include a company overview" into a 200-word inline callout earlier in the article (after "Why you need a company overview"). Target pre-launch founders explicitly. |
| 14 | Market opportunity callout (bridges to market analysis) | C3 only | C3 + business-plan structure | **Low** | Add a 1-2 sentence mention at the end of "What to include" pointing readers to the market analysis section as the next chapter. |
| 15 | Board of advisors | C1 only | C1 only | **Low** | Add a one-line mention inside the "Teams and partners" H3 — "for stronger credibility, list advisors, mentors, lawyers, and accountants separately from management." |
| 16 | Service-business example (broader industry diversity) | — | Editorial judgment — current examples are both consumer-product industries | **Low** | If extending the worked example (gap #6) — pick a B2B service business (e.g., a marketing consultancy or local SaaS) to widen reader applicability. |

**UGC-sourced gaps** (from Quora threads — see `step1d-ugc-quora.json`):

- Users frequently confuse "company overview," "business description," "executive summary," "industry overview," and "company history." → Addressed by gap #11.
- First-time founders are intimidated by "20-40 page business plans" — they want lean, decision-tree guidance for which depth is needed. → Addressed by gap #4.
- "How do I write this if I don't have a company yet?" — common pre-launch question. → Addressed by gap #13.
- Investors will "shoot holes" through unprepared overviews with "Why?" — users want anticipatory framing. → Suggested for the new "Adjust to your reader" tip (gap #4).

---

## 7. Links & Backlinks

### 7A. Internal Link Issues

The target page has **11 in-content blog internal links** plus 4 template/download links and 16 nav/share links. Reviewed the 11 in-content links for relevance and current health.

| # | Anchor Text | Target URL | Issue |
|---|-------------|------------|-------|
| 1 | "planning to attract potential investors" | [/blog/what-lenders-look-for-in-business-plan](https://upmetrics.co/blog/what-lenders-look-for-in-business-plan) | Anchor talks about investors, link goes to "lenders" page. Mild semantic mismatch — investors ≠ lenders. Either re-anchor to "attract investors and lenders" OR change the target URL. |
| 2 | "Writing a mission statement" | [/blog/complete-guide-to-write-mission-statement-for-your-business](https://upmetrics.co/blog/complete-guide-to-write-mission-statement-for-your-business) | Healthy link. No issue (verify URL still 200 — see Action #10). |
| — | All other 9 in-content blog links | Various `/blog/...` URLs | No issues detected from extraction. Bulk verification (200 OK check) is Action #10 in §2. |

**Verdict:** Only 1 minor anchor-semantic issue. All 11 in-content links pass the structural test. Action #10 in §2 covers the bulk 200-OK verification.

### 7B. Internal Links to ADD

**⚠️ Every URL below has been verified to exist via GSC data (Step 1B) or Ahrefs data (Step 1C).** No URLs were guessed or constructed.

| Anchor Text | Target URL | Where to Place | Why | Source |
|-------------|------------|----------------|-----|--------|
| "company description" / "business description" | [/blog/legal-structure-of-business](https://upmetrics.co/blog/legal-structure-of-business) | Inside the NEW "Legal Structure" H3 (gap #1 in §6) | The target page already links here once ("legal structure" anchor). When the new Legal Structure section is added, the link should be expanded with stronger anchor text variety. | Target's existing internal links (Step 1A) |
| "products and services section" | [/blog/products-and-services-section](https://upmetrics.co/blog/products-and-services-section) | Inside "Target customer base and services included" H3 | Existing link — verified, no change needed. | Step 1A existing internal links |
| "executive summary" | [/blog/executive-summary-example-for-a-business-plan](https://upmetrics.co/blog/executive-summary-example-for-a-business-plan) | Inside the disambiguation callout (gap #11) | The target page does NOT currently link to the executive summary page despite mentioning the term. Adding this link strengthens the disambiguation section AND consolidates cannibalization authority (see §3). | GSC cannibalization data (step1b-cannibalization.json) |
| "business plan outline" / "business plan structure" | [/blog/business-plan-outline](https://upmetrics.co/blog/business-plan-outline) | Inside "Why do you need a company overview?" or new "When to write" callout (gap #12) | Sister page in business-plan-structure cluster. Consolidates authority + addresses cannibalization. | GSC cannibalization data |
| "executive summary example" / sister-link | [/blog/business-plan-components](https://upmetrics.co/blog/business-plan-components) | Footer of intro section or "Prepare an effective company overview section" | Consolidates the cluster — business-plan-components is the parent page that lists all sections. | GSC cannibalization data |
| "market analysis" | [/blog/market-analysis-in-business-plan](https://upmetrics.co/blog/market-analysis-in-business-plan) | Inside new "Market Opportunity" callout (gap #14) | Existing link — verified. The new Market Opportunity callout should re-emphasize this link as the natural next chapter. | Step 1A existing internal links |
| "financial plan" | [/blog/write-financial-section-startup-business-plan](https://upmetrics.co/blog/write-financial-section-startup-business-plan) | Inside "6. Future goals for the business" H3 | Existing link — verified. When Future Goals is updated, ensure this link stays. | Step 1A existing internal links |

### 7C. Pages That Should Link TO This Page

| Source Page URL | Where to Add (on source page) | Suggested Sentence (anchor text) | Source |
|-----------------|-------------------------------|----------------------------------|--------|
| [/blog/business-plan-outline](https://upmetrics.co/blog/business-plan-outline) | Inside the company overview chapter | "For a complete walkthrough, see our [company overview guide]." Anchor: "company overview guide" | GSC cannibalization (ranks pos 1 for "company overview" with 119 impr — likely an anchor snippet, not a full guide) |
| [/blog/business-plan-components](https://upmetrics.co/blog/business-plan-components) | Company overview subsection | "Read our full [how to write a company overview] guide for examples and templates." Anchor: "how to write a company overview" | GSC cannibalization (ranks pos 1, 21 impr) |
| [/blog/executive-summary-example-for-a-business-plan](https://upmetrics.co/blog/executive-summary-example-for-a-business-plan) | Where executive summary vs company overview is discussed | "The executive summary differs from your [company overview] — learn the distinction." Anchor: "company overview" | GSC cannibalization (ranks pos 1, 8 impr); pages should cross-link bidirectionally |
| [/blog/legal-structure-of-business](https://upmetrics.co/blog/legal-structure-of-business) | Near top, as related-resource link | "Your legal structure feeds into your business plan's [company overview]." Anchor: "company overview" | Reciprocal — target already links TO legal-structure page; should be bidirectional |
| [/blog/what-is-business-plan](https://upmetrics.co/blog/what-is-business-plan) | Wherever business plan structure is mentioned | "The [company overview] is the first major section after the executive summary." | Step 1B cannibalization mention (3 impr at pos 53 — currently very weak relevance signal; an internal link would strengthen it) |
| [/blog/how-to-write-a-business-plan-complete-guide](https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide) | In the company overview chapter | Direct link with strong anchor "[how to write your company overview]" | Step 1A — target already links TO this page; should be bidirectional |
| [/blog/common-business-plan-mistakes-to-avoid](https://upmetrics.co/blog/common-business-plan-mistakes-to-avoid) | Where company overview mistakes are mentioned | "[How to write an effective company overview]" | Step 1A — target already links TO this page; should be bidirectional |

**Note on Action #7, #8, #9 in §2:** These are the highest-leverage incoming links because the cannibalization data confirms those pages already rank for "company overview" related queries. Linking them to the target consolidates authority on the canonical page.

### 7D. External Link Issues

| # | Anchor Text | Target URL | Issue | Fix |
|---|-------------|------------|-------|-----|
| — | — | — | **No in-content external links to flag.** The page has 0 in-content outbound links. The 4 detected external links are all footer/social icons (Upmetrics YouTube, Facebook, Twitter, LinkedIn — own branded profiles, not citations). | The actionable item is **adding** outbound citations, which is gap #5 in §6C and is covered in the Update Brief Section 14E. |

**No competitor outbound links present** — the page does not link to any of the configured competitor domains. Clean.

### 7E. Backlink Gap

| Metric | Target Page | Avg Top 5 Competitors (SERP) |
|--------|-------------|------------------------------|
| Referring Domains (live) | **2** | ~14 (Indeed 13, NerdWallet 13, The Balance 13, Visme 10, bplans 35) |
| Referring Domains (all-time) | 20 | (not pulled for competitors — outside API budget) |
| Total Backlinks (live) | 2 | (not pulled — beyond API budget) |
| URL Rating (UR) | **6.0** | 4-7 range (Indeed UR 6, NerdWallet UR 4, The Balance UR 7, Visme UR 4, bplans UR 4) |
| Domain Rating (DR) | 73 | 78-92 range (target is the lowest-DR in top 10) |

**Gap summary:**

- **86% below competitor average for referring domains** (2 vs ~14). This is the single biggest reason a high-quality page sits at position 9 instead of 3-5. Closing this gap (adding ~12 quality referring domains) would meaningfully improve ranking with no other changes needed.
- **18 of 20 all-time referring domains have decayed.** That's a 90% decay rate — unusually high. Likely causes: blog roundups that have been deleted, old syllabi that have been refreshed, or pages that were never indexed long-term. **Recovery is faster than new acquisition** — Action #15 in §2 schedules a broken-link reclamation campaign.
- **URL Rating (6.0) is competitive — Domain Rating (73) is the weakness.** UR matches the SERP average; the deficit is brand authority. Building blog-cluster topical authority (via the internal link consolidation in 7C) and earning more referring domains lifts UR further AND signals topical relevance to Google.
- **Specific link-building targets** (Action #13): SBA Resource Partners directory (e.g., SCORE, SBDC chapters — many maintain resource lists); university entrepreneurship program syllabi (.edu links); regional small-business associations; partner content swaps with non-competing SaaS in the small-business space (accounting tools, payroll, banking). Pitch: the 2 downloadable templates + Upmetrics YouTube video make this a high-utility resource for educators.

---

## 8. E-E-A-T & Citations

Read from `verified-facts.json`. Only rows with gaps are listed.

### E-E-A-T Signal Comparison

| Signal | Target Page | Best Competitor | Gap? |
|--------|-------------|-----------------|------|
| Author name | "Upmetrics" (brand, not a person) | Liveplan: Tim Berry (founder of Palo Alto Software, creator of Lean Business Planning) | ✗ **Gap** — replace with a named expert. |
| Author bio | None (verified: `author_has_bio=false`) | Liveplan: dedicated author H2 with credentials | ✗ **Gap** — add 2-3 sentence bio. |
| Author photo | None (verified: `author_has_photo=false`) | Liveplan (implied via author block) | ✗ **Gap** — add author photo. |
| Updated date visible on page | No (only published date visible) | Liveplan: "May 13, 2026" prominently displayed; Indeed: "Updated December 15, 2025" | ✗ **Gap** — add visible "Last updated" label. |
| Expert quotes / named sources in body | None | Liveplan: testimonial quote from Madeleine Morgan (named, with title); references Dr. Mildred Johnson background credentials in worked example | ✗ **Gap** — add 1-2 expert quotes or named sources. |
| External citations (.gov / studies / experts) | 0 in-content | Liveplan: 5 external citations | ✗ **Gap** — add 3-5. |
| FAQs / structured Q&A | 4 FAQs with FAQPage schema ✅ | Liveplan: 1 FAQ; Indeed/Joorney: 0 | (target leads — no gap) |
| Schema markup | Article + WebPage + BreadcrumbList + FAQPage + Organization + Person ✅ | (similar) | (no gap) |
| Years of experience / credentials claim | Missing | Liveplan establishes Tim Berry's authorship credentials | ✗ **Gap** — author bio should include credentials |

### Citation Audit

The target page has **0 in-content external citation links**, so there are no citations to audit. The 4 external links found by the scraper are all footer social icons (Upmetrics' own branded profiles), not citations.

This is not a citation-quality issue — it's a citation-existence issue. **Recommended new citations** (with verified URLs) appear in the Update Brief Section 14E (annotated outline), where the writer gets section-level placement context.

### Unsourced Claims

The page makes several factual statements that would benefit from outbound citation. Examples (exact quotes from the body):

| Unsourced Claim (exact quote) | Location | Recommended Source URL |
|--------------------------------|----------|------------------------|
| "If you were to invest in a business, what would be the first thing you'd like to know? Of course, you'll look at financials and numbers, but the first thing you would want to know would be the business idea..." | Intro | (Editorial framing — no citation needed but could borrow data from SBA's "[Write your business plan](https://www.sba.gov/business-guide/plan-your-business/write-your-business-plan)" guide) |
| "A company description falls just after an executive summary and it's an important section of any business plan." | "What is a company overview?" | [SBA: Write your business plan](https://www.sba.gov/business-guide/plan-your-business/write-your-business-plan) — confirms structural order |
| Various tips ("Add a structure," "Highlight the basics") presented as best practices without sources | "Tips to write an effective company overview" | These can be backed by linking to: 1 SBA.gov resource, 1 expert authority (Tim Berry / Palo Alto Software / Lean Planning), and 1 statistic from a credible source (Bureau of Labor Statistics or Census Bureau on business formation). |
| The two industry examples (ice cream cones, solar) — no citation that they are illustrative composites | "Company overview examples" | Add a 1-line disclaimer: "These examples are illustrative composites and do not represent real companies." (Not a citation but a credibility safeguard.) |

**Verified citation URLs to consider** (each manually checked via Claude in Chrome / WebSearch — all return 200):
- [https://www.sba.gov/business-guide/plan-your-business/write-your-business-plan](https://www.sba.gov/business-guide/plan-your-business/write-your-business-plan) — SBA on business plan structure (.gov authority)
- [https://www.census.gov/programs-surveys/abs.html](https://www.census.gov/programs-surveys/abs.html) — US Census Annual Business Survey (data on business demographics for the "Why you need" section)
- [https://www.bls.gov/bdm/](https://www.bls.gov/bdm/) — BLS Business Employment Dynamics (data point: "X% of businesses succeed past Y years" claim, common in business-planning content)

**→ All new citation suggestions go into the Update Brief Section 14E** so the writer sees them in context, not in this report.

---

## 9. Appendix

### Ahrefs API Consumption Log

| # | Call | Endpoint | Units Consumed |
|---|------|----------|----------------|
| 1 | Organic Keywords (target page) | `site-explorer-organic-keywords` | 120 |
| 2 | SERP Overview (primary keyword) | `serp-overview` | 154 |
| 3 | Keyword Overview (primary + secondary) | `keywords-explorer-overview` | 64 |
| 4 | Backlinks Stats (target page) | `site-explorer-backlinks-stats` | 50 |
| 0 | Subscription check (free, pre-flight) | `subscription-info-limits-and-usage` | 0 |
| | **Total this audit** | | **388** |
| | Remaining in cycle (after this audit) | | 398,178 → ~397,790 |
| | Reset date | | 2026-06-21 |

**Note on Call 1:** First attempt with `where: "volume >= 100"` failed with "bad where: invalid filter expression" (Ahrefs MCP filter syntax issue). Retried with `where: "volume>=100"` — also failed. Removed the `where` filter and relied on `order_by: volume:desc` + `limit: 30` to surface the top-volume keywords. All 10 keywords the page ranks for were captured.

### Data Files (workspace)

All raw data is saved in `./workspace/how-to-write-an-effective-business-overview-for-your-business-plan/audit-data/`:
- `step1a-target-page.json` — full target page scrape
- `verified-facts.json` — single source of truth for author/date/templates/schema
- `step1a-page-text.txt` — clean body text
- `step1b-gsc-data.json` — 500 GSC queries
- `step1b-gsc-trends.json` — monthly trend data (22 queries with ≥30 impressions)
- `step1b-cannibalization.json` — 6 query+page lookups
- `step1c-organic-keywords.json` — Ahrefs organic keywords
- `step1c-serp-overview.json` — Ahrefs SERP top 10
- `step1c-keyword-overview.json` — Primary + secondary keyword metrics
- `step1c-backlinks.json` — Backlink profile
- `step1c-serp-features.json` — Live SERP features (Claude in Chrome) + Ahrefs SERP overview
- `step1d-competitor-1.json` + `step1d-competitor-1-text.txt` — Liveplan (Python scraper)
- `step1d-competitor-2.json` + `step1d-competitor-2-text.txt` — Indeed (Claude in Chrome)
- `step1d-competitor-3.json` + `step1d-competitor-3-text.txt` — Joorney (Claude in Chrome)
- `step1d-ugc-quora.json` — 2 Quora UGC threads

---

*End of audit report. See the Content Update Brief (.docx) for writer-facing recommendations.*
