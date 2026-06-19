Task7 - CSS Summary

This file lists the CSS selectors and rules used in `index.css` and describes their purpose.

- Global reset: `*` — removes default margin/padding and sets `box-sizing: border-box`.
- `body` — sets the base font-family to Arial/Helvetica/sans-serif.
- `nav` — padding for the navigation area (`20px 40px`).
- `.logo` — inline-block logo area, `width: 20%`, larger font-size and bold.
- `nav ul` — inline block centered menu area, `width: 55%`, `text-align: center`.
- `nav ul li` — inline-block list items with horizontal spacing.
- `nav ul li a` — link styling: no underline, black color.
- `.user` — user area styling: inline-block, right-aligned, skyblue text, rounded background, fixed height/width.
- `.hero` — top section spacing (`margin-top: 50px`) and horizontal padding.
- `.left` — left column: `width: 49%`, inline-block layout.
- `.left h1` — large heading using viewport-height units (`font-size: 10vh`).
- `button` — fixed size buttons, blue background, white text, rounded corners.
- `.right` — right column: `width: 49%`, inline-block.
- `.right img` — image sizing: `width: 80%`, `height: 60vh`.

Media queries:
- Tablet (commented-out): a media query for ~900-1023px was present but commented.
- Phone: `@media screen and (min-width: 200px) and (max-width: 600px)` — hides `nav ul` and adjusts `.left`/`.left h1` for small screens. (Note: breakpoint adjusted to 200–600px in `index.css`.)

Notes:
- Units used: `px`, `vh`, `%`, `vh` for responsive heading and image heights.
- Colors used: `rgb(15, 173, 235)` (buttons), `rgb(233, 244, 249)` (user background), `skyblue` (user text).
- Consider refining breakpoints and using flexbox/grid for more robust responsive layouts.

File: Task7/index.css
