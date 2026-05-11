# SEO Page Audit — Business Plan Competitions

**Page:** [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions)
**Primary Keyword:** business plan competition
**Audit Date:** 2026-05-11
**Brand:** Upmetrics (upmetrics.co)
**Geography:** United States

---

## 1. EXECUTIVE DASHBOARD

### Page Snapshot

| Metric | Value |
|--------|-------|
| URL | [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions) |
| Primary Keyword | business plan competition |
| Primary KW — US Search Volume | 150/mo (Ahrefs) |
| Primary KW — Current Position | 20.5 avg (GSC, 6 mo, 182 impr, 1 click, 0.5% CTR) |
| Primary KW — Keyword Difficulty | 19 (low) |
| Title Tag | "The Top 20 Business Plan Competitions to get funding in 2026" (60 chars) |
| OG Title | ⚠️ "The Best 20 Business Plan Competitions to Get Funding in ([currentyear])" — unresolved Yoast `[currentyear]` shortcode in `og:title` |
| Meta Description | "Looking to secure funding for your business or validate your idea? Check out the top 20 business plan competitions of 2026 and learn how to win them." (149 chars) |
| H1 | The Best 20 Business Plan Competitions to Get Funding in (2026) |
| Word Count (article body only) | 2,212 (source: `.blog-content-area`) |
| Internal Links | 68 in-content |
| External Links | 25 (mostly to competition organizers — appropriate) |
| Content Images | 1 image, 1 with alt — extremely thin for a 20-item listicle |
| Schema Markup | BreadcrumbList ✅, FAQPage ✅, but **no Article/BlogPosting schema** ❌ |
| Canonical Tag | [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions) (self-referencing ✅) |
| Page Type | Listicle / blog article |
| Content Freshness | Updated May 6, 2026 ✅ (visible + meta) |
| Author Attribution | Byline "Upmetrics" (generic brand byline — no human author, no bio, no photo) |
| Downloadable Templates/Freebies | 4 in-content links to Upmetrics business plan template ✅ |
| Backlinks | 1 live backlink from 1 referring domain (Ahrefs) — very low |
| Total GSC Queries (6 mo) | 272 queries, 4 clicks, 3,950 impressions |

### Top 3 Problems

1. **Severe content depth deficit vs. only listicle competitor.** The page is 2,212 words; Growthink — the only listicle in the SERP top 10 (pos 4) — is 4,004 words and includes prize amounts, deadlines, and 19 specific dollar/data points. Our 20 competitions are described in 1-3 short lines each. Google's lone "best of" listicle slot is currently rewarded to depth, not brevity.
2. **Cannibalization is bleeding away the few high-ranking impressions.** For the primary keyword, two OTHER Upmetrics pages also rank: [how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) at avg pos 3.5 and [business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) at avg pos 4 — both vastly outrank the target page (pos 20.5). Internal authority is fragmented across 3 URLs for the same query.
3. **Almost zero backlink authority + broken `[currentyear]` token in `og:title`.** Only 1 live referring domain (Ahrefs) and the `og:title` exposes a literal `[currentyear]` Yoast shortcode placeholder — this likely surfaces in social-card previews and is a visible production bug.

### Traffic Opportunity

> Primary KW: 150 vol, KD 19. Page already gets 182 impressions/mo at avg pos 20.5 with 0.5% CTR — moving into the top 5 (single listicle slot Google is willing to give) realistically delivers 20-40 clicks/mo on the head term alone. Including the 270+ long-tail variants (small business competition, business idea competition, startup competitions, etc.) currently impression-only, full top-10 visibility could plausibly drive 200-400 clicks/mo. Biggest blocker is content depth + internal cannibalization, not external competition (KD=19).

---

## 2. MASTER ACTION TABLE

