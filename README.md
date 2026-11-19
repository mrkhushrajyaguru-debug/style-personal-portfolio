# Khush Rajyaguru - Styled Personal Portfolio

## Project Overview

A styled personal portfolio website for the Week 2 CSS assignment. It builds on the Week 1 HTML structure by adding an external stylesheet (`style.css`), custom typography, color variables, Flexbox and CSS Grid layouts, hover effects, and mobile responsiveness.

## Setup Instructions (How to Run)

1. Open this folder in Visual Studio Code.

2. Make sure `index.html`, `style.css`, `README.md`, and `IMG/img-pro.jpeg` are in place.

3. Open `index.html` in a browser, or use the Live Server extension in VS Code.

4. The page can also be opened directly by double-clicking `index.html`.

## Code Structure

```
personal-portfolio/
├── index.html
├── style.css
├── README.md
├── IMG/
     └── img-pro.jpeg

```

## CSS Concepts Used

* **CSS Reset and Box Model:** `* { margin: 0; padding: 0; box-sizing: border-box; }` so padding and borders stay inside element widths.

* **CSS Selectors:** Element selectors (`body`, `header`, `nav`, `footer`), class selectors (`.card`, `.sub-box`, `.btn-submit`), ID selectors (`#about`, `#contact`), and pseudo-classes (`:hover`, `:focus`).

* **CSS Custom Properties:** Color variables defined inside `:root` (`--primary-color`, `--secondary-color`, `--bg-color`, `--card-bg`, `--text-color`, `--border-color`).

* **Typography and Colors:** Google Font `Poppins` imported in `index.html` and styled with readable font sizes, line heights, background colors, and borders.

* **Flexbox and CSS Grid:** `display: flex` used for the header/navigation bar and About section; `display: grid` used for multi-column cards in Skills, Projects, and Education.

* **Transitions and Hover Effects:** Smooth `transition` effects and `:hover` / `:focus` states on navigation links, cards, inputs, and buttons.

* **Responsive Design:** `@media (max-width: 768px)` media query to adjust layouts for smaller screens.

## Design Decisions

* **Color Palette:** Used a dark slate header and footer (`#1e293b`), light gray page background (`#f1f5f9`), white section cards (`#ffffff`), and blue accents (`#2563eb`) for clean contrast and readability.

* **Card-Based Layout:** Grouped each major section inside a `.card` container and individual items inside `.sub-box` cards so content is organized and easy to scan.

* **Sticky Header:** Kept the navigation header fixed at the top (`position: sticky; top: 0;`) on desktop screens for quick access to every section.

## Responsiveness Approach

* **Viewport Configuration:** Included `<meta name="viewport" content="width=device-width, initial-scale=1.0">` in `index.html` for proper mobile scaling.

* **Mobile Breakpoint (`768px`):** On screens `768px` wide or smaller, the header stacks vertically and unsticks, the About photo and paragraph stack and center-align, and two-column grids switch to a single column (`grid-template-columns: 1fr`).

## Website Sections

About Me, Technical Skills, Projects, Education, Certifications, and Contact.

## Technical Details

This is a static, single-page HTML and CSS website. HTML defines the content and semantic structure (`index.html`), while external CSS (`style.css`) controls layout, styling, and responsiveness. No JavaScript, database, server, or complex algorithm is used, keeping the project at a beginner Week 2 level.

## Testing Evidence

1. **Stylesheet Link:** Opened `index.html` in a browser and confirmed all colors, fonts, and layouts from `style.css` loaded properly.

2. **Navigation Links:** Clicked each link (`About`, `Skills`, `Projects`, `Education`, `Certifications`, `Contact`) and confirmed smooth scrolling to the right section.

3. **Hover & Focus States:** Hovered over navigation links, cards, and the Submit button, and clicked inside form inputs to confirm visual feedback.

4. **Responsive Layout:** Resized the browser below `768px` using Chrome DevTools and confirmed grids and header elements stacked cleanly without horizontal scrolling.

5. **Form Validation:** Submitted the empty form and tested an invalid email address to confirm browser validation prompts appear.