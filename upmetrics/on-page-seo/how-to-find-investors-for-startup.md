# SEO On-Page Report — How to Find Investors for a Startup

| Field | Value |
|-------|-------|
| **Page URL** | https://upmetrics.co/blog/how-to-find-investors-for-startup |
| **Post ID** | 82959 |
| **Post Type** | `post` (Blog Post) |
| **Category** | Funding |
| **Word Count** | 1,903 |
| **Published / Last Modified** | 2025-04-26 / **2026-08-27** |
| **Report Date** | 2026-09-09 |
| **GSC Data Range** | 2026-06-11 to 2026-09-06 (90 days) |
| **GA4 Data Range** | Report A: last 30 days · Report E: last 90 days |
| **Brand** | Upmetrics |

---

## Read This First — The Page Has Not Been Recrawled Since the Rewrite

| Signal | Value |
|--------|-------|
| Last Google crawl | **2026-08-25 21:00 UTC** |
| Content last modified | **2026-08-27 14:23** |
| Index status | PASS — "Submitted and indexed", canonical self-referencing |
| Page performance (90d) | **1,977 impressions · 3 clicks · avg position 43.6** |

**Google's index still holds the pre-rewrite version of this article.** Proof: GSC is still serving four heading-anchor URLs that no longer exist in the current content, and they rank far better than the page itself.

| Indexed URL fragment | Impressions | Position |
|----------------------|:--:|:--:|
| `#understand-the-types-of-investors` | 43 | **5.6** |
| `#how-to-reach-out-to-investors` | 30 | **5.8** |
| `#where-to-find-investors-based-on-their-type` | 12 | **5.3** |
| `#make-sure-youre-ready-to-seek-investment` | 1 | **3.0** |

None of those anchors exist any more — the current H2 IDs are `which-type-of-investor-fits-your-startup-stage`, `where-to-find-investors-for-your-startup`, `other-ways-to-find-investors-for-your-startup`, and `conclusion`.

**Action before anything else:** request re-indexing in Search Console. Every on-page change below should go live first, then submit the URL once. Judging this page's rankings on current data is judging content Google has not read.

---

## Section B: Page Health Score & Action Summary

### Page Health Score: 4.5 / 10

| Deduction | Severity | Amount |
|-----------|----------|:--:|
| Canonical Blog Post End CTA is absent (a custom `delivery-block` occupies the slot) | Critical | -2.0 |
| Zero editorial internal links across 1,903 words | Critical | -1.0 |
| Meta title is identical to the H1 and carries no differentiation hook | Needs Improvement | -1.0 |
| Four previously-indexed heading anchors are now broken; H3s carry no `id` attributes | Needs Improvement | -1.0 |
| Downloadable Resource CTA is not set | Minor | -0.5 |
| **Total** | | **4.5 / 10** |

### Status Summary

| Status | Count | Items |
|--------|:--:|-------|
| **Critical** | 2 | Missing end CTA · No editorial internal links |
| **Needs Improvement** | 3 | Meta title/keyphrase · Heading IDs · Resource CTA unset |
| **Good** | 6 | Indexing · Image alt text · Heading hierarchy · URL slug · Category · External link quality |

### Action Summary

