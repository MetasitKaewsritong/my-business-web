# NoBugs Business Website

## About the Project

This project is the official website of **NoBugs Co., Ltd.**, a pest control business committed to creating safe, healthy, and bug-free environments for homes and businesses.

## Website Pages

| Page | Description | Link |
|------|-------------|------|
| Home | Mission statement and featured services | [index.html](index.html) |
| About | Company vision and executive team | [about.html](about.html) |
| Services | Service details and pricing table | [services.html](services.html) |
| Contact Us | Contact form and location map | [contact_us.html](contact_us.html) |

## File Structure

```
my-business-web/
├── index.html
├── about.html
├── services.html
├── contact_us.html
├── css/
│   └── styles.css
├── Pictures/
│   └── ...
└── README.md
```

## CSS Implementation

### Selectors
| Type | Examples | Usage |
|------|----------|-------|
| Universal | `*` | Reset margin, padding, box-sizing |
| Element | `h1`, `h2`, `p`, `a`, `table`, `form` | Base typography and elements |
| Class | `.hero`, `.card`, `.btn`, `.team`, `.services` | Reusable components |
| ID | `#header`, `#footer` | Unique page sections |
| Pseudo-class | `:hover`, `:active`, `:focus`, `:last-child`, `::after` | Interactive states |

### CSS Units
| Unit | Usage |
|------|-------|
| `px` | Borders, box-shadows, small fixed spacing |
| `rem` | Font sizes, margins, paddings |
| `%` | Container widths, responsive images |
| `vh` | Hero section height (60vh) |
| `vw` | Viewport-based font sizes |

### Color Palette
| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary | `#1a365d` | Header, Footer background |
| Secondary | `#2b6cb0` | Buttons, Links, Accents |
| Accent | `#38a169` | Submit buttons, Highlights |
| Neutral | `#718096` | Secondary text |
| Light | `#f7fafc` | Page background |

### Typography
- **Font Family:** Roboto (Google Fonts) with Arial fallback
- **Font Weights:** 400 (normal), 600 (semi-bold), 700 (bold)
- **Line Height:** 1.6 (body), 1.8 (paragraphs)
- **Text Effects:** `text-transform`, `letter-spacing`, `text-shadow`

### Box Model
- **Padding:** Used on containers, cards, buttons, header, footer
- **Margin:** Spacing between sections and elements
- **Border:** Card accents, input fields, table cells
- **Border-radius:** Rounded corners (8px, 12px, 50%)

### Positioning & Layout
| Property | Usage |
|----------|-------|
| `position: sticky` | Header stays at top when scrolling |
| `position: fixed` | Back-to-top button, chat widget |
| `position: absolute` | Hero overlay effect |
| `position: relative` | Parent for absolute children |

### Display & Layout Systems
| System | Usage |
|--------|-------|
| `display: flex` | Header navigation, services cards, form layout |
| `display: grid` | Team members section (auto-fit columns) |
| `flex-wrap: wrap` | Responsive card wrapping |
| `justify-content` | Centering and spacing items |
| `align-items` | Vertical alignment |

### Hover & Interaction Effects
| Effect | CSS Properties |
|--------|----------------|
| Button hover | `transform: translateY(-2px)`, `box-shadow` |
| Card hover | `transform: translateY(-5px)`, border color change |
| Link hover | Color change, underline animation with `::after` |
| Scale effect | `transform: scale(1.1)` on fixed buttons |
| Transitions | `transition: all 0.3s ease` |

### Responsive Design
| Breakpoint | Changes |
|------------|---------|
| `768px` | Stack header, smaller fonts, column layout |
| `480px` | Smaller buttons, reduced padding |

---

## Screenshots

### NoBugs - Home
![NoBugs - Home](<Pictures/NoBugs - Home.png>)

### NoBugs - About
![NoBugs - About](<Pictures/NoBugs - About.png>)

### NoBugs - Services
![NoBugs - Services](<Pictures/NoBugs - Services.png>)

### NoBugs - Contact Us
![NoBugs - Contact Us](<Pictures/NoBugs - Contact Us.png>)

---

© 2025 NoBugs Co., Ltd. All rights reserved.
