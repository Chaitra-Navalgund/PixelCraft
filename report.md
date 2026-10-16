# Frontend Developer Intern Task — Design Report

## 1. Objective
The objective was to create a static webpage using HTML5 and CSS3, with a clear visual hierarchy, semantic structure, and responsive layouts for desktop, tablet, and mobile screens.

## 2. Design concept
**PixelCraft** is a fictional digital studio landing page. Because no wireframe was supplied, a new concept was selected for this exercise. The design uses a white background, dark navy typography, blue accents, soft tinted panels, rounded cards, and generous spacing. CSS-created abstract artwork and mock project previews keep the page self-contained without external image assets.

## 3. Technologies and tools
- HTML5 for semantic page structure
- CSS3 for layout, visual styling, and responsive behaviour
- Visual Studio Code for editing
- Chrome Developer Tools for viewport testing

## 4. HTML structure
The page uses semantic elements including `header`, `nav`, `main`, `section`, `article`, and `footer`. Headings are arranged hierarchically. Navigation links point to page sections, the main content has an identifiable target, and a skip link supports keyboard users. The document includes a viewport meta tag and a short description.

## 5. CSS and layout decisions
- CSS custom properties centralize the palette, container width, and common values.
- Flexbox is used for navigation, action groups, section headings, and footer alignment.
- CSS Grid is used for the hero, service cards, project showcase, and about section.
- `clamp()` provides fluid heading sizes.
- A centered container and consistent spacing create alignment between sections.
- Hover and keyboard-focus styles help communicate interactive affordances.
- Media queries at 900px and 640px adapt multi-column sections to smaller screens.
- A reduced-motion media query respects the visitor's motion preference.

## 6. Responsive testing plan
Use Chrome Developer Tools and check at least these viewport widths:
- 1440px — desktop
- 1024px — small desktop / landscape tablet
- 768px — tablet
- 390px — mobile
- 320px — narrow mobile

At each size, check for horizontal overflow, readable text, clear navigation, card stacking, balanced spacing, visible buttons, and working in-page links. Record the actual results after testing; do not mark a viewport as passed before checking it.

## 7. Challenges and solutions
The main design challenge was creating a visually engaging page without supplied wireframes or image assets. This was addressed by establishing a consistent spacing and colour system and creating decorative visuals with CSS. Another challenge was fitting multi-column layouts onto narrow screens; responsive grid changes and media queries stack content at smaller widths. These are design decisions implemented in the code; add any additional problems you personally encounter and resolve during testing.

## 8. Limitations
This is a static HTML/CSS concept. The contact link opens an email application; there is no backend, form submission, or JavaScript interaction. The brand and showcased projects are fictional and should not be presented as real client work.

## 9. Conclusion
The exercise demonstrates semantic HTML, organized CSS, responsive layout techniques, basic accessibility considerations, and documentation. Final evaluation should be completed after comparing the page against the intended concept and recording real browser test results.
