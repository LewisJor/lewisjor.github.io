# Jordan Lewis Portfolio

Personal portfolio and blog built with [Hugo](https://gohugo.io/), featuring a tactical defense-tech inspired design.

## Quick Start

### Prerequisites
- [Hugo Extended](https://gohugo.io/installation/) v0.112.0+
- Git

### Development
```bash
hugo server -D
# View at http://localhost:1313
```

### Creating Content
```bash
hugo new posts/my-post.md      # New blog post
hugo new projects/my-project.md # New project
```

### Build
```bash
hugo --minify
```

## Deployment

1. Push to GitHub repository
2. Enable GitHub Pages: Settings → Pages → Source: **GitHub Actions**
3. Update `baseURL` in `hugo.toml`:
   ```toml
   baseURL = 'https://YOUR_USERNAME.github.io/'
   ```
4. Push changes - GitHub Actions will auto-deploy

## Customization

**Site config:** Edit `hugo.toml`  
**Colors:** Edit `themes/jl-theme/static/css/style.css` CSS variables  
**Profile image:** Add `static/images/profile.jpg` (280x280px)

## Content Format

**Posts:**
```yaml
---
title: "Post Title"
date: 2024-01-15
tags: ["tag1", "tag2"]
---
```

**Projects:**
```yaml
---
title: "Project Name"
tech: ["Python", "Kubernetes"]
github: "https://github.com/user/repo"
---
```

## Structure

```
content/          # Edit your content here
  ├── posts/      # Blog posts
  ├── projects/   # Project pages
  └── about.md    # About page
themes/jl-theme/  # Theme templates & CSS
hugo.toml         # Site configuration
```

---

Built with [Hugo](https://gohugo.io/). MIT License.
