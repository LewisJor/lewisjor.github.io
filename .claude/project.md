# Project Overview

This is Jordan Lewis's personal blog and portfolio website, deployed at https://jordanlewis.github.io/

## Purpose

A professional portfolio and blog showcasing work in:
- Machine Learning Engineering
- MLOps and infrastructure
- Defense technology
- Edge computing and distributed systems

## Owner Background

Jordan Lewis is a Senior ML Engineer with:
- Military service: 3rd Battalion, 5th Marine Regiment (2011-2015)
- Education: Master's in Data Analytics from University of Wisconsin-Madison
- Focus areas: MLOps platforms, edge computing, defense applications of AI/ML
- Technical stack: Python, C++, Rust, TypeScript, PyTorch, TensorFlow, Kubernetes

## Technology Stack

- **Static Site Generator**: Hugo (Extended v0.112.0+)
- **Theme**: Custom theme (`jl-theme`) with tactical/defense-tech aesthetic
- **Styling**: Dark theme with amber (#f0a500) accents and tactical green (#2ea043)
- **Syntax Highlighting**: Dracula theme
- **Deployment**: GitHub Pages via GitHub Actions
- **Repository**: jordanlewis.github.io

## Site Structure

### Content Types

1. **Blog Posts** (`content/posts/`)
   - Technical articles and thought leadership
   - Tags and categories for organization

2. **Projects** (`content/projects/`)
   - Portfolio pieces showcasing work
   - Includes tech stack, GitHub links, demo links

3. **About Page** (`content/about.md`)
   - Professional background and skills
   - Current focus areas
   - Contact information

### Navigation

- Home (/)
- Projects (/projects/)
- Blog (/posts/)
- About (/about/)

## Development Workflow

- Run locally: `hugo server -D`
- Build for production: `hugo --minify`
- Content creation: `hugo new posts/title.md` or `hugo new projects/title.md`
- Auto-deploy on push to main branch

## Design Philosophy

- Tactical, defense-tech inspired aesthetic
- Clean, professional presentation
- Fast, minimal JavaScript
- Mobile responsive
- SEO optimized

## Key Considerations

- Maintain professional tone appropriate for defense/security sector
- Focus on technical depth and real-world applications
- Keep content aligned with ML/MLOps, edge computing, and defense tech themes
- Preserve the dark tactical aesthetic when making design changes
- Ensure all external links use HTTPS
- Content should reflect expertise in mission-critical systems
