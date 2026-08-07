# On-Page SEO Report: LivePlan Review (Tools Page)

| Field | Value |
|---|---|
| URL | https://upmetrics.co/tools/liveplan |
| Post ID | 28119 |
| Post Type | `tools` (Tool Review — not a documented type in the standard workflow; see note below) |
| Report Date | 2026-08-07 |
| GSC Data Range | 2026-05-10 to 2026-08-05 (90 days) |
| GA4 Data Range | 30 / 90 days ending 2026-08-06 |

**A note on this page's post type:** `tools` is not one of the documented Upmetrics post types (`post`, `page`, `template`, `download`, `compare`, etc.). Checking the WordPress ability schemas directly confirmed: `set-resource-cta` only supports `post`/`download`/`pitch-deck`, and `set-related-pages` doesn't list `tools` either — both fields are absent from this post's ACF data. This post type also has no category/tag taxonomy assigned (empty on the live post) and isn't listed in the categories reference file. **Tasks 3, 4, and 9 are therefore N/A for this page** (see Section B). Separately, `get-post` doesn't return Yoast SEO fields for any post type on this site — Task 5 data below comes from the `page-architecture` ability instead.

---

## Section B: Page Health Score & Action Summary

### Page Health Score: 4 / 10

| Status | Count |
|---|:--:|
| Critical | 2 |
| Needs Improvement | 1 |
| Minor | 2 |
| Good / No Action | 5 |

**Deductions:**
- **-2 (Critical)** — Top query "liveplan" gets 4,904 impressions at position 6.9 but only 0.22% CTR (benchmark for that position is ~5%) — meta title/description are actively losing clicks. Description also contains the banned word "comprehensive."
- **-2 (Critical)** — 3 non-decorative logo images have missing/empty alt text (capped from -3).
- **-0.5 (Minor)** — Open Graph title/description are unset.
- **-0.5 (Minor)** — Existing internal links repeat the same anchor/target pattern heavily (template-driven, see Task 1).

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|:--:|---|:--:|:--:|---|---|---|
| 1 | Internal Links | Medium | Medium | 35 links, heavily template-repeated | Add 2 new feature-page links; fix 1 generic anchor | Add #1, #2. Fix #3. |
| 2 | CTAs | Low | — | Fixed template CTAs throughout (10+ "Try Upmetrics" buttons) | No changes — page is already CTA-dense | Skip |
| 3 | Resource CTA | N/A | — | N/A — not supported on `tools` post type | N/A | Skip (N/A) |
| 4 | Related Content | N/A | — | N/A — not supported on `tools` post type | N/A | Skip (N/A) |
| 5 | Meta Title/Desc | High | Quick Win | Title 55 chars OK; description has banned word; CTR 92% below benchmark | Rewrite title, description, keyphrase, OG fields | Approve |
| 6 | Image Alt Text | High | Quick Win | 3 logo images missing/empty alt | Add descriptive alt to all 3 | Approve all |
| 7 | URL Slug | — | — | `liveplan`, ranks position 6.9 | Keep as-is — clean, keyword-matching, risky to change at this position | Skip (keep) |
| 8 | Headings | — | — | 1 H1, 11 H2, 11 H3, keyphrase in H2 "Liveplan Review" | No changes needed | Skip (good) |
| 9 | Categories | N/A | — | N/A — `tools` post type has no taxonomy assigned | N/A | Skip (N/A) |
| 10 | Incoming Links | Low | — | 1 data-confirmed candidate | SEO team to review manually | Noted |

---

## Section C: Task-by-Task Detail

### Task 1: Internal Linking

**Existing link audit.** This page uses a fixed "Tools" comparison template: every feature table and comparison card links its product logos to the same target, so the same URL is intentionally linked multiple times (e.g., every "Try Upmetrics" button → `/pricing`, x10). That's standard for this template across every tool review page on the site, not a page-specific issue — flagging it here for awareness, not proposing a redesign.