| # | Priority | Category | Action | Assignee | Details | Section Ref |
|---|----------|----------|--------|----------|---------|-------------|
| 1 | P1 | Cannibalization | Resolve 3-page cannibalization for "business plan competition" | SEO + Content | Decide canonical winner. Recommended: keep this page as the listicle, internally link FROM [how-to-write-the-competition-section](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) and [business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) TO this page using anchor "business plan competitions" — DO NOT redirect (the two competing pages each rank for their own intents). Also de-target the bare term "business plan competition" from those two pages (remove the phrase from their title/H1/intro). | §3, §7 |
| 2 | P1 | Meta | Rewrite title tag for CTR + capitalization consistency | Dev/SEO | Copy-paste below in "Title & Meta Copy" block | §5 |
| 3 | P1 | Meta | Fix `og:title` — unresolved `[currentyear]` Yoast shortcode | Dev | Current `og:title` = "The Best 20 Business Plan Competitions to Get Funding in ([currentyear])". The Yoast `%%currentyear%%` token is not being rendered server-side. Inspect Yoast meta config or theme template — replace placeholder with `2026` or fix the shortcode rendering. | §5 |
| 4 | P1 | Schema | Add `Article` (or `BlogPosting`) schema with author, publisher, datePublished, dateModified, image, headline | Dev | Page has BreadcrumbList + FAQPage but no top-level Article/BlogPosting. Use Article schema with `author.@type=Person` + a real author bio page (see §8). | §5 |
| 5 | P1 | Content | Major content update — see Update Brief | Writer | →  Content Update Brief (.docx) covers content depth additions, EDITs, and the per-competition data table (deadline, prize, eligibility, year founded). | §6 + Update Brief |
| 6 | P2 | Schema | Add `ItemList` schema wrapping the 20 competitions | Dev | Helps Google understand this is a ranked list — supports rich result eligibility for "best of" listicles. | §5 |
| 7 | P2 | E-E-A-T | Replace generic "Upmetrics" byline with named human author + bio + photo | SEO + Content | Currently `author=Upmetrics`, no bio, no photo. Growthink and Upmetrics' own competing high-school-competitions page (authored by Vinay Kevadia) both signal weak/named authorship. Pick a named author with funding/startup experience; add 2-3 line bio + headshot. | §8 |
| 8 | P2 | Internal Link | Add internal links FROM 3 specific Upmetrics pages TO target | SEO Team | See §7B for the 3 verified candidate source pages with exact anchor recommendations. | §7B |
| 9 | P2 | Content Freshness | Verify every competition's 2026 deadline + prize amount and stamp the page with "Last verified [date]" | Writer + SEO | Several competitions on the page (e.g., 13th IOT/WT World Cup, U.Pitch) need year-specific deadline verification. | §6 / Update Brief |
| 10 | P3 | Backlinks | Build digital-PR links targeting this URL | Link Builder | Only 1 live referring domain. Pitch to startup-publication roundups ("best startup competitions"), university entrepreneurship-center blog rolls, and HARO/SourceBottle queries about "best business plan competitions". Realistic 6-mo target: 8-15 new referring domains. | §7E |
| 11 | P3 | External Link | Audit & verify all 25 external competition URLs (some pages on the list — e.g., HeroX IOT/WT World Cup — may be defunct/redirected) | Writer + Dev | Spot-check each linked competition page; replace broken links with the closest current equivalent or remove the entry. | §7D |
| 12 | P3 | Internal Link | Audit the 68 in-content internal links and consolidate template/CTA links | SEO | 4 separate links to `/download/business-plan-template` within content — verify this is intentional vs. dilution. | §7A |

**Title & Meta Copy (ready to copy-paste):**

```
Title Tag (NEW): 20 Best Business Plan Competitions to Win in 2026 (with Prizes) [56 chars]
Title Tag (OLD): The Top 20 Business Plan Competitions to get funding in 2026 [60 chars]

Meta Description (NEW): Compare 20 of the top business plan competitions in 2026 — prizes, eligibility, deadlines, and how to win. Includes student, undergrad, and open-stage contests. [158 chars]
Meta Description (OLD): Looking to secure funding for your business or validate your idea? Check out the top 20 business plan competitions of 2026 and learn how to win them. [149 chars]

og:title (FIX): replace literal "[currentyear]" with the actual year — currently the og:title reads "...Funding in ([currentyear])" which is a broken Yoast %%currentyear%% token.
```

