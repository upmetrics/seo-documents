# On-Page SEO Report — How Much Does a Business Plan Writing Cost?

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/business-plan-cost |
| **Post ID** | 6255 |
| **Post Type** | `post` (Blog Post) |
| **Category** | Planning |
| **Word Count** | 1,706 |
| **Published** | 2022-05-03 |
| **Last Modified** | 2026-08-12 (content republished 1 day ago) |
| **Report Date** | 2026-08-13 |
| **GSC Data Range** | 2026-05-15 to 2026-08-10 (90 days) |
| **GA4 Data Range** | 30 days (engagement) / 90 days (conversions) |
| **Brand** | Upmetrics |

> **Important timing note:** The body content was republished on **2026-08-12**. All GSC performance data below reflects the **previous version** of this page. Google has not yet re-evaluated the new content. Treat ranking and CTR figures as a baseline to measure against, not as a verdict on the current copy.

> **Data availability note:** The Google Search Console MCP server was unreachable during this session (connection timeouts on every call, including `list_sites`). All GSC data below was retrieved by calling the Search Console API directly with the project service account. Page-level queries, the device split, and site-wide top pages all returned successfully. The only calls that did not complete were the Task 10 topic-ranking queries (`page` x `query` filtered by topic), so Task 10 is ranked by topical relevance — the specification's primary signal — with GSC clicks used as a tiebreaker where the source page appears in the site's top 40.

---

## Section B — Page Health Score & Action Summary

### Page Health Score: **4.5 / 10**

| Deduction | Points | Detail |
|-----------|:--:|--------|
| Meta underperforming on top query (Task 5 trigger) | −2.0 | `business plan cost` at position 17.5 with 0.47% CTR vs 1.5% benchmark — **69% below** |
| Meta title AND description both under minimum length | −1.0 | Title 43 chars (min 50), description 129 chars (min 140) |
| Meta title near-identical to H1 | −1.0 | "…Business Plan Cost in 2026?" vs H1 "…Business Plan Writing Cost?" |
| Duplicate paragraph in body content | −0.5 | Identical 34-word paragraph appears twice in the consulting-firm section |
| Internal link balance inverted | −0.5 | 37% informational / 63% sales — blog-post target is 60–70% informational |
| OG title encoding defect | −0.5 | Contains a curly apostrophe (`You'll`) instead of straight ASCII |

### Status Summary

| Status | Count |
|--------|:--:|
| Critical | 3 |
| Needs Improvement | 4 |
| Good | 6 |

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|--------------|---------------|
| 1 | Internal Links | Medium | Medium | 8 internal links (1 per 213 words — dense); 37% informational | Swap 1 sales link for an informational match, add 1 link in the unlinked pricing section | None | **Approve #1 + #2, skip #3** |
| 2 | CTA Placements | Medium | Medium | Only the required end CTA; no mid-content CTA in 1,706 words | Add 1 lightweight Yellow Tip CTA after the DIY section | None | **Approve #1** |
| 3 | Resource CTA | Low | Quick Win | `/download/ebook`, combined label 57 chars (over limit, redundant wording) | Keep the resource, shorten the heading to 44 chars | None | **Approve** |
| 4 | Related Content | Medium | Quick Win | 4 items; 2 are weak fits for a pricing article | Replace with 4 cost-and-decision-focused items | Task 1, 2, 3 dedup | **Approve** |
| 5 | Meta Title & Description | **High** | Quick Win | Title 43 chars, near-duplicate of H1; description 129 chars | Rewrite both; lead with the actual price range | None | **Approve** |
| 6 | Image Alt Text | — | — | 1 content image, alt is accurate and 80 chars; 1 decorative CTA icon | No action needed | None | **No action** |
| 7 | URL Slug | — | — | `business-plan-cost` — 3 words, exact keyword, clean | No change | None | **Skip (already optimal)** |
| 8 | Heading Structure | Low | Quick Win | Clean H2/H3 hierarchy, keyword present in H2s; "Conclusion" is generic | Optional: rename the final H2 | None | **Optional** |
| 9 | Categories | — | — | Planning | Correct — no change | None | **Skip (already correct)** |
| 10 | Incoming Links | Medium | Medium | Not measured previously | 7 verified source pages to link from | Task 1 dedup | **Noted — review manually** |
| — | **Content defects** | **High** | Quick Win | Duplicate paragraph + 1 grammar error | Remove duplicate, fix "the provider charge more" | None | **Approve** |