| Anchor Text | Target URL | Occurrences | Status |
|---|---|:--:|---|
| Try Upmetrics / Start Planning Now / Get Started Today! / Try it now | /pricing | 10 | Good — template CTA pattern |
| Upmetrics4.9/5.0 (branded) | / (homepage) | 2 | Good — branded homepage mentions |
| Liveplan / Bizplan (comparison card) | /compare/bizplan-vs-liveplan | 2 | Good — comparison table pattern |
| Liveplan / Growthink (comparison card) | /compare/liveplan-vs-growthink | 2 | Good |
| Liveplan / Ideabuddy (comparison card) | /compare/ideabuddy-vs-liveplan | 2 | Good |
| Liveplan / Enloop (comparison card) | /compare/liveplan-vs-enloop | 2 | Good |
| See All / LivePlan alternatives / strong alternative to LivePlan | /liveplan-alternatives | 3 | Good |
| LivePlan's pricing | /tools/liveplan/pricing | 1 | Good |
| **Learn more** (VentureKit card) | /tools/venturekit | 1 | **Needs improvement — generic anchor** |
| **Learn more** (Ideabuddy card) | /tools/ideabuddy | 1 | **Needs improvement — generic anchor** |
| Ideabuddy4.6 out of 5 / Bizplan4.3 out of 5 / Enloop4.0 out of 5 | /tools/ideabuddy, /tools/bizplan, /tools/enloop | 1 each | Good |

**New link suggestions (target-first, from the WordPress repository):**

> **#1** — `financial forecasting tools` → `/features/financial-forecasting`
>
> **Section:** Upmetrics
>
> **In context:** "The platform also goes beyond the basics of planning. Upmetrics includes AI-powered writing help, **financial forecasting tools**, pitch deck builders, and presentation export options that rival or exceed what LivePlan offers in its premium tier."

---

> **#2** — `collaboration across teams` → `/features/business-plan-collaboration`
>
> **Section:** Upmetrics
>
> **In context:** "While LivePlan offers a simplified experience for solo founders, Upmetrics fills several noticeable gaps, especially in real-time editing, role-based access, and seamless **collaboration across teams**."

**Text fix:**

> **#3** — Generic anchor fix
>
> **Original:** `<a href="https://upmetrics.co/tools/venturekit">Learn more</a>` / `<a href="https://upmetrics.co/tools/ideabuddy">Learn more</a>`
>
> **Modified:** `See VentureKit` / `See Ideabuddy`
>
> **Note:** Both anchors sit in the same alternatives-comparison table and currently read "Learn more" — a banned generic pattern. Low effort, no layout impact.

<details>
<summary>Considered but skipped (3 pages)</summary>

| Page | Reason Skipped |
|---|---|
| Upmetrics' AI Assistants (`/features/upmetrics-ai-assistants`) | Best anchor match ("AI-powered writing help") sits in the same sentence as suggestion #1 — too close to use both |
| Upmetrics vs LivePlan: I Compared Both (`/blog/upmetrics-vs-liveplan`) | No natural existing phrase in the body to wrap; would require adding a new sentence — reserved for Task 10 instead (this page should link *to* the LivePlan review, not the other way) |
| AI Plan Generator (`/features/ai-plan-generator`) | No 2+ word verbatim phrase in the content maps cleanly to this page's topic without forcing it |

</details>

---

### Task 2: CTA Placements

This page's "CTAs" are the fixed Tools-template buttons (Visit Website, Try Upmetrics, Go to Website, Get Started Today!) — not the flexible delivery-block CTAs the standard CTA system targets. They already appear roughly once per major section (10+ instances). Adding a delivery-block CTA on top would put two CTAs in the same viewport in several places.

| # | CTA Type | Placement | Status |
|:--:|---|---|---|
| 1-10 | Template buttons (Visit Website / Try Upmetrics / Go to Website / Get Started Today!) | Throughout, roughly one per section | Good — template-standard, no changes |

**No new CTAs suggested.**

---

### Task 3: Downloadable Resource CTA
Skipped: not supported on `tools` post type (`set-resource-cta` only supports `post`, `download`, `pitch-deck`).

