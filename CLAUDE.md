# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

iacknowledge.ai is a static marketing/landing site for an AI-native supply chain coordination platform. The site is plain HTML + CSS with no build system, framework, or JavaScript.

## Architecture

- `index.html` — Landing page with hero, about, SMS disclosure, contact, and footer sections
- `privacy.html` — Privacy policy page
- `terms.html` — Terms of service page
- `styles.css` — Single shared stylesheet for all pages

No build step, package manager, or dev server is required. Open HTML files directly in a browser to preview.

## Design Conventions

- Font: DM Sans (loaded from Google Fonts CDN)
- Primary brand color: `#3a7a3a` (green)
- Footer background: `#1a3a1a`
- Layout uses flexbox, no CSS grid
- Responsive sizing via `clamp()` for typography
- Policy pages use `.policy-page > .policy-inner` wrapper structure
- Disclosure boxes use `.disclosure-box` with `.blue` or `.green` modifier classes
- All pages share the same footer markup and link to `styles.css`
