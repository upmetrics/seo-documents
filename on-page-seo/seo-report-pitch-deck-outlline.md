# SEO Report: Build a Pitch Deck Outline That Gets Investor Attention

| Field | Value |
|-------|-------|
| **URL** | https://upmetrics.co/blog/pitch-deck-outlline |
| **Post ID** | 87444 |
| **Post Type** | Blog Post (`post`) |
| **Report Date** | 2026-04-07 |
| **GSC Data Range** | Jan 7 – Apr 4, 2026 (88 days) |
| **Category** | Funding |

---

## Section B: Page Health Score + Action Summary

### Health Score: 4/10

| Status | Count | Items |
|--------|:-----:|-------|
| Critical | 1 | Slug typo |
| Needs Improvement | 5 | CTAs, meta fields, resource CTA, related content, Elementor template |
| Good | 3 | Content quality, existing internal links, indexing |

> **Note:** GA4 data was unavailable for this session. CTA and link targets prioritized using GSC data + topical relevance.

---

### Action Summary Table

| # | Task | Impact | Effort | Current State | Suggestion | Your Decision |
|---|------|:------:|:------:|---------------|-----------|---------------|
| T1 | Internal Links | Medium | Medium | 4 body links, 0 issues | Add 2 new links | Approve |
| T2 | CTA Placements | High | Medium | 4 identical legacy CTAs, Elementor missing | Replace 3, keep 1, add Elementor | Approve all |
| T3 | Resource CTA | Medium | Quick Win | Not set | Set Investor Pitch Templates | Approve |
| T4 | Related Content | Medium | Quick Win | Not set | Add 4 related posts | Approve |
| T5 | Meta Title/Desc | High | Quick Win | Not set (empty) | Set title, desc, keyphrase | Approve |
| T6 | Image Alt Text | Low | Quick Win | 1 typo, 1 generic | Fix 2 images | Approve |
| T7 | URL Slug | **Critical** | High | `pitch-deck-outlline` (TYPO) | Fix to `pitch-deck-outline` + 301 redirect | Approve — needs redirect |
| T8 | Headings | Low | Quick Win | "The bottom line" generic H2 | Update closing H2 | Approve or Skip |
| T9 | Categories | Low | Quick Win | Funding only | Keep Funding, skip Planning | Skip |

---

## Section C: Task-by-Task Suggestions

---

## Task 1: Internal Linking

**GSC Context:** "pitch deck outline" = position 68 (poor). "pitch deck mistakes" and "raise money" sections have high-traffic topical targets with exact text already in the post.

### Part A — Existing Link Audit

**4 body links, 0 issues.** All links are well-placed, relevant, and use natural anchor text.

| # | Anchor Text | Target URL | Status |
|---|-------------|-----------|:------:|
| 1 | how to make a pitch deck | /blog/how-to-make-pitch-deck | Good |
| 2 | pitch deck examples | /pitch-deck-examples | Good |
| 3 | how to pitch investors | /blog/how-to-pitch-investors | Good |
| 4 | AI pitch deck builder | /features/pitch-deck | Good |

**Note:** Download link in CTA (`/download/investor-pitch-templates`) is not a body link — it's a styled CTA element. Not counted in body link total.

**External links:** pitchdeckcreators.com (stats) and techcrunch.com (stats) — both are credible sources, not competitors. No action needed.

---

### Part B — New Link Suggestions

> **#1** — `pitch deck mistakes` → `/blog/pitch-deck-mistakes`
>
> **Section:** Don't have all the info yet?
>
> **In context:** "This outline also helps avoid the most common **pitch deck mistakes**, like skipping traction or burying your ask."
>
> **Anchor type:** Partial match | Informational

---

> **#2** — `raise money` → `/blog/how-to-get-funding-for-a-business`
>
> **Section:** The bottom line
>
> **In context:** "If you've made it this far, you already understand more about pitch decks than most people trying to **raise money** with a half-finished file and a lot of hope."
>
> **Anchor type:** Natural/Contextual | Informational

---

<details>
<summary>Considered but skipped (5 pages)</summary>

| Page | Reason Skipped |
|------|----------------|
| What Investors Want to See in Pitch Decks | No clean anchor text match; "investors" appears 1 word only in context |
| How to Design the Perfect Team Slide | "team" is 1 word; no 2+ word phrase match found in team section |
| What are Funding Rounds? | "fundraising process" already has an external link; "funding ask" doesn't match page topic |
| Pitch Deck Competition Slide | Section discusses "competitors" (1 word); no "competition slide" phrase in content |
| What Is a Pitch Deck? | Saved for Task 4 (Related Content) |

</details>

---

## Task 2: CTA Placements

**Critical issue:** All 4 existing CTAs are the same legacy type (`cta-template cta-template-ai`) with identical copy, image, and destination. This causes banner blindness and violates the variety rule.

**Elementor template** (`[elementor-template id="44970"]`) is missing from the end of the post — this is required on all Upmetrics blog posts.

### Part A — Existing CTA Audit

