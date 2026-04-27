# SEO On-Page Report — What Lenders & Investors Look for in a Business Plan

| Field | Value |
|-------|-------|
| URL | https://upmetrics.co/blog/what-lenders-look-for-in-business-plan |
| Post ID | 107358 |
| Post Type | post |
| Category | Funding |
| Word Count | 3,382 |
| Published | 2026-04-26 (1 day old) |
| Report Date | 2026-04-27 |
| GSC Date Range | 2026-03-30 to 2026-04-24 |
| GA4 Date Range | Last 30 days (Report A) / Last 90 days (Report E) |

---

## Section B: Page Health & Action Summary

### Page Health Score: 6 / 10

| Status | Count |
|--------|:--:|
| Critical | 2 |
| Needs Improvement | 2 |
| Good | 6 |

**Why the score is what it is:**
- **-2 Critical** — Existing internal link "non-SBA lending options" → `/blog/sba-loan-alternatives` points to a post in **DRAFT** status (post ID 105656). The URL likely 404s for visitors, leaking link equity and reader trust.
- **-2 Critical** — Image #2 (`debt-service-coverage-ratio.png`) has corrupted alt text containing raw HTML markup (`<a href=...>Source</a>`) instead of a real description. Accessibility failure + image search SEO failure.

**What's working well:**
- Indexed and crawled (last crawl 2026-04-26, mobile-first). Breadcrumbs schema PASS.
- Strong external sourcing (US Census, BLS, IBISWorld, SBA, Federal Reserve, CNBC, Nasdaq).
- Healthy internal-link density (8 contextual + 1 homepage + 1 end CTA).
- Heading hierarchy is clean (10 well-named H2s, no skipped levels).
- 3 editorial Yellow Tip blocks already supporting reader engagement.
- Blog Post End CTA correctly present (canonical copy intact).

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|--------------|---------------|
| 1 | Internal Links | High | Medium | 1 broken (draft target), 8 good. No links yet to top financial-cluster pages. | Fix broken `sba-loan-alternatives` link (publish target post or replace with `/blog/what-is-an-sba-loan`). Add 5 contextual links to high-relevance financial-cluster pages. | None | Approve all |
| 2 | CTA Placements | Medium | Medium | 0 promotional CTAs in body (only End CTA + 3 editorial tips). 3,382-word post, target 3-4 CTAs. | Insert 3 CTAs spaced through the article (Yellow Tip, Financial Dashboards banner, Investor-Ready banner). | None | Approve all |
| 3 | Resource CTA | High | Quick Win | Not set | Set Resource CTA to **Startup Fundraising Checklist** (`/download/startup-fundraising-checklist`). | None | Approve |
| 4 | Related Content | Medium | Quick Win | Not set | Set 4 contextually titled related items (loan checklist, debt vs equity, what investors want, common projection mistakes). | None | Approve |
| 5 | Meta Title & Description | Low | Quick Win | Cannot verify Yoast fields via API. Page is 1 day old — no GSC data to validate CTR. | Set polished title/description as starting point; re-audit in 30 days when GSC data lands. | Verify Yoast first | Approve as starting point |
| 6 | Image Alt Text | High | Quick Win | 1 corrupted alt (HTML markup in alt attribute). 1 good. 1 decorative. | Rewrite the corrupted alt with a clean data-describing alt. | None | Approve |
| 7 | URL Slug | Low | High | `what-lenders-look-for-in-business-plan` — 7 words, slightly long but contains primary keyword. | Skip — slug is acceptable; risky to change a freshly-indexed page. | — | Skip |
| 8 | Heading Structure | Low | Medium | 10 well-named H2s, no H3 substructure. No issues. | Skip — structure is solid. | — | Skip |
| 9 | Categories | Low | Quick Win | Funding | Skip — correct category. | — | Skip |
| 10 | Incoming Internal Links | Medium | None (manual) | New page, no inbound internal links yet. | 7 source pages where SEO team should manually add a link to this article. | Manual review | Noted — manual implementation |

---

## Section C: Task-by-Task Suggestions

### Task 1 — Internal Linking

#### Part A — Existing Internal Link Audit (9 links)

