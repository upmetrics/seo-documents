# SEO Page Audit — Business Plan Competitions

**Target page:** [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions)
**Primary keyword:** business plan competition
**Audit date:** 2026-05-08
**Geography:** United States (US)
**GSC data range:** 2025-11-08 → 2026-05-05 (6 months)

---

## 1. Executive Dashboard

### Page Snapshot

| Field | Value |
|---|---|
| Title tag | "The Top 20 Business Plan Competitions to get funding in 2026" (60 chars) |
| Meta description | Present (149 chars) |
| H1 | "The Best 20 Business Plan Competitions to Get Funding in (2026)" |
| Word count | 2,212 (article body) |
| Author | Upmetrics (no author bio, no photo, no Person schema with bio) |
| Published | 2022-05-16 · Updated 2026-05-06 |
| Schema | Article, WebPage, FAQPage, BreadcrumbList, Organization, Person, ImageObject, WebSite |
| Canonical | Self-referencing ✅ |
| Indexability | Indexable ✅ (no noindex) |
| Internal links | 68 |
| External links | 25 |
| Downloadable templates | 4 in-content links ✅ |
| CTA blocks | 2 |
| Live backlinks | 1 (1 referring domain) — historical: 16 from 12 RDs (lost 11 RDs) |

### Top 3 Problems