| # | Task | Impact | Effort | Current State | Suggestion | Dependencies | Your Decision |
|:--:|------|:--:|:--:|---------------|------------|--------------|---------------|
| 1 | Internal Links | **High** | Medium | 0 editorial internal links (only 1 branded homepage link) | Add 3 contextual links; 2 optional | None | **Add #1, #2, #3** |
| 2 | CTA Placements | **High** | Medium | 2 CTAs; canonical end CTA missing | Restore end CTA + add 1 light inline CTA | None | **Approve #1 (Option A) and #2** |
| 3 | Resource CTA | **High** | Quick Win | Not set | Startup Fundraising Checklist Template | None | **Approve** |
| 4 | Related Content | Medium | Quick Win | 4 set; 2 off-topic, 2 titles over 50 chars | Replace with 4 investor-focused items | Dedup vs Tasks 1/3 | **Approve #1–#4** |
| 5 | Meta Title & Description | Medium | Quick Win | Title = H1, no hook; keyphrase is 6 words | New title + description + 4-word keyphrase | None | **Approve title, description, keyphrase** |
| 6 | Image Alt Text | Low | Quick Win | 3/3 content images have strong alt text | Optional: add primary keyword to 1 alt | None | **Skip — alts are already good** |
| 7 | URL Slug | Low | High | `how-to-find-investors-for-startup` — clean, keyword-led | No change | 301 redirect if changed | **Skip — nothing to fix** |
| 8 | Heading Structure | **High** | Medium | Hierarchy clean; H3s have no IDs; 4 legacy anchors broken | Add H3 IDs; consider restoring the outreach section | Re-index request | **Approve H3 IDs; decide on outreach section** |
| 9 | Category | Low | Quick Win | Funding | Correct — no change | None | **Skip — already correct** |
| 10 | Incoming Internal Links | **High** | Medium | Not measured before | 6 verified source pages to link FROM | Manual implementation | **Noted — will review** |

---

## Section C: Task-by-Task Suggestions

### TASK 1: Internal Linking

#### Part A — Existing Link Audit

The body has **1,903 words and zero editorial internal links.** The only internal anchors on the page sit inside CTA blocks or the closing brand mention.

| # | Anchor Text | Target | Location | Status |
|:--:|-------------|--------|----------|--------|
| 1 | How to Get Funding from Angel Investors | `/blog/angel-investor-funding` | Inside the tip CTA after "Angel investors" | **Good** — audited under Task 2 as a CTA, not a body link |
| 2 | Upmetrics | Homepage | Conclusion paragraph | **Good** — branded homepage mention, standard practice |

**External links: 17, all healthy.** OpenVC, Signal by NFX, Angel Capital Association, Crunchbase, Dealroom, PitchBook, Salesforce Ventures, M12, Alexa Fund, Y Combinator, Techstars, 500 Global, F6S, Wefunder, Republic, StartEngine. All carry `rel="noopener"`, all are authoritative sources rather than competitors, and none appear in the configured competitor list. No changes needed — this is exactly the outbound profile a "where to find X" guide should have.

**No broken links, no query strings, no over-optimised anchors.** The problem is absence, not quality.

#### Part B — New Link Suggestions

**Recommended**

> **#1** — `funding rounds` → `/blog/funding-rounds`
>
> **Section:** Venture capital firms
>
> **In context:** "One practical way to find VC firms is to look at startups similar to yours and see who funded them. Start with 5-10 comparable companies and use Crunchbase to check their **funding rounds** and participating investors. If the same VC firms appear across several companies in your space, they're worth researching further."

---

> **#2** — `jumping straight to VC firms` → `/blog/when-you-shouldnt-raise-funding`
>
> **Section:** Which type of investor fits your startup stage?
>
> **In context:** "Once you have a working product and some early customers, angel investors or pre-seed funds may become more relevant. I'd also avoid **jumping straight to VC firms** just because you need outside funding. Start with the sources that fit where your startup stands today."
>
> **Note:** The target is "When NOT to Raise Venture Capital: 7 Times to Skip Funding" — it argues the exact point this sentence makes. Strongest topical match in the whole repository.

---

> **#3** — `business model` → `/blog/business-model`
>
> **Section:** Conclusion
>
> **In context:** "Once you find the right investors, the next step is making sure you're ready for the conversation. They may want to understand your market, **business model**, financial forecasts, and how you plan to use the money."
>
> **Note:** `financial forecasts` in the same sentence would also link cleanly to `/blog/write-financial-section-startup-business-plan`, but two links in one sentence reads as stuffing. Pick one; `business model` is the stronger slug-level match.

---