| # | Anchor Text | Target URL | Status | Notes |
|:--:|-------------|-----------|--------|-------|
| 1 | market research for your plan | `/blog/types-of-market-research` | Good | Natural placement, relevant target |
| 2 | common reasons SBA loans get denied | `/blog/sba-loan-denied` | Good | Highly relevant to DSCR section |
| 3 | how investors really read your projections | `/newsletter/investors-fund-the-worst-case-not-the-best` | Good | Excellent contextual fit in Forward Projections |
| 4 | major equipment and asset purchases | `/blog/purchase-planning-for-small-businesses` | Good | Natural anchor in Collateral section |
| 5 | buy an existing business | `/blog/sba-loan-to-buy-business` | Good | Direct topical match |
| 6 | non-SBA lending options | `/blog/sba-loan-alternatives` | **Should fix** | **Target post is in DRAFT status (post ID 105656). URL likely 404s. Either publish the draft target OR replace anchor URL with `/blog/what-is-an-sba-loan` (post ID 87588) until the alternatives post is live.** |
| 7 | free SBDC business plan review | `/blog/small-business-development-centers-sbdc` | Good | Strong match — SBDC review is exactly what the sentence promises |
| 8 | Upmetrics | `/` | Good | Branded mention in conclusion — natural |
| 9 | Get Started Now! | `/cta/help` | Good | Canonical Blog Post End CTA |

**Current count:** 9 internal links | **Balance:** 100% Informational (Branded homepage + End CTA serve the sales role)

#### Part B — New Internal Link Suggestions (Recommended: 5)

> **#1 (Recommended)** — `weak cash flow` → `/blog/cash-flow-problems`
>
> **Section:** Revenue model: how the business actually makes money
>
> **In context:** "This is also where strong sales can still create **weak cash flow**. If collections lag or receivables build up, growth on paper turns into a cash strain in practice. If your model has delayed payments built in, you have to show how that gap gets managed."

---

> **#2 (Recommended)** — `financial projections` → `/blog/financial-projections-business-plan`
>
> **Section:** Forward projections: with and without funding
>
> **Original:** "Usually, founders write **projections** as a prediction. In my view, a lender reads them as an argument..."
>
> **Modified:** "Usually, founders write **financial projections** as a prediction. In my view, a lender reads them as an argument..."
>
> **Note:** Minor text adjust — expanded "projections" to "financial projections" for a stronger anchor and a high-conversion target page (390 sessions/30d, 0.79 engagement, 41 conversions/90d). Meaning preserved.

---

> **#3 (Recommended)** — `SBA and conventional lenders` → `/blog/best-sba-lenders`
>
> **Section:** Historical financials and debt service coverage
>
> **In context:** "That's the regulatory minimum, and it's lower than most founders assume. But in practice, most **SBA and conventional lenders** underwrite to 1.25x as internal policy, and some push for 1.5x if your industry is on the riskier side."

---

> **#4 (Recommended)** — `$300K SBA loan` → `/blog/sba-loan-requirements`
>
> **Section:** Historical financials and debt service coverage
>
> **In context:** "A small business applying for a **$300K SBA loan** has no equivalent buffer. That's why lenders underwrite to cash coverage in the first place, not to revenue, and it's what makes the DSCR ratio load-bearing for a decision the rest of the plan can't override."

---

> **#5 (Recommended)** — `industry benchmarks` → `/blog/industry-benchmarking`
>
> **Section:** Forward projections: with and without funding
>
> **In context:** "If you're pre-revenue and building these from scratch, both audiences accept that everything is estimated, but they lean harder on assumptions than on outputs. Cite the source for every key input, **industry benchmarks**, comparable businesses, signed letters of intent, and anything that makes the number credible."

---

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| What Investors Want to See in Pitch Decks | High-conv page, but no natural anchor — content discusses investors but never mentions "pitch deck" |
| Angel Investor Funding | No clean anchor — page mentions "investor" generically, never "angel" |
| Funding Rounds | Article is lender-focused; funding-rounds is investor/equity-focused — relevance medium, no strong anchor |
| Debt vs Equity Financing | Strong topical match for the "lender vs investor" framing, but no clean 2+ word anchor in body — better as Related Content (Task 4) |
| Common Financial Projections Mistakes | No verbatim anchor — "common mistakes" not in content. Better used as Related Content (Task 4) |

