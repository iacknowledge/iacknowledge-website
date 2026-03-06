# PRD: Homepage Redesign — Above-the-Fold Layout

## Overview

Redesign the iacknowledge.ai landing page so all key information is visible immediately without scrolling. The current full-viewport hero pushes content below the fold. The new layout uses a compact hero followed by a two-column content grid, matching a user-provided design mockup.

## Problem Statement

The current homepage has a full-height (`min-height: 100vh`) hero section that fills the entire viewport. Users must scroll to see what iacknowledge.ai does, contact info, and legal links. The business wants a "bam, you see everything" experience on load.

## Solution

Restructure the page into three zones:

1. **Compact Hero** — Green background, logo + tagline + CTA, ~30-40vh tall
2. **Two-Column Content Grid** — White background, all info visible at once
   - Left column: What We Do + SMS Communications
   - Right column: Contact + Business Hours (new) + Legal (new)
3. **Footer** — Unchanged dark green footer

### Additional Changes
- Switch font from Familjen Grotesk → DM Sans
- Center all content (design mockup was slightly left-aligned)
- Use existing `icon.png` (not the placeholder checkmark in the mockup)
- Add "Business Hours" section: Monday – Friday, 9:00 AM – 5:00 PM EST
- Add "Legal" section with Privacy Policy and Terms of Service links

## Scope

### In Scope
- [ ] Compact hero (remove full-height)
- [ ] Two-column content layout below hero
- [ ] Font swap to DM Sans
- [ ] Center alignment for all content
- [ ] New "Business Hours" section
- [ ] New "Legal" section
- [ ] Responsive: columns stack on mobile

### Out of Scope
- Privacy/Terms pages (no changes)
- New images or icons
- JavaScript or interactivity

## Success Criteria
- [ ] All content visible above fold on 1080p+ screens
- [ ] Font is DM Sans throughout
- [ ] Two-column layout matches design mockup
- [ ] Content is horizontally centered
- [ ] Page remains responsive on mobile (columns stack)
- [ ] Existing links (email, phone, privacy, terms) still work
