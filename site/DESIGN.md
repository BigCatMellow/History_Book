# Interactive Textbook Design — Party Realignment

- Surface: `site/party-realignment.html`
- Product truth: the page teaches a novice reader how American party coalitions changed without asking them to absorb a wall of text.
- Design target: **mobile-first, Playskool-simple, textbook-serious**.
- Canonical content: [How America's Political Parties Changed](../book/entries/how-americas-political-parties-changed.md)

## Design Bible sources used

- [Project Package](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/PROJECT-PACKAGE.md)
- [Foundations](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/FOUNDATIONS.md)
- [Interaction and Information](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/INTERACTION-AND-INFORMATION.md)
- [Visual Systems](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/VISUAL-SYSTEMS.md)
- [Accessibility](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/ACCESSIBILITY.md)
- [Anti-Patterns](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/ANTI-PATTERNS.md)

## Product priorities

```text
novice comprehension > density
historical neutrality > partisan visual shorthand
linear reading flow > dashboard/card layout
recognition > recall
progressive disclosure > footnote clutter
large touch targets > compact chrome
content hierarchy > decoration
```

## Visual direction

### Tone

- friendly;
- substantial;
- uncomplicated;
- editorial rather than app-dashboard;
- classroom clarity without looking juvenile.

### Typography

- body/UI: **Inter** with system sans fallback for highly legible reading and controls;
- chapter/display headings: **Source Serif 4** with Georgia fallback, creating a clearer editorial/textbook voice;
- labels, controls, and metadata remain sans-serif so hierarchy is visible before the reader processes the words;
- body prose stays on a narrower reading measure while diagrams, comparisons, and teaching tiles may use the wider content column;
- avoid forcing paragraph-like copy into small concept tiles. Tile descriptors should be short noun phrases or one compact sentence.

### Color

Do **not** use contemporary red-vs-blue party coding as the primary visual language.

Use a neutral educational palette:

- warm paper background;
- dark ink;
- slate/navy structural color;
- gold for emphasis;
- mint/lavender/clay for concept groups.

Color never carries political meaning by itself.

### Shape and depth

- moderate radius only on true independent objects;
- compact teaching tiles use tighter radii and shallow physical depth;
- major historical transitions may use an occasional larger “era shift” surface;
- no card soup and no nested card stacks;
- dividers, type scale, full-width background rhythm, and spacing carry most hierarchy;
- the hero may use a subtle textbook-grid pattern because it establishes page identity and orientation rather than acting as generic decoration.

## Information architecture

The page is one reading path, with a small horizontally scrollable era navigator for orientation rather than tabbed content:

```text
hero / big idea
→ four-layer party model
→ Democrats vs Whigs
→ slavery breaks the old system
→ new Republicans
→ emancipation / Reconstruction
→ mixed-party mid-century politics
→ New Deal
→ 1948
→ 1960 / 1964
→ gradual Southern realignment
→ race and other causes
→ ideological sorting
→ slogan check
→ modern reading rule
→ transfer exercise
```

The reader can skim section labels, but no tab system fragments the story.

## Modal use

Modals are reserved for **bounded detours**:

1. **Party anatomy** — four-layer model.
2. **Glossary** — realignment, coalition, faction, ideology, Dixiecrat.
3. **Evidence & sources** — grouped source package.
4. **1964 coalition** — compact factual detail that would otherwise interrupt the main flow.

Use native `<dialog>` so keyboard/focus semantics are provided by the platform. Each dialog has:

- visible title;
- visible Close button;
- Escape behavior;
- backdrop;
- focus return after close;
- no essential primary reading hidden only in a modal.

## Mobile behavior

Base layout is designed for ~320–480px widths first.

- single column;
- minimum comfortable touch targets;
- no hover-only interactions;
- comparison tables become stacked comparison blocks;
- sticky reading-progress bar uses minimal height;
- long rows never require precise horizontal panning;
- dialogs become bottom-sheet-like on narrow screens but remain native dialogs.

At wider widths:

- content gains breathing room;
- selected comparisons become two-column;
- line length remains constrained.

## Accessibility

Target: WCAG 2.2 AA behavior.

- semantic headings and landmarks;
- skip link;
- native buttons/links/details/dialogs;
- visible focus;
- reduced-motion support;
- no color-only meaning;
- adequate target sizes;
- readable contrast;
- text survives zoom/reflow;
- modal background unavailable while open through native `showModal()`.

## Anti-pattern checks

Explicitly avoid:

- card soup;
- rounded-everything;
- giant SaaS hero;
- gradients for generic polish;
- icon tiles over every heading;
- low-contrast gray;
- hover-only content;
- decorative party red/blue;
- animation for its own sake;
- hiding necessary context in modals.

## Verification

Before calling the surface done:

- validate markup;
- inspect at narrow mobile width and desktop width;
- keyboard through all controls;
- open/close every dialog with keyboard;
- check focus visibility;
- check reduced-motion behavior;
- inspect at 200% zoom;
- confirm no source or interpretation wording changed from the canonical entry without updating the manuscript/source package.


## Spacing rule for teaching tiles

Small interactive concept boxes should not behave like miniature article cards.

For the four-part party model:

- keep title and descriptor visually close;
- remove forced tall minimum heights;
- use equal grid columns only when the copy comfortably fits;
- shorten descriptors rather than accepting ugly wrap fragments;
- let the surrounding grid create separation;
- preserve a minimum comfortable tap target through padding, not empty vertical space.

Preferred microcopy:

```text
Party      → The name and institution.
Coalition  → The voters and groups.
Faction    → Competing wings.
Ideology   → Political beliefs.
```

This follows the Design Bible's cognitive-load and anti-card-soup guidance: the tile's job is fast recognition and entry into a modal, not to carry explanatory prose.