**Optional** — both anchors sit inside the stage/funding-source table. Table cells are a weaker home for links (cramped on mobile) but the topical matches are genuine and both targets pull real search traffic.

> **#4** — `startup competitions` → `/blog/business-plan-competitions`
>
> **Section:** Which type of investor fits your startup stage? (table, row "Idea or early validation")
>
> **In context:** "Your own funds, friends and family, grants, **startup competitions**, some accelerators, and individual angel investors"

---

> **#5** — `relevant grants` → `/blog/startup-business-grants`
>
> **Section:** Which type of investor fits your startup stage? (table, row "Prototype or MVP")
>
> **In context:** "Friends and family, angel investors, accelerators, **relevant grants**, and crowdfunding"
>
> **Note:** Deliberately using the row-2 occurrence. Row 1 already carries #4, and two links in one table cell looks like a nav menu.

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| How to Get Funding from Angel Investors (`/blog/angel-investor-funding`) | Already linked from the tip CTA in the Angel investors section |
| Accelerators & Incubators (`/solutions/accelerators-and-incubators`) | Written for accelerator organisations, not founders looking for one. Wrong audience despite the keyword match |
| What Is Bootstrapping in Business (`/blog/what-is-bootstrapping-in-business`) | Best anchor ("your own funds") sits ~30 words from suggestion #2 — too close |
| How to Prepare a Financial Plan for Startup Business (`/blog/write-financial-section-startup-business-plan`) | Its anchor ("financial forecasts") is in the same sentence as #3 |
| Top 10 Alternative Business Funding Methods (`/blog/alternative-business-funding-methods`) | The natural anchor is "Equity crowdfunding", and this page covers crowdfunding only as one item of ten — not a content match. **No published crowdfunding-specific page exists on the site.** Worth commissioning |

</details>

---

### TASK 2: CTA Placements

#### Part A — Existing CTA Audit

| # | CTA Type | Placement | Status | Notes |
|:--:|----------|-----------|--------|-------|
| 1 | Tip alert (`upm-blog-tip`) | After "Angel investors" section | **Good** | Relevant, editorial in tone, links to a genuine next step. Uses a legacy wrapper class rather than the registry's `yellow-alert` — cosmetic only, no action needed |
| 2 | Custom Delivery Block (`delivery-block`) | Last block of content | **Needs decision** | Headline "Ready to Approach Investors?" — this is a custom Type 3 banner, **not** the canonical Blog Post End CTA |

**Missing required element:** every Upmetrics `post` must end with the canonical Blog Post End CTA (headline "The Quickest Way to turn a Business Idea into a Business Plan"). Neither that block nor a legacy `[elementor-template]` shortcode is present. The end-of-post slot is occupied by a custom banner instead.

There is also a **~1,100-word stretch with no CTA at all**, from the "Venture capital firms" section through to the Conclusion.

#### Part B — New CTA Suggestions

**Recommended**

> **#1** — Blog Post End CTA (canonical) | Last block of content
>
> **Two ways to resolve the conflict — pick one:**
>
> **Option A (recommended):** replace the custom "Ready to Approach Investors?" banner with the canonical end CTA. Both are `delivery-block` banners; stacking them would put two near-identical blue banners back to back.
>
> **Option B:** keep the custom banner where it is and append the canonical CTA after it. Honours the letter of the rule but ships two stacked banners.
>
> **Placed after:** "That's where Upmetrics can help. You can use it to build your business plan, research your market, and create financial forecasts so the key details are ready when investors ask for them."
>
> **CTA Preview:**
> ```
> +---------------------------------------------------------+
> |   The Quickest Way to turn a Business Idea into a        |
> |   Business Plan                                          |
> |                                                          |
> |   Fill-in-the-blanks and automatic financials make       |
> |   it easy.                                               |
> |                                                          |
> |              [ Get Started Now! -> ]                     |
> +---------------------------------------------------------+
> ```
> Copy is fixed by the registry — inserted verbatim, no edits.

---

