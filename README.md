# SEO & Content Toolkit — Team Guide

This repo stores auto-generated reports from our SEO tools. Every time you run a tool, the output report appears here — click any `.md` file to view it formatted in your browser.

---

## Our Brands

| Brand | Website | Focus |
|-------|---------|-------|
| **Upmetrics** | upmetrics.co | Business planning software |
| **Bizplanr** | bizplanr.ai | AI business plan generator |

Both brands share the same toolkit. The brand is detected automatically based on your input.

---

## Available Tools

### 1. Content Brief

Creates a complete, data-driven SEO content brief for a new keyword. Use this **before** a writer starts working on a new article.

| | Details |
|---|---|
| **When to use** | You have a new keyword and need a brief for a writer |
| **What you provide** | Just the keyword (e.g., `how to write a business plan`) |
| **What you get** | A detailed brief with target word count, headings, competitor analysis, search intent, and content guidelines |
| **Output format** | `.md` report + `.docx` file (uploaded to Google Drive) |
| **Brand** | Claude will ask you which brand |

**How to run:**
```
cd ~/Documents/Claude/Upmetrics/content-brief
claude
Brief: how to write a business plan
```

**Reports saved to:** [`content-brief/`](./content-brief/)

---

### 2. Content Review

Reviews a draft written by a writer — finds factual errors, grammar issues, SEO gaps, and suggests improvements. Returns a marked-up document with comments.

| | Details |
|---|---|
| **When to use** | A writer has submitted a draft and you need to review it before publishing |
| **What you provide** | A Google Doc link or `.docx` file path |
| **What you get** | A review summary with issues found, suggestions, and a marked-up document |
| **Output format** | `.md` review summary + reviewed `.docx` with inline comments |
| **Brand** | Auto-detected from the document content |

**How to run:**
```
cd ~/Documents/Claude/Upmetrics/content-review
claude
Review this: https://docs.google.com/document/d/YOUR_DOC_ID/edit
```

**Reports saved to:** [`content-review/`](./content-review/)

---

### 3. Page Draft

Converts an approved document into a fully formatted WordPress draft post. Handles all formatting, images, CTAs, categories, tags, SEO fields, and FAQs.

| | Details |
|---|---|
| **When to use** | The article is reviewed, approved, and ready to publish |
| **What you provide** | A Google Doc link or `.docx` file path |
| **What you get** | A WordPress draft post — fully formatted and ready to review in WordPress |
| **Output format** | WordPress draft (with post URL and edit URL) |
| **Brand** | Auto-detected from the document content |

**How to run:**
```
cd ~/Documents/Claude/Upmetrics/page-draft
claude
Draft this: https://docs.google.com/document/d/YOUR_DOC_ID/edit
```

**No report in this repo** — output goes directly to WordPress.

---

### 4. On-Page SEO

Analyzes a live page and applies SEO fixes directly to WordPress. Sets internal links, CTAs, related posts, meta tags, and more.

| | Details |
|---|---|
| **When to use** | A page is published and needs SEO optimization |
| **What you provide** | The page URL |
| **What you get** | Direct fixes applied to the live page + a change report |
| **Output format** | `.md` change report listing everything that was modified |
| **Brand** | Auto-detected from the URL |

**How to run:**
```
cd ~/Documents/Claude/Upmetrics/on-page-seo
claude
Optimize: https://upmetrics.co/blog/your-page-slug
Optimize: https://bizplanr.ai/blog/your-page-slug
```

**Reports saved to:** [`on-page-seo/`](./on-page-seo/)

---

### 5. Page Audit

Performs a comprehensive SEO and content audit of a live page. Produces detailed reports with recommendations — does NOT make any changes to the page.

| | Details |
|---|---|
| **When to use** | You want to understand how a page is performing and what can be improved |
| **What you provide** | The page URL |
| **What you get** | Three reports: full audit, action items, and an update brief for writers |
| **Output format** | 3 separate `.md` reports |
| **Brand** | Auto-detected from the URL |

**How to run:**
```
cd ~/Documents/Claude/Upmetrics/page-audit
claude
Audit: https://upmetrics.co/blog/your-page-slug
Audit: https://bizplanr.ai/blog/your-page-slug
```

**Reports saved to:** [`page-audit/`](./page-audit/) (one subfolder per page with 3 files)

---

## Typical Workflow

Here's the recommended order for a new article from start to finish:

```
Step 1  →  Content Brief      →  Creates the brief for a new keyword
Step 2  →  Writer writes the article using the brief
Step 3  →  Content Review      →  Reviews the writer's draft, adds feedback
Step 4  →  Writer makes revisions based on feedback
Step 5  →  Page Draft          →  Publishes the approved article to WordPress
Step 6  →  On-Page SEO         →  Applies SEO fixes (links, CTAs, meta tags)
```

For **existing pages** that need improvement:
```
Page Audit    →  Get a full analysis with recommendations
On-Page SEO   →  Apply fixes directly to the page
```

---

## Which Tool Should I Use?

| I want to... | Use this tool |
|---|---|
| Plan a new article for a keyword | **Content Brief** |
| Check a writer's draft before publishing | **Content Review** |
| Publish an approved article to WordPress | **Page Draft** |
| Fix SEO issues on a live page | **On-Page SEO** |
| Get a full analysis of a live page (no changes) | **Page Audit** |

---

## Key Differences

| Question | Answer |
|----------|--------|
| **Content Brief vs Page Audit?** | Brief = for NEW keywords (no page exists yet). Audit = for EXISTING pages that need improvement. |
| **On-Page SEO vs Page Audit?** | On-Page SEO = makes direct fixes to the live page. Page Audit = produces a report only (no changes). |
| **Content Review vs Page Draft?** | Review = checks quality BEFORE publishing. Draft = converts to WordPress AFTER review is done. |

---

## Updating Tools

If someone from the team tells you to update, just type this in Claude Code:

```
update tools
```

Claude will pull the latest changes automatically.

---

## Report Folders

| Folder | Tool | What's Inside |
|--------|------|---------------|
| [`content-brief/`](./content-brief/) | Content Brief | Keyword research briefs (`.md`) |
| [`content-review/`](./content-review/) | Content Review | Draft review summaries (`.md`) |
| [`on-page-seo/`](./on-page-seo/) | On-Page SEO | SEO change reports (`.md`) |
| [`page-audit/`](./page-audit/) | Page Audit | Full audit reports — 3 files per page |

Click any `.md` file to view it formatted in your browser.
