# SEO Suggestion Report: TAM SAM SOM Market Size Metrics

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/tam-sam-som-market-size-metrics |
| **Post ID** | 6137 |
| **Post Type** | Blog Post (`post`) |
| **Category** | Planning |
| **Report Date** | 2026-04-09 |
| **GSC Data Range** | Jan 8 – Apr 7, 2026 (90 days) |
| **GA4 Data Range** | Mar 10 – Apr 8, 2026 (30 days) |
| **Last Modified** | 2025-09-17 |

---

## Section B: Page Health Score + Action Summary

### Page Health Score: 4 / 10

| Status | Count | Items |
|--------|:-----:|-------|
| **Critical** | 1 | Meta title/description not optimized → 0.024% CTR across 16k+ impressions |
| **Needs Improvement** | 4 | Image trapped inside H2 tag; blog tip CTA generic; low engagement (28.9%); no Resource CTA or Related Content set |
| **Minor** | 3 | `<b>T</b>` artifact in heading; HTTP external link; anchor text leading space |
| **Good** | 5 | Indexed + crawled; FAQ schema; Elementor template; 4 quality internal links; readable content structure |

**Headline issue:** This page gets **16,728 impressions** but only **4 clicks** over 90 days — a 0.024% CTR. Average position is 45–55, placing it on page 4–6 for "tam sam som" (1,099 impressions, pos. 49). The meta title and description are un-optimized and not compelling enough to earn clicks even when the page does appear. Combined with a 28.9% engagement rate and 71% bounce rate in GA4, this page needs foundational SEO fixes before content refinement.

---

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|---|------|:------:|:------:|---------------|------------|---------------|
| 1 | Internal Links | High | Medium | 4 body links; 1 HTTP external link | Add 2 new links; fix existing issues | Approve #1–#2; Skip #3 |
| 2 | CTA Placements | Medium | Medium | 3 CTAs (download, tip, elementor); tip is weak | Replace blog tip; add 1 investor-ready banner | Approve both |
| 3 | Resource CTA | Medium | Quick Win | Not set | Set Market Analysis Kit | Approve |
| 4 | Related Content | Medium | Quick Win | Not set | Set 4 topically relevant items | Approve all |
| 5 | Meta Title & Desc | **High** | Quick Win | Not customized (defaulting to post title) | New title + description targeting "tam sam som" | Approve suggested |
| 6 | Image Alt Text | Low | Quick Win | Both alts basic/keyword-stuffed | Improve both images | Approve both |
| 7 | URL Slug | Low | Skip | `tam-sam-som-market-size-metrics` — acceptable | Skip — slug is fine; position too low to risk redirect | Skip |
| 8 | Heading Structure | Medium | Medium | Image inside H2 tag (bug); `<b>T</b>` artifact | Fix empty H2 wrapper; clean heading formatting | Approve both fixes |
| 9 | Category | Low | Quick Win | `Planning` only | Keep — correct assignment | Keep |

---

## Section C: Task Suggestions

---

## Task 1: Internal Links

### Existing Link Audit

| # | Anchor Text | Target URL | Status |
|---|-------------|------------|--------|
| 1 | Airbnb's pitch deck | `/newsletter/i-reviewed-airbnbs-original-pitch-deck` | Good |
| 2 | (space) strategic business plan | `/blog/strategic-business-planning` | Needs Fix — leading space before "strategic" in anchor text; minor cleanup |
| 3 | market analysis section of your business plan | `/blog/market-analysis-in-business-plan` | Good |
| 4 | business plan for investors | `/blog/business-plan-for-investors` | Good |
| 5 | Upmetrics (×2) | `/` | Good — branded homepage mentions |
| 6 | Marketresearch.com | `http://marketresearch.com` | Needs Fix — HTTP link (not HTTPS); update to `https://marketresearch.com` |
| 7 | How to Conduct Industry Analysis | `/blog/industry-analysis-in-business-plan` | Good (read-link div) |

**Current count:** 4 meaningful body links (plus 2 branded homepage + 1 read-link div). Existing balance is ~100% informational — adding 1 high-conversion sales link is recommended.

