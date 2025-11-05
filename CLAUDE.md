# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages website (jikhanjung.github.io) showcasing paleontology software tools. The site uses Jekyll with the "hacker" theme and is configured to serve a custom HTML landing page.

## Architecture

The repository is a simple static website with minimal structure:

- **index.html**: Main landing page with embedded CSS - a Korean/English bilingual showcase page for paleontology software (Modan2 and CTHarvester)
- **index.md**: Legacy markdown file (not currently used in favor of index.html)
- **_config.yml**: Jekyll configuration specifying the theme
- **README.md**: Standard GitHub Pages boilerplate documentation

The site is deployed automatically via GitHub Pages when changes are committed to the main branch.

## Development

### Local Testing

To test the site locally with Jekyll:

```bash
# Install Jekyll and dependencies (first time only)
gem install bundler jekyll

# Serve the site locally
jekyll serve
```

The site will be available at `http://localhost:4000`

### Deployment

Changes pushed to the `main` branch are automatically deployed to GitHub Pages. No build commands are needed - GitHub handles the Jekyll build process.

### Making Changes

When editing index.html:
- The page is bilingual (Korean/English) - maintain both language versions
- CSS is embedded in the HTML file (lines 7-136)
- The design uses a gradient background with a card-based layout
- Software cards are displayed in a responsive grid (grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)))
