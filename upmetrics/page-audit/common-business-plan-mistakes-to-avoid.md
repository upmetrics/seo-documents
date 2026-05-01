# SEO Page Audit — Common Business Plan Mistakes to Avoid

**Page URL:** [https://upmetrics.co/blog/common-business-plan-mistakes-to-avoid](https://upmetrics.co/blog/common-business-plan-mistakes-to-avoid)
**Primary Keyword:** business plan mistakes
**Audit Date:** 2026-05-01
**Country:** United States
**Brand:** Upmetrics

---

## 1. Executive Dashboard

### Page Snapshot

| Metric | Value | Status |
|---|---|---|
| Primary keyword | business plan mistakes | — |
| US search volume (Ahrefs) | 150/mo | Low-volume informational keyword |
| Keyword difficulty (Ahrefs) | 1 | 🟢 Trivially easy — top 10 should be reachable |
| Traffic potential (Ahrefs) | ~50/mo | Long-tail variants matter as much as the head term |
| Current best position (GSC, primary KW) | 37.7 (US, 6 mo) | 🔴 Page 4 — invisible |
| GSC clicks (US, 6 mo) | 1 | 🔴 Effectively no traffic |
| GSC impressions (US, 6 mo, all queries) | ~865 | Demand exists; rankings don't |
| Ahrefs ranking keywords (vol ≥100) | 0 | 🔴 Not ranking for anything in Ahrefs database |
| Word count | 1,569 | 🟡 Below #1 LivePlan (2,284) |
| Backlinks (live / refdomains) | 1 / 1 | 🔴 Very thin link profile |
| Author E-E-A-T | "Upmetrics" generic, no bio, no photo | 🔴 Weakest E-E-A-T signal in the SERP |
| Title length | 61 chars | ✅ |
| Meta description length | 165 chars | 🟡 Slightly over 160 |
| Schema | Article, FAQPage, BreadcrumbList, Person, Organization, WebPage | ✅ |
| Canonical | Self-referencing | ✅ |
| Indexable | Yes (no noindex) | ✅ |

### Top 3 Problems

1. **Position 37.7 on a KD-1 keyword is a content/authority gap, not a difficulty problem.** The keyword is trivially easy (KD 1, vol 150) yet the page sits on page 4. Every top-10 result is a higher-authority domain (DR 80-95: LivePlan, URI SBDC, Reddit, Emory, US Chamber). Upmetrics has only 1 referring domain to this URL — competitors have 4-13. Internal linking and E-E-A-T are the leverage points.

2. **Author E-E-A-T is the weakest in the SERP.** The byline reads "Upmetrics" (a brand, not a person) with no bio, no photo, no credentials. URI's page cites named SBDC counselors (Manuel Batlle, Josh Daly); w3financialgroup names a real author (Kelly Galambos). Google treats this as a YMYL-adjacent topic for entrepreneurs — author credibility moves rankings.

3. **Content depth and angle gaps vs LivePlan #1.** LivePlan covers 17 mistakes with a strong "the biggest mistake is not planning at all" framing, multiple short-answer summaries near each H2, and a Henry Ford analogy. Upmetrics covers 13 with thinner per-mistake examples and only 1 external citation (Forbes 7-seconds). Adding 4 missing mistake categories (cash flow / contingency, ignoring risks, ignoring the customer, lack of measurable goals), tightening the intro, and adding 3-5 named external citations would close the visible gap.

### Traffic Opportunity (1-liner)

If the page reaches positions 5-8 on the primary keyword and 15-25 long-tail variants currently sitting at positions 30-90, expected lift is ~40-80 monthly clicks (from 1 today) — small in absolute terms, but a 40-80× multiple and a clear win at KD 1.

---

## 2. Master Action Table

All non-content SEO actions for this page, sorted by priority. Content rewrites/additions/edits are in the **Content Update Brief** (separate `.docx`).

| # | Priority | Action | Why (data) | Section ref |
|---|----|--------|---------|---------|
| 1 | P1 | Rewrite meta description to 150-158 chars and pull primary KW into the first 60 chars | Current (165 chars) is over the snippet limit; opens with "Discover the 13 common…" — generic. KD 1 with no traffic = SERP CTR is gated by snippet quality. See Title & Meta Copy block below. | §5 (technical), §2 copy |
| 2 | P1 | Build a real author byline — assign a named expert with credentials, photo, and a 50-80 word bio block | Author currently shows "Upmetrics" with `hasBioSection=false`, `hasPhoto=false` (verified-facts.json). Every top-10 SERP result with a real byline outranks this page. URI cites Manuel Batlle (SBDC counselor) and Josh Daly; w3financialgroup names Kelly Galambos. | §8 |
| 3 | P1 | Add the missing alt text to the AI assistant image (`ai-assistant-blog-image-1-282x240.png`) under heading "9. Poor writing and presentation" | Scraper found 1 of 2 content images missing alt | §5 |
| 4 | P1 | Internal-link 8-12 high-authority Upmetrics pages TO this page using anchor text variants of "business plan mistakes" / "common business plan mistakes" | Page has only 1 backlink (Ahrefs) and Ahrefs reports 0 ranking keywords with vol ≥100 — internal authority transfer is the fastest lever. Source pages must come from verified GSC/Ahrefs/internal-link data only. | §7C |
| 5 | P1 | Tighten title to 55-58 chars and front-load primary KW; current is 61 chars, brand suffix eats space | Title: "13 Common Business Plan Mistakes to Avoid in 2026 - Upmetrics" (61). Cleaner front-load opens room for a power word. See Title & Meta Copy block below. | §2 copy |
| 6 | P2 | Replace the 4 social-only external links (`youtube.com/c/Upmetrics`, `facebook.com/upaborant`, `twitter.com/upaborant`, `linkedin.com/company/upmetrics`) with high-authority editorial citations woven into the article body (SBA, Forbes, HBR, BLS, US Chamber) | Page currently has 5 external links — 4 are social (don't count as citations) and 1 is Forbes (the "7 seconds" stat). Top competitors have 1-3 substantive external citations each. Source: scraper externalLinks. | §8 |
| 7 | P2 | Add `og:image` and verify Twitter card image are configured in WordPress for this post | `ogTagsFound=true` but the social preview is brand-default; a custom 1200×630 social card improves social CTR | §5 |
| 8 | P3 | Audit the 3 in-page template/sample CTAs (currently 3 found) for placement variety; current 2 of 3 sit close together in-content | `downloadableTemplates` shows 2 in-content + 1 outside-content; the outside-content one is the actual template download | §5 |

### Title & Meta Copy Block (authoritative — used by Update Brief)

**Current title** (61 chars):
`13 Common Business Plan Mistakes to Avoid in 2026 - Upmetrics`

**Recommended title options** (front-loaded primary KW, 55-58 chars, year and brand kept):

| # | Title | Chars | Why |
|---|-------|-------|-----|
| A | `13 Business Plan Mistakes to Avoid in 2026 \| Upmetrics` | 53 | Primary KW front-loaded, drops "Common" (low-CTR filler), keeps year and brand |
| B | `Business Plan Mistakes: 13 Costly Errors to Avoid (2026)` | 56 | Lead with exact KW + curiosity hook ("costly errors") |
| C | `13 Common Business Plan Mistakes (and How to Avoid Each)` | 56 | Listicle promise + "how to avoid each" parallels Reddit/SBDC SERP framing |

**Recommended:** Option B — leads with exact-match primary KW, sets a stakes hook, fits 56 chars.

**Current meta description** (165 chars):
`Discover the 13 common business plan mistakes entrepreneurs must avoid at all costs. Also, learn how business planning software can help you avoid the same mistakes.`

**Recommended meta description options** (150-158 chars, primary KW within first 60 chars):

| # | Description | Chars |
|---|-------------|-------|
| A | `13 business plan mistakes that quietly kill investor confidence — and the fixes founders use to write a plan that actually gets funded.` | 135 |
| B | `Avoid the 13 business plan mistakes that wreck investor pitches, sink financial projections, and stall funding — with quick fixes for each.` | 138 |
| C | `Business plan mistakes cost founders funding every day. Here are the 13 most common errors — and a 30-second fix you can apply to each.` | 135 |

**Recommended:** Option B — primary KW in first 8 chars, names 3 specific stakes (investor pitches, financial projections, funding), promises a fix.

---

## 3. Keyword & Ranking Analysis

### 3A. Top 10 Queries (GSC, US, last 6 months)

Sorted by impressions. Page has 1 click total — all rows show meaningful impressions but near-zero CTR because positions are deep.

| # | Query | Impr | Clicks | CTR | Avg position | Trend |
|---|-------|------|--------|-----|--------------|-------|
| 1 | business plan mistakes (primary) | 513 | 1 | 0.2% | 37.7 | Flat (insufficient click data) |
| 2 | common business pitfalls | 65 | 0 | 0% | 61.5 | Flat |
| 3 | avoiding business pitfalls | 44 | 0 | 0% | 84.3 | Flat |
| 4 | 3 common mistakes to avoid when writing a business plan | 41 | 0 | 0% | 11.5 | Flat — striking distance |
| 5 | what are some common mistakes to avoid when writing a business plan | 32 | 0 | 0% | 33.2 | Flat |
| 6 | common mistakes in business | 18 | 0 | 0% | 47.4 | Flat |
| 7 | how to avoid common startup business plan mistakes | 13 | 0 | 0% | 39.6 | Flat |
| 8 | common business plan errors | 12 | 0 | 0% | 49.0 | Flat |
| 9 | how long should a business plan be | 9 | 0 | 0% | 1.0 | Position 1 — wrong intent (see §3C) |
| 10 | common pitfalls in business strategy | 8 | 0 | 0% | 73.6 | Flat |

> Trend column is qualitative because page has only 1 click in 6 months — month-by-month variance is noise, not signal.

### 3B. Striking-Distance Queries (positions 5-15)

| Query | Impressions | Position | What it tells us |
|-------|-------------|----------|------------------|
| 3 common mistakes to avoid when writing a business plan | 41 | **11.5** | One position-1 push could capture 4-8 clicks/month. The page literally answers this — needs a clear "3 most common" callout near the top. |
| common errors in business plan formulation | 2 | 12 | Tail variant — addressed naturally by improving the listicle |
| bad business plan example | 7 | 12.3 | Examples are missing on the page — no failed-plan walkthrough |
| common mistakes in business plans | 2 | 13 | Tail variant |
| presenting a business plan with a unique format could be a mistake because | 1 | 14 | Educational/quiz query — minor |
| common mistakes in business planning | 1 | 8 | Tail variant — close to page 1 |

**Action:** Add a "3 most common business plan mistakes" sub-callout near the top of the listicle and an "example of a bad business plan" mini-section. Both are addressed in the Update Brief.

### 3C. Cannibalization Check

The primary KW and top 5 high-impression queries were checked for other Upmetrics URLs ranking.

| Query | Primary URL impr | Other URLs ranking | Cannibalization risk |
|-------|------------------|---------------------|----------------------|
| business plan mistakes | 513 | [/blog/business-plan-components](https://upmetrics.co/blog/business-plan-components) (1 impr, pos 13), [/blog/common-financial-projections-mistakes](https://upmetrics.co/blog/common-financial-projections-mistakes) (3 impr, pos 62) | 🟢 None — stray impressions only |
| common business pitfalls | 65 | None | 🟢 None |
| avoiding business pitfalls | 44 | None | 🟢 None |
| 3 common mistakes to avoid when writing a business plan | 41 | None | 🟢 None |
| what are some common mistakes to avoid when writing a business plan | 32 | None | 🟢 None |

**Verdict:** No real cannibalization. The single appearance of `/blog/common-financial-projections-mistakes` at position 62 (3 impressions) is a tangentially-related sibling page — not a threat. Internal-link from that page TO this page using anchor "business plan mistakes" to consolidate signal (see Section 7).

---

## 4. SERP & Intent Analysis

### Intent Classification

**Intent:** Informational — listicle-driven. Searchers want a numbered, scannable list of mistakes with explanations. Every top-10 result is a listicle (5, 7, 13, 17 mistakes). Reddit at position 3 confirms users also want anecdotal/community angles.

### Angle Derivation (no user-supplied angle)

The SERP rewards three things:
1. **Numbered listicles** with clear H2/H3 hierarchy (LivePlan 17 H2s, w3financialgroup 15 H2s).
2. **Authority framing** — SBDC, US Chamber, regional small-business centers dominate. Implication: brand authority + named expert > generic blog post.
3. **A "biggest mistake" framing** — LivePlan opens with "the biggest business plan mistake is not planning at all" and gets position 1. URI opens with "not researching the market." Upmetrics already does this well in its first H2 — keep and strengthen.

**Confirmed angle for the rewrite:** A founder-facing listicle of 13-17 business plan mistakes, each paired with a 1-line "quick fix," led by a strong "the biggest mistake" intro, and grounded in named expert commentary + 3-5 substantive external citations. No tool-pitch in the body — the existing CTA placement is fine.

### SERP Features (US, primary KW)

| Feature | Present? | Notes |
|---------|----------|-------|
| Featured snippet | No | Opportunity — see §4 below |
| AI Overview | [UNABLE TO CONFIRM — manual check recommended] | Worth a manual check; if present, page should target an "is/are" definition near top |
| People Also Ask | Yes (4 questions at ~position 9) | "What are the common errors in business plan?", "What are the 3 C's of a business plan?", "Why do 90% of small businesses fail?", "What are the 5 P's of a business plan?" — the page does NOT answer the latter three. Add to FAQ section. |
| Reddit / forum | Yes (position 3) | r/Startup_Ideas thread — confirms community-style answers rank. Tighten the page's tone to feel less corporate. |
| Image pack | No | — |
| Video carousel | No | — |
| PDF in top 10 | Yes (Emory at position 4) | Indicates Google rewards downloadable assets — Upmetrics already has 3 template links in-content (verified-facts.json: `has_downloadable_templates=true`) ✅ |

### Featured Snippet Opportunity

No featured snippet currently appears for the primary KW. The PAA question "What are the common errors in business plan?" is unanswered with a tight definition in the SERP. **Insertion point:** rewrite the existing first H2 ("What is the biggest mistake when creating a business plan?") to also include a 40-50 word direct answer to "What are the most common business plan mistakes?" — formatted as a tight bullet list of the top 3-5. This is the most realistic snippet target.

---

## 5. Technical SEO (Failures Only)

| # | Issue | Evidence | Severity |
|---|-------|----------|----------|
| 1 | Meta description over snippet limit | 165 chars, target 150-158 (verified from scraper `metaDescriptionLength`) | P1 — see §2 copy block |
| 2 | Image missing alt | `ai-assistant-blog-image-1-282x240.png` under heading "9. Poor writing and presentation" — `hasAlt=false` (scraper `contentImages.details`) | P1 |
| 3 | Title slightly long for safe rendering | 61 chars (Google truncates ~58-60 in many SERPs) | P1 — see §2 copy block |
| 4 | External citation profile is thin | Only 5 external links; 4 are social profiles, only 1 (Forbes) is a real citation | P2 — see §2 row 6 and §8 |
| 5 | `og:image` exists but generic; consider article-specific 1200×630 social card | `ogTagsFound=true` but no per-post image | P2 |

**Passing checks (not listed):** canonical self-referencing, no noindex, schema present (Article + FAQPage + BreadcrumbList + Person + Organization + WebPage), publish + modified dates in meta and visible on page, OG tags found, HTTPS, mobile-rendered (scraper succeeded without UA workaround), 76 internal links present, 3 downloadable templates in-content.

> Title and meta rewrites live in **§2 (Title & Meta Copy block)** — the authoritative source for the Update Brief's `meta_titles` / `meta_descriptions` fields.

---

## 6. Content Gaps & Competitor Depth

### 6A. Content Depth Comparison

| Property | Upmetrics (target) | LivePlan #1 | URI #2 | US Chamber #10 | w3financial #6 | Maryland WBC #8 | Sunrise #5 |
|----------|---|---|---|---|---|---|---|
| Word count | 1,569 | **2,284** | 952 | 797 | 1,887 | 526 | 330 |
| Mistakes covered | 13 | 17 | 7 | 7 | 10 | 5 | 5 |
| H2s | 4 | 5 | 1 | 2 | 15 | 0 | 1 |
| Has FAQs | Yes (3) | Yes (2) | No | No | Yes (3) | No | No |
| Tables/visuals | 2 imgs | 5 | 0 | 1 | 0 | 0 | 0 |
| External citations | 1 | 3 | 5 | 3 | 0 (regulatory only) | 0 | 3 |
| Has named author | No (brand only) | No | No (cites named SBDC counselors in body) | No | Yes — Kelly Galambos | No | No |
| DR | (Upmetrics ~70+) | 80 | 82 | 89 | 16 | 38 | 42 |
| Live referring domains to URL | 1 | 4 | 13 | 1 | 6 | 1 | 2 |

### 6B. Competitor Heading Map (by mistake category)

Mistakes covered by each competitor vs. the target page. ✅ = covered, blank = missing.

| Mistake / topic | Upmetrics | LivePlan | URI | US Chamber | w3financial | Maryland WBC |
|-----------------|:--:|:--:|:--:|:--:|:--:|:--:|
| Not planning at all (biggest mistake) | ✅ | ✅ | | | | |
| Poor / weak executive summary | ✅ | ✅ | | | ✅ | |
| Targeting wrong audience / not tailoring | ✅ | ✅ | | | ✅ | ✅ |
| Insufficient market research | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Unrealistic financial projections | ✅ | ✅ | ✅ | | ✅ | ✅ |
| Ignoring or downplaying competition | ✅ | ✅ | ✅ | ✅ | ✅ | |
| Weak marketing strategy | ✅ | ✅ | | | ✅ | |
| Not highlighting team / management | ✅ | ✅ | ✅ | | ✅ | |
| Poor writing / presentation | ✅ | ✅ | | ✅ | | ✅ |
| Incomplete / missing financial statements | ✅ | ✅ | | | ✅ | |
| Too much information / over-stuffing | ✅ | ✅ | | ✅ | | |
| Inconsistency across plan sections | ✅ | ✅ | | | ✅ | |
| Unclear exit strategy | ✅ | ✅ | | | | |
| **Cash flow / contingency planning** | 🆕 | ✅ | | | ✅ | |
| **Ignoring business risks** | 🆕 | ✅ | | ✅ | | |
| **Ignoring the customer** | 🆕 | | | ✅ | | |
| **Lack of measurable goals / KPIs** | 🆕 | ✅ | | | | |
| **Underestimating costs / budget** | 🆕 | ✅ | | | ✅ | |
| **Not updating the plan over time** | 🆕 | ✅ | | | ✅ | |
| **Bad / pessimistic OR overly optimistic tone** | 🆕 | ✅ | | ✅ | | |

### 6C. Topic Gap Detail (NEW sections to add)

These topics appear on multiple top-10 competitors but are missing or underdeveloped on the target. Full enrichment in Update Brief Section 14E.

1. **Cash flow / contingency planning** — covered by LivePlan and w3financialgroup. Most relevant for the founders who actually pitch plans. (NEW H3, ~150 words)
2. **Ignoring business risks** — LivePlan and US Chamber both flag this; PAA-adjacent. (NEW H3, ~120 words)
3. **Lack of measurable goals / KPIs** — LivePlan stresses "ambition vs execution." (NEW H3, ~120 words)
4. **Underestimating costs / budget** — LivePlan + w3financialgroup. Distinct from financial projections (which is forward-looking revenue). (NEW H3, ~120 words)
5. **Not updating the plan** — LivePlan + w3financialgroup; reframes the plan as a living document. (NEW H3, ~100 words)
6. **PAA gap: "What are the 3 C's of a business plan?"** — none of the FAQs address this. (Add to existing FAQ block)
7. **PAA gap: "What are the 5 P's of a business plan?"** — same. (Add to existing FAQ block)
8. **PAA gap: "Why do 90% of small businesses fail?"** — frame the "ignoring risks" section to answer this directly with a stat-led intro line.

> All NEW sections, EDIT recommendations, and rewrites are detailed in the Content Update Brief (`.docx`).

---

## 7. Links & Backlinks

### 7A. Internal Links Already on Page (issues only)

The page has 76 internal links (mostly nav/footer/related). No internal-linking issues flagged — internal anchor distribution is healthy. The action is to add MORE links TO this page (see 7C).

### 7B. Internal Links to ADD (from this page)

Two contextually-relevant pages already appear in the page's existing internal links:

| Anchor (in-context) | Link target | Why |
|---|---|---|
| "executive summary" (in mistake #2) | [https://upmetrics.co/blog/business-plan-executive-summary](https://upmetrics.co/blog/business-plan-executive-summary) (verify exists via WP MCP if not already linked) | Existing internal link target unverified — see note below |

> **Verification needed:** I am NOT recommending unverified URLs per Rule 12. The full set of "internal links to add" suggestions belongs in the Update Brief — they should be sourced by querying WordPress MCP for real Upmetrics pages on these topics: executive summary, financial projections, market research, competitor analysis, business plan template. The Update Brief instructs the writer to verify each link target before insertion.

### 7C. Pages That Should Link TO This Page (from verified data)

The single most impactful action for this page. Source URLs below are verified — they appear in GSC `query+page` data, meaning they exist and are indexed.

| Source page (verified-existing) | Anchor text suggestion | Why |
|---|---|---|
| [https://upmetrics.co/blog/business-plan-components](https://upmetrics.co/blog/business-plan-components) | common business plan mistakes to avoid | Sibling page already ranks at position 13 for "business plan mistakes" — pass topical signal |
| [https://upmetrics.co/blog/common-financial-projections-mistakes](https://upmetrics.co/blog/common-financial-projections-mistakes) | 13 common business plan mistakes | Sibling "mistakes" page; cross-link to consolidate the topic cluster |

**Additional internal link sources** must come from verified Upmetrics pages — the Update Brief asks the writer/SEO to query WordPress MCP for Upmetrics pages on these topics: business plan template, sample business plans, executive summary, financial projections, market analysis, business plan format, business plan basics, how to write a business plan. Then verify each in GSC/Ahrefs/WP-MCP before adding the link.

### 7D. External Links Currently on Page (issues only)

The page has 5 external links:

| URL | Issue |
|---|---|
| [forbes.com/.../you-have-7-seconds-to-make-a-first-impression](https://www.forbes.com/sites/serenitygibbons/2018/06/19/you-have-7-seconds-to-make-a-first-impression-heres-how-to-succeed/?sh=66a5554756c2) | 🟢 Real citation — keep, but verify URL still resolves (2018 article) |
| [youtube.com/c/Upmetrics](https://www.youtube.com/c/Upmetrics) | 🔴 Brand social — does not function as an editorial citation |
| [facebook.com/upaborant](https://www.facebook.com/upaborant/) | 🔴 Brand social |
| [twitter.com/upaborant](https://twitter.com/upaborant) | 🔴 Brand social |
| [linkedin.com/company/upmetrics](https://www.linkedin.com/company/upmetrics/) | 🔴 Brand social |

**Action:** Add 3-5 substantive external citations (SBA, BLS, Forbes, HBR, US Chamber) — see §8.

### 7E. Backlink Gap

| Page | DR | Live RDs to URL |
|------|----|----|
| Upmetrics target | (~70+) | **1** |
| URI #2 | 82 | 13 |
| w3financialgroup #6 | 16 | 6 |
| LivePlan #1 | 80 | 4 |
| sunrisecounty #5 | 42 | 2 |

The page-level link gap is real but small in absolute terms (need to close from 1 → 5-6 to be SERP-competitive). The fastest path is internal authority transfer (§7C). Outreach for backlinks at this traffic level is not high-leverage; revisit after the content rewrite.

---

## 8. E-E-A-T & Citations

### 8A. E-E-A-T Signal Comparison (gaps only)

| Signal | Target | Best-in-SERP | Gap |
|--------|--------|---------------|-----|
| Named human author | ❌ "Upmetrics" generic | ✅ w3financialgroup (Kelly Galambos), URI cites Manuel Batlle / Josh Daly inline | **Yes — biggest E-E-A-T gap** |
| Author bio block | ❌ `hasBioSection=false` | n/a (most SERP results lack bios too) | Yes — opportunity to differentiate |
| Author photo | ❌ `hasPhoto=false` | n/a | Yes — pairs with bio |
| Inline expert quotes | ❌ none | ✅ URI quotes 2 named SBDC counselors | Yes |
| Substantive external citations | 🟡 1 (Forbes) | ✅ 3-5 across competitors | Yes — see 8B |
| Schema (Person, Organization) | ✅ Both present | n/a | None |
| Publish + modified dates | ✅ Visible (Updated April 24, 2026) | n/a | None |

### 8B. Citation Audit — New Citations to Add

The page makes several factual claims with no source. The Update Brief includes specific in-section citation tasks. High-value targets:

| Claim on page (location) | Citation to add (suggested source — verify URL before insertion) |
|---|---|
| "7 seconds to make a first impression" (existing — Forbes 2018) | ✅ Already cited — verify URL still resolves |
| "Most business plans fail because of poor planning / vague goals" (intro and #1) | SBA ([sba.gov](https://www.sba.gov/business-guide/plan-your-business/write-your-business-plan)) data on small business survival, OR BLS Business Employment Dynamics |
| Unrealistic financial projections section | HBR or Investopedia source on common projection errors |
| Ignoring competition section | A SCORE / SBDC report on the role of competitive analysis |
| Why most small businesses fail (if "Ignoring risks" section is added) | BLS BED data ("approximately 20% of new businesses fail in the first year") — gives the page a substantive PAA answer |

> All citation insertions are tasked into the Update Brief at the section level. The writer must verify each URL with WebFetch before inserting.

---

## 9. Appendix — Ahrefs API Consumption

| Call | Endpoint | Units used (this audit) |
|------|----------|-----|
| 0 | subscription-info-limits-and-usage (free) | 0 |
| 1 | site-explorer-organic-keywords (with where filter — failed) | 50 |
| 1b | site-explorer-organic-keywords (retry without filter) | 50 |
| 2 | serp-overview | 143 |
| 3 | keywords-explorer-overview | 50 |
| 4 | site-explorer-backlinks-stats | 50 |
| **Total this audit** | | **343** |

> One extra retry call was needed for `site-explorer-organic-keywords` because the `where: "volume>=100"` filter returned an "invalid filter expression" error. Retrying without the filter still returned 0 keywords, confirming the page does not rank for any keyword in Ahrefs' US database. Future audits: verify `where` syntax against Ahrefs docs before the call to avoid the wasted 50 units.

---

*Audit complete. Content actions for the writer are in the accompanying Content Update Brief (`.docx`).*