---

### New Link Suggestions

> **#1 — Recommended** — `industry reports` → `/blog/free-and-paid-sources-of-industry-reports`
>
> **Section:** "1. Define and calculate TAM" → Top-down approach
>
> **In context:** "The top-down approach starts with broad market research. Here, you dig into **industry reports** and secondary published research to get a fair overview of your total market size. You then take the total market size and narrow it down to your specific segment."

---

> **#2 — Recommended** — `revenue projections` → `/features/financial-forecasting`
>
> **Section:** "5. Misaligning SOM with revenue projections" (in Market Sizing Mistakes)
>
> **In context:** "Investors would seek alignment between your claims in the market opportunity section and your financial projections. That is, if you claim to achieve 10 million SOM in the first year, it should reflect in your **revenue projections** as well."
>
> **Note:** High-conversion target — 329 conversions in 90 days from this feature page.

---

> **#3 — Optional** — `competitor's data` → `/blog/industry-benchmarking`
>
> **Section:** "1. Define and calculate TAM" → Bottom-up approach
>
> **In context:** "In case yours is a startup with no revenue data, you can use a **competitor's data** as a benchmark. If not, you can build fair assumptions based on preliminary surveys and market research."
>
> **Note:** Anchor contains a curly apostrophe in the source HTML. During execution, match against the decoded text "competitor's data" — the script handles this via BeautifulSoup.

---

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How To Use ChatGPT for Market Research | "market research" anchor is in same paragraph as "industry reports" — too close (100-word spacing rule) |
| Pitch Deck Feature (`/features/pitch-deck`) | Best anchor "pitch deck" appears in same sentence as already-linked "business plan for investors" |
| What Investors Want to See in Pitch Decks | No clean anchor text found in content without rewriting |
| Industry Analysis vs Market Analysis | Claimed for Task 4 (Related Content) |
| Startup Financial Planning blog | Claimed for Task 4 (Related Content) |

</details>

---

## Task 2: CTA Placements

### Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|---|----------|-----------|--------|-------|
| 1 | Type 1 (Download Link) | After intro, before "Definitions" H2 | Good | Market Analysis Kit — relevant, lightweight, well-placed |
| 2 | `.read-link` (Read More) | After SOM definition | Good | Industry Analysis link — contextually appropriate |
| 3 | `.upm-blog-tip` | After "Present clearly in your plan" | **Update** | Generic copy; no specific CTA action; link goes to homepage instead of a specific tool |
| 4 | `[elementor-template id="44970"]` | End of post | Good | Standard Elementor CTA ✓ |

---

### New CTA Suggestions

> **#1 — Recommended** — Replace `.upm-blog-tip` with Type 12 (Yellow Tip Alert)
>
> **Placed after:** "Keep it neat and simple. And that's pretty much how you give investors the key market size insights without overwhelming them."
>
> **Replaces:** The existing `.upm-blog-tip` block (which says "Business planning tools like Upmetrics offer built-in templates…")
>
> **CTA Preview:**
> ```
> ┌────────────────────────────────────────────────────────────────┐
> │ 💡 Tip: Got your TAM, SAM, and SOM ready? Plug them into      │
> │ a complete business plan using our free AI business plan       │
> │ generator — and get an investor-ready document in minutes. →   │
> └────────────────────────────────────────────────────────────────┘
> ```
>
> **HTML:**
> ```html
> <div class="yellow-alert"><strong>Tip: </strong>Got your TAM, SAM, and SOM numbers ready? Plug them into a complete business plan using our <a href="https://upmetrics.co/ai-tools/free-ai-business-plan-generator">free AI business plan generator</a> and build an investor-ready document in minutes.</div>
> ```
>
> **Angle used:** Ease / specific next step (connects directly to "present clearly in your plan" section above)

---

