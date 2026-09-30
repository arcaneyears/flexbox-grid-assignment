# CSS Flexbox & Grid Assignment

A multi-page static website demonstrating layout with **Flexbox** and **CSS Grid**.
Every page shares a common navigation bar (Task 0) that links to each task.

**Live demo:** https://arcaneyears.github.io/flexbox-grid-assignment/

## Pages / Tasks

| Page | Task | Techniques |
|------|------|-----------|
| `index.html` | Task 0 — Navigation bar + task index | Flexbox navbar: logo left, links right, vertically centered, spacing via `gap` |
| `task1-cards.html` | Task 1 — Card row | Flex container, equal-height cards (`align-items: stretch`), consistent gaps, hover lift + shadow |
| `task2-layout.html` | Task 2 — Page layout with grid areas | `grid-template-areas`: header across the top, sidebar left, main right, footer across the bottom |
| `task3-gallery.html` | Task 3 — Image gallery | 3 equal-width grid columns, fixed rows, `gap`, caption overlay on hover |
| `task4-portfolio.html` | Task 4 — Portfolio page | Flexbox navbar + flex project cards, Grid main section (projects left, info sidebar right), full-width footer |

All styles live in `css/style.css`; images in `img/` are self-contained SVGs, so the
site works offline with no external dependencies.

## Run locally

No build step needed — it's plain HTML/CSS:

```bash
git clone https://github.com/arcaneyears/flexbox-grid-assignment.git
cd flexbox-grid-assignment
# open index.html in a browser, or serve it:
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
├── index.html            # Home + Task 0 navbar
├── task1-cards.html      # Task 1: Flexbox card row
├── task2-layout.html     # Task 2: Grid areas layout
├── task3-gallery.html    # Task 3: Grid image gallery
├── task4-portfolio.html  # Task 4: Flexbox + Grid portfolio
├── css/style.css         # All styles
└── img/                  # SVG placeholder images
```
