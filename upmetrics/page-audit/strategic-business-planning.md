# SEO Page Audit — Strategic Business Planning

**Page:** [https://upmetrics.co/blog/strategic-business-planning](https://upmetrics.co/blog/strategic-business-planning)
**Primary keyword:** strategic business planning
**Brand:** Upmetrics · **Geography:** United States
**Audit date:** 2026-09-23
**Data windows:** GSC 2026-03-22 → 2026-09-19 (US) · Ahrefs US index, 2026-09-22

---

## 1. EXECUTIVE DASHBOARD

### Page Snapshot

| Metric | Value |
|--------|-------|
| URL | [https://upmetrics.co/blog/strategic-business-planning](https://upmetrics.co/blog/strategic-business-planning) |
| Primary Keyword | strategic business planning |
| Primary KW — US Search Volume | 350/mo (Ahrefs) · **Traffic potential: 15,000** |
| Primary KW — Current Position | **68.7** (GSC, US, 6mo avg) · Ahrefs: not ranking |
| Primary KW — Keyword Difficulty | **KD 5** (very low) · CPC $3.50 |
| Title Tag | `Strategic Business Planning: Explained with Examples` (52 chars) |
| Meta Description | `Crafting a strategic business plan is crucial for achieving long-term success. Learn how to create an effective strategy for your business through strategic business planning with our comprehensive guide.` (**204 chars — over limit**) |
| H1 | Strategic Business Planning: Explained with Examples |
| Word Count (article body only) | 1,709 (selector `.blog-content-area`) |
| Internal Links | 89 page-wide · **9 genuinely in-content** (4 blog + 5 product/asset), parsed from `.blog-content-area`. 3 further blog links sit in the related-posts module, not the body. → §7A |
| External Links | 4 — **all 4 are Upmetrics social profiles. Zero editorial citations.** |
| Content Images | 2 (2 with alt / 0 without) |
| Schema Markup | Yes — Article, WebPage, ImageObject, BreadcrumbList, WebSite, Organization, Person, FAQPage |
| Canonical Tag | `https://upmetrics.co/blog/strategic-business-planning` (self-referencing ✅) |
| Page Type | Blog article / guide |
| Content Freshness | Published 2021-12-30 · Modified 2026-07-02 · Visible on page: "Updated July 2, 2026" |
| Author Attribution | "Upmetrics" (brand name, from meta) — **no bio, no photo, no human author** |
| Downloadable Templates/Freebies | 3 detected by the scraper — 1 in-content (`→ Download Now: A SMART Goal Template`), 2 outside content (`400+ sample business plans`, `Business plan template`). The page **also** links in-content to [/strategic-planning-templates](https://upmetrics.co/strategic-planning-templates) and [/features/strategic-planning](https://upmetrics.co/features/strategic-planning) (both verified HTTP 200) — these are not counted in `verified-facts.json` because they are not `/download/` URLs. |

### Top 3 Problems

1. **The page is invisible despite a KD of 5.** Over 6 months it earned 5,321 US impressions across 266 queries and **exactly 0 clicks**, sitting at average position 50–75. Ahrefs shows it ranking for nothing at all. For a keyword this easy, the bottleneck is not competition — it is that the page does not answer what the SERP is asking.
2. **Rankings collapsed immediately after the 2 July 2026 update.** Positions had climbed to 38–42 in June 2026, then fell to 76–86 in July and have stayed there through September. Whatever changed on 2 July made the page worse, and that regression is the single highest-value thing to investigate.
3. **The content answers the wrong questions with the wrong frameworks.** The H2 "Strategic business plan example" contains no example — it lists SOAR, Porter's Five Forces, STEEPLE, NOISE and CORE. Meanwhile every ranking competitor uses SWOT, and the page answers none of the four live PAA questions.

### Traffic Opportunity

> KD 5 at 350/mo head volume but **15,000 traffic potential** for the winning page. The page currently converts 5,321 impressions into 0 clicks. Moving from position ~69 into the top 10 is realistically worth 150–400 clicks/month; a top-3 position on this cluster is worth 600–1,500+. The zero-click baseline means every gain is incremental.

---

## 2. MASTER ACTION TABLE

> Content actions (rewrites, additions, filler removal) are **not** in this table — they live in the Content Update Brief (`.docx`). This table is SEO/technical/link work only.

| # | Priority | Category | Action | Assignee | Details | Section Ref |
|---|----------|----------|--------|----------|---------|-------------|
| 1 | **P1** | Investigation | Diff the page against its pre-2 July 2026 revision and identify what changed | SEO Team | Rankings fell from p38–42 (June) to p76–86 (July–Sept) immediately after the 2026-07-02 modification. Pull the WordPress revision history for post `strategic-business-planning` and compare. If content or headings were removed, restore them. | §3 |
| 2 | **P1** | Meta | Rewrite meta description — current is 204 chars and truncates in SERP | Dev | Copy-paste from Title & Meta Copy block below | §5 |
| 3 | **P1** | Meta | Rewrite title tag to match the three sub-intents Google serves (definition / benefits / how-to) | Dev | Copy-paste from Title & Meta Copy block below | §5 |
| 4 | **P1** | Cannibalization | Resolve overlap with [https://upmetrics.co/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | SEO Team | That page competes on 3 of 6 checked queries, is 63% longer (2,793 vs 1,709 words) and fresher (updated 2026-09-17). Keep both, but sharpen roles: the comparison page owns "business plan vs strategic plan"; the target owns "how to do strategic business planning". Add a reciprocal in-content link from the comparison page back to the target. | §3, §7 |
| 5 | **P1** | E-E-A-T | Replace the "Upmetrics" brand byline with a named human author + bio + photo | Dev / Content | `verified-facts.json` confirms `author_has_bio=false`, `author_has_photo=false`. 5 of 9 competitors carry a named author or a named quoted expert. Person schema is already emitted — populate it with a real person. | §8 |
| 6 | **P2** | Internal Link | Add reciprocal in-content link from [https://upmetrics.co/blog/elements-of-strategic-planning](https://upmetrics.co/blog/elements-of-strategic-planning) to the target page | SEO Team | Anchor: "strategic business planning process". Source: target page's own `internalLinks` array (verified). | §7B |
| 7 | **P2** | Internal Link | Add in-content link from [https://upmetrics.co/blog/how-to-create-a-business-strategy](https://upmetrics.co/blog/how-to-create-a-business-strategy) to the target page | SEO Team | Anchor: "strategic business planning". That page already ranks at position 27 for "business strategy planning" — it can pass relevance. Source: GSC. | §7C |
| 8 | **P2** | Internal Link | Add in-content link from [https://upmetrics.co/blog/strategic-marketing-process](https://upmetrics.co/blog/strategic-marketing-process) to the target page | SEO Team | Anchor: "strategic business planning". Source: target page's own `internalLinks` array (verified). | §7C |
| 9 | **P2** | Technical | Add the four live PAA questions to the existing FAQPage schema | Dev | FAQPage schema already exists — extend it with the 4 PAA questions once the writer adds the answers (see Update Brief). No new schema type needed. | §5 |
| 10 | **P2** | Backlinks | Rebuild the lost link profile — 0 live referring domains, 13 lost | Link Builder | The page historically held 26 backlinks from 13 referring domains; **all are now dead**. First action: run a lost-backlink report on this URL, identify the 13 domains, and pursue reclamation before net-new outreach. | §7E |
| 11 | **P3** | External Link | Add editorial outbound citations — page currently has zero | Content | All 4 external links are Upmetrics social profiles. Competitors at positions 8 and 10 cite sourced research with outbound links. Specific citations are assigned per-section in the Update Brief. | §8 |
| 12 | **P3** | Assets | Commission a strategic-plan comparison graphic and a process diagram | Design | Target has 2 content images. Position-2 competitor has 5 custom diagrams; the Upmetrics comparison page has 9 tables/visuals. | §6A |

### Title & Meta Copy (ready to copy-paste)

```
Title Tag (OLD): Strategic Business Planning: Explained with Examples (52 chars)
Title Tag (NEW): Strategic Business Planning: Steps, Benefits & Examples (55 chars)

Meta Description (OLD): Crafting a strategic business plan is crucial for achieving long-term success. Learn how to create an effective strategy for your business through strategic business planning with our comprehensive guide. (204 chars)
Meta Description (NEW): Strategic business planning explained: what it is, the 5 steps, the 7 core elements, and a full worked example you can copy. Free template inside. (146 chars)
```

**Why this title:** The position-9 result ([https://ca.indeed.com/career-advice/career-development/strategic-business-planning](https://ca.indeed.com/career-advice/career-development/strategic-business-planning)) ranks on a Canadian subdomain in a US SERP with **zero referring domains**, purely on a title that mirrors the query plus its three sub-intents — "Strategic Business Planning (Definition, Benefits, and How-To)". The current Upmetrics title promises "Examples" and does not deliver one, which is both an intent mismatch and a likely CTR/pogo-sticking problem.

---

## 3. KEYWORD & RANKING ANALYSIS (US)

### Top 10 Keywords — GSC, US, 2026-03-22 → 2026-09-19

| Keyword | Impressions | Clicks | CTR | Avg Position | Trend (6mo) |
|---------|------------|--------|-----|-------------|-------------|
| strategic business plan | 547 | 0 | 0.00% | 59.9 | ↓ p39.2 (Jun) → p84.0 (Sep) |
| business strategic planning | 424 | 0 | 0.00% | 64.0 | ↓ p42.1 (Jun) → p82.9 (Sep) |
| **strategic business planning** *(primary)* | 409 | 0 | 0.00% | 68.7 | ↓ p38.2 (Jun) → p71.9 (Sep) |
| business strategy planning | 227 | 0 | 0.00% | 64.7 | ↓ p39.6 (Jun) → p86.2 (Sep) |
| benefits of strategic planning | 215 | 0 | 0.00% | 65.4 | → impressions growing (1 → 93/mo), position flat ~p60–68 |
| what is strategic business planning | 194 | 0 | 0.00% | 63.4 | — no trend data (row cap) |
| strategic planning for businesses | 171 | 0 | 0.00% | 60.2 | — no trend data (row cap) |
| strategic plans for small business | 149 | 0 | 0.00% | 74.8 | — no trend data (row cap) |
| strategic planning for small business | 121 | 0 | 0.00% | 63.6 | — no trend data (row cap) |
| example of planning in business management | 119 | 0 | 0.00% | 67.2 | ↓ p42.7 (Jun) → p86.3 (Aug) |

**Totals across all 266 queries:** 5,321 impressions · **0 clicks** · 0.00% CTR.

> ⚠️ GSC Call 2 returned exactly 2,000 rows, meaning the daily data was truncated. Trend analysis is therefore reliable for the top 5 queries only; rows 6–9 had no surviving daily rows.

### The July 2026 Regression — the headline finding

Every query with trend data shows the same shape: steady improvement through spring, a peak in **June 2026** around position 38–42, then a sharp fall in **July 2026** to position 76–86 that has not recovered.

| Query | Mar | Apr | May | **Jun** | **Jul** | Aug | Sep |
|-------|-----|-----|-----|---------|---------|-----|-----|
| strategic business plan | 78.6 | 87.2 | 51.3 | **39.2** | **76.1** | 84.0 | 84.0 |
| business strategic planning | 64.5 | 71.8 | 52.5 | **42.1** | **72.9** | 78.5 | 82.9 |
| strategic business planning | 75.2 | 80.5 | 61.5 | **38.2** | **84.2** | 84.5 | 71.9 |
| business strategy planning | 86.8 | 79.7 | 49.6 | **39.6** | **68.7** | 80.1 | 86.2 |
| example of planning in business management | 72.3 | 81.0 | 60.6 | **42.7** | **84.4** | 86.3 | — |

The page's `modifiedDate` is **2026-07-02**. The correlation is tight enough that the July edit should be treated as the prime suspect and diffed before anything else is changed. This is Action #1 in the Master Action Table.

### Striking Distance Opportunities (positions 4–20)

| Keyword | Impressions | Clicks | Position | Opportunity |
|---------|------------|--------|----------|-------------|
| strategic business outlook | 45 | 0 | 15.8 | The **only** query on the entire page inside striking distance. Low commercial value and off-topic for the page's core intent — not worth optimising for directly. |

Out of 266 queries, exactly one sits in positions 4–20. This is not a page that needs nudging over the line; it needs to re-enter contention.

### Cannibalization Check

| Query | Target Page Position | Competing Page URL | Competing Page Position | Recommendation |
|-------|---------------------|-------------------|------------------------|----------------|
| strategic business planning | 68.7 (409 impr) | [https://upmetrics.co/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | 87.2 (5 impr) | Keep both. Differentiate roles (see below). |
| strategic business plan | 59.9 (547 impr) | [https://upmetrics.co/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | 65.1 (115 impr) | **Strongest overlap.** 115 impressions is material. |
| strategic business plan | 59.9 (547 impr) | [https://upmetrics.co/blog/everything-you-need-to-know-about-pricing-strategy](https://upmetrics.co/blog/everything-you-need-to-know-about-pricing-strategy) | 1.0 (20 impr) | Position 1 on only 20 impressions over 6 months — almost certainly an image or sitelink surface, not a true organic listing. No action. |
| what is strategic business planning | 63.4 (194 impr) | [https://upmetrics.co/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | 76.5 (29 impr) | Keep both, differentiate. |
| business strategy planning | 64.7 (227 impr) | [https://upmetrics.co/blog/how-to-create-a-business-strategy](https://upmetrics.co/blog/how-to-create-a-business-strategy) | 27.0 (2 impr) | Negligible overlap (2 impressions), but that page ranks at p27 — use it as a **link source**, not a competitor. |

**Verdict: real but manageable cannibalization.** The target page outranks `business-plan-vs-strategic-plan` on every shared query, so the target is the correct canonical asset for the "how to do strategic planning" intent. However, the comparison page is 2,793 words to the target's 1,709 and was updated 2026-09-17 versus the target's 2026-07-02 — it is both deeper and fresher. It already links *into* the target page; the target does not link back with strong anchor text.

**Recommended split:**
- `business-plan-vs-strategic-plan` → owns **"business plan vs strategic plan"** (the comparison intent)
- `strategic-business-planning` (target) → owns **"what strategic business planning is and how to do it"** (the definition + process + example intent)
- The target page should cover the comparison in one tight section with a link out, not compete on it.

---

## 4. SERP & INTENT ANALYSIS

### What Google is rewarding

- **Dominant intent:** Informational, with a strong **definitional + comparative** skew.
- **Content types ranking:** 8 organic results — 4 are "business plan vs strategic plan" comparisons (positions 4, 6, 7 plus partial at 2), 3 are definitional guides (positions 5, 8, 10), 1 is a how-to guide (position 9). **Zero SaaS blog posts. Zero template/download pages. Zero forum threads.**
- **Who wins:** institutes (balancedscorecard.org, thestrategyinstitute.org), banks and insurers (BDC, The Hartford, Hiscox), enterprise software (Workday), a university (AMU) and a job board (Indeed).
- **What this means:** Google reads a large share of this query as *"what is a strategic plan, and how is it different from a business plan?"* — and rewards institutional authority plus clean, extractable structure over length. The position-2 page is only ~1,300 words.

### The KD 5 proof point

[https://ca.indeed.com/career-advice/career-development/strategic-business-planning](https://ca.indeed.com/career-advice/career-development/strategic-business-planning) holds **position 9** with:
- a **Canadian** subdomain in a **US** SERP,
- **zero** referring domains to the URL,
- **zero** images, tables or downloads,
- ~2,300 words of plain text.

Its only real advantages are Indeed's DR 92 and a title/H1 that mirrors the query and its three sub-intents exactly. This is the clearest evidence that KD 5 is genuine and that the target page's problem is relevance and structure, not competitive strength.

### Intent match/mismatch

- **Current page type:** Blog article / guide
- **Match status:** ⚠️ **Partial mismatch**
- **Why:** The page's structural intent is right (definition + process guide), but three things break the match:
  1. The H2 **"Strategic business plan example"** contains no example. It presents five analysis frameworks (SOAR, Porter's Five Forces, STEEPLE, NOISE, CORE). A user arriving from a title promising "Explained with Examples" finds no example — a direct pogo-sticking risk.
  2. **The frameworks are the wrong ones.** SWOT is named by 5 of 9 competitors and sits in the PAA orbit; the balanced scorecard by 3. The target names neither. SOAR, NOISE and CORE appear on no ranking competitor.
  3. **No comparison content.** Half the first page is business-plan-vs-strategic-plan material; the target handles it in a single FAQ line.

### SERP Features

| Feature | Present? | Who Owns It | Can We Win? | Action |
|---------|----------|-------------|-------------|--------|
| **AI Overview** | ✅ Yes — position 1, 9 cited sources | balancedscorecard.org, AMU, BDC, The Hartford, AFP, FranklinCovey, Workday, Hiscox, a YouTube explainer | **Realistic** — cited sources include DR 63 and DR 70 pages, not just giants | Write short, self-contained definition blocks and numbered lists that can be lifted verbatim. Upmetrics is not currently cited. |
| **Featured Snippet** | ❌ Not present | — (absorbed by the AI Overview) | Possible if reinstated | A clean `What is strategic business planning?` paragraph of 40–55 words directly under the H2, plus a numbered 5-step list. |
| **PAA** | ✅ Yes — position 3, 4 questions | Various | **Yes — highest-value, lowest-effort win** | See table below. The page answers **none** of the four. |
| **Video results** | ✅ Yes — 1 YouTube explainer cited inside the AI Overview | HR Courses Online | Later-stage | Upmetrics has a YouTube channel already linked in the footer. Out of scope for this update. |
| **Image pack** | ✅ Ahrefs flags `image_th` on every AI Overview sitelink | Competitors | Yes | Custom diagrams are being pulled into the AI Overview. Target has 2 images; the position-2 competitor has 5 custom diagrams. |
| **Knowledge panel** | ❌ No | — | — | No action. |

**Net effect:** with an AI Overview at position 1 and a PAA block at position 3, organic CTR is heavily suppressed even for page-one results. Winning here means being **extractable** — clean definitions, numbered steps, comparison tables — not merely being long.

### PAA Questions — none currently answered

| PAA Question | Answered on target page? | Who answers it well | Action |
|---|---|---|---|
| What are the 5 steps of strategic planning? | ❌ No — the page has a 5-step guide, but the steps are Upmetrics-specific (vision, team, goals, strategies, execute) and the H2 does not match the question | [balancedscorecard.org](https://balancedscorecard.org/strategic-planning-basics/) — 5 numbered H3s | Reframe the existing process section so the question is answered verbatim |
| What are the 5 P's of strategic planning? | ❌ No | Upmetrics' own [business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) answers this in its FAQ | Add to FAQ |
| What are the 7 basic elements of a strategic plan? | ❌ No | [The Hartford](https://www.thehartford.com/insights-center/business-management/strategic-planning) — dedicated H2 | Add a dedicated section |
| What are the 5 C's of strategic planning? | ❌ No | Not well covered by any top-10 competitor — **open opening** | Add to FAQ |

### Featured Snippet Optimization

| Query | Snippet Type | Current Owner | What Target Page Needs | Where to Place |
|-------|-------------|---------------|----------------------|----------------|
| what is strategic business planning | Paragraph | None (AI Overview absorbed it) | A 40–55 word standalone definition, no product mention, immediately under the H2 | First paragraph under `What is strategic business planning?` |
| what are the 7 basic elements of a strategic plan | List | The Hartford | A numbered 7-item list with a one-line lead-in sentence | New H2 section |
| what are the 5 steps of strategic planning | List | balancedscorecard.org | Numbered H3s whose text starts with the step verb | Existing process section, re-headed |

---

## 5. TECHNICAL SEO (Failures Only)

Most technical checks pass. Canonical is self-referencing, robots is `index, follow`, there is no `noindex`, all Open Graph and Twitter Card tags are present, both content images have alt text, the URL is clean, and schema is rich (Article, WebPage, ImageObject, BreadcrumbList, WebSite, Organization, Person, **FAQPage**). Only the following need work.

| # | Issue | Current | Fix | SEO Impact |
|---|-------|---------|-----|------------|
| 1 | **Meta description too long** | 204 chars — truncates at ~160 in the SERP, so the useful half is cut off | → See §2 Title & Meta Copy for the rewrite | Wasted SERP real estate; weak CTR signal on a page that already earns 0 clicks from 5,321 impressions |
| 2 | **H1 is identical to the title tag** | Both read `Strategic Business Planning: Explained with Examples` | Differentiate: title tag targets the SERP, H1 targets the reader. → See §2 for the new title; the H1 should stay closer to the query itself | Minor. Two identical strings waste a chance to cover query variants |
| 3 | **FAQPage schema does not cover the live PAA questions** | Schema exists and is valid, but is populated with the page's own 6 FAQs — none of which match the 4 PAA questions Google is showing | Extend the existing FAQPage node with the 4 PAA questions once the writer supplies answers (see Update Brief). **No new schema type is required.** | PAA eligibility — the cheapest available win on this SERP |
| 4 | **Person schema emitted with a brand, not a person** | `Person` schema is present but the author resolves to "Upmetrics" with no bio and no photo | Populate with a real named author. → See §8 | E-E-A-T; structured-data accuracy |
| 5 | **No `hreflang`** | Empty | No action required — Upmetrics targets US/global English only. Listed for completeness. | None |

> **Not a technical issue but worth stating plainly:** the title tag promises "Examples" and the page contains no example. That is a content problem (§6, and the Update Brief), not a markup problem — but it is the likeliest single cause of poor engagement on the impressions the page does earn.

---

## 6. CONTENT GAPS & COMPETITOR DEPTH

### 6A. Content Depth Comparison

| Page | URL | Content Type | Word Count | H2s | H3s | Visuals | FAQs | Ext. Citations | Downloads |
|------|-----|-------------|-----------|-----|-----|--------|------|-----------|-----------|
| **OURS** | [strategic-business-planning](https://upmetrics.co/blog/strategic-business-planning) | Blog guide | **1,709** | 7 | 17 | 2 | 6 | **0** | 1 in-content |
| C1 (pos 2) | [balancedscorecard.org](https://balancedscorecard.org/strategic-planning-basics/) | Guide / pillar | ~1,300 | 9 | 5 | 5 | 0 | 0 | 3 |
| C2 (pos 4) | [bdc.ca](https://www.bdc.ca/en/articles-tools/business-strategy-planning/define-strategy/business-plan-vs-strategic-plan-whats-difference) | Comparison | 576 | 3 | 0 | 0 | 2 | 0 | 2 |
| C3 (pos 5) | [financialprofessionals.org](https://www.financialprofessionals.org/glossary/strategic-planning) | Glossary / landing | 1,616 | 7 | 2 | 4 | 2 | 3 | 0 |
| C4 (pos 6) | [thestrategyinstitute.org](https://www.thestrategyinstitute.org/insights/business-plan-vs-strategic-plan-what-you-must-know) | Comparison | ~1,100* | 4 | 3 | 19 | 1 | 4 | 4 |
| C5 (pos 7) | [amu.apus.edu](https://www.amu.apus.edu/area-of-study/business-administration-and-management/resources/business-plan-vs-strategic-plan/) | Comparison | 2,315 | 7 | 17 | 1 | 0 | 2 | 0 |
| C6 (pos 8) | [thehartford.com](https://www.thehartford.com/insights-center/business-management/strategic-planning) | Blog article | **3,062** | 10 | 17 | 6 | 7 | **6** | 0 |
| C7 (pos 9) | [ca.indeed.com](https://ca.indeed.com/career-advice/career-development/strategic-business-planning) | How-to guide | ~2,300 | 3 | 13 | 0 | 0 | 0 | 0 |
| C8 (pos 10) | [workday.com](https://www.workday.com/en-us/topics/fpa/strategic-planning.html) | Blog article | 1,391 | 6 | 15 | 0 | 1 | 3 | 0 |
| C9 (internal) | [business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | Comparison | 2,793 | 9 | 12 | 9 | 13 | 0 | 2 |

*\*C4 word count approximate — `content_area_confidence: low`; the scraper's 1,194 figure includes ~900 words of footer/legal boilerplate.*

**⚠️ Word count methodology:** article-body extraction only (excludes nav, footer, sidebar, CTAs). The target uses the site-specific `.blog-content-area` selector; competitors use the universal content-area detector. Treat as directionally comparable.

**The key read: length is not the problem.** At 1,709 words the target sits mid-pack, and the **position-2 result is shorter than it is** (~1,300 words). What separates the winners is structure and evidence — the target has **zero external citations** (four competitors cite sourced research), **zero data tables** (five competitors have one), and **no worked example** (five competitors have one). Upmetrics' own comparison page, which is not even in the top 10, beats the target on every one of those dimensions.

### 6B. Competitor Heading Map

Legend: C1 balancedscorecard · C2 BDC · C3 AFP · C4 Strategy Institute · C5 AMU · C6 The Hartford · C7 Indeed · C8 Workday · C9 Upmetrics comparison page (internal)

| Topic / Section | C1 | C2 | C3 | C4 | C5 | C6 | C7 | C8 | C9 | OURS | Action |
|----------------|----|----|----|----|----|----|----|----|----|----|--------|
| Definition of strategic planning | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| **"What is a strategic *plan*?" (artifact vs process)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✗ | ✗ | ✅ | ✗ | **✗ GAP** |
| Step-by-step planning process | ✅ | ✗ | ✅ | ✗ | ✅ | ✅ | ✅ | ✅ | ✗ | ✅ | ✅ go deeper |
| **The 7 basic elements of a strategic plan** | ✗ | ✗ | ✗ | ✅ | ✗ | ✅ | ✗ | ✗ | ✅ | ✗ | **✗ GAP (PAA)** |
| Benefits of strategic planning | ✅ | ✗ | ✅ | ✅ | ✗ | ✅ | ✅ | ✅ | ✗ | ✅ | ✅ go deeper |
| **SWOT analysis** | ✅ | ✗ | ✅ | ✅ | ✗ | ✅ | ✅ | ✅ | ✅ | ✗ | **✗ GAP** |
| **Balanced scorecard** | ✅ | ✗ | ✅ | ✗ | ✗ | ✅ | ✗ | ✗ | ✗ | ✗ | **✗ GAP** |
| **A real worked example** | ✗ | ✅ | ✗ | ✗ | ✅ | ✅ | ✗ | ✅ | ✅ | ✗ | **✗ GAP — critical** |
| **Business plan vs strategic plan (as a section)** | ✗ | ✅ | ✗ | ✅ | ✅ | ✗ | ✗ | ✅ | ✅ | ✗ | **✗ GAP** |
| **A comparison table** | ✗ | ✅ | ✗ | ✅ | ✅ | ✗ | ✗ | ✅ | ✅ | ✗ | **✗ GAP** |
| Vision / mission statements | ✅ | ✗ | ✗ | ✅ | ✅ | ✗ | ✗ | ✗ | ✗ | ✅ | ✅ table stakes |
| **Time horizon guidance (3–5 yrs)** | ✗ | ✗ | ✅ | ✗ | ✅ | ✅ | ✗ | ✗ | ✅ | ✗ | **✗ GAP** |
| KPIs & measurement | ✅ | ✗ | ✅ | ✅ | ✅ | ✗ | ✅ | ✗ | ✗ | ⚠️ thin | ✅ go deeper |
| **Who owns / manages the process** | ✗ | ✗ | ✅ | ✗ | ✗ | ✅ | ✗ | ✗ | ✗ | ✗ | ✗ GAP |
| **Budget, resourcing & staffing** | ✗ | ✗ | ✅ | ✅ | ✗ | ✗ | ✅ | ✗ | ✗ | ✗ | ✗ GAP |
| Challenges / failure modes | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ✗ | ⚠️ FAQ only | ✅ go deeper |
| Review & update cadence | ✗ | ✗ | ✅ | ✗ | ✗ | ✅ | ✅ | ✅ | ✅ | ⚠️ FAQ only | ✅ go deeper |
| **Cited statistics with sources** | ✗ | ✗ | ✅ | ✅ | ✅ | ✅ | ✗ | ✅ | ✗ | ✗ | **✗ GAP** |
| **Key Takeaways / summary box** | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ✗ | ✗ | ✗ | ✗ | ✗ GAP |
| Strategic plan template / checklist | ✅ | ✅ | ✅ | ✅ | ✗ | ✅ | ✗ | ✗ | ✅ | ⚠️ SMART goal only | **✗ GAP + Upmetrics** |
| Small-business-specific angle | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ✗ | ✗ | ✗ | ⚠️ FAQ only | ✅ go deeper |
| Strategic vs operational planning | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ✗ | ✅ FAQ | ✅ go deeper |
| Strategic management vs execution | ✅ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ low priority |
| Scenario planning | ✗ | ✗ | ✅ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ low priority |
| SOAR / Porter's / STEEPLE / NOISE / CORE | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ⚠️ **UNIQUE but unrewarded** — see 6C #11 |

### 6C. Topic Gap Detail

| # | Missing Topic | Covered By | Evidence Source | Priority | Recommended Action |
|---|--------------|------------|----------------|----------|-------------------|
| 1 | **An actual worked example** | C2, C5, C6, C8, C9 (5 competitors) | AMU writes a full sample strategic plan for a named company (XYZ, eco-fashion) with vision, mission, values, 5 goals, 10 objectives, 30+ action steps, a 3-year timeline and KPIs. Upmetrics' own C9 uses a coffee shop with a $150K SBA loan. | **High** | Replace the mis-labelled "Strategic business plan example" section with one continuous worked example for a single named business, carried end-to-end. The H2 already promises this. |
| 2 | **SWOT analysis** | C3, C4, C6, C7, C8, C9 (6 of 9) | Named by two-thirds of the competitive set and by Upmetrics' own comparison page. The target names SOAR, Porter's Five Forces, STEEPLE, NOISE and CORE — none of which appear on any ranking page. | **High** | Add SWOT as the primary named framework inside the situational-analysis step. Keep one or two alternatives as a short "other frameworks" aside. |
| 3 | **The 7 basic elements of a strategic plan** | C4, C6, C9 | Live PAA question: *"What are the 7 basic elements of a strategic plan?"* The Hartford owns it with a dedicated H2. | **High** | New H2 with a numbered 7-item list and a one-line lead-in — snippet- and AI-Overview-extractable. |
| 4 | **A comparison table** | C2, C4, C5, C8, C9 (5 of 9) | Every comparison-format competitor uses one. C9 (Upmetrics' own page) has three. The target page has zero tables of any kind. | **High** | Add one business-plan-vs-strategic-plan table (scope, time horizon, audience, purpose, components) with a link out to the C9 page for depth. |
| 5 | **"What is a strategic plan?" as distinct from the process** | C1, C2, C3, C4, C5, C6, C9 (7 of 9) | The clearest structural convention in the SERP: separate the *artifact* from the *activity*. C1 (position 2) devotes an H2 to each. | **High** | Split the existing single "What is strategic planning?" H2 into two short, extractable sections. |
| 6 | **Cited statistics with outbound sources** | C3, C4, C5, C6, C8 | The Hartford cites a small-business survey (22% inflation, 18% cash flow), 73% marketing-confidence and 92%/27% website stats, all linked. Workday cites Digital.ai's 17th State of Agile Report (57% better alignment) with a numbered Sources block. **The target page contains zero statistics and zero editorial outbound links.** | **High** | Add 3–5 sourced statistics with outbound links. Specific citations are assigned per-section in the Update Brief. |
| 7 | **Time horizon guidance** | C3, C5, C6, C9 | AFP: most strategic plans run 3–5 years, varying by asset lifecycle — longer for oil/automotive, shorter for software/retail. The Hartford notes IT plans run only 12–16 months. AMU gives 1–3 years (business plan) vs 3–5+ (strategic plan). | **Medium** | Add a short "How far ahead should a strategic plan look?" block with the industry variation. |
| 8 | **An in-article strategic-plan checklist** | C2, C3, C4, C6, C9 | The Hartford offers an 8-section strategic planning template *checklist inside the article*. The target already links in-content to [/strategic-planning-templates](https://upmetrics.co/strategic-planning-templates) (verified 200) — so the **asset exists**; what is missing is the on-page checklist that makes it useful before the click. | **Medium** | Do not build a new asset. Add an 8-item strategic-plan checklist in the body, then link the existing templates page from it. |
| 9 | **Challenges / what goes wrong** | C8 only | Workday devotes a section to downsides — time-consuming setup, overplanning and bottlenecks. The target has one FAQ line. | **Medium** | Promote the existing FAQ answer into a full section. Only one competitor covers this, so it is also a differentiation opening. |
| 10 | **Budget, resourcing and staffing as a step** | C3, C7 | Indeed makes "Determine budget and staffing needs" step 6 of 8. AFP frames the current-year budget as the bridge between strategy and execution. | **Medium** | Add as a step in the process section. |
| 11 | ⚠️ **Framework mismatch (existing content)** | — | The target's five frameworks (SOAR, Porter's Five Forces, STEEPLE, NOISE, CORE) appear on **zero** ranking competitors, while SWOT appears on six and the balanced scorecard on three. They sit under a heading that promises an example and deliver an unrelated framework list. | **High** | Not an addition — a **relocation**. Cut to a brief aside; give the freed space to SWOT and the worked example. |
| 12 | **Key Takeaways box** | C6 | The Hartford opens with an above-the-fold summary block — a highly extractable answer unit for AI Overviews. | **Low** | Add a 4–5 bullet summary box under the intro. |
| 13 | **Who owns the process** | C3, C6 | The Hartford: "Who manages organizational strategic planning?" — owner/CEO, senior leadership, department heads. | **Low** | Fold into the existing "Build the right team" step rather than adding a section. |

> **No UGC data.** No Reddit or Quora threads appeared in the top 10 SERP results for this keyword, so no user-language or pain-point mining was possible. Per the audit rules, no additional searches were run to find them.

---

## 7. LINKS & BACKLINKS

### 7A. Internal Link Issues

The scraper found **89 internal links** page-wide but does not classify in-content vs navigation. Parsing the `.blog-content-area` HTML directly, **9 links are genuinely in-content**:

| Anchor / context | Target URL | Status |
|---|---|---|
| "vision of your business" | [/blog/vision-statement-business-plan](https://upmetrics.co/blog/vision-statement-business-plan) | ✅ Healthy |
| "SMART goal framework" | [/blog/write-smart-goals](https://upmetrics.co/blog/write-smart-goals) | ✅ Healthy |
| "business plan" | [/blog/how-to-write-a-business-plan](https://upmetrics.co/blog/how-to-write-a-business-plan) | ✅ Healthy |
| "Key Difference Between a Business Plan and Strategic Plan" | [/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | ✅ Healthy |
| Product / asset links | [/strategic-planning-templates](https://upmetrics.co/strategic-planning-templates), [/features/strategic-planning](https://upmetrics.co/features/strategic-planning), [/download/smart-goal-template](https://upmetrics.co/download/smart-goal-template), `/download/ebook`, `/cta/help` | ✅ All verified HTTP 200 |

**No broken internal links found.** All in-content targets return 200.

The remaining 3 blog links — [/blog/elements-of-strategic-planning](https://upmetrics.co/blog/elements-of-strategic-planning), [/blog/types-of-business-plans](https://upmetrics.co/blog/types-of-business-plans) and [/blog/strategic-marketing-process](https://upmetrics.co/blog/strategic-marketing-process) — sit in the "related posts" module below the article, **not in the body**. Related-post modules pass far less relevance than an in-context editorial link.

### 7B. Internal Links to ADD (outbound from the target page)

All URLs below were verified via the target page's own `internalLinks` array **and** re-checked with a live HTTP request (all 200). No URL in this table was inferred or constructed.

| Anchor Text | Target URL | Where to Place | Why | Source |
|------------|-----------|----------------|-----|--------|
| "the 7 core elements of a strategic plan" | [https://upmetrics.co/blog/elements-of-strategic-planning](https://upmetrics.co/blog/elements-of-strategic-planning) | In the new "7 basic elements" section (gap 6C-3) | Currently only a related-post link. Moving it in-content supports the PAA section directly. | Target `internalLinks` + verified 200 |
| "strategic planning templates" | [https://upmetrics.co/strategic-planning-templates](https://upmetrics.co/strategic-planning-templates) | Inside the new in-article checklist (gap 6C-8) | Already linked in-content, but not from a section that earns the click. | Target `internalLinks` + verified 200 |
| "how a business plan differs from a strategic plan" | [https://upmetrics.co/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | Under the new comparison table (gap 6C-4) | Sends the comparison intent to the page that should own it — the core of the cannibalization fix. | GSC + scraped |
| "strategic marketing process" | [https://upmetrics.co/blog/strategic-marketing-process](https://upmetrics.co/blog/strategic-marketing-process) | In the "develop strategies and tactics" step | Currently related-posts only. | Target `internalLinks` + verified 200 |

### 7C. Pages That Should Link TO This Page

| Source Page URL | Where to Add | Suggested Anchor Text | Source |
|----------------|--------------|----------------------|--------|
| [https://upmetrics.co/blog/business-plan-vs-strategic-plan](https://upmetrics.co/blog/business-plan-vs-strategic-plan) | It already links in ("Read more") — **strengthen the anchor**, and add a second link from the "What is a strategic plan?" section | "how to run the strategic business planning process" | GSC + scraped |
| [https://upmetrics.co/blog/how-to-create-a-business-strategy](https://upmetrics.co/blog/how-to-create-a-business-strategy) | In the body, near the planning/execution discussion | "strategic business planning" | GSC (ranks p27 for "business strategy planning") + verified 200 |
| [https://upmetrics.co/blog/elements-of-strategic-planning](https://upmetrics.co/blog/elements-of-strategic-planning) | Introduction or conclusion | "the full strategic business planning process" | Target `internalLinks` + verified 200 |
| [https://upmetrics.co/blog/strategic-marketing-process](https://upmetrics.co/blog/strategic-marketing-process) | Where it references wider business strategy | "strategic business planning" | Target `internalLinks` + verified 200 |
| [https://upmetrics.co/blog/types-of-business-plans](https://upmetrics.co/blog/types-of-business-plans) | Wherever strategic plans are listed as a plan type | "strategic business planning" | Target `internalLinks` + verified 200 |

> **Rule 12 note:** every URL in 7B and 7C came from GSC data or the target page's own outbound link list, and each was additionally confirmed with a live HTTP 200 check. No URLs were guessed from slug patterns.

### 7D. External Link Issues

| # | Anchor Text | Target URL | Issue | Fix |
|---|------------|-----------|-------|-----|
| 1 | *(icon, no anchor text)* | [https://www.youtube.com/@Upmetrics](https://www.youtube.com/@Upmetrics) | Own social profile in footer — not an editorial citation | No fix needed |
| 2 | *(icon, no anchor text)* | [https://www.facebook.com/upmetrics](https://www.facebook.com/upmetrics) | Own social profile in footer | No fix needed |
| 3 | *(icon, no anchor text)* | [https://x.com/upmetrics](https://x.com/upmetrics) | Own social profile in footer | No fix needed |
| 4 | *(icon, no anchor text)* | [https://www.linkedin.com/company/upmetrics-co/](https://www.linkedin.com/company/upmetrics-co/) | Own social profile in footer | No fix needed |

**No broken outbound links and no links to competitor domains** (checked against `COMPETITOR_DOMAINS`: liveplan.com, bizplan.com, enloop.com, planguru.com, growthink.com, bplans.com, planful.com, planbuilr.com, bizplanr.com — zero matches).

**The real issue is absence, not breakage:** all 4 external links are Upmetrics' own social profiles. The page cites **no external sources at all**, while competitors at positions 5, 6, 8 and 10 all cite sourced research with outbound links. See §8.

### 7E. Backlink Gap

| Metric | Target Page | Top 5 Competitors (avg) | Top 5 (median) |
|--------|------------|------------------------|----------------|
| Referring Domains | **0 live** (26 backlinks / 13 refdomains all-time — all lost) | 62.8 | **7** |
| Total Backlinks | **0 live** (26 all-time) | — | — |
| URL Rating | not measured* | 5.4 | 6 |
| Domain Rating (domain-level) | not measured* | 73.8 | 75 |

*\*Upmetrics' own DR and this URL's UR were not pulled — the audit is capped at 4 Ahrefs calls and those units were spent on keyword, SERP and backlink data. Pull separately if needed.*

**Gap summary:**

- **The page has zero live backlinks.** It once held 26 backlinks from 13 referring domains and has lost every one. This is unusual and worth diagnosing on its own — link rot on a single URL at 100% suggests the linking pages were removed, redirected, or the URL changed at some point.
- **The bar is lower than the average suggests.** The mean of 62.8 referring domains is skewed entirely by balancedscorecard.org's 281. The **median is 7**, and two page-one results ([financialprofessionals.org](https://www.financialprofessionals.org/glossary/strategic-planning) at position 5 and [ca.indeed.com](https://ca.indeed.com/career-advice/career-development/strategic-business-planning) at position 9) rank with **zero** referring domains to the URL. Links are not the gating factor on this SERP — relevance is.
- **Specific recommendation:** run an Ahrefs *lost backlinks* report on this exact URL first and attempt reclamation on the 13 known domains, before spending any budget on net-new outreach. Reclaiming even half would put the page at the SERP median.

---

## 8. E-E-A-T & CITATIONS

Read from `verified-facts.json`. Signals already present — publish date, visible updated date, `Person`/`Organization`/`Article` schema — are **not** listed below and require no action.

### E-E-A-T Signal Comparison (gaps only)

| Signal | Target Page | Best Competitor | Gap? |
|--------|------------|----------------|------|
| Named human author | ❌ "Upmetrics" (brand name, pulled from meta) | [AMU](https://www.amu.apus.edu/area-of-study/business-administration-and-management/resources/business-plan-vs-strategic-plan/) — "T. Leigh Buehler, 07/05/2024" with full academic credentials | **Yes** — a brand name in a `Person` schema slot is a weak and technically inaccurate signal |
| Author bio | ❌ `author_has_bio: false` | AMU — full academic credential bio block | **Yes** |
| Author photo | ❌ `author_has_photo: false` | AMU | **Yes** |
| Expert quotes | ❌ 0 | [BDC](https://www.bdc.ca/en/articles-tools/business-strategy-planning/define-strategy/business-plan-vs-strategic-plan-whats-difference) — Jerome Cote, Business Advisor, BDC Advisory Services, quoted twice with job title | **Yes** |
| Cited external sources | ❌ **0** | [The Hartford](https://www.thehartford.com/insights-center/business-management/strategic-planning) — 6 linked sources; [Workday](https://www.workday.com/en-us/topics/fpa/strategic-planning.html) — numbered Sources footnote block | **Yes — the largest E-E-A-T gap** |
| Institutional credential signal | ❌ None | [AFP](https://www.financialprofessionals.org/glossary/strategic-planning) — FPAC certification; [The Strategy Institute](https://www.thestrategyinstitute.org/insights/business-plan-vs-strategic-plan-what-you-must-know) — ABSP/SBSP credentials | Partial — Upmetrics' equivalent is product authority, which the page does not currently assert with evidence |

**Signals where there is no gap:** publish date (2021-12-30) and visible updated date ("Updated July 2, 2026") are both present, and the updated date is fresher than 4 of the 9 competitors — including [The Strategy Institute](https://www.thestrategyinstitute.org/insights/business-plan-vs-strategic-plan-what-you-must-know) at position 6, whose on-page date is September 2019. Freshness is **not** this page's problem.

### Citation Audit

**No editorial citations exist on the page to audit.** The only 4 outbound links are Upmetrics' own social profiles (see §7D). There are therefore no broken or low-quality citations to fix — the recommendation is purely additive, and specific sources are assigned per-section in the Content Update Brief.

### Unsourced Claims

Scanning the full page text for statistics, percentages and research claims returned **no unsourced factual claims**. The only numbers on the page are illustrative examples inside hypothetical goals:

| Text (exact quote) | Location | Assessment |
|---|---|---|
| "Capturing 25% market share" | Under "3. Set your strategic goals" | Illustrative example, not a factual claim — **no citation needed** |
| "increasing the market share by 15% or getting big clients" | Under "What to include in a strategic business plan?" | Illustrative example — **no citation needed** |
| "being a market leader by 2030" | Under "1. Define your business vision" | Illustrative example — **no citation needed** |

> The page is not making unsupported claims. The problem is the opposite: it makes **no evidence-backed claims at all**, which is why it reads as generic next to The Hartford's cited small-business survey data or Workday's Digital.ai research citation. Recommended sourced statistics are assigned per-section in the Update Brief.

---

## 9. APPENDIX

### Ahrefs API Consumption Log

| # | Call | Endpoint | Rows | Units |
|---|------|----------|------|-------|
| 0 | Subscription check | `subscription-info-limits-and-usage` | 1 | 0 (free) |
| 1 | Organic Keywords | `site-explorer-organic-keywords` | 0 | 50 |
| 2 | SERP Overview | `serp-overview` | 25 | 275 |
| 3 | Keyword Overview | `keywords-explorer-overview` | 1 | 50 |
| 4 | Backlinks Stats | `site-explorer-backlinks-stats` | 1 | 50 |
| | **Total this audit** | | | **425** |

**Budget note:** 425 units against the ~630 budgeted. Call 1 returned 0 rows so it cost only the 50-unit minimum instead of the estimated ~410; Call 2 cost more than estimated (275 vs ~120) because the SERP returned 25 rows — AI Overview sitelinks, PAA entries and sitelinks all count as rows alongside the 8 organic results.

**Workspace remaining:** 765,753 units of 800,000. Reset date: 2026-10-21.

### Data Collection Notes

| Step | Outcome |
|------|---------|
| 1A Target scrape | ✅ Python scraper, 1,709 words via `.blog-content-area` |
| 1A-ii Validation | ✅ Canonical self-referencing · no redirect · no `noindex` |
| 1B GSC | ✅ 266 queries / 5,321 impressions / 0 clicks. Call 2 hit the 2,000-row cap — trends reliable for top 5 queries only. 6 cannibalization calls run. |
| 1C Ahrefs | ✅ 4 calls. Organic keywords returned 0 rows (page not ranking in Ahrefs' US index) — not a failure, documented in §3. |
| 1C SERP features | ✅ Ahrefs SERP + 1 WebSearch |
| 1D Competitors | ✅ 9 of 9 captured — 7 via Python scraper, 2 via WebFetch fallback ([balancedscorecard.org](https://balancedscorecard.org/strategic-planning-basics/) crashed the scraper with `ERROR: 'content_text'`; [ca.indeed.com](https://ca.indeed.com/career-advice/career-development/strategic-business-planning) returned HTTP 403) |
| 1D UGC | ⚪ No Reddit/Quora threads in the top 10 SERP — no UGC data collected, per audit rules no extra searches were run |

### Known Data Caveats

1. **C4 word count is inflated** — [thestrategyinstitute.org](https://www.thestrategyinstitute.org/insights/business-plan-vs-strategic-plan-what-you-must-know) scraped at 1,194 words with `content_area_confidence: low`; roughly 900 words are footer/legal boilerplate. Real body is ~1,100 words.
2. **C5 author field reads `NOT FOUND`** in the scraper output, but the page visibly carries a byline (T. Leigh Buehler, 07/05/2024) and a credential bio. The §8 comparison uses the visible truth, not the scraper field.
3. **C1 and C7 word counts are WebFetch estimates**, not scraper measurements — treat as ±15%.
4. **Upmetrics' domain rating and this URL's URL rating were not measured** — outside the 4-call Ahrefs budget.
