# SEO Suggestion Report — How to Identify a Target Market

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/how-to-find-your-target-market |
| **Post ID** | 83922 |
| **Post Type** | Blog Post |
| **Report Date** | 2026-04-06 |
| **GSC Data Range** | 2026-01-06 to 2026-04-03 (90 days) |
| **GA4** | Not available (MCP not configured) |

---

## Section B: Page Health Score + Action Summary

**Page Health Score: 6/10**

| Status | Count |
|--------|-------|
| Critical | 1 |
| Needs Improvement | 4 |
| Good | 4 |

**Critical:** Yoast SEO fields (title, description, focus keyphrase) are completely empty — Google is auto-generating your meta from post title/excerpt.

---

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|---|------|--------|--------|---------------|------------|---------------|
| 1 | Internal Links | High | Medium | 3 good links; 0 sales links | Add 4 new informational links | Approve #1–4 |
| 2 | CTA Placements | High | Medium | 0 CTAs in 2,303-word post | Add 2 CTAs (Type 6 + Type 12) | Approve both |
| 3 | Resource CTA | Medium | Quick Win | Not set | Customer Persona Template | Approve |
| 4 | Related Content | Medium | Quick Win | Not set | Set 4 related items | Approve #1–4 |
| 5 | Meta Title/Desc | High | Quick Win | NOT SET (critical) | Add optimized title + description | Approve |
| 6 | Image Alt Text | Low | Quick Win | 3 images, 1 improvable | Update image #2 alt text | Approve |
| 7 | URL Slug | — | — | `how-to-find-your-target-market` — clean | No change needed | Skip |
| 8 | Heading Structure | — | — | Well-structured, no skips | No change needed | Skip |
| 9 | Categories | — | — | Planning + Starting — correct | No change needed | Skip |

---

## Section C: Task-by-Task Suggestions

---

## Task 1: Internal Linking

**Current:** 3 internal links (market analysis, industry analysis, marketing strategy) + 1 branded homepage link = 4 total. For 2,303 words, target is 5–7 links. No sales/features links.

### Part A — Existing Link Audit

| # | Anchor Text | Target URL | Status |
|---|-------------|------------|--------|
| 1 | "market analysis" | `/blog/market-analysis-in-business-plan` | Good |
| 2 | "industry analysis" | `/blog/industry-analysis-in-business-plan` | Good |
| 3 | "marketing strategy" | `/blog/marketing-strategy-business-plan` | Good |
| 4 | "Upmetrics" | `/` (homepage) | Good — branded mention |
| E1 | "42% of marketers" | HubSpot blog | Good — external stat citation |
| E2 | "27% of marketers" | HubSpot blog | Good — external stat citation |

**Notes:** Both external links point to the same HubSpot URL — acceptable for citation purposes but consider diversifying sources if the post is updated. No competitor domains detected.

---

### Part B — New Link Suggestions

> **#1** — `value proposition` → `/blog/business-concept-guide`
>
> **Section:** 5. Pain Points
>
> **In context:** "This analysis taps into the frustrations and unmet needs of your customers. Understanding their pain points helps you shape a **value proposition** that feels relevant—because it speaks directly to what they're trying to fix or avoid."
>
> **Classification:** Informational

---

> **#2** — `industry reports` → `/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** Step 3 — Research what else your ideal customers are using
>
> **In context:** "Start with secondary research. Gather **industry reports**, consumer trend studies, and published surveys to get a broad overview of your customers and the market."
>
> **Classification:** Informational

---

> **#3** — `competitive edge` → `/blog/industry-benchmarking`
>
> **Section:** Step 5 — Look at who your competitors target (and ignore)
>
> **In context:** "But go beyond, and observe the gaps. The market where they are lagging. Aspects where there is a clear demand but an unfulfilled gap. [...] The stronger your **competitive edge**, the higher your chances of cutting through a crowded market and winning real attention."
>
> **Classification:** Informational

---