> **#2** — Inline Help CTA (Type 2) | Immediately before the "Other ways to find investors for your startup" H2
>
> **Placed after:** "This is how you can find investors for your startup through the main investor types and platforms. But there are also other practical ways to uncover relevant investors. Let's look at those next."
>
> **CTA Preview:**
> ```
> +---------------------------------------------------------+
> | Building the investor list is the slow part.             |
> | Let AI draft your business plan.                         |
> +---------------------------------------------------------+
> ```
>
> **Why here:** it lands ~850 words after the tip CTA and ~720 words before the end CTA — the two CTAs never share a screen. The reader has just finished the full survey of where investors live, so "the list is the slow part" is the honest next thought. Persuasion angle is **speed**, which neither existing CTA uses.

**Resulting mix:** 1 light tip + 1 light inline + 1 end banner. That matches the "one large banner plus one or two light text CTAs" guidance for a ~1,900-word post.

---

### TASK 3: Downloadable Resource CTA

**Currently unset** — `related_resource` is empty, so the page shows no resource banner at all.

| Rank | Resource | URL | Post ID | Why |
|:--:|----------|-----|:--:|-----|
| **1** | Startup Fundraising Checklist Template | `/download/startup-fundraising-checklist` | 7345 | Exact next step after building an investor list. A reader who just learned *where* to look needs *what to prepare* |
| 2 | Investor Pitch Templates | `/download/investor-pitch-templates` | 7335 | Good fallback, but pitch materials come a step later than this article's stage |

**Recommended settings:**

| Parameter | Value | Chars |
|-----------|-------|:--:|
| `resource_url` | `https://upmetrics.co/download/startup-fundraising-checklist` | — |
| `resource_link_text` | `Get Checklist` | 13 |
| `heading` | `Startup Fundraising Checklist` | 29 |
| **Rendered as** | **Get Checklist: Startup Fundraising Checklist** | **44** |

Comfortably under the ~55-character single-line limit.

---

### TASK 4: Related Content

#### Currently set (4 items)

| # | Current Title | Target | Chars | Assessment |
|:--:|---------------|--------|:--:|------------|
| 1 | How to Write a Business Plan That Attracts Investors | `/blog/business-plan-for-investors` | 51 | Relevant, title 1 char over |
| 2 | How to Secure a Business Loan Even with Bad Credit | `/blog/how-to-get-a-business-loan-with-bad-credit` | 49 | **Off-topic** — debt financing, not investors |
| 3 | How to Build an Investment-Ready Pitch Deck to Raise Capital Successfully | `/blog/how-to-make-pitch-deck` | **72** | Relevant, title far too long |
| 4 | 10 Proven Ways to Fund Your Business Without Relying on a Bank Loan | `/blog/alternative-business-funding-methods` | **67** | Loosely relevant, title far too long |

#### Suggested replacement set

`set-related-pages` replaces everything, so this is the complete new list.

| # | Post ID | Target | Suggested Title | Chars | Why |
|:--:|:--:|--------|-----------------|:--:|-----|
| 1 | 64304 | `/blog/business-plan-for-investors` | What Investors Expect in Your Plan | 34 | Direct next step; 7,596 impressions on investor-plan queries |
| 2 | 96035 | `/blog/what-investors-want-to-see-in-pitch-decks` | What Wins Investors Over in a Deck | 34 | 496 sessions, 86% engagement, **58 conversions** in 90 days |
| 3 | 54194 | `/blog/how-to-make-pitch-deck` | Build a Deck Investors Say Yes To | 33 | 543 sessions, 84% engagement, **82 conversions** — strongest converting blog page in this cluster |
| 4 | 81725 | `/blog/what-is-a-fair-percentage-for-an-investor` | How Much Equity Do Investors Get? | 33 | Ranks **position 8.9** with 6,546 impressions — the site's best-performing investor page |

Items 1 and 3 keep destinations from the current set where they earn it; the loan and alternative-funding items are dropped as off-topic. No overlap with Task 1 or Task 3 targets. Alternative if you want less pitch-deck weighting: swap #3 for `/blog/questions-to-ask-investors` (post 82876).

