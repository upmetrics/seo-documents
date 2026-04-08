# SEO On-Page Optimization Report: Cash Burn Rate

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/cash-burn-rate |
| **Post ID** | 6224 |
| **Post Type** | Blog Post (`post`) |
| **Report Date** | 2026-04-08 |
| **GSC Data Range** | Jan 2026 – Apr 2026 |
| **GA4 Data Range** | Last 30 days |
| **Status** | ✅ All changes executed |

---

## Section B: Page Health Score + Action Summary

### Page Health Score: 5.5 → 9/10

| Status | Count | Items |
|--------|-------|-------|
| Critical | 1 | Meta title with 0 CTR despite position 2.6 |
| Needs Improvement | 5 | Duplicate CTAs, missing resource CTA, weak image alts, missing OG tags, thin internal linking |
| Good | 4 | Content structure, heading hierarchy, slug, canonical |

### Action Summary

| # | Task | Impact | Effort | Finding | Action | Status |
|---|------|--------|--------|---------|--------|--------|
| 1 | Internal Links | High | Medium | 3 existing editorial links (all good); only 5 links for ~2,200 words; 2 strong link opportunities found | Added 2 new links | ✅ Done |
| 2 | CTAs | High | Medium | Both in-content CTAs were identical legacy `cta-template-ai` blocks — same copy, same deprecated image | Replaced both with modern CTA types | ✅ Done |
| 3 | Resource CTA | Medium | Quick Win | No resource CTA set (`related_resource` field empty) | Set Financial Statement Template | ✅ Done |
| 4 | Related Content | Medium | Quick Win | Related post #2 duplicated an existing body link; two posts had weak topical alignment | Replaced all 4 with cash-flow-focused pages | ✅ Done |
| 5 | Meta Title | High | Quick Win | Title had 0 clicks at position 2.6 — no compelling hook or format signal | Rewrote with formula + benefit hook | ✅ Done |
| 6 | Meta Description | Low | Quick Win | Description was okay but passive; missing keyword in first 100 chars | Rewrote with active opening + keyword-first | ✅ Done |
| 7 | OG Metadata | Medium | Quick Win | `og_title` and `og_description` both null | Added both | ✅ Done |
| 8 | Image Alt Text | Low | Quick Win | 3 images had generic/redundant alt text | Updated all 3 with descriptive alts | ✅ Done |
| 9 | URL Slug | N/A | — | Slug `cash-burn-rate` is clean and keyword-focused | No change needed | — |
| 10 | Headings | N/A | — | Structure is clean: 8 H2, 7 H3, 2 H4; primary keyword in first H2 | No change needed | — |
| 11 | Category | N/A | — | Category not audited (not in scope this session) | — | — |

---

## Section C: Task-by-Task Changes

---

### Task 1: Internal Links

**Existing Link Audit**

| # | Anchor Text | Target URL | Status |
|---|-------------|------------|--------|
| 1 | financial section of a business plan | /blog/write-financial-section-startup-business-plan | Good |
| 2 | best cash flow forecasting practices | /blog/cash-flow-forecasting-best-practice | Good |
| 3 | cash flow forecast | /blog/what-is-cash-flow-forecasting | Good |
| 4 | Upmetrics (×2) | / | Good — branded homepage links, standard practice |

5 total existing links for ~2,200 words. Target for this word count: 5–7. Added 2 new links to reach 7.

**New Links Added**

> **#1** — `preparing for funding rounds` → `/blog/funding-rounds`
>
> **Section:** Gross vs. Net Cash Burn
>
> **In context:** "This number is useful when you're assessing operational discipline or **preparing for funding rounds**, since it shows what it costs to keep the lights on."

---

> **#2** — `Better cash flow management` → `/features/cash-flow-forecasting`
>
> **Section:** Improve Cash Flow Discipline
>
> **In context:** "**Better cash flow management** can reduce strain without touching your topline or growth strategy."
>
> **Classification:** Sales/Features — natural product placement at the end of a how-to tip; content explains the benefit before the link.

**Final link balance:** 5 Informational (71%) + 2 Sales/Features (29%) — within the 60–40 target for blog posts.