> **#4** — `market research` → `/blog/how-to-use-ai-for-market-research`
>
> **Section:** What to do when your target market changes?
>
> **In context:** "**Reassess your market research:** As and when the industry or market shifts, adjust your market segments and redefine the original personas to maintain relevance."
>
> **Note:** Using the occurrence in the "changes" section (not Step 3) to keep link spacing to 600+ words from the nearest existing link.
>
> **Classification:** Informational

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Write a Business Plan: Complete Guide | Within 100 words of #3 (competitive edge) in content flow — too close to link safely |
| Industry Analysis vs Market Analysis | "industry analysis" anchor already used for a different existing link |
| How To Use ChatGPT for Market Research | Closely related to #4 — reserved for Task 4 Related Content instead |
| SWOT Analysis Examples (5 Top Brands) | No matching anchor text in content for this topic |
| Business Plan Components (10 Essential) | "value proposition" matched to business-concept-guide instead |

</details>

---

## Task 2: CTA Placements

**Current:** 0 custom CTAs. Elementor template `[elementor-template id="46013"]` at end of post.

> **Note:** CLAUDE.md specifies the standard end-of-post Elementor template is `id="44970"`. This post uses `id="46013"`. Please verify this is the correct variant — if not, update to 44970 at the end of the content.

### Part A — Existing CTA Audit

| # | Type | Placement | Status | Notes |
|---|------|-----------|--------|-------|
| 1 | Elementor Template | End of post | Good — keep as-is | Standard end-of-post CTA block |

---

### Part B — New CTA Suggestions

> **#1** — Flex Banner: AI Writing (Type 6) | After Step 5 conclusion
>
> **Placed after:** "These steps should give you a well-defined target customer profile (or a few profiles) that you can confidently aim your marketing and product development at."
>
> **Persuasion angle:** Speed
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  Skip the blank page.                                   │
> │                                                         │
> │  Write your target market section in minutes            │
> │                                                         │
> │  [ Start Writing Now ]              🖼 AI Writing       │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **CTA HTML:**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> Skip the blank page.
> <p class="title h2">Write your target market section in minutes</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Start Writing Now</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-writing-200.svg" alt="AI Writing" width="200" height="170" /></div>
> </div>
> ```

---

> **#2** — Yellow Tip Alert (Type 12) | After "How detailed should your target market be?"
>
> **Placed after:** "That said, chase the details that help you shape your messaging, pricing, or product fit. If a detail is not adding any value, cut it down. Be specific, but only when it's relevant."
>
> **Persuasion angle:** Ease / Specificity
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │ 💡 Tip: Upmetrics walks you through the target market   │
> │ section step by step. Write your plan free →            │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **CTA HTML:**
> ```html
> <div class="yellow-alert"><strong>Tip: </strong>Upmetrics walks you through the target market section step by step — demographics, personas, market size, and all. <a href="https://upmetrics.co/cta/help">Write your plan free</a>.</div>
> ```

**Spacing check:** CTA #1 at ~word 1,450. CTA #2 at ~word 1,950. ~500 words apart ✓. CTA #2 is ~350 words before the Elementor template ✓.

---

## Task 3: Downloadable Resource CTA

**Recommendation:** `/download/customer-persona-template` — **Customer Persona Template**

**Rationale:** The post explicitly walks readers through building a buyer's persona (with a visual example in the "How to define your target market in a business plan" section). The Customer Persona Template is the natural next step for anyone who wants to apply what they just learned.

| Field | Value |
|-------|-------|
| `resource_url` | `https://upmetrics.co/download/customer-persona-template` |
| `heading` | `Customer Persona Template` |
| `resource_link_text` | `Download Template` |
| Combined display | `Download Template: Customer Persona Template` (44 chars) ✓ |

**Alternative if this doesn't fit:** `/download/market-analysis-kit` (The Market Analysis Kit — covers market research more broadly).

---

## Task 4: Related Content

Post type `post` supports related content ✓. Currently not set.

| # | Page | Post ID | Custom Title | Rationale |
|---|------|---------|--------------|-----------|
| 1 | `/blog/industry-analysis-vs-market-analysis` | 96105 | "Industry Analysis vs. Market Analysis" | Direct complement — readers defining target market also need to understand both analysis types |
| 2 | `/blog/how-to-use-chatgpt-for-market-research` | 98033 | "Research Your Market Faster with AI" | Natural follow-on — step 3 of the guide is about market research |
| 3 | `/blog/what-is-business-plan` | 77811 | "Business Plans, Explained Simply" | Target market is presented in a business plan — this answers the next question |
| 4 | `/blog/market-analysis-in-business-plan` | — | "How to Write a Market Analysis" | The target market section lives inside market analysis — direct extension |