> **#2 — Recommended** — Type 8 (Investor-Ready Plan, Image Right) | After market sizing mistakes intro
>
> **Placed after:** "So, let me save you from that awkward moment by walking you through the most common traps:"
>
> **Before:** H3 "1. Inflating TAM & ignoring SAM/SOM"
>
> **CTA Preview:**
> ```
> ┌────────────────────────────────────────────────────────────────┐
> │  7 in 10 pitches get the market sizing wrong                   │
> │                                                                │
> │  Build yours into a plan investors can't poke holes in         │
> │                                                                │
> │  [ Try Upmetrics Free ]                     🖼 AI Business Plan│
> └────────────────────────────────────────────────────────────────┘
> ```
>
> **HTML:**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> 7 in 10 pitches get the market sizing wrong
> <p class="title h2">Build yours into a plan investors can't poke holes in</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Try Upmetrics Free</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-business-plan.svg" alt="AI Business Plan" width="200" height="170" /></div>
> </div>
> ```
>
> **Angle used:** Social proof / fear of mistake (connects directly to "mistakes that kill your funding chances" section)

---

## Task 3: Downloadable Resource CTA

**Recommendation:** Set the Resource CTA (ACF hero field) to the Market Analysis Kit.

This is the most topically aligned downloadable resource available — the post's entire premise is helping founders size their market, and the Market Analysis Kit provides templates to do exactly that. It's already referenced as an inline download CTA in the content body (the download CTA in Task 2 audit), but the ACF hero CTA is a separate UI placement.

| Field | Value |
|-------|-------|
| **Resource URL** | `https://upmetrics.co/download/market-analysis-kit` |
| **`heading`** | `Market Analysis Kit` |
| **`resource_link_text`** | `Download Now` |
| **Combined display** | "Download Now: Market Analysis Kit" (35 chars) ✓ |

---

## Task 4: Related Content

**Current state:** No related pages set.

**Suggested items (4):**

| # | Post ID | Custom Title | Raw Title |
|---|---------|-------------|-----------|
| 1 | 6040 | What Goes Into a Startup Financial Plan? | How to Prepare a Financial Plan for Startup Business (w/ example) |
| 2 | 91714 | Funding Rounds Every Founder Should Know | What are Funding Rounds? (Key Stages for Founders) |
| 3 | 96035 | What Investors Actually Want to See | What Investors Want to See in Pitch Decks That Get Funded |
| 4 | 96105 | Market vs. Industry Analysis, Explained | Industry Analysis vs Market Analysis: Key Differences |

**Rationale:** These 4 items form a natural "next step" cluster for a reader who just learned about market sizing — they naturally want to know about financial planning, investor expectations, pitch deck standards, and how market analysis fits in.

---

## Task 5: Meta Title & Description

**Current state:** SEO fields not customized — page defaults to post title as meta title.

**Performance context:** 16,728 impressions / 4 clicks = **0.024% CTR** — average position 49. The primary fix opportunity is the meta title, which must be compelling enough to earn clicks once the page improves its ranking.

### Meta Title

| | Text | Chars |
|--|------|:-----:|
| **Current** | TAM SAM SOM: The Complete Market Sizing Guide for Startups | 58 |
| **Suggested** | TAM SAM SOM Explained: Calculate Market Size for Startups | 58 |

*Differentiator:* "Explained" signals clarity (answers the definitional query); "Calculate" signals action (answers the how-to query) — covers both search intents of "tam sam som" and "calculate tam sam som."

### Meta Description

| | Text | Chars |
|--|------|:-----:|
| **Current** | This guide shows how you can calculate TAM, SAM, and SOM correctly... *(215 chars — truncated by Google)* | 215 |
| **Suggested** | TAM, SAM, and SOM explained step by step — learn how to calculate market size using top-down and bottom-up methods, with real startup examples. | 143 |

### Other SEO Fields

| Field | Suggestion |
|-------|------------|
| **Focus Keyphrase** | `tam sam som` |
| **Canonical URL** | `https://upmetrics.co/blog/tam-sam-som-market-size-metrics` (already set correctly per inspect_url) |
| **OG Title** | TAM SAM SOM Explained: Calculate Market Size for Startups |
| **OG Description** | Learn what TAM, SAM, and SOM mean, how to calculate them using top-down and bottom-up methods, and the common mistakes that kill funding chances. |

