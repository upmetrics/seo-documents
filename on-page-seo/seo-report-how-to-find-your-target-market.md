# SEO Suggestion Report — How to Find Your Target Market

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/how-to-find-your-target-market |
| **Post ID** | 83922 |
| **Post Type** | Blog Post (`post`) |
| **Report Date** | 2026-04-06 |
| **GSC Data Range** | Last 90 days |
| **GA4** | Skipped (property ID not configured) |

---

## Page Health Score: 4 / 10

| Issue | Severity | Deduction |
|-------|----------|-----------|
| Zero body CTAs in content | Critical | -2.0 |
| Focus keyphrase not set in Yoast | Critical | -1.0 |
| Meta title too long (~67 chars rendered) | High | -1.0 |
| No canonical URL set | Medium | -0.5 |
| No OG title / description set | Medium | -0.5 |
| Non-standard Elementor template ID (`46013` vs `44970`) | Low | -0.5 |
| **Total** | | **4 / 10** |

| Status | Count |
|--------|-------|
| Critical | 2 |
| Needs Improvement | 4 |
| Good | 5 |

---

## Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|---|------|--------|--------|---------------|------------|---------------|
| 1 | Internal Links | High | Medium | 3 body links; 2 external stats links | Add 2 new links | Approve #1, #2 |
| 2 | CTAs | High | Medium | 0 body CTAs | Add 2 CTAs (Inline Banner + AI Business Plan) | Add both |
| 3 | Resource CTA | Low | Quick Win | "Market Analysis Kit" set | Keep existing | Keep |
| 4 | Related Content | Medium | Quick Win | 4 set — all conflict with other tasks | Replace all 4 | Approve all |
| 5 | Meta Title / Desc | High | Quick Win | Title ~67 chars; no keyphrase; no canonical; no OG | New title (59 chars) + full SEO fields | Approve all |
| 6 | Image Alt Text | Low | Quick Win | 1 of 3 images needs better alt | Update image 2 alt | Approve |
| 7 | URL Slug | None | — | `how-to-find-your-target-market` — clean and keyword-focused | Keep as-is | Skip |
| 8 | Heading Structure | None | — | Clean H2/H3 hierarchy, one H1 | No changes | Skip |
| 9 | Categories | None | — | Planning + Starting — correct | No change | Skip |

---

## Task 1: Internal Links

### Existing Link Audit

| # | Anchor Text | Target URL | Status |
|---|-------------|------------|--------|
| 1 | market analysis | `/blog/market-analysis-in-business-plan` | **Good** |
| 2 | industry analysis | `/blog/industry-analysis-in-business-plan` | **Good** |
| 3 | marketing strategy | `/blog/marketing-strategy-business-plan` | **Good** |
| 4 | Upmetrics | `https://upmetrics.co/` | **Good** (branded homepage — expected) |

**External links noted (not internal):** "42% of marketers" and "27% of marketers" both link to `blog.hubspot.com` — these are fine external citations.

**Current body link count:** 4 internal links (3 editorial + 1 branded). No competitor domains detected.

---

### New Link Suggestions

> **#1** — `secondary research` → `https://upmetrics.co/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** Step 3 — Research what else your ideal customers are using
>
> **In context:** "Start with **secondary research**. Gather industry reports, consumer trend studies, and published surveys to get a broad overview of your customers and the market."
>
> **Type:** Informational | Anchor wraps existing text — zero text changes needed.

---

> **#2** — `industry reports` → `https://upmetrics.co/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** Step 3 — Research what else your ideal customers are using
>
> **In context:** "Start with secondary research. Gather **industry reports**, consumer trend studies, and published surveys to get a broad overview of your customers and the market."
>
> **Classification:** Informational | Anchor wraps existing text — zero text changes needed.
>
> ⚠️ **Note:** #1 and #2 target the same URL and are in the same sentence — implement **one or the other, not both**. "secondary research" is the broader, more descriptive anchor; "industry reports" is more specific. Pick whichever reads more naturally to you in context.

---

> **#3** — `competitive edge` → `https://upmetrics.co/blog/what-is-a-competitive-analysis-how-to-conduct-it-effectively`
>
> **Section:** Step 5 — Look at who your competitors target (and ignore)
>
> **In context:** "The stronger your **competitive edge**, the higher your chances of cutting through a crowded market and winning real attention."
>
> **Type:** Informational | Anchor wraps existing text — zero text changes needed.