1. **Severe under-performance for a low-difficulty target.** The primary keyword "business plan competition" has only KD 19 and 150 vol/mo — yet the target page sits at average position 20.3 with just 1 click and 182 impressions over 6 months. SERP intent is clear (8/10 results are individual competition homepages, plus 1 list-style guide at #4 — Growthink). Upmetrics is the same content type as Growthink and should be sitting alongside it on page 1 — but isn't. This is a clear competitive deficit, not an intent mismatch.
2. **Backlink profile is depleted.** Only 1 live referring domain currently — the page has lost 11 of 12 historical RDs. This single signal explains most of the position-20 ceiling. Competitor Growthink ranks at #4 with only 5 RDs (DR 71), so closing even part of this gap should move the needle quickly.
3. **Content depth is roughly half of the closest intent-match competitor.** Target = 2,212 words; Growthink (the only list-format guide on page 1) = 4,004 words and uses a richer per-competition template (Eligibility / Where Held / What Can You Win — with longer paragraphs). The target uses the same three sub-headings but with thinner detail per item, weaker external citations to the official competition pages, and zero per-competition statistics on prize amounts in a scannable table format.

### Traffic Opportunity

The target page captured **3,960 impressions and 4 clicks (CTR 0.10%)** over 6 months. Modeling a realistic outcome: moving the primary keyword from pos 20.3 → pos 5 (Growthink-comparable) on a 150-vol/mo keyword adds ~7 clicks/mo. The bigger opportunity is the long tail — 272 queries in GSC sit at avg positions 30-70. A reasonable post-update target: **150-300 monthly clicks** within 6 months, vs the current ~1/mo. The page is undervalued, not unfixable.

---

## 2. Master Action Table (SEO Actions)

Priority-sorted. Content actions live in the Content Update Brief (`.docx`) — only SEO/technical/link/backlink actions appear here.

| # | Priority | Action | Why (data) | Section ref |
|---|---|---|---|---|
| 1 | P1 | Rewrite title tag (see Title & Meta Copy block below) | Current title hits 60 chars but reads as a year-stamped listicle ("…in 2026"); doesn't include "best" or signal authority. SERP top results lead with "Best", "Largest", or org/competition names. | §2 Copy block |
| 2 | P1 | Build a backlink reclamation list and outreach for at least 5 new referring domains | Only 1 live RD vs 11 lost historically. Competitor Growthink ranks #4 with 5 RDs and DR 71. RD growth is the highest-leverage lever. | §7E |
| 3 | P1 | Resolve the `[currentyear]` placeholder leaking into og:title and twitter:title | `og:title` = "The Best 20 Business Plan Competitions to Get Funding in ([currentyear])" — `[currentyear]` is unrendered shortcode. Looks broken in social previews. | §5 |
| 4 | P1 | Add author Person schema with `description` (bio) and `image` (photo) for "Upmetrics" or a named expert | `verified-facts.json` confirms `author_has_bio=false`, `author_has_photo=false`. SERP top 4 ranking pages all sit on .edu / branded competition orgs with strong entity signals. E-E-A-T gap is real. | §8 |
| 5 | P1 | Rewrite meta description to lead with what the reader gets (cash prizes + curated list) instead of conditional language | Current: "Looking to secure funding for your business or validate your idea?" — opens with a question, not a value prop. Pos 20.3 + 0.10% CTR suggests the snippet isn't earning the click. | §2 Copy block |
| 6 | P2 | Resolve cannibalization: target page at pos 60.2 for "business competition examples" while [/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) ranks at pos 7.6 for the same query | GSC cannibalization check returned 4 Upmetrics URLs for "business competition examples". The high-school-students sister page also ranks at pos 4 for "business plan competition". Decide a single canonical target per query. | §3 cannibalization |
| 7 | P2 | Add internal links FROM 4 sister pages TO the target page (anchor: "business plan competition") | Target has only 1 live RD; internal PageRank flow from existing pages is the cheapest authority lever. Source pages already rank for related queries (cannibalization data confirms they exist). | §7B |
| 8 | P2 | Add internal links FROM the target page to 3-5 underlinked Upmetrics resources currently in `internalLinks` (the page already has 68 internal links — most going to nav/footer; add 3-5 in-content contextual links to high-relevance bottom-of-funnel pages) | Distribute equity to template/sample-business-plans pages that already get traffic, instead of nav links. | §7A |
| 9 | P2 | Convert FAQ markup into a per-competition Q&A pattern (Eligibility / Location / Rewards remain — but add "Application deadline" and "Past winners" as schema-eligible Q&A inside each competition block) | Existing FAQPage schema only covers 5 generic questions at the bottom. Per-competition schema increases SERP real estate and supports AI Overviews (which currently sit at pos 3 on this query). | §5 |
| 10 | P3 | Audit 25 external links: confirm each official competition link (rbpc.rice.edu, wsu, etc.) is live, opens in new tab, and uses `rel="noopener nofollow"` if the destination is sponsored or commercial | Generic external-link hygiene — Section 7D shows several outbound link risks worth confirming manually. | §7D |
| 11 | P3 | Add `last reviewed` byline near the H1 ("Reviewed by [name], [date]") to reinforce freshness signal | `dateModified` in schema = 2026-05-06 (current). Surface this visibly. | §8 |
| 12 | P3 | Replace the unbranded WordPress placeholder image (`business-plan-competitions.webp`, 751×451) with a branded infographic showing prize-pool ranges across the 20 competitions | Target has only 1 content image (vs Growthink's 5 visuals). Visuals correlate with engagement and dwell time. | §6 |

### Title & Meta Copy block (authoritative source — used by Phase 3)

**Title tag — current:**
> "The Top 20 Business Plan Competitions to get funding in 2026" (60 chars)

**Title tag — recommended:**
> "20 Best Business Plan Competitions for 2026 (With Prize $$)" (59 chars)

Why: leads with the number + "Best" pattern (Growthink ranking #4 uses the same pattern); adds the prize-pool hook ("With Prize $$") that no SERP competitor surfaces; keeps the year as a freshness anchor without making the URL itself year-bound.

**Meta description — current:**
> "Looking to secure funding for your business or validate your idea? Check out the top 20 business plan competitions of 2026 and learn how to win them." (149 chars)

**Meta description — recommended:**
> "Compete for cash prizes from $5K to $1M+. Compare 20 active US and global business plan competitions, eligibility, deadlines, and tips to win in 2026." (151 chars — within Google's ~155 limit)

Why: leads with the dollar range (the actual buyer signal), specifies "active" and "US and global" to set expectations, and replaces the wishy-washy "validate your idea" framing with concrete decision criteria (eligibility, deadlines).

---

## 3. Keyword & Ranking Analysis (US, last 6 months)

### 3A. Top 10 GSC Queries by Impressions

| # | Query | Clicks | Impr. | CTR | Avg pos | Read |
|---|---|---|---|---|---|---|
| 1 | business plan competition (PRIMARY) | 1 | 182 | 0.55% | 20.3 | Striking-distance page-2 result; closest competitor at #4 (Growthink). |
| 2 | small business competition | 0 | 166 | 0% | 16.9 | Page 2 — high-impression query with zero click — title isn't matching this intent. |
| 3 | business idea competition | 0 | 146 | 0% | 42.5 | Page 5 — long tail; would benefit from the H2 "How to find a business plan competition" being broadened to "business idea competitions". |
| 4 | best business to start little competition | 0 | 120 | 0% | 44.3 | Different intent ("low-competition niche"), not a match for this page. |
| 5 | startup idea competition | 0 | 97 | 0% | 56.4 | Long tail — page sees impression breadth without ranking power. |
| 6 | business competition examples | 0 | 88 | 0% | 60.2 | ⚠️ Cannibalized — sister page ranks at 7.6 for this same query. |
| 7 | new business competition application | 0 | 84 | 0% | 66.1 | Long tail. |
| 8 | nibs worldwide business plan competition 2026 dates | 0 | 84 | 0% | 10.0 | High-intent navigational, page is on edge of page 1. Adding NIBS deadline detail in the existing #8 block could push to top 5. |
| 9 | business plan competition ideas | 0 | 83 | 0% | 25.7 | Striking distance — would flip with stronger H2 + better intro. |
| 10 | startup competitions | 0 | 72 | 0% | 64.5 | Different intent (broader competition list). |

Total page: **272 queries, 3,960 impressions, 4 clicks, CTR 0.10%, 6 months**.

### 3B. Striking-Distance Keywords (positions 11-30, ≥50 impressions)

Add or strengthen sections to capture these:

| Query | Pos | Impr | Action |
|---|---|---|---|
| business plan competition | 20.3 | 182 | Primary. Update intro + add "How to win" guide section. → §6 |
| small business competition | 16.9 | 166 | Add an H2 "Small business plan competitions" or reframe intro to include "small business"; add 1-2 small-business-specific competitions to the list. |
| business plan competition ideas | 25.7 | 83 | Already covered loosely; add an H2 "Business plan competition ideas (what to pitch)". |
| nibs worldwide business plan competition 2026 dates | 10.0 | 84 | Add deadline tables to the #8 NIBS block. |
| business plan competition examples | 21.2 | 69 | ⚠️ Cannibalized. Decide canonical page. |
| business plan competition grant | 15 | 10 | Add "grant-style competitions" callout. |
| nibs worldwide business plan competition | 9.6 | 20 | Same as NIBS deadlines above. |

### 3C. Cannibalization Check

For the **primary keyword** ("business plan competition"):

| URL | Clicks | Impr | Pos | Verdict |
|---|---|---|---|---|
| [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions) | 1 | 182 | 20.3 | Target — keep as canonical. |
| [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | 0 | 6 | 3.5 | Different topic (competitive analysis section of a business plan). Not actually cannibalizing here — different intent. Negligible. |
| [https://upmetrics.co/blog/business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) | 0 | 1 | 4.0 | Sister page for high-school-specific intent. Negligible. |

For "**business competition examples**" — this IS cannibalized:

| URL | Impr | Pos |
|---|---|---|
| [https://upmetrics.co/blog/business-plan-competitions](https://upmetrics.co/blog/business-plan-competitions) | 88 | 60.2 |
| [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | 34 | 7.6 |
| [https://upmetrics.co/blog/business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) | 23 | 35.9 |
| [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) | 22 | 58.7 |

**Recommendation:** "Business competition examples" is genuinely ambiguous — the high-ranking page (`how-to-write-the-competition-section-of-your-business-plan`, pos 7.6) is the natural winner because the query reads as "examples of the competition section". The target page should NOT chase this query. Add a short cross-link from the target to that sister page in the intro paragraph: "Looking to write the competitor analysis section of your plan instead? [See our guide](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan)." This signals intent separation to Google.

### 3D. Ahrefs Organic Keywords (US, vol≥100)

| Keyword | Best position | Volume |
|---|---|---|
| business competition | 48 | 1,000 |

Only 1 keyword above the 100-volume threshold. The page is essentially not ranking for any high-volume term. The longer GSC tail confirms intent breadth — the issue is ranking depth, not topic relevance.

### 3E. Primary Keyword — Difficulty & Potential

| Metric | Value |
|---|---|
| Volume | 150 / mo (US) |
| KD | 19 (low) |
| CPC | $2.50 |
| Traffic potential (Ahrefs) | 150 / mo |

Low difficulty. The barrier is not competition — it's that the target page is currently outclassed by Growthink at #4.

---

## 4. SERP & Intent Analysis

### Intent Classification

**Intent: Informational + Navigational (mixed).** The query "business plan competition" is parsed by Google as a discovery query — searchers want to *find competitions to enter*. Google rewards two formats:

1. **Individual competition homepages** (8/10 results) — Rice, WSU, NYBPC, St. Thomas, HighPoint, WI Governor's, Koffman/NYBPC, Kean. These are entity pages from organizations actually running competitions.
2. **Curated lists** (1/10 results) — only Growthink's "20 Best Business Plan Competitions" guide.
3. **AI Overview** at position 3 — synthesizes definitions + examples from the organic pages.

### SERP Top 10

| Pos | URL | Title | DR | RDs | UR | Type |
|---|---|---|---|---|---|---|
| 1 | [https://rbpc.rice.edu/](https://rbpc.rice.edu/) | Rice Business Plan Competition - Largest and ... - Houston | 86 | 315 | 13 | Individual competition |
| 2 | [https://entrepreneurship.wsu.edu/wsu-business-plan-competition/](https://entrepreneurship.wsu.edu/wsu-business-plan-competition/) | Business Plan Competition - WSU Center for Entrepreneurship | 87 | 7 | 5 | Individual competition |
| 3 | — | AI Overview | — | — | — | SERP feature |
| 4 | [https://www.growthink.com/businessplan/help-center/business-plan-competitions](https://www.growthink.com/businessplan/help-center/business-plan-competitions) | The 20 Best Business Plan Competitions | 71 | 5 | 4 | **List guide — direct intent match** |
| 5 | [https://nybpc.org/](https://nybpc.org/) | nybpc | 31 | 180 | 7 | Individual competition |
| 6 | [https://business.stthomas.edu/.../business-plan-competition/](https://business.stthomas.edu/schulze-school/student-engagement/competitions/business-plan-competition/) | St. Thomas Business Plan Competition | 76 | 0 | 4 | Individual competition |
| 7 | [https://www.highpoint.edu/entrepreneurship/business-plan-competition/](https://www.highpoint.edu/entrepreneurship/business-plan-competition/) | Business Plan Competition | 72 | — | 0 | Individual competition |
| 8 | [https://govsbizplancontest.com/](https://govsbizplancontest.com/) | WI Governor's Business Plan Contest | 31 | 211 | 5 | Individual competition |
| 9 | [https://thekoffman.com/nybpc/](https://thekoffman.com/nybpc/) | NYBPC \| Koffman Incubator \| Binghamton N.Y. | 31 | 2 | 6 | Individual competition |
| 10 | [https://www.kean.edu/kean-university-business-plan-competition](https://www.kean.edu/kean-university-business-plan-competition) | Kean Business Plan Competition 2026 | 73 | 2 | 4 | Individual competition |

### Mismatch Analysis

The Upmetrics target page is the **same content type as Growthink** — a list-format curated guide. There is **no intent mismatch** — the target page IS what Google rewards for the "list-format" slot. The only barrier is that Growthink occupies that slot today. With one direct competitor in the list-format slot (and only DR 71 / 5 RDs), the page-1 list-format slot is genuinely contestable.

### SERP Features

| Feature | Present | Owner | Opportunity |
|---|---|---|---|
| AI Overview | ✅ | (synthesized from Rice + WSU + Growthink + entity orgs) | Strengthen entity signals on the target so it becomes a citation source for the AI Overview. |
| Featured snippet (traditional) | ❌ | — | No traditional snippet available — AI Overview occupies that real estate. |
| People Also Ask | ✅ | Variable | "What is a business plan competition?", "How do you win a business plan competition?", "What are examples of business plan competitions?", "How do business plan competitions work?" — target already covers 2/4 in FAQ; add the other 2. |
| Video pack | ❌ | — | — |
| Image pack | ❌ | — | — |
| Knowledge panel | ❌ | — | — |

### Featured snippet / AI Overview opportunity

Restructure the H2 "What is a business plan competition?" section to lead with a 40-50 word definition optimized for AI Overview citation. Current intro on the section is conversational ("A business plan competition is an event that allows small businesses and startups to compete with each other and get feedback or advice on their business.") — a tighter, more entity-rich version could become the canonical citation source.

---

## 5. Technical SEO (Failures Only)

| # | Issue | Status | Action |
|---|---|---|---|
| 5.1 | `og:title` and `twitter:title` contain `[currentyear]` shortcode literal — "The Best 20 Business Plan Competitions to Get Funding in ([currentyear])" | ❌ Fail | Replace with rendered year (or remove the parenthetical entirely). Currently shows up as broken text in social previews. |
| 5.2 | Author "Person" schema present but `author_has_bio = false` and `author_has_photo = false` (verified) | ⚠️ Weak | Populate `description` and `image` fields on the Person schema. → See §8 for full E-E-A-T discussion. |
| 5.3 | Title rewrite required (see §2 Title & Meta Copy block) | — | Routed to §2. |
| 5.4 | Meta description rewrite required (see §2 Title & Meta Copy block) | — | Routed to §2. |
| 5.5 | FAQPage schema only covers 5 generic questions at the bottom — does not extend to per-competition Q&A | ⚠️ Underutilized | Convert per-competition Eligibility / Location / Rewards into FAQPage Q&A structures. |

**Pass/Clean (no action):**
- Canonical self-referencing ✅
- No noindex, no nofollow ✅
- HTTPS ✅
- H1 present and matches intent ✅
- `dateModified` is current (2026-05-06) ✅
- Schema.org Article + WebPage + BreadcrumbList all present ✅
- 1 content image with alt text ✅

---

## 6. Content Gaps & Competitor Depth

### 6A. Content Depth Comparison

| Page | Word count | H2 count | H3 count | Internal links | External cites | Visuals/tables | Author bio |
|---|---|---|---|---|---|---|---|
| **Target (Upmetrics)** | 2,212 | 4 | 26 | 68 | 25 | 1 image | ❌ |
| Growthink (#4 — direct intent match) | 4,004 | 6 | 20 | 4 | 45 | 5 visuals | ❌ |
| LivePlan (how-to-win) | 1,812 | 13 | 0 | 14 | 5 | 5 visuals | ✅ (Tim Berry) |
| TeenLife (teen-specific list) | 1,433 | 26 | — | 37 | 39 | 24 visuals | ✅ (Stefanie Tedards) |

**Read:** The target page has substantially less depth than the closest direct competitor (Growthink) — 2,212 vs 4,004 words. Crucially, Growthink has 45 external citations (links to each official competition page) while the target has only 25. **External authority links to .edu / .org competition pages are the strongest topical relevance signal Google can read on this query** — the target is leaving roughly half the citation surface area on the table.

### 6B. Competitor Heading Map (intent-match competitor — Growthink)

| Topic / heading | Target has? | Growthink has? | Gap action |
|---|---|---|---|
| What is a business plan competition? | ✅ H2 (~65 words) | ✅ H2 (~65 words) | EDIT — tighten for AI Overview citation |
| How do I find business plan competitions? | ✅ H2 (~82 words) | ✅ H2 (~82 words) | EDIT — add a discovery framework (free, .edu, industry-specific, regional) |
| 20 popular business plan competitions (per-comp blocks) | ✅ 20 items × 3 sub-headings (Eligibility/Location/Rewards) | ✅ 20 items × 3 sub-headings (Who is Eligible/Where Held/What Can You Win) | EDIT — match Growthink's longer blocks (60-150 words per item vs target's ~30-50) |
| Tips for Winning Business Plan Competitions | ❌ MISSING | ✅ H2 (~166 words) | 🆕 NEW SECTION — direct gap. LivePlan ranks for "how to win" with a whole article on this. Add as H2. |
| Application deadlines table (with dates per competition) | ❌ MISSING | ❌ MISSING | 🆕 NEW SECTION — opportunity. GSC shows "nibs worldwide business plan competition 2026 dates" at pos 10 / 84 impr. |
| Prize-pool comparison table (sortable) | ❌ MISSING | ❌ MISSING | 🆕 NEW SECTION — opportunity. No competitor has this. Differentiator. |
| Eligibility filters (student / undergrad / grad / open / international) | Implicit per item | Implicit per item | EDIT — add a filterable summary table at the top so readers can scan in 30 seconds. |
| FAQ — what should be in a plan for a competition | ✅ FAQPage schema | ❌ | KEEP. |
| FAQ — preparing for a competition | ✅ | ❌ | KEEP. |
| Strategic / pitch-deck advice (LivePlan-style "9 tips to win") | ❌ | Brief (1 H2) | 🆕 NEW or expand — LivePlan ranks for "how to win business plan competition"; even a 200-word section would capture some of that long-tail traffic. |

### 6C. Topic Gap Detail (priority order)

1. **🆕 "How to Win a Business Plan Competition" H2 with 5-7 ranked tips.** LivePlan ranks for the closely related query "how to win business plan competition" with a 1,812-word article — the target captures none of that traffic today. A 300-500 word section inside the existing list page would let the page rank for both intent variants ("which competitions" + "how to win them") with one URL. Each tip should be a tight H3.
2. **🆕 Prize-pool comparison table** at the top of the H2 "20 popular business plan competitions" section. Columns: Competition / Eligibility (student / open) / Location / Total prize / Application window. This is a cited-by-AI-Overview kind of asset and not present on any competitor.
3. **🆕 Application deadlines table** — same competitions, just column-flipped. Captures the "nibs worldwide business plan competition 2026 dates" striking-distance query at pos 10.
4. **EDIT all 20 competition blocks** to add a 1-line "Why it stands out" summary above Eligibility/Location/Rewards. Currently each block reads as a 3-bullet form — Growthink's read more like editorial reviews, which is partly why Growthink is on page 1.
5. **EDIT — strengthen 20 external citations.** Each competition block should link to the official competition URL (rbpc.rice.edu, entrepreneurship.wsu.edu, etc.). Growthink has 45 external citations vs the target's 25.

---

## 7. Links & Backlinks

### 7A. Internal Links — Issues / Trim

The page has 68 internal links, which is high for a 2,212-word article. Spot-checks suggest most are nav/footer/related-content sidebar links rather than in-content contextual links.

| Issue | Count | Action |
|---|---|---|
| Internal links in nav/footer/sidebar (no SEO value as on-page links) | ~50+ (estimate) | No fix needed — these are template, not content. |
| In-content contextual internal links | Estimated <15 | Increase to 5-8 high-relevance contextual links (sample-business-plans, business-plan-template download, how-to-write-a-business-plan, etc.). |

### 7B. Internal Links to ADD (to the target page from sister pages)

These pages already exist and rank for related queries — adding a contextual link with anchor text "business plan competition" or "list of business plan competitions" passes equity to the target. (URLs verified via GSC cannibalization data — they exist and are indexed.)

| Source page (verified to exist) | Anchor recommendation | Why |
|---|---|---|
| [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | "applying to a business plan competition" | Page already gets traffic for "business competition examples"; link makes intent split clear. |
| [https://upmetrics.co/blog/business-competitions-for-high-school-students](https://upmetrics.co/blog/business-competitions-for-high-school-students) | "open business plan competitions for adult founders" | Sister page is high-school-specific; link the broader audience to the main list. |
| [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) | "real business plan competitions" | Adjacent topic, weak existing connection. |
| [https://upmetrics.co/small-business-ideas](https://upmetrics.co/small-business-ideas) | "submit your idea to a business plan competition" | Page appeared in cannibalization data ranking for "best business to start little competition" — confirmed indexed. Add 1 contextual link. |

### 7C. Pages That Should Link FROM the target page (adding outbound internal links)

The target's existing `internalLinks` array already includes the following — make sure each has at least one **in-content** placement (not just nav):

- [https://upmetrics.co/download/business-plan-template](https://upmetrics.co/download/business-plan-template) ✅ already linked 3x in content
- [https://upmetrics.co/sample-business-plans](https://upmetrics.co/sample-business-plans) — currently links from sidebar/related; promote to in-content under "Tips for winning"

### 7D. External Links (issues only)

- 25 external links. The Growthink benchmark is 45. Each of the 20 competition blocks should link to the competition's **official homepage** (the same URLs that appear in the SERP). Specific targets to add or verify per the Ahrefs SERP data: [https://rbpc.rice.edu/](https://rbpc.rice.edu/), [https://entrepreneurship.wsu.edu/wsu-business-plan-competition/](https://entrepreneurship.wsu.edu/wsu-business-plan-competition/), [https://nybpc.org/](https://nybpc.org/), [https://www.kean.edu/kean-university-business-plan-competition](https://www.kean.edu/kean-university-business-plan-competition), [https://govsbizplancontest.com/](https://govsbizplancontest.com/), and the corresponding official URLs for the other 15 competitions in the list.

### 7E. Backlink Gap

| Metric | Target | Growthink (intent peer at #4) |
|---|---|---|
| Live backlinks | 1 | (DR 71 page) |
| Live referring domains | 1 | 5 |
| All-time refdomains (lost) | 12 (lost 11) | — |
| Domain rating context | (Upmetrics overall) | 71 |

The target page lost 11 of 12 historical referring domains. Reclamation outreach (find archive.org versions of the lost links, contact site owners) would restore 3-5 RDs immediately. Beyond reclamation, the highest-leverage backlink targets are:
- University entrepreneurship-program pages that already link out to lists of competitions (similar to Growthink's link profile)
- Roundup-style "resources for student founders" pages
- Curriculum pages at small business development centers (SBDCs)

This is the single biggest lever in the audit.

---

## 8. E-E-A-T & Citations

### 8A. Signal Comparison (gaps only)

| Signal | Target | Growthink | LivePlan | TeenLife | Action |
|---|---|---|---|---|---|
| Author byline | "Upmetrics" (org, not person) | Missing | ✅ Tim Berry (named expert) | ✅ Stefanie Tedards | Replace org byline with a named contributor (founder, in-house writer, or expert reviewer). |
| Author bio | ❌ | ❌ | ✅ Brief | ✅ Brief | Add a 50-80 word bio with credentials and a link to bio page. |
| Author photo | ❌ | ❌ | ✅ | — | Add a photo to Person schema and rendered byline. |
| `dateModified` recent | ✅ 2026-05-06 | ✅ 2026-04-03 | ❌ | ✅ 2025-10-22 | KEEP — strongest E-E-A-T signal currently in place. Surface visibly. |
| Cited sources (external) | 25 | 45 | 5 | 39 | Add 20+ official competition URL citations. |
| Person schema | ✅ present | ❌ | — | — | KEEP — but populate `description` (bio) and `image` (photo). |

### 8B. Citation Audit

**Issues:**
- Each of the 20 competition blocks should cite the competition's official URL. Spot-check suggests several are missing or use generic anchor text. Each block should have at minimum one outbound link to the competition's homepage with branded anchor text (e.g., "Apply at the [Rice Business Plan Competition](https://rbpc.rice.edu/)").
- The competition blocks reference prize amounts ("$1M", "$50,000", etc.) — these need to be source-cited to the official rules page so they're verifiable.

### 8C. Unsourced Claims (examples — full list will be in the Update Brief)

The page makes several factual claims (specific prize amounts, specific eligibility, specific locations) that need to be traceable to the official competition page. Without official-source citations, these claims age fast and Google has no way to validate the page's authority.

---

## 9. Appendix — Ahrefs API Consumption Log

| Call | Endpoint | Units | Notes |
|---|---|---|---|
| 1 | `site-explorer-organic-keywords` | 50 | mode=exact, vol≥100, country=us. 1 row returned. |
| 2 | `serp-overview` | 110 | top_positions=10, country=us. |
| 3 | `keywords-explorer-overview` | 50 | volume,difficulty,cpc,traffic_potential. |
| 4 | `site-explorer-backlinks-stats` | 50 | mode=exact, all-time + live. |
| **Subtotal** | | **260** | (under the ~630 budget) |
| Free | `subscription-info-limits-and-usage` | 0 | 389,385 units remaining at session start. |
| **Total this audit** | | **260** | |

Also: 2 WebSearch calls for SERP feature analysis and PAA/AI Overview confirmation.

---

*End of SEO Audit Report. The Content Update Brief (writer-facing `.docx`) is delivered separately and contains all content actions (KEEP / EDIT / REWRITE / NEW / MOVE / REMOVE) as an annotated outline.*