| # | Type | Placement | Status | Notes |
|---|------|-----------|:------:|-------|
| 1 | Legacy AI Banner (cta-template-ai) | After slide 3 (Problem) | Replace | Legacy template, same as #2-4 |
| 2 | Legacy AI Banner (cta-template-ai) | After slide 6 (Product) | Remove | Too close to #1; same message |
| 3 | Legacy AI Banner (cta-template-ai) | After slide 12 (Team) | Replace | Placement is good; CTA needs refresh |
| 4 | Legacy AI Banner (cta-template-ai) | After "zero revenue" section | Remove | Too close to download link; same message |
| 5 | Download Link (Type 1) | Before "The bottom line" | Good | Already uses correct format |
| – | Elementor End CTA | End of post | **Missing** | Must add `[elementor-template id="44970"]` |

---

### Part B — New CTA Suggestions

> **#1 — Replace CTA #1** | Type 11 (Inline Banner) | After slide 3 (Problem)
>
> **Placed after:** "The stronger the problem, the more believable your solution becomes. This slide is about friction, frustration, and unmet needs. Make it clear."
>
> **CTA Preview:**
> ```
> ┌──────────────────────────────────────────────────────────────┐
> │  Your problem slide is ready — now build the whole deck  [ Try Upmetrics AI ] │
> └──────────────────────────────────────────────────────────────┘
> ```
>
> **Angle:** Ease — lightweight mid-list CTA, doesn't interrupt the slide walkthrough
>
> **HTML:**
> ```html
> <div class="upm_blog_bg_cta inline-cta-banner">
> Your problem slide is ready &mdash; now build the whole deck
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Try Upmetrics AI</a>
> </div>
> ```

---

> **#2 — Replace CTA #3** | Type 8 (Investor-Ready Plan) | After slide 14 (Vision & Exit)
>
> **Placed after:** "Give investors a reason to believe there's a return ahead."
>
> **Rationale:** The end of the 14-slide walkthrough is the ideal conversion point — reader now understands the full structure and is ready to act.
>
> **CTA Preview:**
> ```
> ┌─────────────────────────────────────────────────────────┐
> │  All 14 slides planned. Now build the real thing.       │
> │                                                         │
> │  Build your investor-ready pitch deck with AI           │
> │                                                         │
> │  [ Start Building Now ]                    🖼 AI Plan   │
> └─────────────────────────────────────────────────────────┘
> ```
>
> **Angle:** Outcome — the reader just finished planning their deck structure, now they can execute
>
> **HTML:**
> ```html
> <div class="upm_blog_bg_cta flex-cta-banner flex-col-reverse">
> <div>
> All 14 slides planned. Now build the real thing.
> <p class="title h2">Build your investor-ready pitch deck with AI</p>
> <a class="cta-btn cta-btn-bg-orange" href="https://upmetrics.co/signup">Start Building Now</a>
> </div>
> <div class="cta_img_wrapper"><img src="https://upmetrics.co/wp-content/uploads/2025/06/ai-business-plan.svg" alt="AI Business Plan" width="200" height="170" /></div>
> </div>
> ```

---

> **#3 — Add Elementor End-of-Post CTA** | Required element | End of content
>
> **Placed after:** "You bring the idea. We help shape the pitch investors actually want to read. From structured slides to aligned financials, Upmetrics gives you the full setup to get pitch-ready so you can focus on pitching your plan to investors with clarity."
>
> **Action:** Add `[elementor-template id="44970"]` as the very last line of content.

---

**CTAs removed:** #2 (after Product slide) and #4 (after "zero revenue" section) — too close to other CTAs, identical message.

---

## Task 3: Downloadable Resource CTA

**Recommendation:** Set the "Investor Pitch Templates" download as the Resource Hero CTA.

| Field | Value |
|-------|-------|
| **Resource** | Investor Pitch Templates |
| **Post ID** | 7335 |
| **URL** | https://upmetrics.co/download/investor-pitch-templates |
| **heading** | `Investor Pitch Deck Templates` |
| **resource_link_text** | `Download Template` |
| **Combined display** | "Download Template: Investor Pitch Deck Templates" (49 chars ✓) |

This download is already linked in the post as an inline CTA, but the ACF Resource Hero banner (which appears prominently above the fold) is not set. Setting it adds a high-visibility conversion element without duplicating — the inline CTA and the hero banner serve different positions on the page.

---

## Task 4: Related Content

Post type `post` supports related content.

| # | Post ID | Suggested Title | Raw Title | URL |
|---|---------|----------------|-----------|-----|
| 1 | 96035 | What Do Investors Actually Want? | What Investors Want to See in Pitch Decks That Get Funded | /blog/what-investors-want-to-see-in-pitch-decks |
| 2 | 84221 | What Is a Pitch Deck, Really? | What Is a Pitch Deck? Everything Need to Know | /blog/what-is-a-pitch-deck |
| 3 | 95967 | Nailing Your Team Slide | How to Design the Perfect Team Slide | /blog/team-slide-pitch-deck |
| 4 | 91714 | Funding Rounds, Explained | What are Funding Rounds? (Key Stages for Founders) | /blog/funding-rounds |