**Rationale (for the title/meta rewrite):**
- New title shifts "Best 20" to the front, adds the high-intent action verb "Win" (matches PAA #2 "how do I win a business plan competition") and tees up the "Prizes" hook competitors mention — Growthink's title is "The 20 Best Business Plan Competitions" (no hook, no year).
- New meta description front-loads action ("Compare 20..."), surfaces the four most-clicked attributes from PAA (prizes, eligibility, deadlines, how to win), and ends with the audience qualifier (student / open-stage) — directly addressing the long-tail queries currently impression-only (e.g., "best business plan competitions for college students", 27 impressions, pos 27).

**⚠️ Content actions NOT included here:** content additions, rewrites, gap fills → all in **Content Update Brief (Section 14, .docx)**.

---

## 3. KEYWORD & RANKING ANALYSIS (US)

### Top 10 Keywords (GSC, last 6 months)

| Keyword | Impressions | Clicks | CTR | Avg Position | Trend (6 mo) |
|---------|------------|--------|-----|-------------|-------------|
| business plan competition | 182 | 1 | 0.5% | 20.5 | → flat (23.8 → 23.6) |
| small business competition | 153 | 0 | 0% | 17.7 | ↓ declining (10.2 → 19.0) |
| business idea competition | 147 | 0 | 0% | 42.4 | ↓ declining (14.9 → 29.0) |
| best business to start little competition | 124 | 0 | 0% | 44.7 | ↓ declining (irrelevant query — misranking) |
| startup idea competition | 97 | 0 | 0% | 56.4 | — |
| business competition examples | 91 | 0 | 0% | 60.0 | ↑ improving (85.5 → 38.8) |
| new business competition application | 84 | 0 | 0% | 66.1 | ↑ improving (69.5 → 19.5) |
| nibs worldwide business plan competition 2026 dates | 84 | 0 | 0% | 10.1 | → flat (1 month of data) |
| business plan competition ideas | 83 | 0 | 0% | 25.7 | ↑ improving (22.0 → 12.8) |
| business plan competition examples | 69 | 0 | 0% | 21.2 | ↓ declining (16.2 → 36.2) |

**Headline read:** 272 unique queries, 4 clicks, 3,950 impressions in 6 months. CTR on the primary keyword is 0.5% at pos 20.5 — well below the ~2% expected at that position. The page is impression-rich and click-starved: **(a)** the title/meta is not earning clicks, and **(b)** the page is stuck in low double-digit positions where Growthink alone occupies the single listicle slot at pos 4.

### Striking Distance Opportunities (positions 4-20 with ≥30 impressions)

| Keyword | Impressions | Clicks | Position | Opportunity |
|---------|------------|--------|----------|-------------|
| small business competition | 153 | 0 | 17.7 | High — 0 clicks at near-top-20. Add a dedicated "Small business plan competitions" sub-section or filter. |
| business plan competition | 182 | 1 | 20.5 | High — the head term. Cannibalization + depth fixes should move into top 10 within 1-2 update cycles. |
| business plan competition examples | 69 | 0 | 21.2 | High — query implies real-world case studies; add 2-3 winner pitch case studies. |
| business plan competition ideas | 83 | 0 | 25.7 | Medium — trending up. Surface common winning industry/idea themes (HealthTech, climate, B2B SaaS). |
| nibs worldwide business plan competition 2026 dates | 84 | 0 | 10.1 | Medium — already top-10, no clicks. Expand NIBS section with deadlines + application steps. |

### Cannibalization Check

**⚠️ Cannibalization detected for the primary keyword "business plan competition":**

| Query | Target Page Position | Competing Page URL | Competing Page Position | Recommendation |
|-------|---------------------|-------------------|------------------------|----------------|
| business plan competition | 20.5 (182 impr, 1 click) | [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | 3.5 (6 impr) | Internal-link FROM that page TO target with anchor "business plan competitions" near the intro; de-target the bare phrase from H1/meta/intro on the competing page (focus it on "competition section of business plan"). |
| business plan competition | 20.5 | [https://upmetrics.co/blog/business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) | 4 (1 impr) | Internal-link FROM that page TO target with anchor "business plan competitions"; clarify on that page that it is the *high-school* variant. |

The two competing pages outrank the target by ~17 positions on the head term but only earn 7 impressions combined — Google occasionally swaps them in for tiny slices. Consolidating internal anchors to point at the listicle should restore signal to the right URL.

For all other top-5 queries, no external cannibalization was found.

---

## 4. SERP & INTENT ANALYSIS

**What Google is rewarding:**
- **Dominant intent:** Mixed — heavily transactional/navigational, lightly informational.
- **Content types ranking:** 9 of 10 organic results are individual competition organizer pages (Rice, WSU, NYBPC, St. Thomas, High Point, WI Governor's, Koffman/NYBPC, Kean) — universities and regional contests. Position 4 (Growthink) is the **only listicle-guide** in the SERP top 10. Position 3 is an AI Overview.
- **What this means:** Google has decided this query is mostly people looking for a *specific* competition. It is willing to give a *single* "best of" listicle slot, currently held by Growthink. Our page competes for THAT slot, not for the whole SERP.

**Intent match/mismatch:**
- **Current page type:** Listicle / "best of" blog article.
- **Match status:** ✅ Match — same content type as the single listicle in the SERP.
- **Note:** The page is in the right format. The reason it is at pos 20.5, not pos 4, is depth and authority — not intent.

**SERP Features (US, primary keyword):**

| Feature | Present? | Who Owns It | Can We Win? | Action |
|---------|----------|-------------|-------------|--------|
| AI Overview | ✅ Yes (pos 3 in SERP) | Synthesized from organizer pages + listicles | Partially — aim to be cited by AIO | Add precise definition + ranked list with prize amounts at top of page; use ItemList + Article schema; cite primary sources for prize data. |
| Featured Snippet | ❌ No | — (AIO took the slot) | Unlikely while AIO is present | Skip. |
| PAA (People Also Ask) | ✅ Yes (6+ questions) | Various | ✅ Yes — current FAQ schema is a head start | Map existing FAQs to PAA questions and add the missing ones (see Section 6 / Update Brief). |
| Video results | ❌ No | — | — | Not a SERP feature on this query. |
| Image pack | ❌ No | — | — | Not a SERP feature on this query. |

**PAA questions to target** (from WebSearch):
1. What is a business plan competition? — ✅ already in FAQ
2. How do I win a business plan competition? — ❌ missing (high-priority add)
3. What do judges look for in a business plan competition? — ❌ missing
4. Are business plan competitions worth it? — ❌ missing
5. How much money can you win in a business plan competition? — ❌ missing (matches "business plan competition grant" query)
6. Who can participate in a business plan competition? — partial (current FAQ only covers "do I need a complete business")

**Featured Snippet Optimization:** Not applicable while AI Overview occupies the slot. Optimize for AIO citation instead (precise definitions, structured data, primary-source citations on prize amounts).

---

## 5. TECHNICAL SEO (Failures Only)

| # | Issue | Current | Fix | SEO Impact |
|---|-------|---------|-----|------------|
| 1 | `og:title` exposes unresolved Yoast `[currentyear]` shortcode | `og:title = "The Best 20 Business Plan Competitions to Get Funding in ([currentyear])"` | Inspect Yoast `%%currentyear%%` token rendering — replace with `2026` or fix the shortcode pipeline. The page-level `<title>` renders correctly ("...in 2026"), so the bug is isolated to OG/social. | Social card previews and AIO citation snippets show a literal `[currentyear]` placeholder — undermines trust and freshness signals. |
| 2 | No Article / BlogPosting schema | Schema types present: BreadcrumbList, FAQPage. No `Article` or `BlogPosting`. | Add `Article` (or `BlogPosting`) schema with `headline`, `author` (Person), `publisher` (Organization with logo), `datePublished` (2022-05-16), `dateModified` (2026-05-06), `image`. | Loss of `Article` rich-result eligibility; weaker E-E-A-T signals for AIO consideration. |
| 3 | No `ItemList` schema for the 20-item list | The page IS a ranked list of 20 competitions but provides no `ItemList` markup. | Add `ItemList` schema with one `ListItem` per competition (name + URL + position). | Helps Google parse list semantics; supports enhanced list rich result on "best of" SERPs. |
| 4 | Title and meta description copy not optimized for CTR | See Section 2 Title & Meta Copy block | → See Section 2 | At pos 20.5 the 0.5% CTR is below the ~2% benchmark — title needs a stronger value hook and the meta needs to surface deadlines/prizes/eligibility. |
| 5 | Only 1 in-content image for a 2,212-word listicle covering 20 competitions | 1 image (`crossline.png`, decorative, near Conclusion) | Add per-competition logos (with proper attribution + permission/fair use), a hero image, and at least 1 comparison chart. Use unique alt text per logo (e.g., "Rice Business Plan Competition logo"). | Image SEO + dwell time + Google Discover eligibility. |
| 6 | Generic brand byline "Upmetrics" with no human author bio or photo | `author=Upmetrics`, `author_has_bio=false`, `author_has_photo=false` (from `verified-facts.json`) | Assign a named human author with relevant credentials; add 2-3 line bio + headshot in the post template. | E-E-A-T — particularly important for YMYL-adjacent funding content. |

All other technical checks passed (canonical self-referencing, no noindex/nofollow, OG/Twitter cards present, mobile viewport implied via Yoast, URL structure clean).

---

## 6. CONTENT GAPS & COMPETITOR DEPTH

### 6A. Content Depth Comparison

| Page | URL | Content Type | Word Count | H2s | H3s | Images | FAQs | External Citations | Downloads |
|------|-----|-------------|-----------|-----|-----|--------|------|----|-----------|
| **TARGET** | [upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions) | listicle | **2,212** | 4 | 25 | **1** | 5 | 25 | 4 (template links) |
| C1 (SERP pos 4) | [growthink.com/.../business-plan-competitions](https://www.growthink.com/businessplan/help-center/business-plan-competitions) | listicle | **4,004** | — | — (Growthink uses non-standard heading levels) | — | 5 | 45 | multiple template CTAs |
| C2 (cannibal — different intent) | [upmetrics.co/.../how-to-write-the-competition-section](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | blog article | 2,158 | — | — | — | 10 | 1 | 1 (template) |
| C3 (cannibal — HS variant) | [upmetrics.co/.../business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) | listicle | **3,606** | — | — | — | 7 | 24 | 1 (template) |
| C4 (external listicle, off-SERP) | [startupowl.com/fund/business-plan-competitions](https://startupowl.com/fund/business-plan-competitions) | blog article | **3,522** | — | — | — | 0 | 9 | — |

**Headline:** Target is 2,212 words; the 3 relevant listicle/guide competitors average **3,711 words** (Growthink 4,004; HS variant 3,606; StartupOwl 3,522). Target needs ~1,400-1,800 additional words of substance to be competitive — but **what** to add matters more than raw length; see 6B/6C.

### 6B. Competitor Heading Map (topic coverage)

| Topic / Section | C1 Growthink | C3 HS-var. | C4 StartupOwl | OURS | Action |
|----------------|----|----|----|----|--------|
| Definition: "What is a business plan competition?" | ✅ | ✅ | ✅ | ✅ | ✅ table stakes — keep |
| How to find a competition | partial | ✅ | partial | ✅ | ✅ table stakes — keep |
| Ranked list of named competitions (≥15) | ✅ | ✅ | ✅ | ✅ (20) | ✅ go deeper (add a comparison table) |
| **At-a-glance comparison table** (prize, deadline, eligibility, location, stage) | ❌ (inline) | ✅ | ✅ | ❌ | ✗ **GAP** — must add (highest priority) |
| **Tips for winning / How to win** section | ✅ | ❌ | ✅ | ❌ | ✗ **GAP** — must add (matches PAA + "business plan competition grant" intent) |
| **What judges look for** (rubric / criteria) | partial | partial (in FAQ) | ✅ | ❌ | ✗ **GAP** — must add |
| **Prize money detail** per competition (1st/2nd/3rd $) | ✅ | ✅ | ✅ | partial | ✅ go deeper — make prize amounts consistent across all 20 |
| **Application deadlines & 2026 calendar** | ❌ | ✅ | ✅ | ❌ | ✗ **GAP** — add deadline + status (open/closed) per competition |
| **Eligibility filtering** (student / open-stage / post-revenue) | ✅ | ✅ | ✅ | partial (Eligibility line only) | ✅ go deeper — add filter chips/index |
| **How to prepare / application steps** per competition | ❌ | ✅ (per-comp) | ✅ (general) | ❌ | ✗ **GAP** — add a "How to apply" generic playbook |
| **Time, cost, ROI analysis** of competing | ❌ | ❌ | ✅ | ❌ | ✗ **GAP** — add (compelling differentiator vs. Growthink) |
| **Pros & Cons** of business plan competitions | ❌ | partial (benefits FAQ) | ✅ | partial (Conclusion only) | ✗ **GAP** — add a clean pros/cons block |
| **Named winner case studies** (e.g., Intero Biosystems @ RBPC 2026) | ❌ | ❌ | ✅ | ❌ | ✗ **GAP** — add 2-3 winner stories (matches "business plan competition examples" query, 69 impr) |
| **Pitch video tips** | ❌ | ❌ | ✅ | ❌ | ✗ GAP (medium) — add a sidebar/callout |
| **Equity vs non-dilutive funding** framing | partial | ❌ | ✅ | ❌ | ✗ GAP (medium) — important for E-E-A-T |
| **Audience filter — small business / SMB competitions** | partial | ❌ | partial | ❌ | ✗ **GAP** — directly addresses "small business competition" query (153 impr, 0 clicks) |
| **Audience filter — student/college competitions** | ✅ | ✅ | partial | partial (some entries are student) | ✅ go deeper — add a "Best for college students" sub-list |
| **PAA: "Are business plan competitions worth it?"** | partial | ❌ | ✅ | ❌ | ✗ GAP — add to FAQ |
| **PAA: "How much money can you win?"** | answered by prize detail | ✅ | ✅ | ❌ | ✗ GAP — answer with $ range + median |
| **Author bio + photo** (E-E-A-T) | partial | ✅ (Vinay Kevadia) | ✅ (Eliot Reynolds) | ❌ | ✗ GAP — see §8 |
| **Editorial standards / methodology disclosure** | ❌ | ❌ | ✅ | ❌ | ✗ GAP (medium) — add a "How we picked these 20" note |
| **Inline downloadable template CTAs** | ✅ | ✅ | ❌ | ✅ (4 links) | ✅ table stakes — keep, but audit redundancy (§7A) |
| **Resource roundup / related articles at end** | ✅ | partial | ❌ | partial | ✅ go deeper |
| **20 competition profiles** | partial (different list) | n/a (HS-specific) | partial (different list) | ✅ | ✅ UNIQUE EDGE — Upmetrics covers competitions the others miss (Pistoia, Climatech, CodeLaunch, 13th IOT/WT). Verify all 20 are current. |

### 6C. Topic Gap Detail

| # | Missing Topic | Covered By | Evidence Source | Priority | Recommended Action |
|---|--------------|------------|----------------|----------|-------------------|
| 1 | At-a-glance comparison table (Prize / Eligibility / Deadline / Format) | C3, C4 | C3 has per-competition at-a-glance table; C4 has a global comparison table | **High** | Add an HTML/Markdown table at the top of the listicle: Competition | Prize Pool | Eligibility | 2026 Deadline | Stage | Apply. Updates per refresh cycle. |
| 2 | "How to win" / "Tips for winning" deep section | C1, C4 | C1 has dedicated section; C4 has a 3-tactic playbook | **High** | Add a 600-900 word section with 5-7 winning tactics, sourced (HBR / Steve Blank counterpoint / Paychex). Maps directly to PAA #2 and the "business plan competition grant" query. |
| 3 | "What judges look for" / Judging rubric | C4 | C4: 5-criteria breakdown (problem statement, customer validation, market sizing, moat, team) | **High** | 300-400 word section, table format. Maps to PAA #3. |
| 4 | Named winner case study (concrete example) | C4 | C4 cites Intero Biosystems @ RBPC 2026 with prize breakdown | **High** | Add 2-3 short winner case studies (1 paragraph each). Maps to "business plan competition examples" query (69 impr, 0 clicks). |
| 5 | 2026 deadlines & "open vs closed" status per competition | C3, C4 | C3 has Competition Dates column; C4 has 2026 Dates column | **High** | Per-competition: add a `Deadline` and `Status` field. Add a top-of-page note "Last verified [date]". |
| 6 | Small-business / SMB filter (not just student) | C4 partial | "small business competition" query has 153 impressions, 0 clicks, pos 17.7 | **High** | Add a sub-section "Best business plan competitions for small businesses" with 3-5 picks from the existing 20 (Get Seeded, NIBS, HATCH Pitch, etc.) + 1-2 SBA / state-level adds (e.g., WI Governor's Business Plan Contest from SERP pos 8). |
| 7 | Time / cost / ROI analysis of entering a competition | C4 | C4 has founder-hour math + Low/High estimate table | Medium | 300-word section with a "40-60 hours per entry" benchmark, win-rate baseline (<5%), and breakeven analysis. |
| 8 | Pros & Cons block | C4 | C4 lists tradeoffs with dollar figures | Medium | Clean pros/cons block above or below the listicle. |
| 9 | Generic "How to apply" playbook | C3 (per-comp), C4 | C3 has per-competition application steps | Medium | 200-300 word section: register early, prepare a 90-sec to 4-min pitch video, finance model, deck, advisor letters. |
| 10 | Equity vs non-dilutive framing | C4 | C4 notes cap-table dilution comparison | Medium | One paragraph + one sentence in intro: "All prizes here are non-dilutive". |
| 11 | Add PAA "Are business plan competitions worth it?" | C4 | PAA + WebSearch | Medium | Add to FAQ. |
| 12 | Add PAA "How much can you win?" | C3, C4 | PAA + WebSearch + "business plan competition grant" query | Medium | Add to FAQ; cite Rice's $1M total + median prize range. |
| 13 | Add PAA "What do judges look for?" | C4 | PAA + WebSearch | Medium | Reuse the 5-criteria from gap #3. |
| 14 | Methodology note ("How we picked these 20") | C4 (Editorial Standards) | E-E-A-T transparency | Low | 80-word note above the listicle. |
| 15 | Pitch video production tips callout | C4 | C4: $30 lapel mic, multiple takes, audio over lighting | Low | A 100-word sidebar/callout box. |

**Important caveat:** C2 (`how-to-write-the-competition-section…`) is a different intent and is NOT used for content gap analysis here — its only relevance is the cannibalization fix in §3. The HS-variant page (C3) is used for E-E-A-T + structural patterns only; we should NOT clone its competition list onto the target page (that would re-create cannibalization).

---

## 7. LINKS & BACKLINKS

### 7A. Internal Link Issues

The target page has 68 in-content internal links. Spot-check findings:
- **4 separate links to `/download/business-plan-template`** within the article body. Each one is a CTA-style link with similar anchor ("Download Now: Free Business Plan Template" / "Business plan template" / etc.). Three of them are intentional CTAs in `.cta-blocks` (rendered as banners), one is inline within content. Likelihood of value loss is low (these are template/funnel CTAs, not topical interlinks) but the page's link equity is being heavily concentrated on a single destination URL. **Recommendation:** keep the in-content CTA links; consider diversifying 1-2 of them to deeper template/example pages (e.g., a `/sample-business-plans` example matching the user's stage).
- Otherwise the in-content internal link inventory looks healthy — links go to relevant blog, template, and example pages.

### 7B. Internal Links to ADD (to the target page)

**⚠️ Rule 12 applied:** every URL below is verified via GSC or via existing internal links on this site (sources noted).

| Anchor Text | Target URL | Where to Place | Why | Source |
|------------|-----------|----------------|-----|--------|
| business plan competitions | [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions) — add link FROM [/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | Near intro, in a "Looking for a list of competitions?" callout | Resolves cannibalization for the head term (this page outranks target by 17 positions on the head query with 0 clicks) | GSC (`step1b-cannibalization.json`) |
| business plan competitions for high school students | n/a — keep the link FROM [/blog/business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) TO target with anchor "business plan competitions (open-stage)" | Near intro of HS page | Disambiguates the two listicles in Google's eyes; restores head-term equity to the open-stage target page | GSC (`step1b-cannibalization.json`) |
| how to write the competition section of a business plan | [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | In a new "How to write a winning business plan for a competition" section on TARGET | Tightens topic cluster; gives writers a one-click jump to the competitor-analysis methodology | C2 enrichment + scraper internal-links inventory |
| business plan template | [https://upmetrics.co/download/business-plan-template](https://upmetrics.co/download/business-plan-template) | Keep existing 4 CTA placements (see 7A) | Funnel link to product | Existing internal link |
| sample business plans | [https://upmetrics.co/sample-business-plans](https://upmetrics.co/sample-business-plans) | New: add inside the new "winner case studies" section | Anchors a related "by industry" example resource | Existing internal link (location: outside-content currently — promote into content) |

### 7C. Pages That Should Link TO This Page (incoming internal links)

**⚠️ Rule 12 applied:** sources verified via the target page's own internal-links list (these are pages the site already cross-links into the target's neighborhood) plus the GSC cannibalization data.

| Source Page URL | Where to Add | Suggested Anchor | Source |
|----------------|----------------------------------------|----------------------------------|--------|
| [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | Intro paragraph + a "Looking for a competition to enter?" callout above the FAQ | business plan competitions | GSC cannibalization |
| [https://upmetrics.co/blog/business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) | "Looking for open-stage / non-high-school competitions?" callout in intro | business plan competitions for founders & startups | GSC cannibalization |
| [https://upmetrics.co/sample-business-plans](https://upmetrics.co/sample-business-plans) | Inside any "ready to enter a competition?" sidebar or related-resource block | Top business plan competitions in 2026 | Existing internal link inventory |
| [https://upmetrics.co/download/business-plan-template](https://upmetrics.co/download/business-plan-template) | Bottom of the download page (related resources) | Top business plan competitions in 2026 | Existing internal link inventory |

### 7D. External Link Issues

The page has 25 outbound links, all of which point to competition organizer pages (RBPC, MIT 100K, NIBS, etc.) or Upmetrics social profiles. Issues to verify (spot-check during the content update):
- **`https://www.uoic.org/`** (New Venture Championship) — domain ownership/redirect status should be verified; some past New Venture Championship listings have moved.
- **`https://www.herox.com/IOT-WTINNOVATION21`** (13th IOT/WT World Cup) — the `INNOVATION21` slug suggests this is a 2021 challenge; needs re-verification of current relevance.
- **`https://codelaunch.com/tag/startup-competition/`** (CodeLaunch second link) — a tag archive page is not as authoritative as the rules page; consider deduping with the existing `codelaunch.com/startups/rules/`.
- **`https://www.facebook.com/upaborant/`, `https://twitter.com/upaborant`** — handles look mis-typed (should be `upmetricsai` / `upmetricsapp` / similar). These are footer/social links and may not be on this content area, but worth verifying.

| # | Anchor Text | Target URL | Issue | Fix |
|---|------------|-----------|-------|-----|
| 1 | (none — implicit competition link) | https://www.uoic.org/ | Verify domain ownership & content currency | Replace with closest current sponsor page (UO LCB) or remove |
| 2 | (none — implicit competition link) | https://www.herox.com/IOT-WTINNOVATION21 | URL slug is `INNOVATION21` — likely a 2021 archive | Re-verify; replace with most recent IOT/WT competition page or remove |
| 3 | (none) | https://codelaunch.com/tag/startup-competition/ | Duplicate-ish CodeLaunch link (already linked to `/startups/rules/`) | Dedupe |
| 4 | (none) | https://www.facebook.com/upaborant/, https://twitter.com/upaborant | Possibly incorrect Upmetrics social handles | Confirm correct handles and update if wrong |

No `COMPETITOR_DOMAINS` (LivePlan, Bplans, etc.) appear in the external link list. ✅

### 7E. Backlink Gap

| Metric | Target Page | Top SERP Competitor (Rice, pos 1) | Top Listicle (Growthink, pos 4) |
|--------|------------|----------------------|----------------------------------|
| Referring Domains (live) | 1 | 317 | 5 |
| Total Backlinks (all-time / live) | 16 all-time / 1 live | — | — |
| URL Rating | — | 13 | 4 |
| Domain Rating | (Upmetrics DR — out of scope) | 86 | 71 |

**⚠️ Sanity note:** Ahrefs returned only `live=1`, `live_refdomains=1` for the target URL in `mode=exact`, and `all_time=16`, `all_time_refdomains=12` — so there has been some historical link decay. Worth a manual Ahrefs UI check.

**Gap summary:**
- We are not competing with Rice (DR 86, 317 refdomains) on link authority — we are competing with **Growthink, the only other listicle**, which has just 5 referring domains. **The link gap to overtake Growthink is small (4-7 high-quality refdomains).**
- Realistic path: 8-15 new referring domains over the next 6 months via (a) digital PR roundups, (b) startup-publication mentions, (c) university entrepreneurship-center "resource" page placements.
- One concrete play: pitch this page to the editor of any university blog that already runs a "business plan competition prep" post (TechCrunch's `/startup-battlefield`, MIT, Baylor, UChicago Polsky already on our outbound list — reciprocal links are reasonable to request).

---

## 8. E-E-A-T & CITATIONS

Read from `verified-facts.json`: `author_present=true (Upmetrics)`, `author_has_bio=false`, `author_has_photo=false`, `date_visible_on_page=true (Updated May 6, 2026)`, `has_downloadable_templates=true`, `schema_types_found=[Article, WebPage, ImageObject, BreadcrumbList, WebSite, Organization, Person, BreadcrumbList, FAQPage]`. *(Note: `Article` and `Person` are listed inside nested schema graphs but no top-level Article schema block is being used to mark up the post itself — verified via `step1a-target-page.json`.)*

### E-E-A-T Signal Comparison (gaps only)

| Signal | Target Page | Best Competitor | Gap? |
|--------|------------|----------------|------|
| Named human author | ❌ "Upmetrics" generic byline | ✅ Vinay Kevadia (C3, same site!), Eliot Reynolds with credentials (C4) | ✅ Yes — assign a named author |
| Author bio (2-3 lines) | ❌ None | ✅ C3, C4 | ✅ Yes |
| Author photo / headshot | ❌ None | ✅ C3, C4 | ✅ Yes |
| Author credential/role (e.g., "Senior Legal Researcher") | ❌ | ✅ C4 | ✅ Yes |
| Expert quotes / named sources | ❌ (zero external citations in body text) | ✅ C4 cites HBR, Steve Blank, MassChallenge, Paychex, SBE Council, Flowlu, Rice | ✅ Yes — needs 3-5 citations |
| Methodology / "how we picked" disclosure | ❌ | ✅ C4 (Editorial Standards) | ✅ Yes |
| Per-competition prize-data source citations | partial | ✅ C1 | ✅ Yes |
| Last-verified date on the listing | ❌ (only "Updated" date) | ✅ implied via 2026 dates on C3, C4 | ✅ Yes — add "Data verified [date]" |

### Citation Audit

The target page has **25 outbound links to competition organizer pages** — appropriate primary sources for the named competitions. But within the article *body text*, there are **zero external citations supporting factual claims** (stats, prize amounts, win rates). All the "facts" are implicit.

| Citation | URL Status | Source Quality | Issue (if any) |
|----------|-----------|---------------|----------------|
| (no external citation links in body text) | n/a | n/a | All 25 external links are to the competitions themselves, not to supporting sources for statements about competitions in general. Need to add citations for the "How to win" / "What judges look for" / prize-range statements added in §6. |

### Unsourced Claims (in current page text)

| Unsourced Claim (paraphrased; verify exact text during update) | Location | Recommended Source URL |
|------------------------------|----------|----------------------|
| Specific prize amounts ("up to $25,000…", "$100,000 prize…") for each competition | Per competition (H3-level Rewards bullet) | Cite each competition's own rules page (already linked — just add the citation pattern: "Prize: $X — source: rbpc.rice.edu") |
| General benefit claims about competitions (mentorship, validation, funding) | "What is a business plan competition?" and Conclusion | Cite HBR / MassChallenge / Forbes |
| Claims about who can participate / eligibility | "Frequently Asked Questions" → "Do I need to have a complete business…" | Cite NIBS or Rice eligibility rules pages |

**→ Broken link fixes go in §2 Master Action Table. New citation recommendations go in the Content Update Brief (Section 14E annotated outline).**

---

## 9. APPENDIX

### Ahrefs API Consumption Log

| # | Call | Endpoint | Units |
|---|------|----------|-------|
| 1 | Organic Keywords | `site-explorer-organic-keywords` | 50 (returned 0 keywords — min charge) |
| 2 | SERP Overview | `serp-overview` | 110 |
| 3 | Keyword Overview | `keywords-explorer-overview` | 50 |
| 4 | Backlinks Stats | `site-explorer-backlinks-stats` | 50 |
| | **Total** | | **260** |

### Files saved (this audit)

- `./workspace/business-plan-competitions/audit-data/step1a-target-page.json`
- `./workspace/business-plan-competitions/audit-data/step1a-page-text.txt` (2,222 words)
- `./workspace/business-plan-competitions/audit-data/verified-facts.json`
- `./workspace/business-plan-competitions/audit-data/step1b-gsc-data.json` (272 queries)
- `./workspace/business-plan-competitions/audit-data/step1b-gsc-trends.json` (2,000 query+date rows)
- `./workspace/business-plan-competitions/audit-data/step1b-cannibalization.json` (5 queries checked)
- `./workspace/business-plan-competitions/audit-data/step1c-organic-keywords.json`
- `./workspace/business-plan-competitions/audit-data/step1c-serp-overview.json`
- `./workspace/business-plan-competitions/audit-data/step1c-keyword-overview.json`
- `./workspace/business-plan-competitions/audit-data/step1c-backlinks.json`
- `./workspace/business-plan-competitions/audit-data/step1c-serp-features.json`
- `./workspace/business-plan-competitions/audit-data/step1d-competitor-{1,2,3,4}.json` (enriched)
- `./workspace/business-plan-competitions/audit-data/step1d-competitor-{1,2,3,4}-text.txt`

---