</details>

---

### Task 2 — CTA Placements

#### Part A — Existing CTA Audit (4 elements)

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Yellow Tip block (`upm-blog-tip`) | End of "Business history and operating track record" | Good | Editorial tip — keep as is |
| 2 | Yellow Tip block (`upm-blog-tip`) | End of "Revenue model" section | Good | Editorial tip — keep as is |
| 3 | Yellow Tip block (`upm-blog-tip`) | End of "Collateral and available assets" | Good | Editorial tip — keep as is |
| 4 | Blog Post End CTA (`delivery-block`) | Very end of post | Good | Canonical copy intact (`The Quickest Way to turn a Business Idea into a Business Plan` / `Get Started Now!`) |

**Current promotional CTA count:** 0 mid-content + 1 End CTA. For 3,382 words, target is 3-4 CTAs total. Recommending 3 new mid-content CTAs.

#### Part B — New CTA Suggestions (Recommended: 3)

> **#1 (Recommended)** — Yellow Tip Alert (Type 12) | After "The management team behind the plan" section
>
> **Placed after:** "If you're a solo founder, the same exercise still works. The receipts just have to come from somewhere else, prior roles, smaller ventures, or projects where you owned the outcome end-to-end."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │ 💡 Tip: Mapping team capabilities to plan needs takes   │
> │ longer than founders expect. Use our AI Business Plan   │
> │ Generator → to auto-generate a structured team section. │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Angle:** Ease | **URL:** `/ai-tools/free-ai-business-plan-generator`

---

> **#2 (Recommended)** — Flex Banner: Financial Dashboards (Type 9) | After "Historical financials and debt service coverage" section
>
> **Placed after:** "A small business applying for a $300K SBA loan has no equivalent buffer. That's why lenders underwrite to cash coverage in the first place, not to revenue, and it's what makes the DSCR ratio load-bearing for a decision the rest of the plan can't override."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  Tired of digging through spreadsheets to calculate DSCR?│
> │                                                         │
> │  Auto-build the financials a lender actually wants      │
> │                                                         │
> │  [ Try Upmetrics ]                                      │
> │                                       🖼 Financial Dash │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Angle:** Outcome (lender approval) | **URL:** `/signup`

---

> **#3 (Recommended)** — Flex Banner: Investor-Ready Plan (Type 8) | After "The purpose of the loan (or investment)" section
>
> **Placed after:** "And if your use doesn't map cleanly onto SBA categories, it's worth looking at non-SBA lending options where the purpose-of-funds standards are more flexible."
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  Don't lose months building a plan investors won't read │
> │                                                         │
> │  Finish a funding-ready business plan this weekend      │
> │                                                         │
> │  [ Start Free Draft ]                                   │
> │                                       🖼 AI Business Plan│
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Angle:** Speed | **URL:** `/signup`

---

**Spacing check:** CTA #1 → CTA #2 ≈ ~1,100 words apart. CTA #2 → CTA #3 ≈ ~750 words apart. CTA #3 → End CTA ≈ ~700 words apart. All well above the 400-500 word minimum, all on different screens. Three different formats (Yellow Tip / Financial Dashboards / Investor-Ready), three different angles (Ease / Outcome / Speed). No headline overlap.

---

### Task 3 — Downloadable Resource CTA

| Field | Value |
|-------|-------|
| **Recommended Resource** | Startup Fundraising Checklist |
| **Resource URL** | `/download/startup-fundraising-checklist` |
| **Resource Post ID** | 7345 |
| **Heading** | `Startup Fundraising Checklist` |
| **Resource Link Text** | `Download Now` |
| **Combined Display** | `Download Now: Startup Fundraising Checklist` (43 chars ✓ under 55) |

**Why this fits:** The article is the conceptual companion to a fundraising checklist — readers leave knowing *what* lenders/investors want and the checklist gives them a structured tool to gather it. Stronger thematic match than a generic plan template, and the download is a checklist (active tool) rather than a passive PDF.