**Deduplication:** Items #1–4 are not used by Tasks 1, 2, or 3. All clear.

---

## Task 5: Meta Title & Description

No SEO fields are currently set on this post (empty meta title, description, and focus keyphrase). This is a major gap — Google is using the post title as the SERP title, which is suboptimal for CTR.

### Meta Title

| | Value | Chars |
|--|-------|:-----:|
| **Current** | *(empty — using post title)* Build a Pitch Deck Outline That Gets Investor Attention | 54 |
| **Suggested** | Pitch Deck Outline: 14 Slides to Win Investor Attention | 56 |

Primary keyword "pitch deck outline" in first 22 characters. Includes hook (14 Slides). Under 60 chars ✓

### Meta Description

| | Value | Chars |
|--|-------|:-----:|
| **Current** | *(empty)* | — |
| **Suggested** | Build a pitch deck outline that investors want to see. Walk through all 14 slides, what each one does, and how to structure your startup story. | 143 |

Includes primary keyword in first 45 chars. Clear value proposition. Under 160 chars ✓

### SERP Preview

```
Pitch Deck Outline: 14 Slides to Win Investor Attention
upmetrics.co › blog › pitch-deck-outline
Build a pitch deck outline that investors want to see. Walk through all 14
slides, what each one does, and how to structure your startup story.
```

### Other SEO Fields

| Field | Suggested Value |
|-------|----------------|
| **Focus Keyphrase** | `pitch deck outline` (pos 68 → large opportunity) |
| **Canonical URL** | https://upmetrics.co/blog/pitch-deck-outlline *(update to new slug if Task 7 approved)* |
| **OG Title** | Pitch Deck Outline: 14 Slides to Win Investor Attention |
| **OG Description** | Build a pitch deck outline that investors want to see. Walk through all 14 slides, what each one does, and how to structure your startup story. |

---

## Task 6: Image Alt Text

| # | Image File | Current Alt | Suggested Alt | Issue |
|---|-----------|-------------|---------------|-------|
| 1 | components-of-a-pitch-deck.webp | "components of a pitch deck" | "14 components of a pitch deck outline" | Missing "outline" context |
| 2 | what-to-do-it-you-re-too-early.webp | "what to do it you re too early" | "what to do if you're too early for every pitch deck section" | **Typo** — "it" should be "if" |

*CTA images (ai-assistant-blog) are in legacy CTA blocks being replaced — new CTAs will have correct alt text from the templates.*

---

## Task 7: URL Slug

**This is the #1 SEO issue on this page.**

| | Value |
|--|-------|
| **Current slug** | `pitch-deck-outlline` (**TYPO** — double L) |
| **Suggested slug** | `pitch-deck-outline` |
| **Target keyword** | "pitch deck outline" (position 68 — currently ranking for wrong URL pattern) |

**Why this matters:** The slug signals keyword relevance to Google. The current URL contains `outlline` (double L) which doesn't match the search query "pitch deck outline". This mismatch is a direct contributor to the page ranking at position 68 instead of page 1.

**Risk assessment:** GSC position = 68 (well below position 15 threshold). Page has ~0 organic clicks. **Safe to change.**

**Required action:** Set up a 301 redirect from `/blog/pitch-deck-outlline` → `/blog/pitch-deck-outline` before or immediately after the slug change. Without the redirect, any existing backlinks or bookmarks will 404.

**If slug is changed:** Update the canonical URL in Task 5 to `https://upmetrics.co/blog/pitch-deck-outline`.

---

## Task 8: Heading Structure

Heading hierarchy is clean. One optional improvement:

| # | Current | Suggested | Reason |
|---|---------|-----------|--------|
| 1 | "The bottom line" (H2) | "Ready to Build Your Pitch Deck?" | Generic closing; suggested version adds a conversion hook |

No structural issues (no skipped levels, no duplicate headings, primary keyword in first H2).

---

## Task 9: Categories

| Current | Recommendation |
|---------|---------------|
| Funding | Keep as-is |

"Funding" is the correct primary category. Pitch decks are fundraising tools — no change needed.

---

## How to Respond

Copy, modify, and paste this template:

```
Task 1 (Internal Links): Approve #1 and #2.
Task 2 (CTAs): Replace CTA #1 with Type 11. Replace CTA #3 with Type 8 after slide 14. Remove CTAs #2 and #4. Add Elementor at end.
Task 3 (Resource CTA): Approve investor-pitch-templates.
Task 4 (Related Content): Approve items #1-#4.
Task 5 (Meta): Approve suggested title, description, and focus keyphrase.
Task 6 (Image Alt): Approve both updates.
Task 7 (Slug): Approve — will set up 301 redirect.
Task 8 (Headings): Approve H2 change. / Skip.
Task 9 (Categories): Skip.

Or simply: "Approve all" / "Approve all except Task 7"
```
