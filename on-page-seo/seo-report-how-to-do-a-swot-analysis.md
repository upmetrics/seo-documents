# SEO Suggestion Report — How to Do a SWOT Analysis

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/how-to-do-a-swot-analysis |
| **Post ID** | 6165 |
| **Post Type** | Blog Post (`post`) |
| **Post Title** | What is SWOT Analysis & How to Conduct it |
| **Report Date** | 2026-04-10 |
| **GSC Data Range** | Last 90 days |
| **GA4 Data Range** | Last 30 days (traffic) / Last 90 days (conversions) |

---

## Section B: Page Health Score + Action Summary

### Page Health Score: 4.5 / 10

| Status | Count | Items |
|--------|:-----:|-------|
| Critical | 1 | Yoast SEO fields completely unset |
| Needs Improvement | 4 | Post title/H1 mismatch, alt text issues (typo + generic), internal links below target, Resource Hero CTA missing |
| Good | 3 | Heading structure, existing body links, Elementor CTA present |

**Why 4.5:** The page has 0 clicks despite ~3,400 impressions over 90 days. Root cause: ranking at position 57.7 for the primary keyword with zero Yoast metadata set. The content is solid and structured well — all the SEO gaps are fixable in one pass.

---

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|---|------|:------:|:------:|---------------|------------|---------------|
| 1 | Internal Links | Medium | Medium | 4 body links (target: 5-7 for 2,480 words) | Add 2 new links | Approve #1, #2. Skip #3. |
| 2 | CTA Placements | Medium | Medium | 2 content CTAs + Elementor | Update Type 1 resource; add 1 new banner | Approve update to #1; add #2 |
| 3 | Resource CTA | Low | Quick Win | Not set | Set Market Analysis Kit | Approve |
| 4 | Related Content | Low | Quick Win | Not set | Set 4 related pages | Approve all |
| 5 | Meta Title & Desc | **High** | Quick Win | All fields unset | Full Yoast setup | Approve all |
| 6 | Image Alt Text | Medium | Quick Win | 1 typo, 2 generic labels | Fix 4 images | Approve all 4 |
| 7 | URL Slug | — | — | `how-to-do-a-swot-analysis` — already optimal | Skip | Skip |
| 8 | Heading Structure | Low | Quick Win | 5 H2 + 14 H3, minor improvement possible | Update 1 H2 | Approve |
| 9 | Categories | Low | Quick Win | Unknown — verify | Assign Planning | Approve |

---

## Section C: Task-by-Task Suggestions

---

## Task 1: Internal Links

### Existing Link Audit

**Current count:** 5 internal links (4 body + 1 branded homepage)

| # | Anchor Text | Target URL | Status |
|---|-------------|------------|--------|
| 1 | SWOT analysis examples | /blog/5-top-brands-swot-analysis-examples | Good |
| 2 | competitive analysis | /blog/competitive-analysis-frameworks | Good |
| 3 | business strategy | /blog/how-to-create-a-business-strategy | Good |
| 4 | strategic business planning | /blog/strategic-business-planning | Good |
| 5 | Upmetrics | / | Good (branded homepage) |

No broken links, no competitor links, no query strings detected. All 5 links are well-placed and contextually relevant.

---

### New Link Suggestions

**RECOMMENDED**

> **#1** — `business plan for funding` → `/blog/how-to-write-a-business-plan-complete-guide`
>
> **Section:** Step 1 — Define the Objective
>
> **In context:** "If you're writing a **business plan for funding**, your SWOT should focus on what an investor wants to see: Your market position, growth potential, and financial stability."

---

> **#2** — `your financial plan` → `/blog/financial-plan-for-startup`
>
> **Section:** How to Use Your SWOT — Using SWOT results in your business plan
>
> **In context:** "Think about it this way. A strength like '80% customer retention' can also support your traction and marketing section. A weakness like '30% of revenue tied to one client' can be used in **your financial plan**."

---

**OPTIONAL**

> **#3** — `investor presentation` → `/blog/business-plan-for-investors`
>
> **Section:** What it's "not"?
>
> **In context:** "Some even assume it's a tool only relevant when drafting an **investor presentation** or a five-year plan, while others treat it like an academic framework filled with jargon."
>
> **Note:** Placement context is mildly dismissive of the assumption (not a strong recommendation). Include only if investor content targeting is a priority.

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| 5 Top Brands SWOT Analysis Examples | Already linked in body (anchor: "SWOT analysis examples") |
| Competitive Analysis Frameworks | Already linked in body (anchor: "competitive analysis") |
| How to Create a Business Strategy | Already linked in body (anchor: "business strategy") |
| Strategic Business Planning | Already linked in body (anchor: "strategic business planning") |
| Market Analysis Kit download | Claimed by Task 3 (Resource CTA) |

