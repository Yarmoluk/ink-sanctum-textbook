# Ink Sanctum

[![MkDocs](https://img.shields.io/badge/Made%20with-MkDocs-526CFE?logo=materialformkdocs)](https://www.mkdocs.org/)
[![Material for MkDocs](https://img.shields.io/badge/Material%20for%20MkDocs-526CFE?logo=materialformkdocs)](https://squidfunk.github.io/mkdocs-material/)
[![GitHub Pages](https://img.shields.io/badge/View%20on-GitHub%20Pages-blue?logo=github)](https://yarmoluk.github.io/ink-sanctum-textbook/)
[![GitHub](https://img.shields.io/badge/GitHub-Yarmoluk%2Fink--sanctum--textbook-blue?logo=github)](https://github.com/Yarmoluk/ink-sanctum-textbook)
[![Claude Code](https://img.shields.io/badge/Built%20with-Claude%20Code-DA7857?logo=anthropic)](https://claude.ai/code)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## View the Live Site

Visit the interactive textbook at: [https://yarmoluk.github.io/ink-sanctum-textbook/](https://yarmoluk.github.io/ink-sanctum-textbook/)

## Overview

**Ink Sanctum** is a comprehensive, AI-generated intelligent textbook covering tattoo preparation, aftercare, and long-term preservation. Built using MkDocs with the Material theme, it provides evidence-based protocols grounded in wound healing science to help tattoo clients achieve optimal results.

This guide covers the complete tattoo journey—from pre-appointment preparation through the entire healing process and into decades of maintenance. Whether you're getting your first tattoo or adding to an existing collection, Ink Sanctum provides the knowledge you need to protect your investment in body art.

The textbook features:

- **12 comprehensive chapters** covering skin anatomy, healing phases, hygiene, aftercare products, and long-term care
- **200 concepts** organized in a learning graph with proper prerequisite sequencing
- **45 interactive diagram specifications** for MicroSims, infographics, and visual aids
- **198 glossary terms** with ISO 11179-compliant definitions
- **66 FAQ questions** addressing common concerns

## Site Metrics

| Metric | Count |
|--------|-------|
| Chapters | 12 |
| Concepts in Learning Graph | 200 |
| Glossary Terms | 198 |
| FAQ Questions | 66 |
| Diagram Specifications | 45 |
| Total Words | 60,395 |
| Equivalent Pages | 252 |

## Chapter Overview

1. **Skin Anatomy Fundamentals** - Understanding how tattoos work at the skin level
2. **The Healing Process** - Week-by-week guidance through all healing stages
3. **Hygiene & Aftercare Products** - Choosing and using the right products
4. **Washing & Moisturizing** - Proper daily care techniques
5. **Healing Signs & Warnings** - Knowing what's normal vs. what needs attention
6. **Hydration & Nutrition** - Pre-appointment preparation
7. **Physical Preparation & Clothing** - Getting ready for your session
8. **Pain Management** - Strategies for a more comfortable experience
9. **Health Screening** - Medical factors that affect tattoo timing
10. **Activity Restrictions** - What to avoid during healing
11. **Sun Protection & UV Care** - Preserving your tattoo from UV damage
12. **Long-Term Preservation** - Maintaining your tattoo for decades

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Yarmoluk/ink-sanctum-textbook.git
cd ink-sanctum-textbook
```

### Install Dependencies

This project uses MkDocs with the Material theme:

```bash
pip install mkdocs-material
```

### Build and Serve Locally

Serve locally for development (with live reload):

```bash
mkdocs serve
```

Open your browser to `http://localhost:8000`

### Deploy to GitHub Pages

The site automatically deploys to GitHub Pages via GitHub Actions when changes are pushed to the `main` branch.

## Repository Structure

```
ink-sanctum-textbook/
├── docs/                           # MkDocs documentation source
│   ├── chapters/                   # Chapter content (12 chapters)
│   │   ├── 01-skin-anatomy-fundamentals/
│   │   ├── 02-healing-process/
│   │   └── ...
│   ├── learning-graph/             # Learning graph data and metrics
│   │   ├── concept-list.md         # 200 concepts
│   │   ├── book-metrics.md         # Overall book statistics
│   │   └── chapter-metrics.md      # Per-chapter breakdown
│   ├── course-description.md       # Course overview and learning outcomes
│   ├── glossary.md                 # 198 defined terms
│   ├── faq.md                      # 66 frequently asked questions
│   └── index.md                    # Home page
├── .github/workflows/              # GitHub Actions for deployment
│   └── deploy.yml
├── mkdocs.yml                      # MkDocs configuration
└── README.md                       # This file
```

## Reporting Issues

Found a bug, typo, or have a suggestion for improvement? Please report it:

[GitHub Issues](https://github.com/Yarmoluk/ink-sanctum-textbook/issues)

When reporting issues, please include:

- Description of the problem or suggestion
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Screenshots (if applicable)

## License

This work is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

**You are free to:**

- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

**Under the following terms:**

- **Attribution** — Give appropriate credit with a link to the original
- **NonCommercial** — No commercial use without permission
- **ShareAlike** — Distribute contributions under the same license

## Acknowledgements

This project is built on the shoulders of giants in the open source community:

- **[MkDocs](https://www.mkdocs.org/)** - Static site generator optimized for project documentation
- **[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)** - Beautiful, responsive theme
- **[Claude AI](https://claude.ai)** by Anthropic - AI-assisted content generation
- **[GitHub Pages](https://pages.github.com/)** - Free hosting for open source projects

## Contact

Questions, suggestions, or collaboration opportunities? Feel free to open an issue on GitHub.

---

*Ink Sanctum is an intelligent textbook built with evidence-based protocols grounded in wound healing science.*
