# Improvement Plan: Blog

## Overview
Static article archive with no discoverability, search, or cross-linking between articles. Content is only browsable by navigating the folder tree.

## Improvements

### Discoverability & Navigation
- Add a root-level `README.md` or `index.md` listing all articles with titles, dates, and one-line summaries
- Add cross-references between related articles (e.g., C# series linking to each other)
- Tag articles by topic (C#, Azure, WCF, JS) and generate a topic index

### Content Modernization
- Review articles from 2011–2013 for outdated information (e.g., deprecated .NET APIs, ES3-era JS) and add deprecation notices
- Add "Updated for .NET 8 / ES2023" notes where content was later superseded

### Static Site Generator
- Migrate to a static site generator (e.g., Hugo, MkDocs, or Docusaurus) to generate a proper browsable site from the Markdown/code files
- Add syntax highlighting for code samples

### DevOps
- Add GitHub Actions workflow to lint Markdown and validate internal links
- Deploy the generated site to GitHub Pages automatically on push to `main`

### Repository Hygiene
- Run `git submodule update --init --recursive` and document submodule usage in the README
- Remove or archive year folders with no content