</details>

---

## Task 2: CTA Placements

### Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|---|----------|-----------|--------|-------|
| 1 | Type 1 — Download Link | After "What is a SWOT analysis?" section | Needs improvement | Links to Competitive Analysis Kit — adjacent topic but not SWOT-specific. Suggest updating to a SWOT or planning resource. |
| 2 | Blog Post CTA | After "4. Threats" quadrant | Good | Directly promotes SWOT Generator — topically perfect. |
| 3 | Elementor template `[elementor-template id="44970"]` | End of post | Good | Required end-of-post CTA. Present. |

**Spacing note:** The current blog-post-cta sits before the 6-step how-to section (~1,200 words of content remain after it). There is sufficient spacing for one additional CTA.

---

### New CTA Suggestions

**RECOMMENDED**

> **#1** — Update existing Type 1 Download Link | "What is a SWOT analysis?" section
>
> **Current:** `→ Download Now: Competitive Analysis Kit`
>
> **Suggested update:** Change to a SWOT or planning resource that's more directly relevant.
>
> **Updated HTML:**
> ```html
> <div class="text-center m-40px-t m-25px-b"><a class="cta-link" href="https://upmetrics.co/download/market-analysis-kit" rel="noopener">&rarr; Download Now: Free Market Analysis Kit </a></div>
> ```
>
> **Note:** If a SWOT analysis template exists in the downloads library, that would be an even better fit than Market Analysis Kit.

---

> **#2** — Type 6 Flex Banner (AI Writing) | After "Prioritize and analyze results" (Step 6)
>
> **Placed after:** "These questions strip away the noise. To make it even clearer, I usually plot everything on an impact vs. urgency grid. High-impact and urgent items rise to the top. The rest stay noted, but we don't waste energy on them today."
>
> **CTA Preview:**
> ```
> ┌───────────────────────────────────────────────────────────────┐
> │  Your SWOT is ready. Now build the plan around it.            │
> │                                                               │
> │  Turn SWOT insights into a full business plan with AI         │
> │                                                               │
> │  [ Start Planning Now ]                      🖼 AI Writing    │
> └───────────────────────────────────────────────────────────────┘
> ```
>
> This is placed at the natural "now what?" moment — step 6 ends with analyzing results, and the reader is ready to act.

---

## Task 3: Downloadable Resource CTA

**Recommendation:** Set the Resource Hero CTA to Market Analysis Kit.

| Field | Value |
|-------|-------|
| Resource URL | `/download/market-analysis-kit` |
| `resource_link_text` | `Download Kit` |
| `heading` | `Free Market Analysis Kit` |
| Combined display | "Download Kit: Free Market Analysis Kit" (38 chars) ✓ |

**Rationale:** SWOT analysis pulls heavily from market/competitive data to fill Opportunities and Threats quadrants. The Market Analysis Kit is the most relevant planning resource for this audience.

---

## Task 4: Related Content

**Recommendation:** Set 4 related pages on post 6165.

| # | Title | Custom Display Title | URL |
|---|-------|---------------------|-----|
| 1 | How to Write a Business Plan | What Goes Into a Strong Business Plan? | /blog/how-to-write-a-business-plan-complete-guide |
| 2 | Competitive Analysis Guide | Sizing Up the Competition | /blog/competitive-analysis |
| 3 | Market Research for Business Plan | How to Research Your Market Before Planning | /blog/market-research-for-business-plan |
| 4 | Business Plan Examples | Real Business Plans Worth Studying | /blog/business-plan-examples |

**Note:** Items #1 and #2 are also suggested as new internal links (Task 1). If both are approved, those same URLs will be in the body AND the related sidebar — that creates duplication per cross-task rules. **If Task 1 #1 and #2 are approved, replace Related Content items #1 and #2 with alternates from the repository** (e.g., a strategic planning or SWOT-adjacent page).

---

## Task 5: Meta Title & Description

**Current state: All Yoast fields unset.** This is the primary reason the page ranks at position 57 — Google is inferring the title from the H1 ("What is SWOT Analysis & How to Conduct it"), which doesn't match the primary keyword.

### Meta Title

