# Rosewood University – Campus Information Website

## Project Description

A single-page campus information website built for the CSS Layout & Positioning Practical Assignment. The site presents key campus services, locations, announcements, and layout demonstrations in a clean, accessible, and fully responsive design.

---

## Layout & Responsiveness Behaviors Demonstrated

### Navigation Bar
- Sticky top navigation bar built with Flexbox
- Dropdown menu triggered on hover (desktop) and click (mobile/touch)
- Hamburger toggle button reveals/hides navigation links on small screens

### Campus Services Section
- CSS Grid layout using `auto-fit` and `minmax` for fluid columns
- 4 columns on desktop → 2 columns on tablet → 1 column on mobile
- Cards include hover lift effect via CSS transitions

### Campus Locations / Gallery Section
- CSS Grid with consistent image heights using `object-fit: cover`
- Images resize without distortion across all screen sizes
- 3 columns → 2 columns → 1 column on progressively smaller screens

### Announcements & Notices Section
- One notice uses `position: sticky` to remain visible while scrolling
- On mobile, the sticky notice reverts to normal flow to avoid blocking content
- Notices use a left border accent to stand out visually

### Display Behavior Section
- `display: block` — fully visible element
- `display: none` — element removed from view and layout
- `visibility: hidden` — element occupies space but is invisible
- `display: inline-block` — tag elements sit side by side
- Screen-specific visibility: one paragraph visible only on mobile, another only on desktop (using media queries)

### Responsiveness Breakpoints
| Breakpoint | Target |
|---|---|
| ≥ 1025px | Desktop layout |
| 769px – 1024px | Tablet layout |
| 481px – 768px | Mobile landscape |
| ≤ 480px | Mobile portrait |

Responsive techniques used:
- **Media queries** at 1024px, 768px, 480px, and 320px
- **CSS Flexbox** for navbar, footer, and card alignment
- **CSS Grid** for service cards and gallery
- **`clamp()`** for fluid typography
- **Relative units** (`%`, `vw`, `rem`) throughout

---

## Project Files

| File | Description |
|---|---|
| `index.html` | Main HTML file with all page sections |
| `style.css` | External stylesheet with all layout and responsive styles |
| `README.md` | Project documentation |

---

## Student Information

- **Course:** CSS Layout & Positioning Practical Assignment
- **University:** Rosewood University
- **Year:** 2026