---

### TASK 5: Meta Title & Description

#### Performance context

The CTR-vs-position benchmark does not apply here. Every target query sits at **position 27–60**, far outside the position 1–20 band where the meta title influences clicks. This is a ranking problem, not a snippet problem — treat the changes below as low-priority housekeeping, not a fix for the traffic.

| Top Query | Impressions | Position | Current CTR | Benchmark | Status |
|-----------|:--:|:--:|:--:|:--:|:--:|
| find investors for startup | 174 | 55.5 | 0% | n/a (>20) | Not rankable yet |
| find investors for startup business | 76 | 60.3 | 0% | n/a (>20) | Not rankable yet |
| how to find investors for startup | 64 | 52.1 | 1.6% | n/a (>20) | Not rankable yet |
| find investors | 57 | 56.7 | 0% | n/a (>20) | Not rankable yet |
| find investors for your business | 23 | 31.0 | 0% | n/a (>20) | Not rankable yet |

**Device split (90d):** desktop 1,167 impressions at position 50.2; mobile 193 at position 43.2. Mobile is marginally stronger, so keeping the title under ~55 characters is worth doing.

#### Current vs. suggested

| Field | Current | Chars | Suggested | Chars | Notes |
|-------|---------|:--:|-----------|:--:|-------|
| Meta Title | How to Find Investors for a Startup: Trusted Sources to Look | 60 | Find Investors for Startup: 8 Places That Actually Work | 55 | Current is **identical to the H1** and has no hook; "Trusted Sources to Look" is also grammatically loose. New version front-loads the keyphrase at char 0 and adds two hooks (number + benefit) |
| Meta Description | Wondering where to find investors for a startup? Explore practical ways to find angels, VCs, accelerators, crowdfunding platforms, and more. | 140 | Not sure how to find investors for startup funding? Here are 8 places to look, from angel networks and VC databases to AI-powered investor searches. | 148 | Current is technically compliant. New version carries the keyphrase verbatim at char 16 and names the AI angle, which is the article's genuine differentiator |
| Focus Keyphrase | how to find investors for startup | 6 words | find investors for startup | 4 words | Current keyphrase is 6 words (rule is 2–4) and matches the query with 64 impressions. The suggested one is the top query at **174 impressions** |
| Canonical | (unset) | — | Leave unset | — | Yoast self-references; GSC confirms `userCanonical` = `googleCanonical` = the page URL. **No action** |
| OG Title | How to Find Investors for a Startup (2026 Founder's Guide) | 58 | Keep as is | 58 | Already social-specific and distinct from the meta title. Revisit the "2026" tag in January |
| OG Description | (matches meta description) | 140 | Update to match new meta description | 148 | Keep the two in sync |

**"8 places" is accurate:** friends and family, angel investors, VC firms, corporate VC, accelerators/incubators, equity crowdfunding, AI tools, targeted Google search.

#### SERP Preview

```
─────────────────────────────────────────────────────
upmetrics.co › blog › how-to-find-investors-for-startup
Find Investors for Startup: 8 Places That Actually Work
Not sure how to find investors for startup funding? Here are 8
places to look, from angel networks and VC databases to
AI-powered investor searches.
─────────────────────────────────────────────────────
```

**Differentiator:** competing titles for "find investors for startup" lean on "Guide" and "Ultimate" framings. This one leads with a countable promise ("8 Places") and a scepticism-matching qualifier ("That Actually Work"), which is also the tone the article itself uses.

---

### TASK 6: Image Alt Text

#### Audit Summary

| Status | Count | Action |
|--------|:--:|--------|
| Critical — Missing | 0 | — |
| Critical — Empty (wrong) | 0 | — |
| Needs Improvement | 0 | — |
| Good | 3 | No action |
| Decorative — Correct | 1 | No action |
| **Total images** | **4** | — |

**This task is already in good shape.** All three content screenshots carry specific, descriptive alt text in the 90–99 character range that describes what the screenshot actually shows rather than restating the filename.

| # | src | Status | Current Alt | Chars |
|:--:|-----|--------|-------------|:--:|
| 1 | `...ai-prompt-broad-investor-list.png` | Good | AI prompt result listing 10 US pre-seed investors with portfolio company, round, and investment date | 99 |
| 2 | `...ai-prompt-narrowed-investor-list.png` | Good | Follow-up AI prompt narrowing the list to 7 ranked investors with fit and recent investment | 90 |
| 3 | `...google-ai-mode-investor-search.png` | Good | Google AI Mode results showing active Texas pre-seed and seed investors in retail tech and B2B SaaS | 98 |
| 4 | `crossline.png` | Decorative | `crossline` | 9 |

**Optional refinement (low value):** no alt currently contains the primary keyphrase. If you want the standard 1–2 keyword-bearing alts, image #1 could become "Finding investors for a startup with AI: prompt result listing 10 US pre-seed investors with portfolio and round data" (118 chars). This is a marginal gain and the current alt is arguably more precise. **My recommendation is to skip it.**

**Note (outside the 10 tasks):** the three content images are served from `ct.upmetrics.co` (the WordPress backend) rather than `static-web.upmetrics.co` (the CDN). The featured image on this same post uses the CDN. Worth checking whether WP Offload Media processed the August 2026 uploads — it is a delivery-performance issue, not an SEO task, so no action is proposed here.

---

### TASK 7: URL Slug

| Field | Value |
|-------|-------|
| Current slug | `how-to-find-investors-for-startup` |
| Length | 33 characters, 5 words |
| Contains primary keyword | Yes |
| Format | Lowercase, hyphens, no stop-word bloat, no double hyphens, no parameters |

**No change.** The slug is already what an optimised slug looks like. Changing it would cost the four indexed heading-anchor URLs and require a 301 for no gain.

---

### TASK 8: Heading Structure

#### Current hierarchy

| Level | Heading | ID |
|-------|---------|-----|
| H2 | Which type of investor fits your startup stage? | `which-type-of-investor-fits-your-startup-stage` |
| H2 | Where to find investors for your startup? | `where-to-find-investors-for-your-startup` |
| H3 | Friends and family | *(none)* |
| H3 | Angel investors | *(none)* |
| H3 | Venture capital firms | *(none)* |
| H3 | Corporate venture capital | *(none)* |
| H3 | Accelerators and incubators | *(none)* |
| H3 | Equity crowdfunding | *(none)* |
| H2 | Other ways to find investors for your startup | `other-ways-to-find-investors-for-your-startup` |
| H3 | Find investors using AI | *(none)* |
| H3 | Use Google for targeted investor searches | *(none)* |
| H2 | Conclusion | `conclusion` |

**What passes:** exactly one H1 (rendered from the post title, correctly absent from the content field), no skipped levels, no duplicates, all headings under 70 characters, consistent sentence case, and the primary keyword present in two H2s.

#### Issues

| # | Issue | Impact | Suggestion |
|:--:|-------|--------|------------|
| 1 | **All 8 H3s lack `id` attributes** | High | Add slug IDs to every H3. Google was previously awarding this page position 3–6 for heading-anchor URLs; with no H3 IDs there are only four anchor targets on a 12-heading page. This is the cheapest available win |
| 2 | **The "how to reach out to investors" section was removed in the rewrite** | High | `#how-to-reach-out-to-investors` still earns 30 impressions at **position 5.8** with no content behind it. The article now stops at "here is where they are" and never covers the approach. Consider restoring a short outreach section — this is a content decision, not a markup fix |
| 3 | "Conclusion" is a generic heading | Low | Optional: rename to something descriptive such as "Narrowing your investor list" |

Suggested H3 IDs: `friends-and-family`, `angel-investors`, `venture-capital-firms`, `corporate-venture-capital`, `accelerators-and-incubators`, `equity-crowdfunding`, `find-investors-using-ai`, `use-google-for-targeted-investor-searches`.

---

### TASK 9: Category / Taxonomy Assignment

| Field | Value |
|-------|-------|
| Current category | **Funding** (`funding`, term ID 414) |
| Taxonomy | `category` |
| Assessment | **Correct** |

The Funding category is defined as "raising capital, investor pitches, grants, loans, crowdfunding, SBA loans, venture capital, fundraising strategies" — a precise fit. A second category is permitted but none of the remaining options (Planning, Starting, Managing) describes this article. **No change.**

---

### TASK 10: Incoming Internal Link Suggestions

This page currently receives essentially no internal links, which is a large part of why it sits at position 43 while sibling investor pages rank at 8–9. Below are the pages best positioned to pass equity to it. Every row is verified in WordPress with a real post ID.

| # | Source Page | URL | Post ID | Post Type | Why Link Here | Suggested Anchor | Traffic (90d) | Priority |
|:--:|-------------|-----|:--:|-----------|---------------|------------------|:--:|:--:|
| 1 | What is a Fair Percentage for an Investor? | `/blog/what-is-a-fair-percentage-for-an-investor` | 81725 | post | Site's strongest investor page — position 8.9 with 6,546 impressions. A link from here carries the most equity of any candidate | find investors for your startup | **39 clicks** | High |
| 2 | How to Convince Investors to Invest in Your Business | `/blog/how-to-convince-investors` | 6036 | post | Its own "#1 find investors who match your business" section ranks at position 8.4 with 120 impressions — that section is literally about this topic | where to find investors | 10 clicks | High |
| 3 | How to Write a Business Plan for Investors | `/blog/business-plan-for-investors` | 64304 | post | 7,596 impressions on investor-plan queries; heading fragments rank at position 8 | finding the right investors | 4 clicks | High |
| 4 | How to Pitch to Investors: A Step-by-Step Guide | `/blog/how-to-pitch-investors` | 6210 | post | 1,707 impressions on investor-pitch queries; pitching presupposes a list | find startup investors | 7 clicks | Medium |
| 5 | How to Write a Funding Request in Your Business Plan | `/blog/funding-request-business-plan` | 6104 | post | Its "loan vs investor" fragments rank at position 7.3 across 327 impressions | investors for your startup | — | Medium |
| 6 | What Investors Want From your Business | `/blog/what-investors-want-from-your-business` | 79847 | post | Position 21.2 with 1,137 impressions; natural upstream topic | how to find investors | 3 clicks | Medium |

> Every source URL above is verified in WordPress with a real post ID. Suggested anchor text is a starting search term for the SEO team — the actual anchor depends on what phrasing already exists in that page's content.

**Deliberately excluded:** `/blog/funding-rounds` and `/blog/when-you-shouldnt-raise-funding` (both receive links from this page under Task 1 — avoiding reciprocal pairs), `/blog/angel-investor-funding` (already linked from this page's tip CTA), and every download and product-feature page (too thin or too promotional to host an editorial link).

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Add #1, #2, #3. Skip #4, #5.
Task 2 (CTAs): Approve #1 using Option A (replace custom banner). Approve #2.
Task 3 (Resource CTA): Approve Startup Fundraising Checklist.
Task 4 (Related Content): Approve items #1-#4.
Task 5 (Meta Title/Desc): Approve title, description, and keyphrase. Keep OG title.
Task 6 (Image Alt Text): Skip - alts are already good.
Task 7 (URL Slug): Skip - nothing to fix.
Task 8 (Headings): Approve H3 IDs. Restoring the outreach section: yes/no.
Task 9 (Categories): Skip - Funding is correct.
Task 10 (Incoming Links): Noted - will review manually.
Also: request re-indexing in Search Console after changes go live.
```

Or simply: **"Approve all"** / **"Approve all except Task 8's content change"**