---

## Section C — Task-by-Task Suggestions

## Task 1: Internal Linking

### Part A — Existing Link Audit

**Current state:** 8 internal content links + 2 external links, across 1,706 words. That is **1 internal link per 213 words** — denser than the 1-per-300-500 guideline. All 8 targets were verified against WordPress; none are broken, redirected, or carrying query strings, and none appear inside headings.

| # | Anchor Text | Target URL | Type | Status |
|:--:|-------------|-----------|------|--------|
| 1 | business plan template | `/download/business-plan-template` | Informational | **Good** |
| 2 | Upmetrics | `/` | Branded homepage | **Good** |
| 3 | professional business plan writing service | `/services/business-plan-writing` | Sales | **Good** |
| 4 | financial projections | `/blog/financial-projections-business-plan` | Informational | **Good** |
| 5 | market research | `/blog/types-of-market-research` | Informational | **Good** |
| 6 | business plan review service | `/services/business-plan-review` | Sales | **Good** |
| 7 | industry research | `/features/industry-research` | Sales | **Needs Fix** — see #1 below |
| 8 | Upmetrics' AI business plan generator | `/features/ai-plan-generator` | Sales | **Good** |

**External links:** `score.org` and `sba.gov` — both authoritative, contextually correct, and neither is in the competitor list. **Keep both.**

**The balance problem:** 3 informational vs 5 sales/features links = **37% / 63%**. The target for a blog post is **60–70% informational**. This page currently reads more promotionally than the content warrants, and it is the single clearest internal-linking issue here — not a shortage of links.

---

### Part B — New Link Suggestions

Because the page is already link-dense, the recommended fix is **one swap plus one addition**, not a batch of new links.

> **#1 — RECOMMENDED (replace)** — `industry research` → change target from `/features/industry-research` to `/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** Factors that affect business plan costs → Research required
>
> **In context:** "If you already understand your market and competitors, the research may be fairly limited. A plan that requires deeper customer, competitor, market, or **industry research** may take more time or require paid research support."
>
> **Note:** The sentence ends on "require paid research support" — an article listing 21 free and paid industry report sources answers that directly, while a product feature page does not. Anchor text is unchanged; only the target moves. Fixes relevance and balance with zero added link density.

---

> **#2 — RECOMMENDED (add)** — `how you create the plan` → `/blog/how-to-write-a-business-plan`
>
> **Section:** What does a business plan typically cost? (by options)
>
> **In context:** "A business plan can typically cost anywhere from $0 to $25,000 or more. What you pay mainly depends on **how you create the plan**, what you need it for, how much work is already done, and how much professional help you need."
>
> **Note:** This H2 section currently has zero internal links. Wraps existing text with no wording change. Nearest existing link is ~108 words away, so spacing is clean.

---

> **#3 — OPTIONAL (add)** — `visa-related plan` → `/blog/e2-visa-cost`
>
> **Section:** Factors that affect business plan costs → Purpose of the plan
>
> **In context:** "A plan for internal use may require less supporting information. A lender, investor, acquisition, or **visa-related plan** may involve additional documentation, research, or financial detail depending on what the intended reader requires."
>
> **Note:** Topically excellent — the target breaks down E2 visa costs including business plan fees, which fits a cost article well. **Caveat:** it sits roughly 75 words after the link in suggestion #1, below the 100-word spacing guideline, and pushes an already-dense page to 10 links. Approve only if you want the extra depth here.

