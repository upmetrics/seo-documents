# SEO On-Page Audit — Accounts Receivable

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/accounts-receivable |
| **Post ID** | 107327 |
| **Post Type** | post |
| **Current Category** | Funding |
| **Published** | 2026-04-25 |
| **Modified** | 2026-04-25 |
| **Word Count** | 3,205 |
| **Brand** | Upmetrics |
| **Report Date** | 2026-04-27 |
| **GSC Data Range** | 2026-03-30 to 2026-04-24 |
| **GA4 Data Range** | last 30 days (engagement); last 90 days (conversions) |
| **Index Status** | Indexed (last crawled 2026-04-26); Breadcrumbs + FAQ schema detected |
| **GSC Performance** | No query data yet — page is too new (2 days post-publish) |

---

## Page Health Score: 7.0 / 10

| Status | Count |
|--------|:--:|
| Critical | 1 |
| Needs Improvement | 4 |
| Good | 5 |

**Deductions:**
- −2.0 — Yoast SEO meta fields appear unset (no `seo` object in `get-post` response). Page is currently relying on the auto-generated title/description.
- −1.0 — Wrong primary category (`Funding` should be `Forecasting` — page is about cash flow management, not raising capital).
- −0.5 — 3 image alt texts are too vague (under 60 chars, lack data specifics).
- −0.5 — Sales/Features link ratio is slightly hot (3 sales : 2 informational on a `post` type — should be ~2:1 informational).

The page itself is in strong shape: 3,205 words, well-structured (11 H2s, 10 H3s), all images have alt text, FAQ + Breadcrumb schema, the Blog Post End CTA is present, and the slug is clean. The fixes below are calibration, not rescue.

---

## Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|:--:|------|:------:|:------:|---------------|------------|---------------|
| 1 | Internal Links | Medium | Medium | 5 main-domain content links (3 sales / 2 informational) | Add 3 informational links to balance ratio + add depth on financial-statements topics | Approve all 3 |
| 2 | CTAs | Medium | Medium | 1 CTA (Blog Post End) | Add 1 banner CTA after the financial statements section + 1 optional flex banner | Approve #1, optional #2 |
| 3 | Resource CTA | High | Quick Win | None set | Set Financial Statements Template as Resource CTA | Approve |
| 4 | Related Content | High | Quick Win | None set | Add 4 related items (forecasting + financial projections + working capital) | Approve all 4 |
| 5 | Meta Title/Desc | High | Quick Win | Yoast fields appear unset (auto-fallback to H1) | Set explicit meta title + description + focus keyphrase | Approve |
| 6 | Image Alt Text | Low | Quick Win | All 6 images have alt; 3 are vague | Rewrite 3 alts with data specifics | Approve all 3 |
| 7 | URL Slug | — | — | `accounts-receivable` (clean, 2 words, primary kw) | No change needed | Skip |
| 8 | Heading Structure | — | — | 11 H2s, 10 H3s, hierarchy clean | No change needed | Skip |
| 9 | Categories | High | Quick Win | `Funding` (wrong fit) | Change primary to `Forecasting` | Approve |
| 10 | Incoming Links | Medium | Manual | n/a — suggestion only | 6 source pages flagged for SEO team to manually link FROM | Note |

---

## TASK 1 — Internal Linking

### Existing Internal Link Audit

Main-domain content links only (help center subdomain links and the end-CTA button are excluded from this audit).

| # | Anchor Text | Target URL | Type | Status |
|:--:|-------------|-----------|------|--------|
| 1 | cash flow forecast | /features/cash-flow-forecasting | Sales/Features | Good |
| 2 | cash flow calculator | /ai-tools/cash-flow-calculator | Sales/Features | Good |
| 3 | Upmetrics' cash flow forecasting feature | /features/financial-forecasting | Sales/Features | Good |
| 4 | financial section of your business plan | /blog/write-financial-section-startup-business-plan | Informational | Good |
| 5 | financial forecasting | /blog/what-is-financial-forecasting | Informational | Good |
| 6 | Upmetrics | / | Branded homepage | Good |

