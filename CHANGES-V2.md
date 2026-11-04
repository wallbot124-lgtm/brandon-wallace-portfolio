# Portfolio Prototype V2 — Changes

## Files Created
- `index-v2.html` — Updated homepage
- `work/skriber-v2.html` — Updated Skriber case study
- `styles-v2.css` — Updated styles with improvements

## Key Changes

### Homepage (`index-v2.html`)
1. ✅ **Fixed contact links** — Changed from `mailto:hello@example.com` to `bran.wall14@gmail.com`
2. ✅ **Removed broken Resume link** — Replaced with direct contact CTA
3. ✅ **Clarified credential bar** — Split into "Experience" (companies) and "Domains" (expertise areas)
4. ✅ **Improved flow diagram** — Added decision branch showing STT provider selection
5. ✅ **Added process explanation** — Concrete examples of discovery and MVP approach
6. ✅ **Shortened footer CTA** — More mobile-friendly phrasing

### Skriber Case Study (`work/skriber-v2.html`)
1. ✅ **Enhanced flow diagram** — Shows decision points (capture method, STT provider) with rationale
2. ✅ **Expanded technology table** — Added comparison across 5+ providers with actual criteria
3. ✅ **Added Deepgram decision reasoning** — Explicit "Why Deepgram" section with comparative analysis
4. ✅ **Added MVP prioritization rationale** — Explains why web-first, why EMR deferred
5. ✅ **Added "What I'd do differently" section** — Retrospective learning on validation, instrumentation, scope
6. ✅ **More specific validation details** — Changed vague "major health system" to concrete demo context
7. ✅ **Consistent flow diagrams** — Homepage and case study now match

### Styles (`styles-v2.css`)
1. ✅ **Button hover states** — Smooth transitions with opacity/transform
2. ✅ **Mobile nav breakpoint** — Keeps "Work" link visible until 600px (was 900px)
3. ✅ **Tighter mobile h1** — Case study heading starts at 42px (was 58px)
4. ✅ **New flow diagram styles** — Decision points, branch labels, deferred options
5. ✅ **Credential section grid** — Better responsive behavior
6. ✅ **Glance box mobile padding** — 16px on mobile (was 20px)
7. ✅ **TOC hover states** — Subtle color transition
8. ✅ **Card link animations** — Slide-right effect on hover

## Visual Improvements

### Decision Flow Diagrams
- Green highlight border for chosen solutions
- Gray deferred options
- Decision labels in uppercase micro-copy
- Vertical flow option for complex sequences

### Interactive States
- All buttons have smooth hover feedback
- Links transition smoothly
- Mobile-friendly touch targets

### Responsive Behavior
- Credential grid: 3 cols → 2 cols → 1 col
- Navigation: Full → Work only → Hamburger
- Decision flows: Horizontal → Vertical

## How to Review

1. Open `index-v2.html` in a browser
2. Compare side-by-side with `index.html`
3. Navigate to Skriber case study
4. Test mobile responsiveness (DevTools or resize)

## Next Steps

If approved:
1. Rename `-v2` files to production versions
2. Expand flow diagrams to Frequency UAM case
3. Build remaining case studies (LicenseHub, Sling Arcade)
4. Add snapshots detail pages (optional)
5. Final polish pass on copy
6. Export production build