---

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| Market Analysis in Business Plan | Already linked in existing content (link #1 above) |
| Industry Analysis in Business Plan | Already linked in existing content (link #2 above) |
| TAM SAM SOM / Market Size post | Proximity conflict — falls ~57 words from existing "industry analysis" link; spacing rule would be violated |
| Customer Persona Template | Considered for Task 1 but better fit as Task 3 or Task 4 resource; no strong anchor text match in body content |
| Target Audience post (if exists) | No verbatim anchor text match found in content; topic is covered but no exact phrase surfaces |

</details>

---

## Task 2: CTA Placements

### Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|---|----------|-----------|--------|-------|
| 1 | `[elementor-template id="46013"]` | End of post | **Needs investigation** | Standard Upmetrics posts use `id="44970"`. This ID is non-standard — may be a different template variant. Verify in WP admin before changing. |

**Body CTA count: 0** — no CTAs anywhere in the ~1,600-word content.

---

### New CTA Suggestions

> **#1** — Type 11 (Inline Banner) | After "6. Goals" H3
>
> **Placed after:** "Goals reflect what your customers want to achieve using your product or service. Maybe they're trying to save money, make faster decisions, or improve how they work. When you understand these outcomes, you can position your offer in a way that they actually care about."
>
> **Persuasion angle:** Outcome — natural bridge from understanding your customer to acting on it.
>
> **CTA Preview:**
> ```
> ┌────────────────────────────────────────────────────────────┐
> │  Know your customer — now write a plan they'll actually    │
> │  fund.                          [ Start Planning ]         │
> └────────────────────────────────────────────────────────────┘
> ```
>
> **HTML:**
> ```html
> <div class="upm_blog_bg_cta inline-cta-banner">
> Know your customer&mdash;now write a plan they'll actually fund.
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/cta/help">Start Planning</a>
> </div>
> ```

---

> **#2** — Type 8 (Flex Banner: AI Business Plan, Image Right) | After buyer persona image
>
> **Placed after:** "Let's now see what a buyer's persona for a clean protein brand would look like: [buyer persona image]"
>
> **Context:** Directly follows the complete business plan example — strong moment to offer the tool.
>
> **Persuasion angle:** Speed — after seeing a detailed buyer persona, offering to build it fast is compelling.
>
> **CTA Preview:**
> ```
> ┌────────────────────────────────────────────────────────────┐
> │  A sharp target market section doesn't write itself.       │
> │                                                            │
> │  Write yours in minutes — AI fills in the rest             │
> │                                                            │
> │  [ Try Upmetrics AI ]                    🖼 AI Biz Plan   │
> └────────────────────────────────────────────────────────────┘
> ```
>
> **HTML:**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> A sharp target market section doesn't write itself.
> <p class="title h2">Write yours in minutes &mdash; AI fills in the rest</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Try Upmetrics AI</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-business-plan.svg" alt="AI Business Plan" width="200" height="170" /></div>
> </div>
> ```

**Spacing check:** CTA #1 → CTA #2: ~900+ words (entire 5-step guide + business plan section). CTA #2 → Elementor template: ~400 words. Both within guidelines.

---

## Task 3: Downloadable Resource CTA

**Current resource CTA:** "The Market Analysis Kit" — topically well-matched to this post about target market research.

**Recommendation:** Keep as-is. No change needed.

**Alternative (if you want to swap):** A customer persona template or target market worksheet would also work here. Run `list-posts` with `search: "customer persona"` and `post_type: "download"` to find options.

---

## Task 4: Related Content

**Current related posts:** All 4 conflict with other tasks (2 claimed by new Task 1 links, 1 already linked in body, 1 low topical relevance). Replace all.

### Suggested Replacements

| # | Post ID | URL | Custom Title | Reason |
|---|---------|-----|--------------|--------|
| 1 | 96105 | `/blog/industry-analysis-vs-market-analysis` | Which Analysis Does Your Plan Actually Need? | Direct topical complement — reader just learned to research their market |
| 2 | 98033 | `/blog/how-to-use-chatgpt-for-market-research` | Research Your Market Using ChatGPT | Practical next step after learning the research methodology |
| 3 | 83417 | `/blog/business-growth-plan` | Build a Plan That Grows With You | Natural follow-on — from defining market to planning for growth |
| 4 | 77811 | `/blog/what-is-business-plan` | Business Plans, Explained Simply | Foundational context for readers new to business planning |

**Implementation:** Pass all 4 as `related_posts` with custom `title` values. This **replaces** the current related posts.

---

## Task 5: Meta Title & Description

### Current State vs. Suggestion

| Field | Current | Suggested | Chars |
|-------|---------|-----------|-------|
| **SEO Title** | ~67 chars (too long, truncated in SERP) | How to Find Your Target Market (With Business Plan Example) | 59 |
| **Meta Description** | Not set or auto-generated | Learn how to find and define your target market in 5 steps. Includes six key dimensions, real examples, and tips on writing it in your business plan. | 152 |
| **Focus Keyphrase** | *(blank)* | how to find your target market | — |
| **Canonical URL** | *(not set)* | https://upmetrics.co/blog/how-to-find-your-target-market | — |
| **OG Title** | *(not set)* | How to Find Your Target Market (With Business Plan Example) | 59 |
| **OG Description** | *(not set)* | Learn how to find and define your target market in 5 steps. Includes six key dimensions, real examples, and tips on writing it in your business plan. | 152 |

### SERP Preview

```
https://upmetrics.co/blog/how-to-find-your-target-market

How to Find Your Target Market (With Business Plan Example)
Learn how to find and define your target market in 5 steps. Includes
six key dimensions, real examples, and tips on writing it in your
business plan.
```

**Primary GSC keyword:** "how to find your target market" — appears in the first 5 words of suggested title. Strong match.

---

## Task 6: Image Alt Text

| # | Image File | Current Alt | Suggested Alt | Status |
|---|------------|-------------|---------------|--------|
| 1 | `6-key-dimensions-to-define-your-target-market.webp` | "6 key dimensions to define your target market" | Keep | Good |
| 2 | `how-to-find-your-target-market.webp` | "how to find your target market" | "five-step process for finding your target market: start with the product, list customer traits, research, analyze data, and study competitors" | **Needs update** |
| 3 | `buyer-persona-for-a-clean-protein-brand.webp` | "buyer persona for a clean protein brand" | Keep | Good |

**Note on Image 2:** The current alt is a keyword string, not a description. The image is a step-by-step infographic — alt text should describe what it shows, not just repeat the keyword.

---

## Task 7: URL Slug

**Current slug:** `how-to-find-your-target-market`

**Assessment:** Clean, keyword-rich, 5 words. No stop words needed. Already well-optimized.

**Recommendation:** No change.

---

## Task 8: Heading Structure

| Level | Count | Assessment |
|-------|-------|------------|
| H1 | 1 | ✓ Single H1 — good |
| H2 | 7 | ✓ Well-structured major sections |
| H3 | 11 | ✓ Proper subsections under H2s (6 dimensions + 5 steps) |

**Observations:**
- Primary keyword appears naturally in the H1 and first H2 area.
- H2s follow logical reading order.
- No skipped levels.
- Last H2 ("Need help figuring out your target market? And more?") is question-style — acceptable as a conclusion CTA section, no change needed.

**Recommendation:** No changes.

---

## Task 9: Category / Taxonomy

**Current categories:** Planning + Starting

**Assessment:** Correct. This post explains a business research concept (Planning) for entrepreneurs starting out (Starting). Max 2 categories followed.

**Recommendation:** No change.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1 OR #2 (same URL — pick one), add #3. Keep all existing links.
Task 2 (CTAs): Add CTA #1 after Goals. Add CTA #2 after buyer persona image. [Investigate / change / keep] Elementor template ID.
Task 3 (Resource CTA): Keep existing.
Task 4 (Related Content): Approve all 4 replacements.
Task 5 (Meta Title/Desc): Approve title. Approve description. Set keyphrase. Set canonical. Set OG.
Task 6 (Image Alt Text): Approve image 2 update.
Task 7 (URL Slug): Skip.
Task 8 (Headings): Skip.
Task 9 (Categories): Skip.

Or simply: "Approve all" / "Approve all except Task X"
```