**Balance after applying #1 and #2:** 5 informational / 4 sales = **56% / 44%** (63% / 37% excluding the branded homepage link) — inside the target band.

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| What Lenders & Investors Look for in a Business Plan | Only natural anchor ("lenders, investors") sits ~20 words after an existing link in the Conclusion — fails spacing |
| How to Write a Business Plan Using ChatGPT | Anchor "ChatGPT or Claude" sits ~45 words after the template link — fails spacing |
| Financial Forecasting Software | Anchor "financial forecasting" exists, but it is a Sales page and would worsen the already-inverted balance |
| Business plan writer vs. AI generator | Sales/compare page — would worsen balance; assigned to Task 4 instead |
| Upmetrics vs LivePlan | No verbatim anchor in the content matches the page's topic; assigned to Task 4 instead |

</details>

---

## Task 2: CTA Placements

### Part A — Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Blog Post End CTA (`delivery-block`) | Last block of content | **Good** | Canonical headline, subtitle, button text, and URL all match the registry exactly. Required element is present. |

**Gap:** 1,706 words with a single CTA at the very end. The guideline for this length is 1–2 CTAs, so there is room for exactly one lightweight mid-content CTA. Given the post's length, a light text CTA is the right call over a second banner.

---

### Part B — New CTA Suggestions

> **#1 — RECOMMENDED — Yellow Tip Alert (Type 12)** | After the "Write it yourself" section
>
> **Placed after:** "This route keeps your direct costs low, but it requires more of your own time and judgment to complete and check the plan."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │ 💡 Tip: Want a free starting point? Our AI Business     │
> │ Plan Generator builds a structured first draft from     │
> │ your inputs — no account or credit card needed.         │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Target:** `/ai-tools/free-ai-business-plan-generator` — 368 sessions and **251 conversions** in 90 days, the highest-converting content page on the site.
>
> **Why here:** The reader has just been told the DIY route is cheapest but leaves research, financials, and review on their plate. A free tool is the natural next step, and "free" matches the section's cost framing. **Angle: Ease.**

---

> **#2 — OPTIONAL — Inline Banner (Type 11)** | After the "Which business plan option should you choose?" section
>
> **Placed after:** "From my experience, I can say that a low-cost plan is not automatically weak. A high-priced plan also does not guarantee approval. What matters is whether the plan contains the required information, uses reasonable assumptions, presents consistent numbers, and suits the person who will read it."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  A solid business plan shouldn't cost thousands         │
> │                              [ Try Upmetrics AI ]       │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Target:** `/signup`
>
> **Note:** Different type and different angle (**Pain point**) from #1, and well clear of the end CTA. Adding it brings the post to 3 CTAs, slightly above the 1–2 guideline for this length — approve only if you want the extra conversion surface.

---

## Task 3: Downloadable Resource CTA

**Current setting:**

| Field | Current Value | Chars |
|-------|---------------|:--:|
| Resource URL | `https://upmetrics.co/download/ebook` | — |
| `resource_link_text` | Download Guide | — |
| `heading` | Ultimate Guide On Writing A Business Plan | — |
| **Rendered line** | **Download Guide: Ultimate Guide On Writing A Business Plan** | **57** |

**Two problems:** the combined line is 57 characters (over the ~55 limit, so it wraps), and it reads redundantly — "Guide: … Guide".

**Suggested change — keep the resource, fix the label:**

| Field | Suggested Value | Chars |
|-------|-----------------|:--:|
| Resource URL | `https://upmetrics.co/download/ebook` (unchanged) | — |
| `resource_link_text` | Download Guide | — |
| `heading` | How to Write a Business Plan | — |
| **Rendered line** | **Download Guide: How to Write a Business Plan** | **44** |