### SERP Preview

```
TAM SAM SOM Explained: Calculate Market Size for Startups
upmetrics.co › blog › tam-sam-som-market-size-metrics
TAM, SAM, and SOM explained step by step — learn how to calculate market
size using top-down and bottom-up methods, with real startup examples.
```

---

## Task 6: Image Alt Text

| # | Image File | Current Alt | Suggested Alt |
|---|-----------|-------------|---------------|
| 1 | `tam-sam-som-diagram.webp` | "tam sam som diagram" | "TAM SAM SOM funnel diagram showing market sizing layers" |
| 2 | `which-market-sizing-method-should-you-use.webp` | "which market sizing method should you use" | "comparison of top-down vs bottom-up market sizing approaches" |

**Note on Image #2:** This image is currently wrapped inside an `<h2>` tag with no text — a critical HTML bug. The alt text fix must happen alongside the H2 fix in Task 8 (both are part of the Group A content update).

---

## Task 7: URL Slug

**Current slug:** `tam-sam-som-market-size-metrics`

**Recommendation: Skip.** The slug is acceptable — it contains the core acronym and a relevant keyword. With 16,000+ impressions, the page has meaningful exposure history. Changing the slug at position 49 carries redirect risk with low upside. No change needed.

---

## Task 8: Heading Structure

**Issues found:**

> **Fix #1 — Critical** | Empty H2 wrapping Image #2
>
> **Current HTML:**
> ```html
> <h2><img class="wp-block-image..." src=".../which-market-sizing-method-should-you-use.webp" alt="which market sizing method should you use" width="772" height="696" /></h2>
> ```
>
> **Fix:** Remove the `<h2>` wrapper. The image should be a standalone block element between the comparison table and the "TAM, SAM, SOM examples" H2. This is both a structural bug (an H2 with no text is meaningless to search engines) and a Task 6 opportunity (update the alt text simultaneously).
>
> **Note:** This fix cannot use the standard `update_heading` change type — it requires a custom manual edit to remove the H2 wrapper and apply the new alt text in one pass. Flag this during execution as a special case.

---

> **Fix #2 — Minor** | `<b>T</b>` formatting artifact inside H2
>
> **Current:** `<h2><b>T</b>op down vs. bottom up: What is the right approach?</h2>`
>
> **Fixed:** `Top down vs. bottom up: What is the right approach?`
>
> **Type:** `update_heading` — find: `Top down vs. bottom up: What is the right approach?` (BeautifulSoup will parse decoded text), new: `Top down vs. bottom up: What is the right approach?`, tag: `h2`

---

**Heading structure is otherwise solid:** H1 → H2 → H3 → H4 hierarchy is consistent. Primary keyword ("TAM, SAM, and SOM") appears in 2 H2s and the featured snippet H2. No duplicate headings. No skipped levels.

**Minor inconsistency (no change needed):** Definition H3s use "1)" format while calculation H3s use "1." format — cosmetically inconsistent but not an SEO issue.

---

## Task 9: Category Assignment

**Current:** `Planning`

**Recommendation: Keep.** The content is a market sizing guide for business planning — "Planning" is the correct primary category. No changes needed.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve #1, #2. Skip #3. Fix existing: clean space from link #2; update HTTP link #6 to HTTPS.
Task 2 (CTAs): Approve #1 (replace blog tip). Approve #2 (investor-ready banner after mistakes intro).
Task 3 (Resource CTA): Approve Market Analysis Kit.
Task 4 (Related Content): Approve all 4 items.
Task 5 (Meta): Approve suggested title. Approve description. Set focus keyphrase to "tam sam som".
Task 6 (Alt Text): Approve both updates.
Task 7 (Slug): Skip.
Task 8 (Headings): Approve Fix #1 (remove H2 wrapper from image). Approve Fix #2 (remove bold artifact).
Task 9 (Category): Keep Planning.

Or simply: "Approve all except Task 7"
```
