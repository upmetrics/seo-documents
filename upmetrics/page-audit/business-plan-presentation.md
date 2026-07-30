# SEO Page Audit — Business Plan Presentation

**Brand:** Upmetrics ([upmetrics.co](https://upmetrics.co))
**Target Page:** [https://upmetrics.co/blog/business-plan-presentation](https://upmetrics.co/blog/business-plan-presentation)
**Primary Keyword:** business plan presentation
**Target Geography:** United States (US) only
**Audit Date:** 2026-07-30
**GSC Data Range:** 2026-01-30 → 2026-07-27 (6 months, US-filtered)
**Ahrefs Country:** US

---

## 1. EXECUTIVE DASHBOARD

### Page Snapshot

| Metric | Value |
|--------|-------|
| URL | [https://upmetrics.co/blog/business-plan-presentation](https://upmetrics.co/blog/business-plan-presentation) |
| Primary Keyword | business plan presentation |
| Primary KW — US Search Volume | 450/mo (Ahrefs) |
| Primary KW — Current Position | 19.9 average (GSC, 6mo, US) · not present in Ahrefs top 10 · last month 26.8 |
| Primary KW — Keyword Difficulty | **3** (Ahrefs) — traffic potential 450, CPC $2.00 |
| Title Tag | `How to Create a Business Plan Presentation?` (**43 chars** — under the 50-60 target) |
| Meta Description | `Learn everything you need to know about business plan presentations—benefits, components, tips, and the easiest way to create such presentations.` (145 chars) |
| H1 | `How to Create a Quality Business Plan Presentation` |
| Word Count (article body only) | **2,581** (`.blog-content-area`; excludes nav, footer, sidebar, CTA blocks, author bio). Article schema self-reports 2,596 — extraction validated. |
| Internal Links (in-content vs. nav/footer) | 77 total in DOM; **~14 in-content** editorial links, the remaining ~63 are global nav/footer/social-share |
| External Links | 5 — of which **4 are Upmetrics' own social profiles** and 1 is bls.gov. Genuine third-party citations: **0** |
| Content Images (with alt / without alt) | **1 / 0** (main content area) — a single `ai-business-plan.svg` CTA graphic |
| Schema Markup | Yes — Article, WebPage, ImageObject, BreadcrumbList ×2, WebSite, Organization, Person, FAQPage |
| Canonical Tag | `https://upmetrics.co/blog/business-plan-presentation` — self-referencing ✅ |
| Page Type | Blog article / educational how-to guide |
| Content Freshness | Published 2023-06-12 · Modified 2026-07-02 · **"Updated July 2, 2026" visible on page** ✅ (28 days before this audit) |
| Author Attribution | `Upmetrics` (brand-level, from meta + Person schema, links to `/author/upmetrics`). **No author bio block, no author photo** on page |
| Downloadable Templates/Freebies | **3 links present** — "Download Now: Free Investor Pitch Template" (`/download/investor-pitch-templates`), "400+ sample business plans", "Business plan template". All 3 sit **outside the article content area** (sidebar/CTA blocks), and none is a business-plan-*presentation* slide deck |
| Redirect / noindex status | No redirect · no `noindex` · robots meta absent (defaults to index,follow) ✅ |

### Top 3 Problems

1. **The page ranks on page 2 (avg. position 19.9) for a keyword with Keyword Difficulty 3 — and it is getting worse, not better.** The primary keyword peaked at position 17.0 in February 2026 and has slid to 26.8 in July. At KD 3, authority is not the constraint: the #1 organic result ([guides.lib.usf.edu](https://guides.lib.usf.edu/business-plan/how-to-pitch)) has a URL Rating of **0** and just 784 words. Something other than links and length is holding this page back.

2. **Format mismatch with what this SERP actually rewards.** 4 of the 8 organic results are template galleries or product pages ([Canva #3](https://www.canva.com/presentations/templates/business-plan/), [Slidesgo #6](https://slidesgo.com/business-plan), [Beautiful.ai #9](https://www.beautiful.ai/presentations/business-plan)) plus an actual sample deck ([SlideShare #4](https://www.slideshare.net/slideshow/sample-business-plan-presentation-14630613/14630613)). Every guide-format page that outranks us bundles a *usable slide asset and real annotated deck examples* with the advice. This page has **1 image, 0 example decks, and 0 in-content downloadable deck**.

3. **The content is comprehensive but generic — it has no data, no examples, and no specifics.** At 2,581 words it is already **longer than the 2,379-word average** of the six scraped competitors, so adding length will not help. What is missing is substance: **zero third-party citations**, zero statistics, zero named real-world deck examples, no slide-count or runtime numbers in the body, and no Executive Summary slide (4 of 6 competitors include one). Meanwhile 4 competitors publish a "mistakes to avoid" section and 3 publish investor-Q&A preparation content — this page has neither.

### Traffic Opportunity

> KD 3 at 450/mo US volume, currently 1,688 impressions and **0 clicks** over 6 months. 0 clicks is explained by *position* (page 2), not by CTR — do not treat this as a title/CTR problem. Fixing format and specificity to reach the top 5 is realistically worth **40-90 clicks/mo**; top 3 is worth **100-180 clicks/mo**, after discounting for the AI Overview that occupies position 1. The secondary query "how to present a business plan" (447 impressions) is independently climbing — 96.8 → 36.3 over six months — and is the fastest-moving asset on the page.

---

## 2. MASTER ACTION TABLE

All SEO actions, priority-sorted. **Content actions are NOT here** — they live in the Content Update Brief (Section 14, separate `.docx`).

*Cross-checked against `verified-facts.json`: author is present, a visible updated date is present, downloadable template links are present, a meta description is present, and FAQPage schema is present. No action items were generated for any of those.*

| # | Priority | Category | Action | Assignee | Details | Section Ref |
|---|----------|----------|--------|----------|---------|-------------|
| 1 | P1 | Meta | Rewrite title tag to `Business Plan Presentation: Examples, Slides & Template` (55 chars) | Dev | Current title is 43 chars and carries no modifier for the asset types this SERP rewards. The three top-ranking guide titles all name their assets: SlideUpLift = "Guide, Examples & Free Templates"; SlideModel = "Quick Guide"; Adobe = "How to Make a…". Copy-paste block below. | §5 |
| 2 | P1 | Meta | Rewrite meta description to the copy in the block below (139 chars) | Dev | Current description is generic ("everything you need to know") and names no asset or number. New copy names the slide count, examples, and template. | §5 |
| 3 | P1 | Technical | Remove the standalone duplicate `BreadcrumbList` JSON-LD block and fix its broken URL | Dev | The page ships **two conflicting BreadcrumbList declarations**. Yoast's `@graph` block declares Home → Article (2 levels). A second standalone block declares upmetrics → blog → Article and points "blog" at `https://upmetrics.co/post`, **which is not the blog URL** (the blog is at [https://upmetrics.co/blog](https://upmetrics.co/blog)). Delete the standalone block; keep the `@graph` one. | §5 |
| 4 | P2 | Technical | Change the Article author node from `@type: Person` to `@type: Organization` | Dev | Schema declares `{"@type":"Person","name":"Upmetrics"}` with a company description ("Upmetrics is the #1 business planning software…"). A company is not a Person. Either retype as `Organization`, or attribute the article to a named human author. | §8 |
| 5 | P2 | Internal Link | Add in-content link to [https://upmetrics.co/blog/business-plan-for-investors](https://upmetrics.co/blog/business-plan-for-investors) | SEO Team | Anchor: `business plan for investors`. Place in the "11. Funds Being Raised" section. URL verified via GSC. | §7B |
| 6 | P2 | Internal Link | Add in-content link to [https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide](https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide) | SEO Team | Anchor: `complete business plan guide`. Place in the "What is a Business Plan Presentation?" section, where the deck-vs-plan distinction belongs. URL verified via GSC. | §7B |
| 7 | P2 | Internal Link | Add in-content link to [https://upmetrics.co/services/pitch-deck](https://upmetrics.co/services/pitch-deck) | SEO Team | Anchor: `pitch deck creation service`. Place in the closing Upmetrics section as the done-for-you alternative to the DIY path. URL verified via GSC. | §7B |
| 8 | P2 | Internal Link | Add inbound links to this page from 3 verified Upmetrics pages | SEO Team | Sources and placements in §7C. All 3 source URLs verified via GSC or the target's own outbound link graph. | §7C |
| 9 | P3 | Backlinks | Deprioritise link building for this page; pursue only asset-led links after the content update ships | Link Builder | At KD 3, links are demonstrably not the blocker — the #1 organic result has URL Rating 0. The page has decayed from 7 all-time referring domains to 2 live (71% loss). Re-attempt outreach only once a downloadable deck + annotated examples exist to link to. | §7E |
| 10 | P3 | Technical | Reclaim the 2 lost referring domains | Link Builder | 7 referring domains linked historically, 2 are live. Pull the lost-links list manually in the Ahrefs UI (not via API — audit budget is capped at 4 calls) and re-request placements. | §7E |

### Title & Meta Copy (ready to copy-paste)

```
Title Tag (NEW): Business Plan Presentation: Examples, Slides & Template (55 chars)
Title Tag (OLD): How to Create a Business Plan Presentation? (43 chars)

Meta Description (NEW): Build an investor-ready business plan presentation: the 12 slides to include, real deck examples, delivery tips, and a free pitch template. (139 chars)
Meta Description (OLD): Learn everything you need to know about business plan presentations—benefits, components, tips, and the easiest way to create such presentations. (145 chars)
```

> **Note on the new title and description:** both promise a template and real deck examples. The template promise is already honest — `/download/investor-pitch-templates` exists and is linked. The *examples* promise depends on the Content Update Brief work landing. **Ship items 1 and 2 together with the content update, not before it.**

**⚠️ Content actions NOT included here:** content fixes, additions, and rewrites — including the missing Executive Summary slide, mistakes-to-avoid section, investor Q&A content, real deck examples, slide visuals, and new citations — are all in the **Content Update Brief (Section 14)**.

---

## 3. KEYWORD & RANKING ANALYSIS (US)

**Source:** GSC, `sc-domain:upmetrics.co`, page-filtered, country = USA, 2026-01-30 → 2026-07-27.
**Totals: 95 queries · 1,688 impressions · 0 clicks · 0.00% CTR.**

### Top 10 Keywords (by impressions)

| Keyword | Impressions | Clicks | CTR | Avg Position | Trend (6mo) |
|---------|------------|--------|-----|-------------|-------------|
| business plan presentation | 857 | 0 | 0% | 19.9 | **↓ declining** — 42.4 (Jan) → **17.0 (Feb peak)** → 22.6 → 28.5 → 27.9 → 28.1 → 26.8 (Jul) |
| how to present a business plan | 447 | 0 | 0% | 57.4 | **↑ improving strongly** — 96.8 → 80.9 → 76.7 → 81.8 → 57.6 → 38.7 → **36.3 (Jul)** |
| how to make a business plan presentation | 30 | 0 | 0% | 64.3 | **↑ improving** — 79.2 → 80.8 → 76.4 → 63.5 → 38.5 → 41.5 |
| business plan writers for investor presentations | 26 | 0 | 0% | 67.8 | ↑ improving — 80.0 → 81.5 → 68.9 → 61.2 (commercial query; see cannibalization note) |
| presentation for a business plan | 19 | 0 | 0% | 21.0 | → flat — 29.0 → 18.1 → 24.2 → 19.5 |
| presentation business plan | 17 | 0 | 0% | 29.3 | ↑ improving — 39.0 → 77.0 → 40.2 → 31.0 → **20.5 (Jul)** |
| presenting business plan | 17 | 0 | 0% | 22.2 | → volatile/flat — 15.0 → 22.0 → 49.0 → 23.0 → 37.0 |
| plan presentation | 14 | 0 | 0% | 53.6 | **↑ improving** — 93.0 → 99.0 → 63.3 → 59.5 → 43.8 → 24.0 → 25.5 |
| presentation of business plan | 14 | 0 | 0% | 39.3 | ↑ improving — 22.5 → 13.0 → 90.0 → 53.2 → 49.0 → 30.3 |
| business plans presentation | 10 | 0 | 0% | 35.6 | **↑ improving** — 61.5 → 44.3 → 25.0 → **24.5 (Jul)** |

**Read this table carefully — it contains the single most important pattern in the audit.**

The primary keyword is the **only** query in the top 10 that is *declining*. Nine of the ten are improving, several dramatically (`plan presentation` 93 → 25; `how to present a business plan` 96.8 → 36.3). The page is gaining ground on **delivery-and-presenting** language while losing ground on the head term.

That divergence is diagnostic. Google is increasingly reading this page as an answer to *"how do I present/deliver a business plan"* — which is exactly the topic the page covers most thinly (three short pitching tips totalling ~2,300 characters) — while demoting it for the head term, where the SERP wants slide assets and examples. **The content update should lean into the delivery/presenting angle where momentum already exists, while adding the assets needed to defend the head term.**

**A note on the 0% CTR:** with an average position of 19.9, the primary keyword sits on page 2, where expected CTR is roughly 0.5-1%. Against 857 impressions, that predicts ~5 clicks; 0 is marginally below that but well within noise. **This is a position problem, not a CTR problem.** The title/meta rewrite in §2 is worth doing, but on its own it will not produce clicks — the page has to move onto page 1 first.

### Striking Distance Opportunities (positions 4-20 with meaningful impressions)

| Keyword | Impressions | Clicks | Position | Opportunity |
|---------|------------|--------|----------|-------------|
| business plan presentation | 857 | 0 | 19.9 (26.8 last month) | **Highest-value target on the page.** 450/mo volume at KD 3. Sitting at the page-1/page-2 boundary. Needs the format fix (deck asset + real examples + slide visuals) to cross over. |
| presentation for a business plan | 19 | 0 | 21.0 | Same-intent variant of the primary — will move with it. No separate work needed. |
| presenting business plan | 17 | 0 | 22.2 | Delivery-intent variant. Would benefit directly from a dedicated "how to deliver the presentation" section (see §6C). |
| business plans presentation | 10 | 0 | 35.6 → 24.5 (Jul) | Improving fast; plural variant of the primary. Moves with the primary. |
| presentation business plan | 17 | 0 | 29.3 → 20.5 (Jul) | Improving fast; entering striking distance this month. |
| business project presentation | 6 | 0 | 8.7 | **Already on page 1** — the only query on the page that is. Very low volume, but proves the page *can* rank when intent is broader/less asset-driven. |
| business plan keynote | 9 | 0 | 30.1 | Format-specific (Apple Keynote). Would be picked up by a "PowerPoint vs. Google Slides vs. Keynote" format section (see §6C). |
| business plan poster presentation | 1 | 0 | 26.0 | Negligible volume — ignore. |

**Striking-distance verdict:** the opportunity is highly concentrated. `business plan presentation` alone accounts for 51% of all impressions on the page, and the top 2 queries account for 77%. Fix the head term and the delivery cluster; ignore the long tail, which will follow.

### Cannibalization Check

Checked the primary keyword plus the 5 next-highest-impression queries (6 GSC `query,page` calls, US-filtered, no page filter).

| Query | Target Page Position | Competing Page URL | Competing Page Position | Recommendation |
|-------|---------------------|-------------------|------------------------|----------------|
| business plan presentation | 19.9 (857 impr) | [https://upmetrics.co/blog/business-plan-questionnaire](https://upmetrics.co/blog/business-plan-questionnaire) | 1.0 (4 impr) | **No action.** 4 impressions vs. 857 — statistical noise, almost certainly branded/site-search surfacing. |
| business plan presentation | 19.9 (857 impr) | [https://help.upmetrics.co/article/175-exploring-upmetrics-s-business-plan-and-pitch-deck](https://help.upmetrics.co/article/175-exploring-upmetrics-s-business-plan-and-pitch-deck) | 1.0 (1 impr) | **No action.** Help-centre subdomain, 1 impression. Not competing. |
| how to present a business plan | 57.4 (447 impr) | [https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide](https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide) | 50.0 (1 impr) | **No action.** 1 impression. Link *from* it to the target instead — see §7C. |
| business plan writers for investor presentations | 67.8 (26 impr) | [https://upmetrics.co/services/business-plan-writing](https://upmetrics.co/services/business-plan-writing) (68 impr @ 38.7), [https://upmetrics.co/blog/business-plan-for-investors](https://upmetrics.co/blog/business-plan-for-investors) (61 @ 55.8), [https://upmetrics.co/](https://upmetrics.co/) (36 @ 63.5), [https://upmetrics.co/features/pitch-deck](https://upmetrics.co/features/pitch-deck) (19 @ 69.9), [https://upmetrics.co/services/pitch-deck](https://upmetrics.co/services/pitch-deck) (6 @ 68.2), + 2 more | 8 Upmetrics URLs total | **Deprioritise — not a real conflict.** This is a commercial *"hire someone"* query that correctly belongs to [services/business-plan-writing](https://upmetrics.co/services/business-plan-writing), which already outranks the target on it. The target page should not chase this query. |
| how to make a business plan presentation | 64.3 (30 impr) | — | — | Target page only. |
| presentation for a business plan | 21.0 (19 impr) | — | — | Target page only. |
| presenting business plan | 22.2 (17 impr) | — | — | Target page only. |

**Verdict: No meaningful cannibalization.** The target page is the unambiguous owner of the entire "business plan presentation" and "how to present a business plan" query space — every competing page is at 1-4 impressions. The only multi-page overlap sits on a commercial service query that belongs to a different page by design. **No consolidation, no redirects, no de-optimisation needed.** No cannibalizing pages were scraped as competitors, because none qualified.

---

## 4. SERP & INTENT ANALYSIS

### What Google is rewarding

- **Dominant intent:** **Mixed — split between DO and LEARN, with DO holding the higher positions.** "DO" here means *get me a deck I can use right now*.
- **Content types ranking (8 organic results in the Ahrefs top 10):**
  - **3 template galleries / product pages** — [Canva #3](https://www.canva.com/presentations/templates/business-plan/) (DR 93), [Slidesgo #6](https://slidesgo.com/business-plan) (DR 77), [Beautiful.ai #9](https://www.beautiful.ai/presentations/business-plan) (DR 79)
  - **1 actual sample slide deck** — [SlideShare #4](https://www.slideshare.net/slideshow/sample-business-plan-presentation-14630613/14630613) (DR 92)
  - **1 template-led resource page** — [USF LibGuides #2](https://guides.lib.usf.edu/business-plan/how-to-pitch), whose headline asset is a downloadable *Business Plan Pitch PowerPoint Template* (784 words, URL Rating **0**)
  - **2 guide-format articles** — [Adobe Express #7](https://www.adobe.com/uk/express/discover/examples/business-plan-presentation) (guide + examples gallery + editor), [PrometAI #8](https://prometai.app/blog/how-to-create-business-plan-presentation) (1,609 words + a linked real example deck)
  - **1 adjacent government guide** — [SBA #10](https://www.sba.gov/business-guide/plan-your-business/write-your-business-plan), about *writing* a plan, not presenting one (5,349 referring domains — ranking on raw authority for an adjacent topic)
- **What this means:** **Only 2 of 8 organic results are pure how-to articles, and both bundle a usable asset with the advice.** The #1 organic slot goes to a 784-word page with zero link equity whose value proposition is a downloadable PowerPoint template. Google has decided this query is mostly about *acquiring a deck*, and only partly about *learning to build one*.

### Intent match/mismatch

- **Current page type:** Blog article / educational how-to guide, 2,581 words, 1 image, no in-content downloadable deck, no example decks.
- **Match status:** ⚠️ **Partial mismatch**
- **Why:** The page competes only for the minority LEARN slots, and even there it is under-equipped. Both LEARN pages that outrank it pair guidance with an asset: Adobe with an examples gallery and an editor, PrometAI with a named, linked real-world deck. Meanwhile a 784-word page with **URL Rating 0** takes the #1 organic position purely on the strength of a downloadable template — the clearest possible evidence that the missing ingredient is a usable asset, not authority, and not word count (this page is already 3.3× longer than that #1 result).
- **The strategic read:** do **not** rebuild this page as a template gallery — Upmetrics cannot beat Canva or Slidesgo at hosting slide templates, and the commercial intent is already served by [features/pitch-deck](https://upmetrics.co/features/pitch-deck). The winnable position is the one Adobe and PrometAI occupy: **the definitive guide that also hands the reader a deck and shows them real annotated examples.** That is the only slot on this SERP where Upmetrics has a structural advantage — it owns an AI pitch deck generator, which is a better asset than a static .pptx file.

### SERP Features

| Feature | Present? | Who Owns It | Can We Win? | Action |
|---------|----------|-------------|-------------|--------|
| **AI Overview** | ✅ Yes — occupies **position 1 entirely**, with 24 cited sitelinks and 7 video thumbnails | Google. Cited sources skew to template galleries (Slidesgo, SlidesCarnival, SlideTeam, Canva, Presentation Base, Showell) and YouTube, plus guides (USF, Adobe, Indeed, Lendio, PrometAI, SlideStack, SBA). **⚠️ LivePlan is cited; Upmetrics is not.** | **Partially** — citation is realistic, ownership is not | Restructure for extractability: an answer-first summary block near the top, plus one-sentence direct answers opening each H2. This is the single highest-leverage structural change. → Update Brief §14E |
| **Featured Snippet** | ❌ No classic snippet returned in the top 10 | Nobody — the AI Overview has displaced it | n/a | Treat the snippet opportunity as an **AI Overview citation** opportunity instead. No separate snippet play exists for this query. |
| **People Also Ask** | ✅ Yes — a 4-question block at **position 5** | Google | **Yes** | The page has FAQPage schema and 5 FAQ questions, but they sit in an accordion *outside* the article content area and answer only 1 of the 4 confirmed PAA themes (the 10-20-30 rule). Move the numeric answers into body content. → Update Brief §14D/§14E |
| **Video results** | ✅ Yes — **7 distinct YouTube videos** cited inside the AI Overview with thumbnails | YouTube creators ("7 Business Plan Presentation Tips", "5 Tips for Presenting Your Business Plan", "How to present your business plan with impact") | Not organically, but embeddable | Video is a materially rewarded format here and this page embeds none. Consider embedding one relevant Upmetrics video. → Update Brief §14E (low priority, production-dependent) |
| **Image pack** | ✅ Effectively — nearly every AI Overview sitelink carries an `image_th` thumbnail marker | Distributed across template sites | **Yes** | Google is surfacing *slide imagery* for this query. The page has **1 content image**; SlideModel has 21 and SlideUpLift has 22. → Update Brief §14E |
| **Knowledge panel** | ❌ No | — | — | No action. |

**Organic results start at position 2.** The AI Overview consumes position 1 in full; a PAA block interrupts again at position 5. Even at position 5-6 organic, real above-the-fold visibility on this SERP is compressed — which raises the bar for how far the page needs to climb before clicks materialise, and reinforces that AI Overview citation matters as much as blue-link position here.

### Featured Snippet Optimization

**No classic featured snippet opportunities identified** — no `featured_snippet` feature is present in the top 10 for this query, and the AI Overview at position 1 has absorbed that real estate. The equivalent opportunity is AI Overview citation, addressed in the table above and routed to the Update Brief.

**Note on PAA question wording:** Ahrefs confirms a PAA block of exactly 4 questions at position 5 but does not return their text. The four question *themes* — presentation length/runtime, slide count, what to include, and the 10-20-30 rule — are confirmed across every top-ranking guide in the SERP corpus and are safe to build against. The **exact PAA wording is [UNABLE TO CONFIRM — a manual SERP check is recommended]** before finalising FAQ copy.

---

## 5. TECHNICAL SEO (Failures Only)

Evaluated against `step1a-target-page.json` and `verified-facts.json`. **Passing checks are omitted.** For the record, the following passed and need no work: canonical (self-referencing), no `noindex`, no redirect, single H1 containing the primary keyword, H1 correctly differs from the title tag, meta description length (145 chars, in range), Open Graph tags present, Twitter card tags present (`summary_large_image`), all content images have alt text (1/1), clean keyword-bearing URL slug, FAQPage schema present, Article schema present with correct `datePublished`/`dateModified`.

### Issues Found

| # | Issue | Current | Fix | SEO Impact |
|---|-------|---------|-----|------------|
| 1 | **Two conflicting `BreadcrumbList` declarations, one containing a URL that does not exist** | Block A (Yoast `@graph`, `@id …#breadcrumb`): Home → Article, 2 levels, names position 1 "Business Plan Software". Block B (standalone JSON-LD): upmetrics → blog → Article, 3 levels, and points the "blog" node at `https://upmetrics.co/post` — the blog actually lives at [https://upmetrics.co/blog](https://upmetrics.co/blog) | Delete Block B entirely. Keep the Yoast `@graph` breadcrumb, which is correctly `@id`-referenced from the `WebPage` node. If a 3-level Home → Blog → Article trail is wanted, add it inside the `@graph` block with the correct `/blog` URL. | Conflicting breadcrumb markup can suppress breadcrumb rich results in the SERP; the invalid `/post` URL is a structured-data error. Sitewide impact if the block is template-level. → §2 item 3 |
| 2 | **Article author is declared as `@type: Person` but is a company** | `{"@type":"Person","name":"Upmetrics","description":"Upmetrics is the #1 business planning software that helps entrepreneurs…","url":"https://upmetrics.co/author/upmetrics"}` — a corporate boilerplate description on a `Person` entity | Retype the node as `@type: Organization`, **or** attribute the article to a named human author with a real bio. See §8 for the E-E-A-T case for the second option. | Invalid entity typing weakens author/publisher signal interpretation. Every competitor with a genuine E-E-A-T advantage on this SERP ([LivePlan](https://www.liveplan.com/blog/funding/business-plan-presentation), [USF](https://guides.lib.usf.edu/business-plan/how-to-pitch)) uses named humans. → §2 item 4 |
| 3 | **Title tag is 43 characters — 7-17 chars below the usable range** | `How to Create a Business Plan Presentation?` | → **See §2 "Title & Meta Copy" for the rewrite.** | Wastes available SERP pixel width and omits the asset modifiers (examples, template, slides) that every top-ranking guide title carries. → §2 item 1 |
| 4 | **FAQ content sits outside the article content container** | The 5 FAQ questions and their answers render outside `.blog-content-area` (confirmed: FAQ headings appear in the document-wide heading list but not in the extracted content sections, and the FAQ body text is absent from the extracted article text). FAQPage schema **is** correctly present. | Low priority and **verify before acting** — the content is in the DOM and schema-eligible, so this may be purely a template-layout artifact with no ranking effect. The actionable part is editorial, not technical: move the *numeric* answers (slide count, runtime) into body prose where they can be extracted for the AI Overview. → Update Brief §14E | The FAQ's ~200 words are excluded from the main content block. Real risk is low; the extractability gain from moving key answers into body content is the actual prize. |

**Not flagged, deliberately:**
- `hreflang` is empty — correct for a single-locale property. No action.
- `robots` meta absent — defaults to `index, follow`. Correct.
- Article schema self-reports `wordCount: 2596` vs. the scraper's 2,581 — a 0.6% variance that *validates* the extraction. No action.
- No `VideoObject` schema — the page embeds no video, so there is nothing to mark up. If a video is added per §4, add the schema then.
- No `HowTo` schema recommendation — Google deprecated HowTo rich results in 2023. Adding it would gain nothing.

---

## 6. CONTENT GAPS & COMPETITOR DEPTH

**Competitor set:** 7 pages. Three from the Ahrefs top 10 (the only guide-format results there), four additional guide-format pages that rank for the exact primary keyword in live Google but sit outside Ahrefs' top-10 snapshot. Template galleries (Canva, Slidesgo, Beautiful.ai) and the SlideShare sample deck were deliberately **not** scraped — they are a different content type, and their role in the analysis is the intent evidence in §4.

**⚠️ Word count methodology:** article-body extraction only (excludes nav, footer, sidebar, CTAs). The target page uses the site-specific `.blog-content-area` selector; competitors use the universal content-area detector. Treat as directionally comparable. The target's FAQ (~200 words) falls outside its content selector and is therefore excluded from its 2,581 — competitor FAQ text is generally included, so **the target's true comparable length is marginally higher than shown**, which strengthens rather than weakens the conclusion below.

### 6A. Content Depth Comparison

| Page | URL | Content Type | Word Count | H2s | H3s | Images/Visuals | FAQs | 3rd-Party Citations | Downloads |
|------|-----|-------------|-----------|-----|-----|--------|------|-----------|-----------|
| **OURS** | [upmetrics.co/blog/business-plan-presentation](https://upmetrics.co/blog/business-plan-presentation) | Blog guide | **2,581** | 7 | 29 (+3 H4) | **1** | 5 | **0** (bls.gov link is a "go find data here" pointer, not a source; other 4 external links are Upmetrics' own socials) | 3 links, **all outside the content area**, none a slide deck |
| C1 — Adobe *(pos 7)* | [adobe.com/uk/express/discover/examples/business-plan-presentation](https://www.adobe.com/uk/express/discover/examples/business-plan-presentation) | Guide + examples gallery | *[SCRAPE FAILED]* | — | — | — | — | — | Adobe Express editor *(inferred from URL pattern — unverified)* |
| C2 — PrometAI *(pos 8)* | [prometai.app/blog/how-to-create-business-plan-presentation](https://prometai.app/blog/how-to-create-business-plan-presentation) | Blog article | 1,609 | 7 | 25 | 2 | 6 | 0 | Template + 1 named real example deck |
| C3 — USF LibGuides *(pos 2)* | [guides.lib.usf.edu/business-plan/how-to-pitch](https://guides.lib.usf.edu/business-plan/how-to-pitch) | **Template-led resource** | **784** | 10 | 0 | 0 | 0 | 3 (named textbooks) | **Business Plan Pitch PowerPoint Template** |
| C4 — SlideModel | [slidemodel.com/business-plan-presentation/](https://slidemodel.com/business-plan-presentation/) | Blog article | **5,129** | 7 | 14 (+37 H4) | **21** | **11** | 0 | 9 industry-specific deck templates |
| C5 — LivePlan ⚠️ | [liveplan.com/blog/funding/business-plan-presentation](https://www.liveplan.com/blog/funding/business-plan-presentation) | Blog article | 1,905 | 8 | 16 | 4 | 2 | 0 (3 external links are own properties) | Free pitch deck template (offered twice) |
| C6 — SlideUpLift | [slideuplift.com/blog/business-plan-presentation/](https://slideuplift.com/blog/business-plan-presentation/) | Blog article | 2,577 | **15** | 15 | **22** | 9 | 0 | Free example deck in **both PPT and PDF** |
| C7 — Prezent | [prezent.ai/zenpedia/business-plan-presentation-guide](https://www.prezent.ai/zenpedia/business-plan-presentation-guide) | Blog article | 2,267 | 9 | 0 (+12 H4) | 0 | 7 | **4 (HBR, CB Insights, Glassdoor, UC Berkeley)** | None |
| | | **Average of 6 scraped competitors** | **2,379** | 9.3 | — | 8.2 | 5.8 | 1.2 | 5 of 6 offer a deck asset |

⚠️ **C5 is liveplan.com — a `COMPETITOR_DOMAINS` entry. Never link to it from Upmetrics content.**

**Three findings jump out of this table:**

1. **Length is not the problem — stop thinking about word count.** At 2,581 words the target already exceeds the competitor average of 2,379 and beats 4 of 6 scraped competitors. The #1 organic result on the SERP is **784 words**, less than a third of the target's length. Any recommendation to "make it longer" would be wrong; the update should add *substance and assets*, and may well trim prose in places.
2. **Visual density is the starkest single gap.** 1 image versus SlideUpLift's 22 and SlideModel's 21. For a query about *slide decks*, where Google is surfacing image thumbnails throughout the AI Overview, publishing one graphic in 2,581 words is the most conspicuous deficiency on the page.
3. **A citation advantage is sitting unclaimed.** Five of six scraped competitors have **zero** third-party citations — SlideModel makes nine specific numeric claims across 5,129 words and sources none of them. Only Prezent cites anything (4 sources: HBR, CB Insights, Glassdoor, UC Berkeley). The target currently has 0 as well. Adding 4-6 genuinely sourced statistics would make this the **best-sourced page on the SERP** — a cheap, defensible differentiator, and exactly the kind of signal AI Overviews favour when selecting citations.

### 6B. Competitor Heading Map

Legend: **C1** Adobe *(unscraped — excluded from counts)* · **C2** PrometAI · **C3** USF · **C4** SlideModel · **C5** LivePlan · **C6** SlideUpLift · **C7** Prezent

| Topic / Section | C2 | C3 | C4 | C5 | C6 | C7 | OURS | Action |
|----------------|----|----|----|----|----|----|------|--------|
| What is a business plan presentation (definition) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| Why present / benefits of a deck | ✅ | ✗ | ✗ | ✅ | ✗ | ✅ | ✅ | ✅ table stakes — ours is the most structured (4 named benefits) |
| Slide-by-slide content checklist | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| Market analysis broken into industry / target market / competitive sub-slides | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ✅ **UNIQUE EDGE** — keep and promote; no competitor decomposes this |
| Design tips (fonts, visual balance, clear writing) | ✅ | ✗ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ table stakes |
| **Executive Summary as a named slide** | ✅ | ✗ | ✅ | ✗ | ✅ | ✅ | **✗** | **✗ GAP** — 4 of 6 include it; our 11-slide checklist omits it entirely |
| **Real annotated deck examples (named companies)** | ✅ (1) | ✗ | ✅ (running case study) | ✅ (links 7 teardowns) | ✅ (8 teardowns) | ✗ | **✗** | **✗ GAP — highest priority.** 4 of 6 competitors show real decks; we show zero |
| **Downloadable slide deck / presentation template** | ✅ | ✅ | ✅ | ✅ | ✅ | ✗ | **✗** | **✗ GAP + Upmetrics** — 5 of 6 offer one. Our 3 template links sit outside the content area and none is a *presentation* deck |
| **Slide visuals / screenshots of each slide** | ✅ (2) | ✗ | ✅ (21) | ✅ (4) | ✅ (22) | ✗ | **✗ (1)** | **✗ GAP** — the most visible deficiency on the page |
| **Mistakes to avoid / don'ts** | ✅ | ✗ | ✅ | ✗ | ✅ | ✅ | **✗** | **✗ GAP** — 4 of 6 cover it |
| **Investor Q&A preparation / anticipating questions** | ✅ (368 words, its longest section) | ✅ (defend your numbers) | ✗ | ✅ (appendix-slide tactic) | ✅ (build an expected-questions list) | ✗ | **✗** | **✗ GAP** — 4 of 6 cover it; PrometAI's is its single biggest section |
| **Concrete slide count + runtime stated in body content** | ✗ | ✗ | ✅ (13-20 slides, 20-30 min) | ✅ (10-12 slides, 10-20 min, 30pt font) | ✅ (10-12 slides, 10-20 min, ×5 mentions) | ✅ (10-12 slides, 20-30 min) | **✗** | **✗ GAP** — 4 of 6 state numbers in prose; ours appear only inside one FAQ answer (10-20-30 rule), outside the content area |
| **Business plan vs. business plan presentation (explicit distinction)** | ✅ | ✗ | ✅ | ✅ | ✅ | ✗ | **✗** | **✗ GAP** — 4 of 6 draw the distinction; we conflate deck and plan throughout |
| Audience tailoring (investors vs. board vs. internal vs. partners) | ✅ | ✗ | ✅ (3 variants) | ✅ (worked example) | ✅ | ✅ | ⚠️ | **✅ go deeper** — we have a 315-char "Know your audience" tip; 5 competitors give differentiated guidance |
| **Delivery mechanics (eye contact, pace, not reading slides, rehearsal)** | ✅ | ✗ | ✅ | ✅ | ✅ | ✅ | ⚠️ | **✅ go deeper** — we have 3 short pitching tips; this is the query cluster with the strongest upward momentum (§3) |
| **Named strategic frameworks (SWOT / Porter / PESTEL / value-prop canvas)** | ✗ | ✗ | ✅ (SWOT, Porter, PESTEL) | ✗ | ✅ (product + value-prop canvas) | ✅ (SWOT) | **✗** | **✗ GAP** — 3 of 6 name frameworks as specific slides |
| **Risk / contingency slide** | ✗ | ✗ | ✅ (risk eval + sensitivity analysis) | ✗ | ✅ (risk + contingency plan) | ✗ | **✗** | **✗ GAP** (2 competitors, both substantial) |
| **Appendix slide strategy** | ✗ | ✗ | ✗ | ✅ (pre-built answer slides) | ✅ (move dense data to appendix) | ✗ | **✗** | **✗ GAP** (2 competitors) |
| Format comparison (PowerPoint / Google Slides / PDF / Keynote / video) | ✗ | ✗ | ✅ (4-way) | ✗ | ✅ (PPT + Slides) | ✅ (FAQ) | ⚠️ | **✅ go deeper** — we have one FAQ line; also maps to the `business plan keynote` query (9 impr @ 30.1) |
| Answer-first / AEO structure (summary block, direct-answer openers) | ✗ | ✗ | ✗ | ✅ (Key takeaways box) | ✅ (Quick Answer + bolded openers) | ✗ | **✗** | **✗ GAP** — the two competitors using it are the freshest and most AI-Overview-shaped |
| Types of business plans taxonomy | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ | ✗ | *Skip* — 1 competitor only, and it dilutes the presentation focus |
| Sourced third-party statistics | ✗ | ✗ | ✗ | ✗ | ✗ | ✅ (4) | **✗** | **✗ GAP → UNIQUE EDGE available** — 5 of 6 have none. Adding 4-6 sourced stats makes us best-in-SERP |
| Named human author with real bio | ✗ | ✅ (3 named librarians + emails) | ✗ | ✅ (Noah Parsons, deep credentials) | ✗ | ⚠️ (name only) | **✗** | **✗ GAP** → see §8 |
| Upmetrics AI pitch deck generator integration | ✗ | ✗ | ⚠️ (generic AI maker) | ✗ | ✗ | ⚠️ (Prezent product) | ✅ | ✅ **UNIQUE EDGE** — a live AI deck generator beats a static .pptx; underplayed today |

**Score: 13 hard GAPs, 4 "go deeper" items, 2 unique edges to protect.** Every ✗ GAP row drives a content addition in the Content Update Brief (Section 14E).

### 6C. Topic Gap Detail

| # | Missing Topic | Covered By | Evidence Source | Priority | Recommended Action |
|---|--------------|------------|----------------|----------|-------------------|
| 1 | **Real annotated deck examples from named companies** | C2 (1 linked deck), C4 (running FotoZoom case study across every slide), C5 (links a 7-deck teardown), C6 (8 teardowns: N26, WeWork, Redfin, Google, McKinsey, Snapchat, Visa, Pinterest) | Competitor scrape ×4; SERP intent (§4 — SlideShare's *sample deck* ranks #4 on DR 92) | **High** | Add an examples section with 3-5 real decks, each with a specific lesson. Upmetrics already owns [pitch-deck-examples](https://upmetrics.co/pitch-deck-examples) — surface and expand it in-content rather than building from scratch. |
| 2 | **Slide visuals / screenshots showing what each slide looks like** | C4 (21), C6 (22), C5 (4), C2 (2) | Competitor scrape; SERP `image_th` markers throughout the AI Overview (§4) | **High** | Add one visual per slide in the checklist (12 images). Biggest single lift available and directly addresses the image-pack signal. |
| 3 | **Executive Summary slide** | C2, C4, C6, C7 (4 of 6) | Competitor scrape ×4 | **High** | Insert as slide 2 in the checklist, taking the count from 11 to 12. SlideModel specifies a 2-slide maximum — a concrete number worth matching. |
| 4 | **Investor Q&A preparation** | C2 (368 words — its largest section, with 10 rehearsal questions), C3 (defend how sales goals were calculated), C5 (appendix answer-slides jumped to live), C6 (build an expected-questions list from the investor's POV) | Competitor scrape ×4 | **High** | New section after the checklist. Directly serves the fast-improving `presenting business plan` / `how to present a business plan` cluster (§3). |
| 5 | **Concrete slide count and runtime in body content** | C4 (13-20 slides, 20-30 min), C5 (10-12 slides, 10-20 min, 30pt font), C6 (10-12 slides, 10-20 min, repeated 5×), C7 (10-12 slides, 20-30 min) | Competitor scrape ×4; **confirmed PAA theme** (§4) | **High** | Put the numbers in prose near the top, not only in the FAQ. Note competitors disagree (10-12 vs. 13-20 vs. 15-30) — take a clear position and say why. C4 even contradicts itself within one article (13-20, then 15-30). |
| 6 | **Mistakes to avoid / don'ts** | C2 (3 named), C4 (4 don'ts), C6 (5 failure modes), C7 (8-item do's and don'ts) | Competitor scrape ×4 | **High** | New section before the CTA. |
| 7 | **Answer-first / AEO structure** | C5 (Key takeaways box), C6 (Quick Answer block + bolded direct answer opening every H2) | Competitor scrape ×2; **AI Overview at position 1 does not cite Upmetrics** (§4) | **High** | Add a ~70-word answer block above the intro and a one-sentence direct answer under each H2. Cheapest structural change with the highest AI-Overview upside. |
| 8 | **Business plan vs. business plan presentation distinction** | C2, C4, C5, C6 (4 of 6) | Competitor scrape ×4; **confirmed PAA/FAQ theme** across C4, C6 | **High** | Fold into the opening definition section. The page currently uses "business plan presentation" and "pitch deck" interchangeably without ever distinguishing deck from document. |
| 9 | **Sourced third-party statistics** | C7 only (HBR 16%, CB Insights 72%, Glassdoor 85%, UC Berkeley study) | Competitor scrape; **5 of 6 competitors have zero citations** | **High** | Add 4-6 verified sourced stats. This is a *gap that converts into a unique edge* — no other page on this SERP is well-sourced. Verify every URL before publishing (§8). |
| 10 | **Delivery mechanics depth** | C2 (no notes, eye contact, gestures, pace), C4, C5 (font floor), C6, C7 (don't read slides word-for-word, respect the time box) | Competitor scrape ×5; **strongest ranking momentum on the page** (§3: `how to present a business plan` 96.8 → 36.3) | **High** | Expand "How to Pitch to Investors?" from 3 thin tips into a full delivery section. The keyword data says Google is already leaning this way. |
| 11 | **Audience tailoring depth** | C4 (in-company / board / investors), C5 (medical-device worked example), C6 (investors vs. partners), C7 (investors / partners / employees), C2 | Competitor scrape ×5 | **Medium** | Expand the 315-character "Know your audience" tip into differentiated guidance for at least investors, board, and internal audiences. |
| 12 | **Named strategic frameworks as slides** | C4 (SWOT with a 3-points-per-quadrant rule, Porter's Five Forces, PESTEL), C6 (product canvas, value proposition canvas), C7 (SWOT) | Competitor scrape ×3 | **Medium** | Name SWOT and the value proposition canvas inside the relevant checklist slides. Do not add standalone framework sections — that is SlideModel's 5,129-word approach and it dilutes focus. |
| 13 | **Format comparison (PowerPoint / Google Slides / PDF / Keynote)** | C4 (4-way comparison incl. the PDF font-embedding caveat), C6 (PPT + Google Slides workflow), C7 (FAQ) | Competitor scrape ×3; GSC: `business plan keynote` 9 impr @ 30.1, `business plan in powerpoint` 2 impr @ 36 | **Medium** | Short comparison block or table. Picks up format-qualified long-tail the page already gets impressions for. |
| 14 | **Risk / contingency content** | C4 (risk evaluation + mitigation + sensitivity analysis), C6 (risk assessment in the pitch + contingency plan in the financials) | Competitor scrape ×2 | **Medium** | Add risk as a brief element inside the financial/funds slides rather than a standalone slide. |
| 15 | **Appendix slide strategy** | C5 (pre-build answer slides and jump to them during Q&A), C6 (move dense data to an appendix) | Competitor scrape ×2 | **Medium** | Fold into the new investor-Q&A section (#4) — the two topics are the same tactic. |
| 16 | **In-content downloadable deck asset** | C3, C4, C5, C6 (+C1 inferred) — 5 of 6 | Competitor scrape ×5; **the #1 organic result (784 words, URL Rating 0) ranks on exactly this** (§4) | **High** | ⚠️ **Read carefully:** `verified-facts.json` confirms 3 template links already exist on the page, so this is *not* "add a template" — it is a **placement and specificity** fix. The 3 existing links sit outside the article content area and none is a presentation deck. Surface [/download/investor-pitch-templates](https://upmetrics.co/download/investor-pitch-templates) prominently *inside* the content, and lead with the [AI pitch deck generator](https://upmetrics.co/features/pitch-deck) — a live generator is a stronger asset than any static .pptx a competitor offers. |

**No UGC-sourced gaps.** No Reddit or Quora threads appear in the Ahrefs top 10 or in either WebSearch pass, so no UGC data was collected (per CLAUDE.md, no additional searches were run to find them).

**Unanswered PAA themes:** 3 of the 4 confirmed PAA themes (runtime, slide count, what to include as prose) are addressed by gaps #5 and #3 above. The fourth (10-20-30 rule) is already answered — but only inside the FAQ accordion, outside the content area.

---

## 7. LINKS & BACKLINKS

### 7A. Internal Link Issues

The page carries 77 internal links in the DOM, of which roughly 14 are in-content editorial links and ~63 are global navigation, footer, and social-share links. Every in-content link points to a live Upmetrics page on a genuinely related topic, and the anchor text is descriptive throughout (`your market analysis`, `competitive advantage`, `day-to-day business operations`, `how to pitch to investors`).

**No internal link issues found — all ~14 in-content internal links are healthy.**

One observation rather than an issue: the in-content link density is well-judged, but **the ratio of navigational to editorial links (roughly 4.5:1) means the page's ~63 boilerplate links dilute the equity flowing through its 14 editorial ones.** That is a sitewide template characteristic, not a fault of this page, and is out of scope for this audit.

### 7B. Internal Links to ADD

**⚠️ Rule 12 compliance:** every URL below was verified as a real, indexed page before inclusion. No URL was constructed, guessed, or inferred from a slug pattern. The `Source` column names the verification method.

| Anchor Text | Target URL | Where to Place | Why | Source |
|------------|-----------|----------------|-----|--------|
| `business plan for investors` | [https://upmetrics.co/blog/business-plan-for-investors](https://upmetrics.co/blog/business-plan-for-investors) | Inside "11. Funds Being Raised" | The page's investor-facing funding section has no onward path to Upmetrics' dedicated investor-plan content. That page draws 61 impressions on `business plan writers for investor presentations` at position 55.8 — a real, indexed, ranking page. | **GSC** (`step1b-cannibalization.json`) |
| `complete business plan guide` | [https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide](https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide) | Inside "What is a Business Plan Presentation?", alongside the new plan-vs-deck distinction (§6C gap #8) | The deck-vs-document distinction is a confirmed content gap; when the page explains that the deck summarises the plan, it should link to the plan guide. Note this is a **different URL** from the `/blog/how-to-write-a-business-plan` the page already links to — both exist. | **GSC** (appears in cannibalization data for `how to present a business plan`) |
| `pitch deck creation service` | [https://upmetrics.co/services/pitch-deck](https://upmetrics.co/services/pitch-deck) | Inside "Create your Business Plan Presentation with Upmetrics" | The closing section offers only the DIY software path. The done-for-you service page is a real page drawing 6 impressions at position 68.2 on the investor-presentation commercial query — a natural conversion alternative for readers who do not want to build the deck themselves. | **GSC** (`step1b-cannibalization.json`) |
| `AI pitch deck generator` *(strengthen existing)* | [https://upmetrics.co/features/pitch-deck](https://upmetrics.co/features/pitch-deck) | Move higher — into "1. Use online resources" | Already linked 3× but only in the tips and closing sections. §6C gap #16 identifies the AI generator as the page's strongest differentiating asset against a SERP full of static templates; it should appear before the tips section. | **Target page's own `internalLinks`** (Step 1A) + **GSC** |
| `free investor pitch template` *(reposition existing)* | [https://upmetrics.co/download/investor-pitch-templates](https://upmetrics.co/download/investor-pitch-templates) | Move **into** the article body near the slide checklist | Currently sits outside `.blog-content-area` in a CTA block. §6C gap #16: the #1 organic result on this SERP ranks on precisely this asset type. This is a repositioning, not a new link. | **Target page's own `internalLinks`** (Step 1A) |

### 7C. Pages That Should Link TO This Page

**⚠️ Rule 12 compliance:** every source URL below is a verified real page. No URL was guessed.

| Source Page URL | Where to Add (placement on source page) | Suggested Sentence (anchor text) | Source |
|----------------|----------------------------------------|----------------------------------|--------|
| [https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide](https://upmetrics.co/blog/how-to-write-a-business-plan-complete-guide) | In the section covering what to do once the plan is written | "Once your plan is written, the next step is turning it into a **business plan presentation** for investors." | **GSC** — this page already surfaces for `how to present a business plan` (1 impr @ 50), confirming topical overlap and that it is indexed |
| [https://upmetrics.co/blog/business-plan-for-investors](https://upmetrics.co/blog/business-plan-for-investors) | Wherever the page discusses presenting or pitching to investors | "Investors rarely read the full document first — most decisions start with a **business plan presentation**." | **GSC** — 61 impressions at position 55.8 on the investor-presentation query; confirmed indexed and topically adjacent |
| [https://upmetrics.co/blog/how-to-make-pitch-deck](https://upmetrics.co/blog/how-to-make-pitch-deck) | In the introduction or a related-reading block | "For the longer-form version that walks through every slide, see our guide to the **business plan presentation**." | **Target page's own `internalLinks`** (Step 1A) — the target already links *to* this page, so it exists; the reciprocal link is missing |
| [https://upmetrics.co/pitch-deck-examples](https://upmetrics.co/pitch-deck-examples) | After the examples list | "Before you build, understand the structure — see how to create a **business plan presentation** slide by slide." | **Target page's own `internalLinks`** (Step 1A) — verified existing page; also the asset that resolves §6C gap #1, making the pairing mutually reinforcing |

*Note: the reciprocal-link opportunities with `/blog/how-to-make-pitch-deck` and `/pitch-deck-examples` are the highest-value of the four, because both are already topically bonded to the target page and the relationship is currently one-directional.*

### 7D. External Link Issues

The page has 5 outbound external links. **None points to a `COMPETITOR_DOMAINS` domain** — no links to liveplan.com, bizplan.com, growthink.com, bplans.com, or any other listed competitor. That is clean.

| # | Anchor Text | Target URL | Issue | Fix |
|---|------------|-----------|-------|-----|
| 1 | `BLS` | [https://www.bls.gov/](https://www.bls.gov/) | **Not a citation.** The link appears in "Industry Overview" inside the sentence *"Ensure that you collect data from highly authoritative sites like BLS and industry publications to increase the reliability of your research."* — it is advice to the reader about where to find data, not a source supporting any claim on the page. It also points at the bls.gov homepage rather than any specific dataset, and carries `rel="nofollow"`. | Keep the link (the advice is sound) but **deep-link it to a relevant BLS dataset** rather than the homepage, and drop the `nofollow` — a `.gov` statistical source is exactly the kind of editorial outbound link that should be followed. Separately, the page needs *actual* citations — routed to Update Brief §14E per §8 below. |
| 2-5 | *(no anchor — icons)* | facebook.com/upmetrics, x.com/upmetrics, linkedin.com/company/upmetrics-co, youtube.com/@Upmetrics | Not an issue. Upmetrics' own social profiles in the footer/share block, correctly `rel="noopener noreferrer"`. | No action. |

**Link status note:** `bls.gov` returned HTTP 403 to the automated fetch attempt. This is bot protection, **not a broken link** — bls.gov is live. No broken-link fix is required.

**The real external-link finding is an absence, not a defect:** across 2,581 words this page cites **zero** third-party sources. See §8.

### 7E. Backlink Gap

| Metric | Target Page | Avg Top 5 Organic Competitors |
|--------|------------|----------------------|
| Referring Domains | **2 live** (7 all-time — 71% decay) | ~13 *(from the 4 of 5 with data: Canva 1, SlideShare 6, Slidesgo 44, Adobe 1; USF not returned)* |
| Total Backlinks | **2 live** (51 all-time) | Not pulled — outside the 4-call API budget |
| URL Rating | Not returned by `backlinks-stats` | **4.2** (USF 0, Canva 6, SlideShare 4, Slidesgo 6, Adobe 5) |
| Domain Rating | Not pulled — outside the 4-call API budget | **89** (USF 87, Canva 93, SlideShare 92, Slidesgo 77, Adobe 96) |

*Sanity check passed: 2 live referring domains is a plausible page-level figure for a single blog post — `mode=exact` was honoured and this is not domain-level data.*

**Gap summary:**

- **Links are not the blocker, and the SERP proves it.** The #1 organic result — [guides.lib.usf.edu](https://guides.lib.usf.edu/business-plan/how-to-pitch) — has a **URL Rating of 0** and outranks pages from Canva (DR 93) and Adobe (DR 96). Two competitors in the top 5 have just **1 referring domain each**. At Keyword Difficulty 3, the target's 2 referring domains are sufficient to compete. **Do not spend link-building budget here before the content update ships** — it would be spent solving a problem the page does not have.
- **The one link action worth taking is defensive, not offensive.** The page has decayed from 7 all-time referring domains to 2 live, losing 71% of its historic link profile. Recovering even 3-4 of those lost placements is cheaper than net-new outreach. Pull the lost-links report manually from the Ahrefs UI (not via API — this audit is capped at 4 calls) and re-request the placements. → §2 item 10.
- **After the content update, one asset-led link angle becomes available.** [Prezent.ai already cites upmetrics.co](https://www.prezent.ai/zenpedia/business-plan-presentation-guide) as one of only 4 external sources on its competing guide — evidence that this topic space already links to Upmetrics editorially. Once the page carries genuinely sourced statistics and real annotated deck examples (§6C gaps #1 and #9), it becomes the only well-sourced page on a SERP where 5 of 6 competitors cite nothing. **That, not outreach volume, is the link acquisition strategy for this page.**

---

## 8. E-E-A-T & CITATIONS

*Read from `verified-facts.json`. The page already has an author attribution, a visible updated date, and a date in meta — **no action items were generated for those.***

### E-E-A-T Signal Comparison (gaps only)

| Signal | Target Page | Best Competitor | Gap? |
|--------|------------|----------------|------|
| Author bio | **None** — `author_has_bio: false`. Attribution is the brand name "Upmetrics" linking to `/author/upmetrics` | [LivePlan](https://www.liveplan.com/blog/funding/business-plan-presentation): Noah Parsons, with a substantive on-page credential bio (Yahoo! 1996 as one of its first 101 employees, Epinions.com, Princeton, COO of Palo Alto Software) | ⚠️ **Yes.** The strongest-credentialed competitor page is also the one Google cites in the AI Overview. |
| Author photo | **None** — `author_has_photo: false` | LivePlan (author headshot), USF (3 named librarians) | ⚠️ **Yes** — minor on its own, meaningful in combination with the bio gap. |
| Author entity type | Declared as `@type: Person` named "Upmetrics" with a **corporate** description — an invalid entity typing | LivePlan and USF both attribute to real, named humans | ⚠️ **Yes.** → §2 item 4 and §5 issue 2 |
| Named human experts offered for help | None | [USF LibGuides](https://guides.lib.usf.edu/business-plan/how-to-pitch): three named business librarians with email addresses, offered for 1:1 pitch help — and this page holds **position 2 with URL Rating 0** | ⚠️ **Yes.** The clearest demonstration on this SERP that human expertise signals outrank link equity. |
| Third-party cited sources | **0** | [Prezent](https://www.prezent.ai/zenpedia/business-plan-presentation-guide): 4 (HBR, CB Insights, Glassdoor, UC Berkeley) | ⚠️ **Yes** — but note 5 of 6 competitors also have 0, so this is a gap that converts into an edge. See §6C gap #9. |
| Expert quotes | 0 | 0 across **all** competitors — nobody on this SERP quotes an expert | ⚠️ **Yes, and entirely unclaimed.** A single sourced quote from an investor or accelerator partner would be unique on this SERP. |
| First-hand experience signals | None — no worked example, no case study, no "we did this" | [SlideModel](https://slidemodel.com/business-plan-presentation/): a running FotoZoom case study carried across every slide example; [SlideUpLift](https://slideuplift.com/blog/business-plan-presentation/): 8 real-company deck teardowns | ⚠️ **Yes** — the "Experience" pillar of E-E-A-T is absent. Overlaps §6C gap #1. |

**Signals with no gap (not listed above, for the record):** publish date ✅ present and visible; updated date ✅ present, visible, and **fresher than 4 of the 6 competitors** (2026-07-02 — only SlideUpLift at 2026-07-20 and LivePlan at 2026-05-13 are comparable, and PrometAI, SlideModel, USF and Prezent are all older or undated); author name ✅ present; publisher Organization schema ✅ present.

**The E-E-A-T read on this page:** freshness and publisher signals are genuinely strong and need no work. The deficit is entirely in **Experience and named human Expertise** — there is no author with credentials, no worked example, no first-hand evidence, and no sourced data. The two competitors that beat this page on nothing but E-E-A-T ([USF](https://guides.lib.usf.edu/business-plan/how-to-pitch) at position 2 with URL Rating 0, and [LivePlan](https://www.liveplan.com/blog/funding/business-plan-presentation) cited in the AI Overview) both win on named humans. Attributing this article to a real Upmetrics team member with a genuine business-planning bio is a low-cost, high-signal change.

### Citation Audit

The page contains **1 outbound editorial link (bls.gov) and 0 citations supporting its own claims.**

| Citation | URL Status | Source Quality | Issue (if any) |
|----------|-----------|---------------|----------------|
| `BLS` → [https://www.bls.gov/](https://www.bls.gov/) | Live (403 to automated fetch = bot protection, not a broken link) | High — US government statistical agency | **Not functioning as a citation.** It is reader advice on where to source data, links to the homepage rather than a dataset, and is `nofollow`ed. → §7D for the fix. |

**There are no other citations to audit.** This is not a "citations are healthy" result — it is a **complete absence of sourcing** across 2,581 words.

### Unsourced Claims

The page makes almost no quantified claims at all — a keyword sweep of the extracted article text for statistics, percentages, dollar figures, study references, and attribution language ("according to", "research shows", "survey") returned **exactly one match: the word "BLS"**. The problem is therefore not unsourced statistics; it is that the page asserts investor behaviour repeatedly without a single data point behind any of it.

| Unsourced Claim (exact quote) | Location | Recommended Source URL |
|------------------------------|----------|----------------------|
| "Investors want to know the viability and feasibility of your business idea to consider funding your business." | H3 "1. Secure the funding" | Needs a sourced investor-decision statistic. Prezent cites CB Insights for "72% of investors consider a business plan presentation an important factor" — **verify that figure at source on [cbinsights.com](https://www.cbinsights.com/) before reusing it; do not copy a competitor's citation on trust.** |
| "No one has time to dive into your detailed business plan" | H3 "2. Explain your business plan" | Assertion presented as fact with no support. Either source it or reframe as guidance rather than a claim about investor behaviour. |
| "Investors want to see the practical aspects of your business. They want to know if you have the skills and understanding essential for running a business." | H3 "8. Operations Plan" | Needs support. Candidate: an SBA or Harvard Business Review source on planning and business outcomes — **verify before publishing.** |
| "This is again the most important section, especially, if you are presenting in front of investors." | H3 "10. Financial Plan And Projections" | Two different sections are each called "the most important" (this one and "2. Problem"). Internally inconsistent and unsupported — resolve in the content update. |

**→ New citation recommendations are routed to the Content Update Brief (§14E)**, where the writer gets section-level context. **Broken external link fixes go to §2** — none are required here, since the only outbound editorial link resolves.

⚠️ **Verification requirement for the writer:** every statistic added must be verified at its original source and the URL confirmed to resolve. Do **not** reuse a competitor's cited figure without independently confirming it — Prezent's four statistics (HBR 16%, CB Insights 72%, Glassdoor 85%, UC Berkeley) are the only sourced numbers anywhere in this competitive set, which means they are also unverified by any second party.

---

## 9. APPENDIX

### Ahrefs API Consumption Log

| # | Call | Endpoint | Units |
|---|------|----------|-------|
| 0 | Subscription check *(free)* | `subscription-info-limits-and-usage` | 0 |
| 1 | Organic Keywords | `site-explorer-organic-keywords` | 50 |
| 2 | SERP Overview | `serp-overview` | 396 |
| 3 | Keyword Overview | `keywords-explorer-overview` | 50 |
| 4 | Backlinks Stats | `site-explorer-backlinks-stats` | 50 |
| | **Total this audit** | | **546** |

**Notes on API usage:**
- **Exactly 4 billable calls were made**, per the hard budget in `reference/ahrefs_api_budget.md`. No additional Ahrefs endpoints were queried.
- **Call 1 returned 0 rows** and therefore cost the 50-unit minimum instead of the estimated ~410. The target URL ranks for **no keyword with US volume ≥ 100** in Ahrefs' index. Per CLAUDE.md low-data handling this is not a failure, and it independently corroborates the GSC picture: the page accumulates impressions from page 2 but holds no tracked commercial-volume position. **It was deliberately not retried at a lower volume threshold**, which would have wasted units.
- **Call 1 was retried once** after an initial `bad where: invalid filter expression` error caused by malformed filter escaping on the first attempt. The failed attempt consumed 0 units.
- **Call 2 (SERP Overview) cost 396 units** — 36 rows × 11 units. The row count exceeded the expected 10 because Ahrefs returns each AI Overview sitelink and each PAA question as its own row. This is the correct behaviour for `top_positions: 10` on a SERP with a 24-sitelink AI Overview, and the extra rows were analytically valuable (they are the source of the §4 AI Overview citation analysis).
- **Total cost was 546 units against the ~630 estimate** — 13% under budget.

### Data Collection Log

| Step | Source | Result |
|------|--------|--------|
| 1A | Python scraper (`scrape_page.py`) | ✅ 2,581 words, 40 headings, 3 schema blocks, `verifiedFacts` produced |
| 1A-ii | Canonical / redirect / noindex validation | ✅ All clean — self-referencing canonical, no redirect, no noindex |
| 1B | Google Search Console (3 query types, 8 calls) | ✅ 95 queries · 1,688 impressions · 0 clicks · trends for top 10 · cannibalization checked on 6 queries |
| 1C | Ahrefs (4 calls) + WebSearch (2 calls) | ✅ KD 3, volume 450, 8 organic SERP results classified, AI Overview + PAA + video features captured |
| 1D | Python scraper competitor mode ×7 | ✅ 6 of 7 fully scraped. **Adobe Express failed** — Python scraper timed out at 30s, WebFetch fallback timed out at 60s; partial entry built from Ahrefs SERP data. Above the 2-competitor minimum. |
| 1D | UGC threads (Reddit/Quora) | ⬜ **None present in SERP** — no additional searches run, per CLAUDE.md. No UGC data in this audit. |
| 1D | Competitor enrichment subagent | ✅ 6 competitors enriched with content type, section summaries, unique topics, and statistics |

### Known Data Limitations

1. **Adobe Express (SERP position 7) could not be scraped.** Both the Python scraper and WebFetch timed out. Its analysis in §6A/§6B is limited to Ahrefs metadata and its title. No specific content gaps were attributed to it, and it is excluded from all competitor averages and gap counts.
2. **Exact PAA question wording is unconfirmed.** Ahrefs verifies a 4-question PAA block at position 5 but returns no text. The four themes are confirmed across the SERP corpus; the wording is not. A manual SERP check is recommended before finalising FAQ copy.
3. **Domain Rating for upmetrics.co was not pulled** — outside the 4-call API budget. The §7E Domain Rating comparison shows competitor values only.
4. **Total backlinks for competitors were not pulled** — outside the 4-call API budget. §7E compares referring domains and URL Rating, which were available from the SERP overview call.
5. **Competitor word counts use a universal content-area detector** while the target uses the site-specific `.blog-content-area` selector. Treat as directionally comparable. The target's FAQ (~200 words) falls outside its selector, so its true comparable length is marginally higher than the 2,581 shown — which strengthens the §6A conclusion that length is not the problem.

---

*Audit generated 2026-07-30 · Upmetrics SEO Page Audit · All data US-filtered · Companion document: Content Update Brief (`.docx`)*