| | Value | Length |
|--|-------|:------:|
| **Current** | What is SWOT Analysis & How to Conduct it | 42 chars |
| **Suggested** | How to Do a SWOT Analysis: Step-by-Step Guide (2026) | 52 chars ✓ |

### Meta Description

| | Value | Length |
|--|-------|:------:|
| **Current** | Not set | — |
| **Suggested** | Learn how to do a SWOT analysis step by step, with real business examples. This consultant-backed guide covers all four quadrants and how to act on findings. | 159 chars ✓ |

### Focus Keyphrase

| Field | Value |
|-------|-------|
| **Suggested** | `how to do a swot analysis` |
| **GSC data** | 280 impressions / position 57.7 — highest impression volume for this page |

### SERP Preview

```
How to Do a SWOT Analysis: Step-by-Step Guide (2026)
upmetrics.co › blog › how-to-do-a-swot-analysis
Learn how to do a SWOT analysis step by step, with real business
examples. This consultant-backed guide covers all four quadrants...
```

### OG / Social Fields

| Field | Suggested |
|-------|-----------|
| OG Title | How to Do a SWOT Analysis: Step-by-Step Guide (2026) |
| OG Description | A practical SWOT analysis guide with real business examples. Learn to identify strengths, weaknesses, opportunities, and threats — and what to do with them. |
| Canonical | https://upmetrics.co/blog/how-to-do-a-swot-analysis (verify current is set) |

---

## Task 6: Image Alt Text

**Current count:** 5 images (4 content + 1 decorative in CTA)

| # | Image File | Current Alt | Issue | Suggested Alt |
|---|-----------|-------------|-------|---------------|
| 1 | ai-assistant.webp | "Ai assistant" | Generic — just the app name, wrong capitalization | "Upmetrics AI assistant suggesting SWOT questions for a cafe business" |
| 2 | perplexity.webp | "Perplexity" | Just the app name — no context | "Perplexity AI answering questions to help frame a SWOT analysis" |
| 3 | heres-a-quick-mental-checklist-to-spot-threats.webp | "Heres a quick mental checklist to spot threats" | Missing apostrophe; long but acceptable otherwise | "Mental checklist for spotting business threats in a SWOT analysis" |
| 4 | swot-anylysis.webp | "Swot anylysis" | **Typo** ("anylysis"), wrong capitalization | "SWOT analysis matrix showing strengths, weaknesses, opportunities, and threats" |
| 5 | swot-analysis-generator.png (in CTA) | "" (empty) | Decorative in CTA block — empty alt is correct | Skip — leave as-is |

---

## Task 7: URL Slug

**Current slug:** `how-to-do-a-swot-analysis`

This is already optimal — contains the exact primary keyword, clean, 5 words. **No change needed.**

---

## Task 8: Heading Structure

**Overall structure is sound.** One minor improvement:

| # | Heading | Current | Issue | Suggested |
|---|---------|---------|-------|-----------|
| 1 | H2 (conclusion) | "The bottom line" | Too generic; no keyword signal | "From SWOT Analysis to Action" |

All other headings are well-structured. H3 numbering is consistent within each section. No skipped levels.

**Note:** The H1/post title ("What is SWOT Analysis & How to Conduct it") doesn't match the primary keyword, but this is addressed via the meta title in Task 5. Changing the display title is optional — it would update H1 and URL breadcrumb across the site.

---

## Task 9: Category / Taxonomy

| Field | Recommendation |
|-------|---------------|
| Primary Category | **Planning** — SWOT is a strategic planning tool; content covers business plan integration, strategy formation, and forecasting |
| Secondary Category | Optional: **Managing** — covers ongoing strategic use of SWOT results |
| Max categories | 2 |

Recommendation: Set **Planning** as primary. Adding **Managing** as secondary is optional — the content leans more toward planning than operations management.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2. Skip #3.
Task 2 (CTAs): Update #1 to Market Analysis Kit. Add #2 after "Prioritize and analyze results".
Task 3 (Resource CTA): Approve Market Analysis Kit.
Task 4 (Related Content): Approve all 4.
Task 5 (Meta): Approve suggested title. Approve description. Approve focus keyphrase. Approve OG fields.
Task 6 (Alt Text): Approve all 4 updates.
Task 7 (Slug): Skip — already optimal.
Task 8 (Headings): Approve H2 conclusion change.
Task 9 (Categories): Approve Planning only.

Or simply: "Approve all" / "Approve all except Task 4 (hold for URL conflict check)"
```
