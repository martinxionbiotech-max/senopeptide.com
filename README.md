# SENO Biotechnology — Technical Documentation

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-FF5252?style=flat&logo=materialformkdocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

Technical documentation for **Zhangjiakou SENO Biotechnology Co., Ltd.** — peptide manufacturing processes, equipment specifications, quality systems, and technology platforms.

## Live Site

**Production**: https://docs.senopeptide.com (Cloudflare Pages)

## Tech Stack

- **Framework**: [MkDocs](https://www.mkdocs.org/) 1.6+
- **Theme**: [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 9.7+
- **Hosting**: Cloudflare Pages (auto-deploy from GitHub)

## Project Structure

```
seno-docs/
├── mkdocs.yml              # Main configuration
├── requirements.txt        # Python dependencies (mkdocs + mkdocs-material)
├── .gitignore              # Excludes site/ and cache files
├── overrides/
│   └── main.html           # JSON-LD Schema + OG meta injection template
└── docs/
    ├── index.md            # Home page with equipment matrix
    ├── faq/                # FAQ page with FAQPage Schema
    ├── equipment/          # 14 equipment types (Spec + SOP per system)
    ├── processes/          # 15 technical process documents
    ├── quality/            # QMS, method validation, reference standards
    ├── platforms/          # SDP™ and MAP-VLP platform docs
    ├── safety/             # Chemical safety, waste disposal, training
    ├── about/              # Manufacturing capabilities, contact
    ├── llms.txt            # Concise AI reference (43 lines)
    ├── llms-full.txt       # Complete AI reference (194 lines)
    ├── robots.txt          # Tiered AI crawler access control
    ├── tags.md             # Content tag index
    └── assets/images/      # Logo and favicon
```

**Total**: 60 Markdown files, 3,584 lines of technical documentation.

## Local Development

```bash
# Install
pip install -r requirements.txt

# Build (outputs to site/)
mkdocs build

# Live preview
mkdocs serve
```

## Deployment (Cloudflare Pages)

| Setting | Value |
|---|---|
| Build command | `pip install -r requirements.txt && mkdocs build` |
| Output directory | `site` |
| Python version | 3.x (Cloudflare default) |

### GitHub Setup

```bash
# Initialize and push
git init
git add .
git commit -m "Initial commit: SENO Biotechnology technical docs"
git remote add origin https://github.com/YOUR_ORG/seno-docs.git
git push -u origin main
```

Then connect the repo to Cloudflare Pages via the Cloudflare Dashboard → Pages → Connect to Git.

## Schema & SEO Architecture

Every page includes structured JSON-LD schema:

| Schema Type | Coverage | Purpose |
|---|---|---|
| Organization | All pages | Knowledge Graph entity |
| WebSite + SearchAction | All pages | Authority flow to main site |
| TechArticle | Equipment, Processes, Quality, Platforms | AI search indexing |
| HowTo | SOP pages | Google How-To rich results |
| FAQPage | /faq/ | Google FAQ rich results |

Authority flows: **Docs → Main Website** (all Schema.author + Schema.publisher anchor to senopeptide.com)

## V12 Compliance

This project follows the V12 Enterprise Knowledge Authority Engine specification:

- **Production First**: Only mkdocs + mkdocs-material dependencies
- **Zero Error**: Passes `mkdocs build` with no warnings or errors
- **Main Website First**: Every page links back to senopeptide.com
- **Human Expert Writing**: Technical, dense, authoritative tone
- **GEO & Knowledge Graph**: Schema.org JSON-LD on every page

---

© 2026 Zhangjiakou SENO Biotechnology Co., Ltd. All rights reserved.
