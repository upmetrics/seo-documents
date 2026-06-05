# SEO Page Audit — Business Plan Questionnaire

**Page:** [https://upmetrics.co/blog/business-plan-questionnaire](https://upmetrics.co/blog/business-plan-questionnaire)
**Primary Keyword:** business plan questionnaire
**Audit Date:** 2026-06-05
**Brand:** Upmetrics
**Country:** United States

---

## 1. EXECUTIVE DASHBOARD

### Page Snapshot

| Metric | Value |
|--------|-------|
| URL | [https://upmetrics.co/blog/business-plan-questionnaire](https://upmetrics.co/blog/business-plan-questionnaire) |
| Primary Keyword | business plan questionnaire |
| Primary KW — US Search Volume | 20/mo (Ahrefs) |
| Primary KW — Current Position | 19.4 avg (GSC, 179 impressions / 0 clicks over 6mo) |
| Primary KW — Keyword Difficulty | 0 (Ahrefs) |
| Title Tag | `The Ultimate Business Plan Questionnaire You Need In 2026` (57 chars) |
| Meta Description | `Go through this questionnaire to cover all essential aspects of your business plan, from defining goals to refining strategies and preparing financial forecasts.` (161 chars — 1 over limit) |
| H1 | `The Ultimate Business Plan Questionnaire You Need in (2026)` ⚠️ broken shortcode |
| Word Count (article body only) | 1,400 (`.blog-content-area` selector) |
| Internal Links (in-content) | 74 in-content / counted only inside content area |
| External Links | 4 — all to Upmetrics social profiles (no editorial citations to authoritative sources) |
| Content Images (with alt / without alt) | 1 total / 0 with alt / 1 without alt |
| Schema Markup | Yes — Article, WebPage, BreadcrumbList, FAQPage, Organization, Person, WebSite, ImageObject |
| Canonical Tag | [https://upmetrics.co/blog/business-plan-questionnaire](https://upmetrics.co/blog/business-plan-questionnaire) (self-referencing ✅) |
| Page Type | Blog article (10-section questionnaire guide) |
| Content Freshness | Visible: "Updated May 13, 2026" ✅ • Meta modified: 2026-05-13 |
| Author Attribution | "Upmetrics" (brand name, no bio, no photo) |
| Downloadable Templates/Freebies | 5 in-content template/sample links — all point to `/download/business-plan-template` or `/sample-business-plans` (no questionnaire-specific download) |

### Top 3 Problems

1. **Broken `[currentyear]` shortcode renders as `(2026)` in the H1** — the H1 reads "The Ultimate Business Plan Questionnaire You Need in (2026)" with literal parentheses, and the Twitter title still shows the raw `([currentyear])` placeholder. This signals neglect to crawlers and users.
2. **No downloadable questionnaire asset** — 6 of the top 10 SERP results are PDF/DOCX downloads, and Growthink (position 3) explicitly offers "Free PDF Download" in its title. The target lists 5 download CTAs but none of them is a printable questionnaire PDF; they all redirect to the generic business plan template.
3. **Cluster cannibalization on "competitive analysis questionnaire" variants** — 5 GSC queries (totalling ~112 impressions) are split between this page and two other Upmetrics pages ([what-is-a-competitive-analysis](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) and [how-to-write-the-competition-section](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan)), diluting authority for the highest-impression secondary keyword family.

### Traffic Opportunity

> Primary KW is KD=0 / 20 vol — but the *secondary* "competitive analysis questionnaire" cluster (~138 impressions across 5 variants, all at positions 24-40) is the real prize. Fixing the H1 shortcode, adding a downloadable PDF, and adding a dedicated "Competitive Analysis Questionnaire" section could realistically move the page to top-5 for both the primary and the competitive-analysis cluster — projecting 30-80 clicks/month from a current baseline of 0.

---

## 2. MASTER ACTION TABLE

| # | Priority | Category | Action | Assignee | Details | Section Ref |
|---|----------|----------|--------|----------|---------|-------------|
| 1 | P1 | Technical/Meta | Fix broken `[currentyear]` shortcode in H1 + Twitter title | Dev | H1 currently renders `in (2026)` with literal parens; Twitter title still contains literal `[currentyear]`. Replace shortcode with a working dynamic year or hard-code `2026`. | §5 |
| 2 | P1 | Meta | Trim meta description to ≤160 chars | Dev | Current = 161 chars (1 over). New copy: see §2 Title & Meta Copy block. | §5 |
| 3 | P1 | Meta | Rewrite title tag to add "Free Template" / "Free PDF" signal | Dev | SERP winners include "+ Free PDF Download" (Growthink #3). New copy: see §2 Title & Meta Copy block. | §5 |
| 4 | P1 | Technical | Add alt text to the 1 in-content image | Dev | Image: `ai-assistant-blog-image-1` (near "1. Executive Summary"). Suggested alt: `Upmetrics AI Assistant helping a founder fill out the executive summary section of a business plan questionnaire`. | §5 |
| 5 | P1 | Asset | Create and link a downloadable PDF questionnaire | Marketing/Design | All 6 PDF results in the top-10 SERP win on "instant download" intent. Build a clean, printable PDF mirroring the 10-section structure. Place download CTA inline at top of page + at section transitions. | §6, §14 |
| 6 | P2 | Internal Link | Add link from [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) → target page | SEO Team | Anchor: "competitive analysis questionnaire" — place inside the section that lists competitive analysis questions. Source: GSC cannibalization. | §7 |
| 7 | P2 | Internal Link | Add link from [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) → target page | SEO Team | Anchor: "sample competitive analysis questionnaire". Source: GSC cannibalization. | §7 |
| 8 | P2 | Internal Link | Add link from [https://upmetrics.co/blog/questions-to-ask-before-hiring-a-business-plan-writer](https://upmetrics.co/blog/questions-to-ask-before-hiring-a-business-plan-writer) → target page | SEO Team | Anchor: "questions to ask when making a business plan". Source: GSC — other page outranks target (40.6 vs 60.2) for "questions to ask when making a business plan", indicating cluster confusion. Internal link signals primary topic owner. | §7 |
| 9 | P2 | Technical | Verify FAQPage schema matches 3 visible FAQ Q&As | Dev | FAQPage schema is present, but only 3 FAQs are on the page. Adding 2-3 more PAA-style FAQ entries (see §4) and matching them in schema unlocks more rich-result eligibility. | §5 |
| 10 | P2 | E-E-A-T | Replace generic "Upmetrics" byline with a real author + bio + photo | SEO Team / Marketing | All 4 SERP competitors lack expert authors too, but Upmetrics already has internal SMEs (e.g., Riya Shah) used elsewhere. Easy E-E-A-T win on a low-DR SERP. | §8 |
| 11 | P3 | Backlinks | Outreach to small-business/SBA-style sites for PDF questionnaire link | Link Builder | 0 live backlinks today. SERP DRs are 0-88 but average UR is only 4 — winnable without heavy link building. Target university SBDC pages, local SCORE chapters, business-incubator resource lists. | §7 |

### Title & Meta Copy (ready to copy-paste)

```
Title Tag (NEW): Business Plan Questionnaire (10 Sections + Free PDF) – 2026 (59 chars)
Title Tag (OLD): The Ultimate Business Plan Questionnaire You Need In 2026 (57 chars)

Meta Description (NEW): A 10-section business plan questionnaire to lock in your strategy, market, and finances—plus a free, printable PDF you can hand to investors. (148 chars)
Meta Description (OLD): Go through this questionnaire to cover all essential aspects of your business plan, from defining goals to refining strategies and preparing financial forecasts. (161 chars)
```

**⚠️ Content actions (rewrites, additions, new sections, citation additions) are in the [Content Update Brief (`business-plan-questionnaire.docx`)](output/business-plan-questionnaire.docx).**

---

## 3. KEYWORD & RANKING ANALYSIS (US Focused)

### Top 10 Keywords (GSC, last 6 months)

| Keyword | Impressions | Clicks | CTR | Avg Position | Trend (6mo) |
|---------|------------|--------|-----|-------------|-------------|
| business plan questionnaire | 179 | 0 | 0% | 19.4 | ↑ improving (positions ~22 in Dec, ~17 in May) |
| questionnaire on competitive analysis in business plan template | 29 | 0 | 0% | 24.3 | → flat |
| questions to ask when making a business plan | 28 | 0 | 0% | 60.2 | ↓ declining |
| questionnaire on competitive analysis in business plan example | 23 | 0 | 0% | 28.9 | → flat |
| sample questionnaire on competitive analysis in business plan | 23 | 0 | 0% | 25.3 | → flat |
| questionnaire on competitive analysis in business plan | 22 | 0 | 0% | 26.0 | → flat |
| sample questionnaire on competitive analysis in business plan pdf | 21 | 0 | 0% | 40.4 | → flat |
| business plan questions | 19 | 0 | 0% | 57.6 | ↓ declining |
| business questionnaires | 18 | 0 | 0% | 71.3 | ↓ declining |
| questionnaire on competitive analysis in business plan pdf | 17 | 0 | 0% | 36.8 | → flat |

**Headline:** 59 queries / 411 total impressions / **0 clicks** over 6 months. The primary keyword is improving (now ~17 from ~22), but the competitive-analysis cluster (5 of top 10) is the larger impression opportunity.

### Striking Distance Opportunities (positions 4-20)

| Keyword | Impressions | Clicks | Position | Opportunity |
|---------|------------|--------|----------|-------------|
| business plan questionnaire | 179 | 0 | 19.4 | Within striking distance of page 1. Title rewrite + PDF download asset should push to top 10. |
| questionnaire for business plan | 1 | 0 | 16.0 | Low volume but already close. Will move with primary KW. |

Only 2 queries sit in positions 4-20 — most striking-distance traffic is concentrated in the primary keyword. Positions 24-30 (competitive-analysis cluster) are the next-best target after page 1 is locked.

### Cannibalization Check

| Query | Target Page Position | Competing Page URL | Competing Page Position | Recommendation |
|-------|---------------------|-------------------|------------------------|----------------|
| questionnaire on competitive analysis in business plan template | 24.3 | [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) | 49.0 | Target outranks. Add internal link FROM competing page TO target with anchor "competitive analysis questionnaire". |
| questionnaire on competitive analysis in business plan template | 24.3 | [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | 27.7 | Same as above — both pages competing on same long-tail variant. Consolidate authority via internal link. |
| sample questionnaire on competitive analysis in business plan | 25.3 | [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) | 49.8 | Same as above. |
| questionnaire on competitive analysis in business plan example | 28.9 | [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | 10.0 | ⚠️ Competing page (position 10) outranks target (28.9). Either: (a) link FROM the competing page to the target to claim the broader "questionnaire" intent here, or (b) accept the split and ensure each page targets a different angle. |
| questions to ask when making a business plan | 60.2 | [https://upmetrics.co/blog/questions-to-ask-before-hiring-a-business-plan-writer](https://upmetrics.co/blog/questions-to-ask-before-hiring-a-business-plan-writer) | 40.6 | Competing page outranks target by ~20 positions. The competing page is about hiring a writer, not making a plan — clear intent mismatch on Google's part. Add an internal link from the writer-hiring page → target with anchor "questions to ask when making a business plan". |

**Summary:** Primary keyword is NOT cannibalized. The competitive-analysis-questionnaire cluster is moderately cannibalized — fix with internal-link consolidation (see actions §2.6, §2.7).

---

## 4. SERP & INTENT ANALYSIS

**What Google is rewarding:**
- **Dominant intent:** Informational + Transactional (download intent) — users want a ready-to-use questionnaire, not just an article describing one.
- **Content types ranking (top 10 organic):** 6 PDF/DOCX downloads (fmarion.edu #1, growthink #3 with PDF, alaska.gov #5, willowlegaladvisors #6, angelo.edu DOCX #9, ceimaine #10) + 3 blog guides (snb-t #2, contentsnare #7, thomasnet #8). An image pack sits at position 4.
- **What this means:** Google is splitting the page-1 slots roughly 50/50 between "give me a PDF I can print" and "give me an HTML guide with embedded download." The hybrid blog + downloadable PDF format (Growthink at position 3) is the strongest pattern for an editorial site.

**Intent match/mismatch:**
- **Current page type:** Blog article / guide (no native PDF download)
- **Match status:** ⚠️ Partial mismatch
- **Why:** Target page has 5 in-content "Download Template" CTAs, but they all link to the *business plan* template, not a *questionnaire* PDF. Users clicking through expect a printable Q&A document. This intent gap is the single largest reason the page is sitting at position 19 despite KD=0.

**SERP Features:**

| Feature | Present? | Who Owns It | Can We Win? | Action |
|---------|----------|-------------|-------------|--------|
| AI Overview | Likely yes (could not confirm via WebSearch) | Synthesized from multiple sources | Yes | Add a 40-60 word definition + use-case paragraph immediately under H1 (snippet bait). |
| Featured Snippet | Could not confirm — likely list format | Unknown | Yes | Format the 10-section breakdown as a clean numbered list with consistent intro per section. |
| PAA (People Also Ask) | Likely yes — unable to confirm exact questions via WebSearch | n/a | Yes | Likely PAA: "What questions should a business plan answer?", "What is a business plan questionnaire?", "How do you write a business plan questionnaire?", "What 7 questions should a business plan answer?". Add as FAQ items + match schema. Manual SERP check recommended. |
| Video results | Not visible | — | n/a | No video strategy needed for this query. |
| Image pack | Yes (position 4) | template.net, pinterest, examples.com, growthink, willowlegaladvisors, etc. | Yes | Add 2-3 unique branded illustrations: (a) the 10-section structure visualized, (b) a sample filled-in questionnaire snippet. Optimize alt text + filenames. |
| Knowledge panel | No | — | — | — |

### Featured Snippet Optimization

| Query | Snippet Type | Current Owner | What Target Page Needs | Where to Place |
|-------|-------------|---------------|----------------------|----------------|
| business plan questionnaire | Likely list/paragraph hybrid | Unknown (likely Growthink or Contentsnare) | A 40-60 word definition paragraph immediately under H1, followed by a 10-item ordered list of sections. | New section directly below H1, before "Questions your business plan should answer". |
| what questions should a business plan answer | Likely list | Unknown | A numbered list (5-7 items) summarizing the highest-level questions. | New paragraph + list at top of "Questions your business plan should answer" H2. |

---

## 5. TECHNICAL SEO (Failures Only)

| # | Issue | Current | Fix | SEO Impact |
|---|-------|---------|-----|------------|
| 1 | Broken `[currentyear]` shortcode in H1 + Twitter title | H1: "...Need in (2026)" with literal parens. Twitter title: "...Need in ([currentyear])". | Replace shortcode with a working tag or hard-code "2026". | Broken parens + literal shortcode signal a stale/broken template to crawlers and social cards. |
| 2 | Meta description exceeds 160 chars | 161 chars (current). | Trim to ≤160. → See §2 Title & Meta Copy. | Description likely truncated in SERP. |
| 3 | Title tag missing "Free PDF / Free Template" signal | "The Ultimate Business Plan Questionnaire You Need In 2026" (57 chars). | → See §2 Title & Meta Copy. | Closest direct competitor (Growthink #3) ranks higher in part because of "+ Free PDF Download" in title. |
| 4 | 1 of 1 content image missing alt | `ai-assistant-blog-image-1-282x240.png` near "1. Executive Summary" — alt is empty. | Add: `Upmetrics AI Assistant helping a founder complete the executive summary of a business plan questionnaire`. | Accessibility + image search eligibility. |
| 5 | 0 inline editorial citations | 4 external links — all to Upmetrics social profiles (LinkedIn, YouTube, Facebook, Twitter). No links to authoritative sources (SBA, SBDC, government data). | Add 2-3 inline citations to authoritative sources where claims are made — see Update Brief §14E for specific placement. | E-E-A-T + topical credibility. |

**Passing checks (not shown):** canonical (self-referencing), no noindex, hreflang correct, OG tags present, FAQPage schema present, viewport configured, schema includes Article + WebPage + BreadcrumbList + Organization + Person.

---

## 6. CONTENT GAPS & COMPETITOR DEPTH

### 6A. Content Depth Comparison

| Page | URL | Content Type | Word Count | H2s | H3s | Images | FAQs | Citations | Downloads |
|------|-----|-------------|-----------|-----|-----|--------|------|-----------|-----------|
| **OURS** | [upmetrics.co/blog/business-plan-questionnaire](https://upmetrics.co/blog/business-plan-questionnaire) | blog article (10-section questionnaire) | 1,400 | 4 | 13 | 1 (0 alt) | 3 | 0 editorial | 5 in-content CTAs (no questionnaire PDF) |
| C1 — Growthink | [growthink.com/businessplan/help-center/business-plan-questionnaire](https://www.growthink.com/businessplan/help-center/business-plan-questionnaire) | blog article | 1,559 | 3 | 10 | 17 visuals | 1 FAQ | 4 external | "Free PDF Download" of full questionnaire |
| C2 — Contentsnare | [contentsnare.com/form-templates/business-planning-questionnaire/](https://contentsnare.com/form-templates/business-planning-questionnaire/) | blog article + form template | 1,262 | 4 | 13 | 12 visuals | 4 FAQ | 1 external | Embedded form template (Contentsnare SaaS) |
| C3 — Thomasnet | [thomasnet.com/insights/business-plan-questionnaire/](https://www.thomasnet.com/insights/business-plan-questionnaire/) | blog article (B2B/industrial angle) | — (scrape blocked, 403) | — | — | — | — | — | — |
| C4 — Superior National Bank | [snb-t.com/business-plan-questionnaire/](https://www.snb-t.com/business-plan-questionnaire/) | landing page | 332 | 0 | 0 | 0 | 0 | 0 | PDF + Excel + Word downloads |

**Read:** Word count is comparable to Growthink (1,400 vs 1,559); Contentsnare is shorter. The gap is NOT length — it's visual density (Growthink has 17 visuals + a downloadable PDF, target has 1 image and no PDF) and intent-fit (Snb-t ranks #2 with only 332 words because it offers PDF + Excel + Word downloads).

### 6B. Competitor Heading Map

| Topic / Section | C1 Growthink | C2 Contentsnare | C3 Thomasnet | C4 SNB-T | OURS | Action |
|----------------|----|----|----|----|----|--------|
| Definition: "what is a business plan questionnaire" | ✅ | ✅ | ? | ✗ | ✗ | ✗ GAP — add a 40-60 word definition paragraph under H1 |
| Who should use it / who it's for | ✅ | ✅ | ? | ✗ | ✅ (in FAQ only) | ✅ go deeper — promote from FAQ to a dedicated intro section |
| Benefits of using a questionnaire | ✅ | ✅ | ? | ✅ | ✅ (in FAQ only) | ✅ go deeper — promote from FAQ to body section with 4-5 bullets |
| Executive Summary section | ✅ | ✅ | ? | ✗ | ✅ | ✅ table stakes |
| Company Overview / Business Description | ✅ | ✅ | ? | ✅ | ✅ | ✅ table stakes |
| Market & Industry Analysis | ✅ | ✅ | ? | ✅ | ✅ | ✅ table stakes |
| Competitive Analysis questions | ✅ | ✅ | ? | ✗ | ✅ | ✅ go deeper — see §6C item 1 (huge GSC demand) |
| Products & Services | ✅ | ✅ | ? | ✅ | ✅ | ✅ table stakes |
| Sales & Marketing | ✅ | ✅ | ? | ✅ | ✅ | ✅ table stakes |
| Operations Plan | ✅ | ✅ | ? | ✅ | ✅ | ✅ table stakes |
| Management Team | ✅ | ✅ | ? | ✗ | ✅ | ✅ table stakes |
| Financial Plan | ✅ | ✅ | ? | ✅ | ✅ | ✅ table stakes |
| Appendix | ✅ | ✗ | ? | ✗ | ✅ | ✅ UNIQUE EDGE |
| Funding/Investment requirements section | ✅ | ✅ | ? | ✅ | ✗ (only briefly in Financial Plan) | ✗ GAP — call out funding amount/use of funds as its own subsection |
| Risk assessment / SWOT questions | ✅ | ✅ | ? | ✗ | ✗ | ✗ GAP — add 4-5 SWOT/risk questions |
| Vision & mission statement section | ✅ | ✅ | ? | ✅ | ✗ | ✗ GAP — split into Company Overview |
| Implementation timeline / milestones | ✅ | ✅ | ? | ✅ | ✗ | ✗ GAP — add a "milestones/timeline" subsection inside Operations |
| Exit strategy questions | ✅ | ✗ | ? | ✗ | ✗ | ✗ GAP (Growthink-only, low priority) |
| Personal background / owner info | ✅ | ✗ | ? | ✅ | ✗ | ✗ GAP — important for lenders, add to Management Team |
| How to use the questionnaire (workflow) | ✅ | ✅ | ? | ✗ | ✅ | ✅ table stakes |
| Tips / best practices for filling it out | ✅ | ✅ | ? | ✗ | ✗ | ✗ GAP — add a "Tips for getting the most out of this questionnaire" section |
| Downloadable PDF questionnaire | ✅ (Free PDF) | ✗ (form embed) | ? | ✅ (PDF + Excel + Word) | ✗ | ✗ GAP — **highest-priority asset** (drives SERP intent match) |
| FAQ section | ✗ | ✅ | ? | ✗ | ✅ | ✅ go deeper — expand from 3 to 6-7 FAQs to capture PAA |
| Brand product CTA | ✅ (Growthink's tool) | ✅ (Contentsnare's tool) | ? | ✅ (bank product) | ✅ (Upmetrics) | ✅ table stakes |

C3 (Thomasnet) is unscraped; "?" means unknown coverage. All ✗ GAP rows drive content additions in the Update Brief (Section 14E).

### 6C. Topic Gap Detail

| # | Missing Topic | Covered By | Evidence Source | Priority | Recommended Action |
|---|--------------|------------|----------------|----------|-------------------|
| 1 | **Downloadable PDF questionnaire** | C1 (Growthink), C4 (SNB-T), plus 6 of 10 SERP slots are PDFs | SERP overview (6/10 results are PDF/DOCX); Growthink title literally says "+ Free PDF Download" | High | Create a printable, branded 10-section questionnaire PDF. Inline CTA at top + at "How to use this questionnaire" section. |
| 2 | **Definition of "business plan questionnaire"** (40-60 words under H1) | C1, C2 | Likely PAA: "What is a business plan questionnaire?" | High | Add as snippet-bait paragraph immediately under H1. |
| 3 | **Standalone "Who should use this" + "Benefits" sections** | C1, C2, C4 | Currently inside FAQ on target page | High | Promote from FAQ to first-screen body sections (2 short blocks: 2-3 sentences each). |
| 4 | **SWOT / risk-assessment questions** | C1, C2 | Common in business-plan templates per SERP context; not in target's 10 sections | High | Add 4-5 risk/SWOT-style questions either inside Market Analysis or as a new "Risk Assessment" subsection. |
| 5 | **Vision & mission statement questions** | C1, C2, C4 | All 3 scraped competitors have a dedicated vision/mission block | High | Add 3-4 vision/mission questions to "Company Overview" (currently absent). |
| 6 | **Funding requirements / use-of-funds questions** | C1, C2, C4 | All 3 scraped competitors break this out from financial plan | Medium | Add 3-4 questions on funding amount, use of funds, repayment terms inside or after "Financial Plan". |
| 7 | **Implementation timeline / milestones** | C1, C2, C4 | All 3 cover this | Medium | Add 3-4 questions on milestones, launch timeline, key dates inside "Operations Plan". |
| 8 | **Personal background / owner info (for lender questionnaires)** | C1, C4 | Common in bank/lender questionnaires; SNB-T (a bank) covers it | Medium | Add 2-3 owner-background questions (years of experience, prior business ownership, personal financial commitment) to "Management Team". |
| 9 | **Tips / best practices for completing the questionnaire** | C1, C2 | Both top competitors have this as a closing block | Medium | Add a 4-5 bullet "Tips for getting the most out of this questionnaire" closing section before the product CTA. |
| 10 | **Expanded FAQ** | C2 | C2 has 4 FAQs (target has 3); likely PAA questions are unanswered | Medium | Add 3-4 more FAQs answering "What questions should a business plan answer?", "How long does it take to complete a business plan questionnaire?", "What format should the answers be in?", "Can I customize this questionnaire for my industry?". |
| 11 | **Exit strategy questions** | C1 only | Growthink covers; others don't | Low | Optional — add 1-2 exit-strategy questions to Appendix or Financial Plan. |

UGC threads not present in SERP — no UGC-sourced gaps added.

---

## 7. LINKS & BACKLINKS

### 7A. Internal Link Issues

Scanned the 74 in-content internal links — no broken, no missing anchor text, no inappropriate nofollow. **All 74 in-content internal links are healthy.**

### 7B. Internal Links to ADD

| Anchor Text | Target URL | Where to Place | Why | Source |
|------------|-----------|----------------|-----|--------|
| competitive analysis section of your business plan | [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | Inside "4. Competitive Analysis" H3 (target page already covers competitive analysis questions — link from intro sentence) | Already linked FROM cannibalizing pages — strengthen the topic cluster | GSC cannibalization (step1b-cannibalization.json) |
| what is competitive analysis | [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) | Inside "4. Competitive Analysis" H3 — link from a phrase like "for a deeper walkthrough, see..." | Reinforce hub-and-spoke; complements §7C | GSC cannibalization |
| sample business plans | [https://upmetrics.co/sample-business-plans](https://upmetrics.co/sample-business-plans) | Already linked once near "10. Appendix" — add a second link inside "1. Executive Summary" with anchor "view sample business plan executive summaries" | Already on page — verified internal link | step1a-target-page.json internalLinks |
| free business plan template | [https://upmetrics.co/download/business-plan-template](https://upmetrics.co/download/business-plan-template) | Already linked 3× — consolidate into the new PDF download CTA section | Already on page | step1a-target-page.json internalLinks |

### 7C. Pages That Should Link TO This Page

| Source Page URL | Where to Add (placement on source page) | Suggested Sentence (anchor text) | Source |
|----------------|----------------------------------------|----------------------------------|--------|
| [https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan](https://upmetrics.co/blog/how-to-write-the-competition-section-of-your-business-plan) | Inside the section that walks through competitive analysis questions/steps | Anchor: "competitive analysis questionnaire" — pointing to target | GSC: page ranks 27.7 / 10 for competitive-analysis-questionnaire variants, cannibalizing target |
| [https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively](https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively) | Near a section discussing how to structure competitive research | Anchor: "sample competitive analysis questionnaire for a business plan" | GSC cannibalization |
| [https://upmetrics.co/blog/questions-to-ask-before-hiring-a-business-plan-writer](https://upmetrics.co/blog/questions-to-ask-before-hiring-a-business-plan-writer) | After explaining what to ask a writer, link out to questions a founder should answer themselves | Anchor: "questions to ask when making a business plan" | GSC: page outranks target on this query (40.6 vs 60.2) — intent mismatch, fix with directional internal link |

### 7D. External Link Issues

| # | Anchor Text | Target URL | Issue | Fix |
|---|------------|-----------|-------|-----|
| 1 | (none — all 4 external links are social profile icons in author/footer block) | facebook.com/upaborant, twitter.com/upaborant, etc. | The target page has **zero in-content editorial citations**. All 4 external links are Upmetrics social profiles in the author block. | Add 2-3 inline citations to authoritative sources (SBA, SBDC, government data, peer-reviewed business research) — see Update Brief §14E for placement. |
| 2 | (Facebook anchor) | [https://www.facebook.com/upaborant/](https://www.facebook.com/upaborant/) | URL `upaborant` is suspicious — likely a typo of "upmetrics" — page may 404 or be the wrong page | Verify the URL resolves to the correct Upmetrics Facebook page; fix or remove. |
| 3 | (Twitter anchor) | [https://twitter.com/upaborant](https://twitter.com/upaborant) | Same — typo `upaborant` | Verify and fix. |

### 7E. Backlink Gap

| Metric | Target Page | Avg Top 5 Competitors |
|--------|------------|----------------------|
| Referring Domains | 0 (live) / 1 (all-time) | 0.4 (most SERP competitors have 0 refdomains; fmarion.edu PDF has 1, angelo.edu DOCX has 1) |
| Total Backlinks | 0 (live) / 1 (all-time) | <1 avg |
| URL Rating | 0 | 1.6 avg (0-4 range) |
| Domain Rating | 64 (Upmetrics estimated) | 55.4 avg (fmarion 60, snb-t 32, growthink 71, alaska 88, willowlegal 0) |

**Gap summary:**
- **Backlinks are NOT the bottleneck.** Most top-10 results have 0-1 referring domains. This page is winnable on content + intent match alone.
- **Easy link-building wins:** Target university SBDC pages, SCORE chapters, small-business incubator resource lists, and local-chamber resource pages — they routinely link to free downloadable questionnaires/templates.
- **1 specific action:** Once the PDF questionnaire asset is live (action §2.5), pitch the PDF as a free resource to 10-15 SBDC sites (US universities have SBA-funded Small Business Development Centers that publish resource lists). Realistic conversion: 2-3 contextual backlinks from DR 50+ .edu sites.

---

## 8. E-E-A-T & CITATIONS

### E-E-A-T Signal Comparison (gaps only)

| Signal | Target Page | Best Competitor | Gap? |
|--------|------------|----------------|------|
| Author name | "Upmetrics" (brand, generic) | Contentsnare: no real author either. Growthink: no real author either. | ⚠️ Small gap — competitors are no better, but a real expert byline is a low-effort differentiator. |
| Author bio | Missing | All competitors also missing | ⚠️ Same as above — competitor-relative parity, but a true E-E-A-T win available. |
| Author photo | Missing | All competitors missing | ⚠️ Same. |
| Cited sources | 0 inline editorial citations | Growthink: 4 external citations | ✅ Clear gap — competitor cites sources. Add 2-3 inline links to SBA, SBDC, or business-planning research. |
| Expert quotes | 0 | 0 across all competitors | — (no gap) |
| Publish/updated date visible | ✅ "Updated May 13, 2026" | C1 Growthink: 2026-03-31. C2 Contentsnare: 2026-01-28. | ✅ Target wins on freshness — keep updating. |
| Schema markup | ✅ Article + FAQPage + Person + Organization | C2 likely has Article schema only | ✅ Target is ahead. |

### Citation Audit (existing citations)

| Citation | URL Status | Source Quality | Issue (if any) |
|----------|-----------|---------------|----------------|
| (no inline editorial citations to audit) | — | — | The page has zero inline editorial citations. The 4 external links are all to Upmetrics social profiles. |

### Unsourced Claims

| Unsourced Claim (exact quote) | Location | Recommended Source URL |
|------------------------------|----------|----------------------|
| (No statistics or quantitative claims found in the page body) | — | — |

The page is structurally a questions-list with intro text; it does not contain statistics or factual claims that need citing. The opportunity is to **add** authoritative citations to support concepts (e.g., link "competitive analysis" to SBA's marketing guide, link "executive summary" to a recognized business-planning reference). Specific placements live in Update Brief §14E.

---

## 9. APPENDIX

### Ahrefs API Consumption Log

| # | Call | Endpoint | Units |
|---|------|----------|-------|
| 1 | Organic Keywords (target) | `site-explorer-organic-keywords` | 50 (returned 0 rows — minimum charge) |
| 2 | SERP Overview (primary KW) | `serp-overview` | 198 |
| 3 | Keyword Overview (primary KW) | `keywords-explorer-overview` | 50 |
| 4 | Backlinks Stats (target) | `site-explorer-backlinks-stats` | 50 |
| | **Total this audit** | | **348** |
| | Remaining in cycle (start) | | 389,486 |
| | Reset date | | 2026-06-21 |
| | Estimated audits remaining | | ~1,118 (at 348 units/audit) |

---

*End of SEO Audit Report. Content actions (rewrites, additions, new sections, citation placement, tips section, FAQ expansion) live in the separate Content Update Brief `.docx`.*