**Why keep `/download/ebook`:** it supports the DIY route, which is the cheapest option the article recommends. The obvious alternative, `/download/business-plan-template`, is already an inline body link (existing link #1) — using it here would surface the same URL twice on the page.

---

## Task 4: Related Content

**Current 4 items:**

| # | Current Title | Target | Assessment |
|:--:|--------------|--------|------------|
| 1 | I Tested the AI Business Plan Generators (Here's What I Found) | `/ai-tools/free-ai-business-plan-generator` | **Replace** — reassigned to Task 2 CTA (higher-value placement) |
| 2 | How Upmetrics Helped OGL Secured $142K in Funding | `/customers/our-genetic-legacy` | **Replace** — funding case study, low relevance to a pricing article |
| 3 | 400+ Business Plan Examples Every Founder Should See | `/sample-business-plans` | **Keep** (retitled) |
| 4 | Should You Hire a Writer or Use an AI to Draft Your Business Plan? | `/compare/business-plan-writer-vs-ai-business-plan-generator` | **Keep** (retitled, promote to #1) |

**Suggested new set (replaces all existing items):**

| # | Related Title | Chars | Post ID | Target URL | Post Type |
|:--:|--------------|:--:|:--:|-----------|-----------|
| 1 | Hire a Writer or Let AI Draft It? | 33 | 78505 | `/compare/business-plan-writer-vs-ai-business-plan-generator` | compare |
| 2 | Rather Write It Yourself? Start Here | 35 | 6056 | `/blog/how-to-write-a-business-plan` | post |
| 3 | Two Planning Tools, Side by Side | 32 | 109372 | `/blog/upmetrics-vs-liveplan` | post |
| 4 | 400+ Plans You Can Learn From | 29 | 1740 | `/sample-business-plans` | page |

All four are under 50 characters, use varied formats (question, imperative, noun phrase, number hook), and mix post types.

> **Dedup check:** Item #2 (`/blog/how-to-write-a-business-plan`) is also Task 1 suggestion #2. Per the priority rules, **Task 1 wins** — if you approve Task 1 #2, swap this sidebar item for **"The Numbers Behind Business Planning"** → `/blog/business-plan-statistics` (post 87158). Both decisions are noted in the feedback template below.

---

## Task 5: Meta Title & Description

### 1. Performance context

| Top Query | Impressions | Position | Current CTR | Benchmark CTR | Status |
|-----------|:--:|:--:|:--:|:--:|:--:|
| business plan cost | 211 | 17.5 | 0.47% | 1.5% | **Underperforming (−69%)** |
| business plan pricing | 76 | 53.9 | 0.00% | — | Too deep to rank |
| business plan services cost | 57 | 14.4 | 0.00% | 1.5% | **Underperforming** |
| business plan price | 54 | 20.3 | 0.00% | 1.5% | **Underperforming** |
| business plan prices | 53 | 25.6 | 0.00% | — | Too deep to rank |
| how much does a business plan cost? | 22 | 7.2 | 4.55% | 3.0% | Healthy |

**Device split (page-level, 90 days):**

| Device | Impressions | Clicks | Avg Position |
|--------|:--:|:--:|:--:|
| Desktop | 2,099 | 2 | 24.2 |
| Mobile | 983 | 0 | 34.9 |
| Tablet | 2 | 0 | 14.5 |

Mobile ranks **10.7 positions worse** than desktop on the same page — worth flagging to whoever owns page-speed and mobile rendering, since it is not something a meta rewrite fixes. It does affect this task in one way: mobile SERPs truncate titles near 50 characters, so the suggested 52-character title needs its keyword front-loaded. It is — "Business Plan Cost" starts at position 0, so nothing important is lost to truncation.

**Read:** the page sits around position 14–25 for nearly every commercial cost query. That is primarily a ranking problem, not purely a CTR problem — but the current title gives Google and searchers nothing distinctive to latch onto, and a title that leads with the actual price range is the cheapest available lever. The one query where the page ranks well (position 7.2) already converts above benchmark, which supports the diagnosis.

### 2. Current vs. suggested

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | `How Much Does a Business Plan Cost in %%currentyear%%?` | 43 rendered | `Business Plan Cost: $0 to $25,000 (%%currentyear%% Price Guide)` | 52 rendered | Keyword at position 0; adds price-range + format hooks; no longer mirrors H1 |
| Meta Description | `What does a business plan cost? Real 2026 prices for DIY, software, freelance writers and consultants — plus how to get one free.` | 129 | `Business plan cost ranges from $0 for DIY templates to $25,000 for consultants. Compare software, freelance writer, and firm pricing before you pay.` | 148 | Now in range; keyword at position 0; removes the raw em dash; drops the hardcoded year |
| Focus Keyphrase | `business plan cost` | — | `business plan cost` (unchanged) | — | Top query by impressions, position 17.5 — best improvement runway |
| Canonical | (unset — Yoast self-references) | — | No change | — | Correct as-is |
| OG Title | `Business Plan Cost: What You'll Pay in 2026` | 43 | `Business Plan Cost: What You Will Actually Pay in 2026` | 54 | **Fixes curly apostrophe** (encoding rule); keeps a distinct social angle |
| OG Description | (matches meta description) | 129 | (match new meta description) | 148 | — |

> **Note on `%%currentyear%%`:** the current title already uses the Yoast year variable — keep that. The suggested title preserves it so the year never goes stale. The current **description**, by contrast, hardcodes "2026"; the replacement drops the year entirely so it needs no annual maintenance.

### 3. SERP Preview

```
─────────────────────────────────────────────────────
upmetrics.co › blog › business-plan-cost
Business Plan Cost: $0 to $25,000 (2026 Price Guide)
Business plan cost ranges from $0 for DIY templates to $25,000
for consultants. Compare software, freelance writer, and firm
pricing before you pay.
─────────────────────────────────────────────────────
```

### 4. Differentiator

Competing titles for "business plan cost" almost all use the question format ("How Much Does a Business Plan Cost?"). Leading with the concrete range **$0 to $25,000** answers the query in the title itself rather than restating it — the strongest available differentiator on a SERP full of questions.

---

## Task 6: Image Alt Text

### Image Audit Summary

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty (wrong) | 0 | — |
| Needs Improvement | 0 | — |
| Good | 1 | No action |
| Decorative — Correct | 1 | No action |
| **Total images** | **2** | — |

**No action required.** Detail for the record:

| # | src | Role | Alt | Chars | Verdict |
|:--:|-----|------|-----|:--:|---------|
| 1 | `business-plan-cost-pricing-by-option.png` | chart | "Business plan cost comparison from $0 DIY templates to $25,000+ consulting firms" | 80 | **Good** — in the 60–125 range, describes the data and the range, carries the primary keyword once |
| 2 | `crossline.png` | icon-decorative | "crossline" | 9 | **Correct** — decorative accent inside the canonical end CTA; must not be modified |

The featured image alt is also set correctly: *"How much does a business plan cost with four options priced from $0 to $25,000+"*.

---

## Task 7: URL Slug

**No change recommended.**

| Field | Value | Assessment |
|-------|-------|------------|
| Current slug | `business-plan-cost` | 3 words, 18 chars, exact primary keyword, lowercase, hyphenated, no stop words |

The slug is already optimal. Changing it would require a 301 redirect and risk the existing impressions for zero gain.

---

## Task 8: Heading Structure

| Check | Result |
|-------|--------|
| Exactly one H1 | Pass — H1 is the post title; body starts at H2 |
| No skipped levels | Pass — H2 → H3 throughout |
| Primary keyword in an H2 | Pass — "Factors that affect business plan costs" |
| Headings under 70 chars | Pass — longest is 55 |
| No duplicate headings | Pass |

**One optional improvement:**

| Current H2 | Suggested | Reason |
|-----------|-----------|--------|
| `Conclusion` | `What Should You Actually Spend on a Business Plan?` | Generic label with no keyword or reader value; a question heading is also a better anchor for the table of contents |

---

## Task 9: Category / Taxonomy Assignment

**No change recommended.** The post is assigned to **Planning**, which is correct per the category reference (business planning, business plan writing, plan structure). No second category is warranted — the article is not about forecasting, funding, or starting a business.

---

## Task 10: Incoming Internal Link Suggestions

Pages on the site that should link **to** this one. Every source below is a verified WordPress post (real `post_id`, post type `post` — a valid prose-heavy source type). Pages used in Task 1 are excluded to avoid reciprocal links.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | How to Write a Business Plan Using ChatGPT (Prompts) | `/blog/chatgpt-business-plan` | 26488 | post | Covers the free-AI route to a plan — the cost trade-off is the target page's whole subject | what a business plan costs | **70 clicks / 3,443 impr. (28d), pos 13.1** | High |
| 2 | How to Write a Business Plan: 10 Easy Steps + Examples | `/blog/how-to-write-a-business-plan` | 6056 | post | Parent topic — readers deciding how to write a plan need the cost comparison | business plan cost | 96 sessions / 78% eng. | High |
| 3 | Upmetrics vs LivePlan: I Compared Both | `/blog/upmetrics-vs-liveplan` | 109372 | post | Software pricing comparison — cost of tools is the page's core subject | business plan software pricing | Below GA4 top 50 | High |
| 4 | How Small Business Development Centers (SBDCs) Can Help Your Business | `/blog/small-business-development-centers-sbdc` | 105993 | post | SBDCs are the free-help route; a paid-vs-free cost breakdown is the natural next click | cost of a business plan | Below GA4 top 50 | High |
| 5 | Upmetrics vs Generative AI Tools: Which Builds Better Business Plans? | `/blog/upmetrics-vs-generative-ai-tools` | 104815 | post | Compares free general AI against paid tools — a direct cost trade-off | business plan pricing | Below GA4 top 50 | Medium |
| 6 | 25+ Business Plan Statistics You Should Know | `/blog/business-plan-statistics` | 87158 | post | Stats roundups naturally cite cost benchmarks | average business plan cost | Below GA4 top 50 | Medium |
| 7 | How to Review a Business Plan: 4-Step Framework | `/blog/business-plan-review` | 62358 | post | Review services are a priced option covered on the target page | business plan writer cost | Below GA4 top 50 | Medium |

> Every source URL above is verified in WordPress (real post_id). Suggested anchor text is a starting term for the SEO team to search within the source page — the actual anchor depends on what text exists in that page's content.
>
> **Traffic caveat:** GSC click data is shown where the source page appears in the site's top 40 pages by clicks (28 days) — only row #1 does. That top-40 list is heavily saturated by sample-plan PDFs hosted on `templates.upmetrics.co`, which crowd out ordinary blog posts, so absence from it is not evidence a page is low-traffic. Rows #2–#7 fall back to GA4 sessions where available; all seven are published, indexed posts verified in WordPress. Pull per-page GSC clicks for rows #2–#7 before prioritising if click volume is your deciding factor.

---

## Content Defects (outside the standard SEO tasks)

Two body-copy problems found while parsing the content. Both need your explicit approval before I touch paragraph text.

**1. Duplicate paragraph — "Hire a full-service consulting firm" section**

This exact 34-word paragraph appears **twice**, separated by one other paragraph:

> "That wider scope is why consulting firms usually charge more. You are paying not only for the finished document, but also for professional help with some of the research and financial work behind it."

**Suggested fix:** delete the second occurrence (the one immediately before "In short, there is no standard price for a business plan.").

**2. Grammar error — "Revisions and consultation" section**

> Current: "If you need several meetings, major changes, or additional revision rounds, the provider **charge** more for the extra time involved."
>
> Suggested: "If you need several meetings, major changes, or additional revision rounds, the provider **may charge** more for the extra time involved."

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve #1 (swap industry research) + #2 (how you create the plan). Skip #3.
Task 2 (CTAs): Approve #1 (Yellow Tip after DIY section). Skip #2.
Task 3 (Resource CTA): Approve — shorten heading to "How to Write a Business Plan".
Task 4 (Related Content): Approve all 4, with the #2 swap to Business Plan Statistics (since Task 1 #2 is approved).
Task 5 (Meta Title/Desc): Approve title, description, and OG title. Keep focus keyphrase.
Task 6 (Image Alt Text): No action needed.
Task 7 (URL Slug): Skip — slug is already optimal.
Task 8 (Headings): Approve the Conclusion rename.
Task 9 (Categories): Skip — Planning is correct.
Task 10 (Incoming Links): Noted — will review manually.
Content defects: Approve both fixes (remove duplicate paragraph, fix grammar).
```

Or simply: **"Approve all"** / **"Approve all except Task X"**
