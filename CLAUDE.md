# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

K4fix is a static HTML landing page for an AI assistant with multiple specialized agents. The site showcases various AI agents for professional consultations including data protection, general meetings, document management, and more.

## Architecture & File Structure

**Working Directory:**
- `qore/` - Main directory containing the website
- `qore/index.html` - Main landing page
- `qore/asset/css/` - CSS stylesheets
- `qore/asset/js/` - JavaScript files (Vanilla JS, jQuery, GSAP, etc.)
- `qore/asset/images/` - Image assets
- `qore/asset/fonts/` - Font files
- `qore/asset/icon/` - Icon fonts

**Development Notes:**
- **IMPORTANT**: Work directly with files in the `qore/` directory
- No build process - all changes are made directly to HTML, CSS, and JavaScript files
- Open `qore/index.html` directly in browser to view changes
- No npm commands needed for development

## Key Technologies

**CSS Framework:**
- Bootstrap 5 (bootstrap.min.css)
- Animate.css for animations
- Custom styles (styles.css)
- Swiper bundle for sliders

**JavaScript Libraries:**
- jQuery (jquery.min.js)
- GSAP (gsap.min.js) - animations
- Bootstrap JS (bootstrap.min.js)
- Odometer (odometer.min.js) - number animations
- Lazysize (lazysize.min.js) - lazy loading images
- Custom scripts: main.js, carousel.js, ScrollSmooth.js, infinityslide.js

## Development Workflow

**Editing Files:**
- Edit HTML directly: `qore/index.html`
- Edit CSS files: `qore/asset/css/`
- All changes are immediate - just refresh the browser

**Asset Handling:**
- Images: Add to `qore/asset/images/`
- Fonts: Add to `qore/asset/fonts/`
- Icons: Icon fonts in `qore/asset/icon/`

## Git Workflow - IMPORTANT

**After making ANY code changes, you MUST:**
1. Stage the changes with `git add`
2. Create a commit with a clear message explaining the changes
3. Use the format: `git commit -m "Description of changes"`

**Example:**
```bash
git add qore/index.html
git commit -m "Actualizar logo responsive y mejorar estilos del header"
```

**Commit Message Guidelines:**
- Write in Spanish
- Be concise but descriptive
- Explain WHAT was changed and WHY
- Use imperative mood (e.g., "Actualizar", "Añadir", "Corregir")

**Do NOT push automatically** - only commit locally unless explicitly requested.