**Notes:**
- Link count: 5 content + 1 branded homepage. Plus 3 help-center links to `help.upmetrics.co` (left as-is — they're product help docs, not blog content).
- Current ratio: 3 Sales/Features : 2 Informational. Slightly Sales-heavy for a `post` type (target ~2:1 Informational). New suggestions below restore the balance.
- Anchor "Upmetrics' cash flow forecasting feature" links to `/features/financial-forecasting` (broader feature page) while a more specific `/features/cash-flow-forecasting` is also linked. Acceptable — both target distinct product areas.

---

### New Internal Link Suggestions

3 recommended links — all informational, all wrap existing text without modification, all in different sections.

> **#1** — `balance sheet` → `/blog/balance-sheet-for-business-plan`
>
> **Section:** What is accounts receivable?
>
> **In context:** "Your **balance sheet** lists AR as a current asset because you expect to collect it within 30 to 90 days. You don't have the cash yet, but your business owns that claim, and that makes it an asset."

---

> **#2** — `cash flow statement` → `/blog/create-cash-flow-statement`
>
> **Section:** How AR shows up on your financial statements
>
> **In context:** "The **cash flow statement** is where the difference becomes clear. If your accounts receivable increase during a period, it reduces your operating cash flow."

---

> **#3** — `cash flow gaps` → `/blog/cash-flow-problems`
>
> **Section:** How to forecast accounts receivable
>
> **In context:** "This is important because it's where most **cash flow gaps** come from. If you're new to financial forecasting, understanding how AR fits into your projections is one of the most practical places to start"

---

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Forecast Cash Flow in 7 Simple Steps | Closest anchor "cash flow projection" lives within 50 words of the new "cash flow gaps" link — drops below 100-word spacing rule |
| How to Calculate Working Capital | Phrase "working capital" does not appear in the source content |
| 9 Most Common Financial Projections Mistakes | No clean anchor; the only matching phrase is already linked to a different target |
| What is Cash Flow Forecasting | "Cash flow forecasting" already linked to the feature page — skipping to avoid double-linking the same concept |
| How to Create Financial Projections for a Business Plan | Reserved for Task 4 (Related Content) — higher value as a sidebar link than a body link |

</details>

---

## TASK 2 — CTA Placements

### Existing CTA Audit

| # | CTA | Placement | Status | Notes |
|:--:|-----|-----------|--------|-------|
| 1 | Blog Post End CTA (canonical `delivery-block`) | Last block of content | Good | Correct headline, button, URL, image — verbatim canonical block |
| — | `upm-blog-tip` (3-touch follow-up) | After "3) Follow up with a system" | Not a CTA | Editorial tip box, no link/button — leave as-is |
| — | `upm-blog-tip` (DSO forecasting tip) | Before "Manage and track in Upmetrics" | Not a CTA | Editorial tip box, no link/button — leave as-is |

**Notes:**
- Only 1 actual CTA (the canonical end CTA). For a 3,205-word post, target is 3-4 CTAs total. The 2 `upm-blog-tip` boxes are editorial callouts, not conversion CTAs — they don't count toward the budget.

---

### New CTA Suggestions

> **#1 (Recommended)** — Type 9: Flex Banner — Financial Dashboards | After "How AR shows up on your financial statements"
>
> **Placed after:** "I always recommend looking at all three together. Strong revenue with rising receivables and weak cash flow is a signal that collection, not sales, is the issue. That's a distinction that matters when you're putting together the financial section of your business plan."
>
> **Destination:** `/signup` (not yet linked anywhere on the page)
>
> **CTA Preview:**
> ```
> ┌──────────────────────────────────────────────────────────┐
> │  Don't let cluttered statements confuse investors         │
> │                                                           │
> │  See your AR and cash flow in one live dashboard          │
> │                                                           │
> │  [ Try Upmetrics ]                  🖼 Financial Dashboards│
> └──────────────────────────────────────────────────────────┘
> ```
>
> **Why this fits:** Section is about reading AR across all three financial statements. Type 9's "data clarity" theme directly addresses readers who feel overwhelmed by spreadsheet-based tracking.

---

> **#2 (Optional)** — Type 4: Flex Banner — Financial Forecasting (image right) | After "Accounts receivable vs. accounts payable"
>
> **Placed after:** "If I'm running a business, I'd focus less on managing one side and more on controlling both sides together. Collect as quickly as possible while using your payment terms without damaging relationships. That balance keeps your cash flow stable."
>
> **Destination:** `/pricing` (not yet linked anywhere on the page)
>
> **CTA Preview:**
> ```
> ┌──────────────────────────────────────────────────────────┐
> │  Spreadsheets are exhausting & time-consuming             │
> │                                                           │
> │  Build a cash flow forecast that ties AR to AP            │
> │                                                           │
> │  [ See Pricing ]                  🖼 Financial Forecasting│
> └──────────────────────────────────────────────────────────┘
> ```
>
> **Why this fits:** Section ends on the importance of managing AR + AP together — a forecasting tool that handles both sides is the natural next step.

**Spacing note:** New CTA #1 sits in section 6 of 11; the end CTA sits at the very end. ~1,100 words separate them — comfortable. If both #1 and #2 are added, ~700 words separate them — still acceptable. Both are well above the 400-500 word minimum.

---

## TASK 3 — Downloadable Resource CTA

| Field | Value |
|-------|-------|
| **Recommended Resource** | Financial Statements Template |
| **Resource URL** | https://upmetrics.co/download/financial-statement |
| **Post ID** | 7281 |
| **`heading` parameter** | `Financial Statements Template` (28 chars) |
| **`resource_link_text` parameter** | `Download Template` (17 chars) |
| **Combined display** | `Download Template: Financial Statements Template` (~48 chars — single line) |

**Why this fits:** The article spends an entire H2 explaining how AR appears on the balance sheet, income statement, and cash flow statement. A free Financial Statements Template download is the most contextually relevant resource on the site. Higher relevance than a generic Business Plan Template.

---

## TASK 4 — Related Content

Set the "Related Posts" repeater to these 4 items. Each `title` is a custom display title written for sidebar curiosity (not the raw post title).

| # | Display Title (chars) | Post ID | Real Title | URL |
|:--:|----------------------|:--:|------------|-----|
| 1 | Project Financial Numbers Like a Pro (36) | 6216 | How to Create Financial Projections for a Business Plan | /blog/financial-projections-business-plan |
| 2 | Cash Flow Forecasting, Step by Step (36) | 81537 | What is Cash Flow Forecasting: Type, Examples, and Best Practices | /blog/what-is-cash-flow-forecasting |
| 3 | Calculate Working Capital the Easy Way (38) | 6236 | How to Calculate Working Capital the Simple Way? | /blog/how-to-calculate-working-capital |
| 4 | 8 Practices That Improve Forecast Accuracy (43) | 81514 | 8 Cash Flow Forecasting Best Practices for Small Business Owners | /blog/cash-flow-forecasting-best-practice |

**Notes:**
- Item #1 is also a high-conversion page in GA4 Report E (41 conversions over 90 days). Linking the sidebar to it gives an extra signal lift.
- All 4 are NOT currently linked from the body, so no Task 1 / Task 4 conflict.
- This call REPLACES any existing related items.

---

## TASK 5 — Meta Title & Description

**Performance context:** Page is 2 days post-publish — no GSC query data yet. Suggestion is based on best practices, not on CTR underperformance. Treat this as setting a clean baseline before traffic builds, not as a fix.

**Why a rewrite is needed:** The `get-post` response did not return any `seo` object — Yoast meta title/description/focus keyphrase appear to be unset. The page is currently relying on auto-generated values (which typically just use the H1 verbatim).

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | (unset — falls back to H1) | — | Accounts Receivable Explained: Examples & Forecasting Tips | 58 | Differentiates from H1 ("…What It Is, Examples, and How It Works"). Keyword in first 19 chars. Hook: "Examples & Forecasting Tips" |
| Meta Description | (unset — falls back to excerpt) | — | Learn what accounts receivable is, how it works, and how to forecast it. Includes journal entry examples, DSO benchmarks, and AR vs AP comparison. | 147 | Verb-led, kw in first 33 chars, soft CTA via "Includes…" |
| Focus Keyphrase | (unset) | — | accounts receivable | — | Primary topic — appears in title, description, H1, slug, multiple H2s |
| Canonical | (auto: /blog/accounts-receivable) | — | (no change) | — | OK |
| OG Title | (unset) | — | (match meta title) | — | — |
| OG Description | (unset) | — | (match meta description) | — | — |

**SERP Preview:**

```
─────────────────────────────────────────────────────
upmetrics.co › blog › accounts-receivable
Accounts Receivable Explained: Examples & Forecasting Tips
Learn what accounts receivable is, how it works, and how to
forecast it. Includes journal entry examples, DSO benchmarks,
and AR vs AP comparison.
─────────────────────────────────────────────────────
```

**Differentiator note:** Most competing AR pages (Investopedia, NetSuite, HighRadius) lead with definitions only. The "& Forecasting Tips" tail signals practical/actionable content, which differentiates this page on the SERP.

---

## TASK 6 — Image Alt Text

### Image Audit Summary

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty (wrong) | 0 | — |
| Needs Improvement | 3 | Rewrite alt text |
| Good | 2 | No action |
| Decorative — Correct | 1 | No action (crossline accent in end CTA) |
| **Total images** | **6** | — |

### Detailed Audit

| # | src (filename) | Status | Current Alt | Suggested Alt | Chars | Notes |
|:--:|----------------|--------|-------------|---------------|:--:|-------|
| 1 | accounts-receivable-cycle-diagram.png | Good | Accounts receivable cycle steps from invoice to payment collection | (no change) | 66 | Already specific |
| 2 | accounts-receivable-balance-sheet.png | Needs Improvement | Accounts receivable on the balance sheet | Sample balance sheet showing accounts receivable listed under current assets with a $5,000 entry | 95 | Adds data specificity |
| 3 | accounts-receivable-income-statement.png | Needs Improvement | Accounts receivable on the income statement | Sample income statement showing service revenue of $5,000 recorded at the time of credit sale | 94 | Ties to the example walkthrough |
| 4 | accounts-receivable-forecasting-upmetrics.png | Good | Upmetrics accounts receivable forecasting inputs for sales on credit and days to get paid | (no change) | 89 | Strong, specific |
| 5 | accounts-receivable-tracking-upmetrics.png | Needs Improvement | Upmetrics accounts receivable tracking dashboard view | Upmetrics receivable and payable tracking report with monthly, quarterly, and yearly views | 91 | Names actual report views |
| 6 | crossline.png | Decorative | crossline | (no change) | 9 | Decorative accent inside canonical end CTA — do not modify |

---

## TASK 7 — URL Slug

| Field | Value |
|-------|-------|
| Current slug | `accounts-receivable` |
| Length | 19 chars / 2 words |
| Primary kw included | Yes |
| Format | Lowercase, hyphenated, no stop words |
| Decision | **Skip — no change needed** |

---

## TASK 8 — Heading Structure

| Check | Result |
|-------|--------|
| Exactly one H1 | Yes (auto-rendered post title) |
| H2/H3 hierarchy clean | Yes — 11 H2s, 10 H3s, no skipped levels |
| Primary keyword in H2s | Yes — appears in 7 of 11 H2s |
| All under 70 chars | Yes |
| No duplicate headings | Confirmed |
| Decision | **Skip — no change needed** |

---

## TASK 9 — Category Reassignment

| Field | Current | Suggested |
|-------|---------|-----------|
| Primary Category | Funding | **Forecasting** |
| Secondary Category | (none) | (leave none) |

**Why:** Per `categories.md`, the Forecasting category covers "financial projections, revenue forecasting, cash flow, income statements, balance sheets, budgeting, financial modeling." Accounts receivable is a cash flow / financial statements topic, not a fundraising topic. The article never discusses raising capital, investors, loans, or grants — it discusses how AR affects cash flow and how to forecast it.

---

## TASK 10 — Incoming Internal Link Suggestions

Source pages on the site that should link TO `/blog/accounts-receivable`. SEO team implements manually after verifying anchor placement on each source page. Every source URL below is verified in WordPress with a real `post_id`.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor (search term) | GA4 Sessions (30d) | Priority |
|:--:|------------|-----|:--:|-----------|--------------|-----------------|:--:|:--:|
| 1 | How to Create Financial Projections for a Business Plan | /blog/financial-projections-business-plan | 6216 | post | Projections require AR assumptions — natural fit; high-conversion source page (41 conv / 90d) | accounts receivable | 390 | High |
| 2 | What is Cash Flow Forecasting | /blog/what-is-cash-flow-forecasting | 81537 | post | Cash flow forecasts directly depend on AR collection timing | accounts receivable | n/a (older post, GSC top tier) | High |
| 3 | 8 Cash Flow Forecasting Best Practices | /blog/cash-flow-forecasting-best-practice | 81514 | post | Best practices include modeling collection lag (DSO) | DSO | n/a | High |
| 4 | 9 Most Common Financial Projections Mistakes | /blog/common-financial-projections-mistakes | 71260 | post | Mistakes often involve unrealistic AR / collection assumptions; high-engagement page | accounts receivable assumptions | 355 | Medium |
| 5 | How to Calculate Working Capital | /blog/how-to-calculate-working-capital | 6236 | post | AR is a primary working-capital component — formula reference | accounts receivable | n/a | Medium |
| 6 | Direct vs Indirect Cash Flow | /blog/direct-vs-indirect-cash-flow | 80468 | post | Indirect method explicitly adjusts for AR changes | accounts receivable | n/a | Medium |

**Notes:**
- Excluded reciprocal sources: `/blog/balance-sheet-for-business-plan`, `/blog/cash-flow-problems`, `/blog/create-cash-flow-statement`, `/blog/how-to-forecast-cash-flow`, `/blog/what-is-financial-forecasting`, `/blog/write-financial-section-startup-business-plan` — these are linked FROM the current page (Task 1 + existing). Reciprocal linking weakens both pages.
- Suggested anchor text is a starting term for the SEO team to search within each source page — actual anchor depends on what text already exists.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2, #3.
Task 2 (CTAs): Add #1 (Type 9 after financial statements section). Optional #2: Skip / Add.
Task 3 (Resource CTA): Approve Financial Statements Template.
Task 4 (Related Content): Approve items #1-#4.
Task 5 (Meta Title/Desc): Approve all suggested fields.
Task 6 (Image Alt Text): Approve rewrites for #2, #3, #5.
Task 7 (URL Slug): Skip — already clean.
Task 8 (Headings): Skip — already clean.
Task 9 (Categories): Approve change to Forecasting.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: `Approve all` / `Approve all except Task 7, Task 8`
