
# AgriDirect SA · "Glasshouse" redesign

Open `Index.html` in any modern browser. Plain HTML / CSS / JS, no frameworks, no build step.

## What's new
- **Collapsible sidebar**: icon button (top-left) shrinks the sidebar to an icon rail with tooltips; on phones it becomes a slide-out drawer. Remembers your choice.
- **Light / dark mode**: sun/moon toggle (top-right) with a ripple-wipe transition. Follows your system setting until you pick one, then remembers it.
- **Blurred background on every page**: each page sits on a slowly drifting, heavily blurred photo of its own produce + soft colour blobs + film grain, with frosted-glass panels on top.
- **Quote basket**: "Add to quote" flies the item into the basket, adjust quantities in the drawer, then "Request one combined quote" pre-fills the Enquiry form.
- **Quick view** pop-up on every product, favourites (heart), live search, category chips, sort, grid/list toggle, empty state.
- **Command palette**: Ctrl/Cmd + K or "/" searches pages, produce and actions.
- **Forms**: live validation (SA phone format, email), progress bar, character counter, shake on error, success card with reference number. Toast notifications replace alert().
- Home: animated hero, live price ticker, count-up stats, harvest calendar (current month highlighted), rotating testimonials.
- About: timeline + animated impact ring. Contact: open-now badges, copy-email buttons, FAQ accordion, dark-mode maps.
- Scroll progress bar, back-to-top ring, scroll reveal, 3D card tilt, cursor glow, first-visit preloader.
- Accessibility: skip link, focus rings, ARIA states, keyboard support, `prefers-reduced-motion` respected.
- Performance: photos compressed from 38 MB to about 3 MB (same filenames).

## Keyboard shortcuts
`Ctrl K` or `/` search · `T` theme · `[` sidebar · `B` basket · `1`–`5` jump to page · `Esc` close