> **Note for #4:** Post ID for `market-analysis-in-business-plan` is already used as an existing in-content link. The cross-task rule doesn't prohibit it appearing in Related Content sidebar (different placement type) — only the same URL as a body link AND related item is restricted. Since this is a sidebar-only addition it's acceptable. **However**, if you prefer clean separation, substitute with `/blog/how-to-use-ai-for-market-research` (post ID 83462) titled "Using AI for Market Research."

---

## Task 5: Meta Title & Description

**Status: CRITICAL — Yoast SEO fields are completely empty.** Google is auto-generating from the post title and excerpt. This is the highest-impact fix in this report.

**Top GSC query (90 days):** "example of target market in business plan" — 227 impressions at position 47.7. Suggests content is being surfaced for business-plan-specific target market queries.

### Current vs. Suggested

| Field | Current | Suggested | Chars |
|-------|---------|-----------|-------|
| **Meta Title** | *(not set — defaults to post title)* | `How to Find Your Target Market: Step-by-Step Guide` | 52 |
| **Meta Description** | *(not set)* | `Learn how to identify your target market with a 5-step process. Covers demographics, psychographics, competitor research, and business plan examples.` | 150 |
| **Focus Keyphrase** | *(not set)* | `how to find your target market` | — |
| **OG Title** | *(not set)* | `How to Find Your Target Market: Step-by-Step Guide` | 52 |
| **OG Description** | *(not set)* | `Not sure who your business is for? Use this 5-step framework to find, define, and document your target market — with a real-world buyer persona example.` | 152 |
| **Canonical URL** | *(auto — correct)* | `https://upmetrics.co/blog/how-to-find-your-target-market` | — |

### SERP Preview

```
┌──────────────────────────────────────────────────────────────────┐
│ How to Find Your Target Market: Step-by-Step Guide               │
│ upmetrics.co › blog › how-to-find-your-target-market            │
│ Learn how to identify your target market with a 5-step process.  │
│ Covers demographics, psychographics, competitor research, and... │
└──────────────────────────────────────────────────────────────────┘
```

**Notes:**
- Current post title is "How to Identify a Target Market" but the URL slug says "how-to-find-your-target-market". The meta title uses "Find" to match the slug and the most natural query form. The post H1 can stay as-is.
- "Step-by-Step Guide" hook without a year (page is about timeless process, no year-specific content).
- Focus keyphrase matches the URL slug exactly — strong signal.

---

## Task 6: Image Alt Text

| # | Current Alt | Suggested Alt | Change? |
|---|-------------|---------------|---------|
| 1 | `6 key dimensions to define your target market` | No change needed | No |
| 2 | `how to find your target market` | `5 steps to find your target market` | Minor improvement |
| 3 | `buyer persona for a clean protein brand` | No change needed | No |

**#2 rationale:** Current alt is lowercase and very generic. "5 steps to find your target market" is more descriptive (references the 5-step infographic the image depicts) and slightly more specific. Small improvement only — prioritize other tasks first.

---

## Task 7: URL Slug

**Current slug:** `how-to-find-your-target-market` — Clean, keyword-focused, 5 words. No change needed.

---

## Task 8: Heading Structure

**Current structure:** 7 H2s + 11 H3s. No H1 in content (correct — post title serves as H1). No skipped levels. Primary keyword "target market" appears in multiple H2s. Structure is clean.

No changes recommended.

---

## Task 9: Category / Taxonomy

**Current:** Planning + Starting

**Assessment:** Correct. The post is about identifying target markets as part of business planning (Planning) and starting a business (Starting). No change needed.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve #1, #2, #3, #4.
Task 2 (CTAs): Approve #1 (Type 6 after Step 5). Approve #2 (Yellow Tip after "How detailed").
Task 3 (Resource CTA): Approve Customer Persona Template.
Task 4 (Related Content): Approve items #1–4.
Task 5 (Meta Title/Desc): Approve suggested title. Approve description. Approve keyphrase. Approve OG fields.
Task 6 (Image Alt Text): Approve image #2 update only.
Task 7 (URL Slug): Skip — slug is already clean.
Task 8 (Headings): Skip — structure is fine.
Task 9 (Categories): Skip — categories are correct.

Or simply: "Approve all" / "Approve all except Task 7, 8, 9"
```