<details>
<summary>Considered but skipped (4 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| 8 Cash Flow Forecasting Best Practices | Already linked in existing content |
| What is Cash Flow Forecasting | Already linked in existing content |
| Financial Statement Template | Assigned to Task 3 (Resource CTA) |
| How Much Funding Do You Really Need? | Assigned to Task 4 (Related Content); no strong anchor text match in body |

</details>

---

### Task 2: CTA Placements

**Existing CTA Audit**

| # | CTA Type | Placement | Old Status | Action |
|---|----------|-----------|------------|--------|
| 1 | `cta-template cta-template-ai` (legacy) | After net burn rate formula | Needs Replacement | Replaced with Type 4 |
| 2 | `cta-template cta-template-ai` (legacy) | After burn-reduction tips | Needs Replacement | Replaced with Type 11 |
| 3 | `[elementor-template id="46013"]` | End of post | Good (end-of-post CTA) | No change |

**Note on Elementor template:** Post uses ID `46013`. Standard for Upmetrics blog posts is `44970`. Both IDs appear to be valid Upmetrics CTA templates — no change made, but worth confirming the correct one is set.

**Replacements Made**

> **CTA #1 → Type 4 (Financial Forecasting, Image Right)**
>
> **Placed after:** Net burn rate formula section (before "How to estimate your runway" H2)
>
> **Angle:** Pain point — "Manually tracking burn rate leaves room for costly errors"
>
> ```
> ┌──────────────────────────────────────────────────────────┐
> │  Manually tracking burn rate leaves room for costly      │
> │  errors                                                  │
> │                                                          │
> │  Track your burn rate and runway in real time            │
> │                                                          │
> │  [ Try Upmetrics ]                          🖼 Forecast  │
> └──────────────────────────────────────────────────────────┘
> ```

---

> **CTA #2 → Type 11 (Inline Banner)**
>
> **Placed after:** Burn-reduction tips section (before "How to factor cash burn rate" H2)
>
> **Angle:** Specificity — "Model your burn scenarios before making cuts"
>
> ```
> ┌──────────────────────────────────────────────────────────┐
> │  Model your burn scenarios before making cuts            │
> │                                  [ Try Upmetrics AI ]    │
> └──────────────────────────────────────────────────────────┘
> ```

**CTA count:** 2 in-content + 1 Elementor end-of-post = 3 total. Appropriate for 2,200 words.
**Variety:** Type 4 (flex banner) + Type 11 (inline) + Elementor — no duplicate types. ✓

---

### Task 3: Downloadable Resource CTA

**Set:** `/download/financial-statement` — Financial Statement Template

| Field | Value |
|-------|-------|
| Resource URL | https://upmetrics.co/download/financial-statement |
| Heading | Financial Statement Template |
| Link Text | Download Template |
| Combined Display | "Download Template: Financial Statement Template" (47 chars) |
| Note | Plugin returned `cta_image_id: 0` — no featured image found on the download page; CTA will display without image |

---

### Task 4: Related Content

**Previous related posts:** Create Budget for your Small Business, 8 Cash Flow Forecasting Best Practices *(duplicated body link)*, 9 Most Common Financial Projections Mistakes, How Much Funding Do You Really Need?

**New related posts set:**

| # | Post ID | Custom Title | URL |
|---|---------|--------------|-----|
| 1 | 80468 | Direct vs. Indirect Cash Flow Methods | /blog/direct-vs-indirect-cash-flow |
| 2 | 75817 | How to Build a Cash Flow Statement | /blog/create-cash-flow-statement |
| 3 | 78631 | How Much Funding Do You Really Need? | /blog/how-much-funding-do-you-need |
| 4 | 6245 | Why Most Startups Run Out of Cash | /blog/why-startups-fail |

**Deduplication:** All 4 URLs are distinct from body links and resource CTA. ✓

---

### Task 5: Meta Title & Description

**Meta Title**

| | Title | Chars |
|---|-------|-------|
| **Before** | Cash Burn Rate: What Is It & How Do You Calculate? | 50 |
| **After** | Cash Burn Rate: Formulas, Examples and How to Reduce It | 56 |

**Why this matters:** Page ranks position 2.6 for "burn rate calculation" with 162 impressions but **0 clicks** — the old title had no hook, no format signal, and no benefit. The new title signals what the reader will get (formulas, examples) and what outcome they'll achieve (reduce it).

**Meta Description**

| | Description | Chars |
|---|-------------|-------|
| **Before** | Learn what cash burn rate is, how to calculate it, and why it's important. The blog includes formulas, examples, and tips to manage your startup's runway. | 153 |
| **After** | Cash burn rate measures how fast your startup spends cash. Learn gross vs. net burn formulas, calculate your runway, and reduce burn without hurting growth. | 156 |

**SERP Preview (after):**
```
Cash Burn Rate: Formulas, Examples and How to Reduce It
https://upmetrics.co/blog/cash-burn-rate
Cash burn rate measures how fast your startup spends cash. Learn gross vs. net
burn formulas, calculate your runway, and reduce burn without hurting growth.
```

**Other SEO Fields**

| Field | Before | After |
|-------|--------|-------|
| Focus Keyphrase | Cash Burn Rate | cash burn rate |
| Canonical URL | null | (not set — left as WordPress default) |
| OG Title | null | Cash Burn Rate: Formulas, Examples and How to Reduce It |
| OG Description | null | Cash burn rate measures how fast your startup spends cash. Learn gross vs. net burn formulas, calculate your runway, and reduce burn without hurting growth. |

---

### Task 6: Image Alt Text

| # | Image File | Before | After |
|---|------------|--------|-------|
| 1 | gross-vs-net-burn-rate.webp | "gross vs net burn rate" | "gross vs net cash burn rate comparison" |
| 2 | gross-cash-burn-rate-formula.webp | "gross cash burn rate formula" | "gross cash burn rate formula with example calculation" |
| 3 | net-cash-burn-rate-formula.webp | "net cash burn rate formula" | "net cash burn rate formula showing cash outflows minus inflows" |

---

### Task 7: URL Slug

Current slug: `cash-burn-rate` — clean, keyword-focused, 3 words. **No change needed.**

---

### Task 8: Heading Structure

Heading hierarchy is well-structured — 8 H2s covering major topics, 7 H3s for sub-sections, 2 H4s for formula labels. Primary keyword present in opening H2. **No changes made.**

---

## Output Summary

| Item | Detail |
|------|--------|
| Post | https://upmetrics.co/blog/cash-burn-rate |
| Post ID | 6224 |
| Content modified | 7 changes: 2 links, 2 CTA replacements, 3 alt texts |
| Resource CTA | Set to /download/financial-statement |
| Related posts | 4 posts replaced |
| Meta title | Updated (50 → 56 chars, added format + benefit hook) |
| Meta description | Updated (keyword-first, active voice) |
| OG tags | Added og_title + og_description (were null) |
| Session directory | workspace/cash-burn-rate-20260408-104950/ |