### Task 4: Related Content
Skipped: not supported on `tools` post type (`set-related-pages` ACF field is not present on this post's field group — only `domain_name`, `domain_link`, `popup_title`, `popup_subtitle`).

---

### Task 5: Meta Title & Description

**Performance context:**

| Top Query | Impressions | Position | Current CTR | Benchmark CTR | Status |
|---|:--:|:--:|:--:|:--:|:--:|
| liveplan | 4,904 | 6.9 | 0.22% | 5% | **Underperforming** |
| live plan | 1,984 | 6.8 | 0.45% | 5% | **Underperforming** |
| liveplan ai | 340 | 8.0 | 0.59% | 3% | **Underperforming** |
| liveplan review | 101 | 15.1 | 3.96% | 1.5% | Healthy |

**Current vs. suggested:**

| Field | Current | Chars | Suggested | Chars | Notes |
|---|---|:--:|---|:--:|---|
| Meta Title | LivePlan Review: Pricing, Features, Pros-Cons, and More | 55 | LivePlan Review 2026: Pricing, Features & Alternatives | 54 | Adds year hook + "Alternatives" angle; keyword front-loaded |
| Meta Description | Check out the detailed Liveplan review! Uncover pricing, features, pros, cons, and more in this comprehensive analysis to make informed decisions! | 146 | See our hands-on LivePlan review: pricing, AI writing tools, financial forecasting, and honest pros and cons. Compare it to Upmetrics before you buy. | 149 | Removes banned word "comprehensive"; adds a comparison hook |
| Focus Keyphrase | Liveplan | — | liveplan review | — | Single-word keyphrase expanded to match 2nd-highest query + page intent |
| Canonical | (auto, self-referencing) | — | No change | — | Yoast auto-generates correctly; GSC confirms `googleCanonical` matches |
| OG Title | (unset) | — | Matches meta title | — | — |
| OG Description | (unset) | — | Matches meta description | — | — |

**SERP Preview:**

```
─────────────────────────────────────────────────────
upmetrics.co › tools › liveplan
LivePlan Review 2026: Pricing, Features & Alternatives
See our hands-on LivePlan review: pricing, AI writing tools,
financial forecasting, and honest pros and cons. Compare it
to Upmetrics before you buy.
─────────────────────────────────────────────────────
```

**Differentiator note:** Competing SERP results for "liveplan" are dominated by generic "LivePlan Review" or "LivePlan Pricing" titles. The "2026" freshness tag plus "& Alternatives" signals both a current review and a comparison angle other results don't lead with.

---

### Task 6: Image Alt Text

**Summary:**

| Status | Count |
|---|:--:|
| Critical — Missing/Empty | 3 |
| Good | 29 |
| **Total images** | **32** |

| # | src (filename) | Status | Current Alt | Suggested Alt | Chars |
|:--:|---|---|---|---|:--:|
| 1 | Tools-logo-Icons-Liveplan-2.png | Empty | `""` | LivePlan business plan software logo displayed on the Upmetrics LivePlan review page | 84 |
| 2 | liveplan-logo.svg (1st feature table) | Missing | *(none)* | LivePlan logo shown in the business planning tools feature comparison table | 75 |
| 3 | Tools-logo-Icons-Upmetrics.png (Price Comparison figure) | Empty | `""` | Upmetrics logo shown alongside LivePlan in the pricing comparison table | 71 |

Note: the same LivePlan/Upmetrics logo files appear correctly with alt text in 8 other places on the page (e.g., the other 4 feature-comparison table headers) — these 3 are inconsistencies, not a deliberate decorative choice.

---

### Task 7: URL Slug Optimization

Current slug `liveplan` is short, lowercase, hyphen-free (single word), and matches the top query exactly. Page ranks position 6.9 — inside the "change only if very bad" band, and this slug isn't bad. **Recommendation: keep as-is.**

---

### Task 8: Heading Structure Audit

Single H1 ("Liveplan"), 11 H2s, 11 H3s, no level skipping, no duplicates, all under 70 characters. Primary keyphrase appears verbatim in H2 "Liveplan Review." **No changes needed.**

---

### Task 9: Category / Taxonomy Assignment
Skipped: `tools` post type carries no category/tag/taxonomy assignment on this site (confirmed empty on the live post, and `tools` isn't referenced in the categories reference file).

---

### Task 10: Incoming Internal Link Suggestions

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic | Priority |
|:--:|---|---|:--:|---|---|---|:--:|:--:|
| 1 | Upmetrics vs LivePlan: I Compared Both | /blog/upmetrics-vs-liveplan | 109372 | post | Ranks for "upmetrics vs liveplan" (12 impr) and "liveplan vs upmetrics" (23 impr) — a direct-comparison blog post that doesn't yet link to the dedicated LivePlan review | liveplan review | 4 clicks | Medium |

Note: `/compare/upmetrics-vs-liveplan` and `/liveplan-alternatives` are stronger topical matches (both rank #2-4 for "upmetrics vs liveplan" queries) but are excluded here — `compare` and `page` post types are outside Task 10's prose-heavy source list. Worth a manual look by the SEO team regardless.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2. Fix #3. 
Task 2 (CTAs): Skip — no changes.
Task 3 (Resource CTA): N/A.
Task 4 (Related Content): N/A.
Task 5 (Meta Title/Desc): Approve suggested title, description, keyphrase, and OG fields.
Task 6 (Image Alt Text): Approve all 3 updates.
Task 7 (URL Slug): Skip — keep as-is.
Task 8 (Headings): Skip — already good.
Task 9 (Categories): N/A.
Task 10 (Incoming Links): Noted — will review manually.
```

Or simply: **"Approve all"** / **"Approve all except Task X"**
