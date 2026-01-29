# Neural Computation & Cognition Lab Website

A simple, elegant research lab website inspired by the eliatorre.com design system.

---

## Proposed Changes

### Project Structure

```
ncc/
├── index.html          # Homepage
├── research.html       # Research page
├── team.html           # Team page
├── workwithus.html     # Work with Us page
└── styles.css          # Shared styles
```

---

### Design System (from eliatorre.com)

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#111213` | Dark background |
| `--fg` | `#ebe7e2` | Primary text |
| `--fg-soft` | `#cfc9c1` | Secondary text |
| `--muted` | `#8c8780` | Muted text |
| `--rule` | `#2a2b2c` | Divider lines |
| `--accent` | `#b86a4b` | Accent color |
| `--icon` | `#eae5df` | Link/icon color |
| `--icon-hover` | `#d9a892` | Hover state |

**Typography:**
- Headings: EB Garamond (serif)
- Body: Fira Code (monospace)

---

### [NEW] `styles.css`

Shared stylesheet with:
- CSS custom properties for design tokens
- Base typography and reset
- Header component (lab name left, navigation right)
- Two-column layout for homepage (text left, animation space right)
- Page layout components
- Responsive breakpoints

---

### [NEW] `index.html`

Homepage with:
- **Header**: "Neural Computation & Cognition" (top-left)
- **Navigation**: Research | Team | Work with Us (top-right)
- **Main content**: Two-column grid
  - Left column: Lab description text
  - Right column: Empty `<div class="animation-container">` placeholder

---

### [NEW] `research.html`

Research page with:
- Same header layout
- Back link to home
- Placeholder sections for research areas

---

### [NEW] `team.html`

Team page with:
- Same header layout
- Back link to home
- Placeholder sections for team members

---

### [NEW] `workwithus.html`

Work with Us page with:
- Same header layout
- Back link to home
- Placeholder content for open positions/opportunities

---

## Verification Plan

### Browser Testing

1. Open homepage in browser and verify:
   - Lab name appears top-left
   - Navigation links appear top-right
   - Lab description text is on center-left
   - Right side is empty (reserved for animation)

2. Click each navigation link and verify correct page loads

3. Verify responsive layout at mobile breakpoint (≤640px)

### Manual Verification

After implementation, open the site in the browser tool to capture screenshots showing:
- Homepage layout
- Navigation functionality
- Responsive behavior