**Alternative (if the fundraising checklist isn't preferred):** Financial Statements Template (`/download/financial-statement`, post 7281) — relevant to the DSCR/historical financials section and a high-traffic download (180 sessions/30d).

---

### Task 4 — Related Content (4 items)

| # | Post | URL | Post ID | Custom Title (≤50 chars) | Why |
|:--:|------|-----|:--:|--------------------------|-----|
| 1 | What Do You Need for a Business Loan | `/blog/what-do-you-need-for-a-business-loan` | 81668 | Business Loan Checklist: What You Need | Direct companion topic — "what lenders look for" + "what you need" |
| 2 | Debt vs. Equity Financing | `/blog/debt-vs-equity-financing` | 87029 | Debt or Equity? How to Choose | Mirrors the lender-vs-investor distinction central to this article |
| 3 | What Investors Want to See in Pitch Decks | `/blog/what-investors-want-to-see-in-pitch-decks` | 96035 | What Investors Look For in Pitch Decks | Investor-side companion (high-conv: 44, high-engagement: 0.86) |
| 4 | 9 Most Common Financial Projections Mistakes | `/blog/common-financial-projections-mistakes` | 71260 | 9 Projection Mistakes to Avoid | Critical financials angle (high-conv: 43, high-engagement: 0.83) |

All four titles are under 50 chars, contextual to this article's themes, and avoid raw post-title regurgitation. None duplicate Task 1 or Task 3 URLs.

---

### Task 5 — Meta Title & Description

**Data caveat:** Page is 1 day old — zero GSC impressions, no top queries, no CTR data. The Yoast `seo` fields were not returned in the `get-post` response, so we cannot confirm what's currently set. Treat this as a starting-point polish to be re-audited in 30 days once GSC data accumulates.

| Field | Current (likely default) | Chars | Suggested | Chars | Notes |
|-------|--------------------------|:--:|-----------|:--:|-------|
| Meta Title | What Lenders & Investors Look for in a Business Plan | 52 | What Lenders Want to See in Your Business Plan [2026] | 53 | Adds year-tag hook; slight angle shift from H1 ("Look for" → "Want to See") |
| Meta Description | Learn what lenders and investors look for in a business plan. Covers financials, DSCR, market demand, and funding use to improve approval chances. | 148 | Lenders read business plans for specific answers, not the way you wrote it. Here's what they actually scan for in a plan, section by section. | 142 | More distinctive opening; primary keyword in first 13 chars; soft CTA via specificity |
| Focus Keyphrase | (unknown) | — | Recommend keeping/setting current title's keyphrase. Re-audit once GSC data lands to align with the actual top query. | — | No GSC data to validate runway |
| Canonical URL | `/blog/what-lenders-look-for-in-business-plan` | — | (unchanged — verified by GSC inspect) | — | OK |
| OG Title | (likely unset) | — | Match suggested meta title | — | If currently unset, set both |
| OG Description | (likely unset) | — | Match suggested meta description | — | If currently unset, set both |

**SERP Preview (with suggestion):**

```
─────────────────────────────────────────────────────
upmetrics.co › blog › what-lenders-look-for-in-business-plan
What Lenders Want to See in Your Business Plan [2026]
Lenders read business plans for specific answers, not the
way you wrote it. Here's what they actually scan for in a
plan, section by section.
─────────────────────────────────────────────────────
```

**Differentiator note:** Most competing SERP titles for "what lenders look for in a business plan" use "What Lenders Look For" verbatim — adding "[2026]" + the angle shift to "Want to See" gives this title a distinctive frame.

---

### Task 6 — Image Alt Text Audit

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty/Wrong | 1 | Rewrite alt |
| Needs Improvement | 0 | — |
| Good | 1 | No action |
| Decorative — Correct | 1 | No action |
| **Total images** | **3** | — |

**Detailed audit (action rows only):**

| # | src (filename) | Status | Current Alt | Suggested Alt | Chars | Notes |
|:--:|----------------|--------|-------------|---------------|:--:|-------|
| 1 | `what-lenders-look-for-in-business-plan-debt-service-coverage-ratio.png` | Critical — Wrong | `<a href="https://www.nasdaq.com/articles/...">Source</a>` (HTML markup as alt) | Nike quarterly inventory chart showing 44% year-over-year jump to $9.7 billion in 2022 | 87 | Replaces corrupted alt with descriptive data-narrative alt |

**Good (no action):**
- `what-lenders-look-for-in-business-plan-revenue-model-cash-flow.png` — alt: "Revenue model showing how cash collection timing impacts a business plan" (74 chars) ✓

**Decorative (no action):**
- `crossline.png` — small UI accent inside the End CTA button, alt: "crossline" — leave as is.

---

### Task 7 — URL Slug

**Skip.** Current slug `what-lenders-look-for-in-business-plan` (38 chars, 7 words) contains the primary keyword and is descriptive. Slightly above the 3-6 word target, but changing the slug on a page that's already been crawled (last crawl 2026-04-26) creates needless redirect risk for marginal gain.

---

### Task 8 — Heading Structure Audit

**Skip.** 10 H2s, no skipped levels, no duplicates, all under 70 characters, all descriptive. No H1 in content (correct — title H1 is rendered separately by the theme). Primary keyword "business plan" appears in H2 #6 ("Forward projections: with and without funding") only via the broader topic — could strengthen, but no urgent fix.

---

### Task 9 — Category Assignment

**Skip.** Current category: **Funding** — correct. The article covers SBA loans, investor underwriting, and funding mechanics. Single category is fine for a blog post (rule allows up to 2; second is not needed here).

---

### Task 10 — Incoming Internal Link Suggestions

**Manual implementation by SEO team.** Pages on the site that should link TO this new article. Every source URL below is verified in WordPress (real `post_id`).

**Note:** Reciprocal links excluded — pages already linked from this article in Task 1 (or proposed as new links) are not suggested as source pages here.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor (search term) | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|
| 1 | What Do You Need for a Business Loan | `/blog/what-do-you-need-for-a-business-loan` | 81668 | post | Direct companion topic — readers learning what to gather should also see what lenders scan for | what lenders look for | High |
| 2 | What is an SBA Loan and How to Get One Fast | `/blog/what-is-an-sba-loan` | 87588 | post | Foundational SBA primer — should reference how lenders actually read plans | how lenders evaluate plans | High |
| 3 | How to Write a Business Plan: 10 Easy Steps + Examples | `/blog/how-to-write-a-business-plan-complete-guide` | 6056 | post | Master guide — should link to a section explaining what lenders actually scan for | what lenders look for | High |
| 4 | How to Get Funding for a Business | `/blog/how-to-get-funding-for-a-business` | 82946 | post | Broader funding overview — natural place to link to the lender-readiness companion | what lenders want to see | Medium |
| 5 | Debt vs. Equity Financing | `/blog/debt-vs-equity-financing` | 87029 | post | Article frames lender vs investor differently — links naturally into the same distinction | what lenders look for | Medium |
| 6 | What are Funding Rounds (Key Stages for Founders) | `/blog/funding-rounds` | 91714 | post | Funding-stages article should reference the lender-perspective companion | what lenders want | Medium |
| 7 | How to Get Funding from Angel Investors | `/blog/angel-investor-funding` | 107174 | post | Angel-investor article should link to the broader lender/investor evaluation framework | how investors read plans | Medium |

> Every source URL above is verified in WordPress (real `post_id`). Suggested anchor text is a starting term for the SEO team to search within the source page — the actual anchor depends on what text exists in that page's content.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve all 5 new (#1-#5). For existing #6, replace URL with /blog/what-is-an-sba-loan (post 87588) until sba-loan-alternatives is published. Keep existing #1-#5, #7-#9 as is.
Task 2 (CTAs): Approve all 3 new (#1 Yellow Tip after Management Team, #2 Financial Dashboards after Historical Financials, #3 Investor-Ready after Purpose of Loan).
Task 3 (Resource CTA): Approve startup-fundraising-checklist.
Task 4 (Related Content): Approve all 4 items.
Task 5 (Meta Title/Desc): Approve suggested title and description as starting point. Re-audit in 30 days when GSC data accumulates.
Task 6 (Image Alt Text): Approve fix for image #1 (Nike inventory chart).
Task 7 (URL Slug): Skip — page just indexed.
Task 8 (Headings): Skip — structure is solid.
Task 9 (Categories): Skip — Funding is correct.
Task 10 (Incoming Links): Noted — SEO team will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task 5"**
