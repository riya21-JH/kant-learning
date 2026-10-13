# Kant Learning — Website

Plain HTML / CSS / JS. No build tools, no npm, no internet needed to look right.

```
KL/
├── index.html        → page content (text + structure)
├── css/style.css     → every color, font and spacing rule
├── js/main.js        → mobile menu toggle
├── fonts/            → Anton, Inter, JetBrains Mono (bundled, self-hosted)
├── images/           → your 3 gallery photos go here
└── README.md
```

## Fonts (matched to the reference design)
- **Anton** — big condensed headlines, numbers, logo
- **JetBrains Mono** — nav, buttons, labels, eyebrow text
- **Inter** — paragraphs

## Colors (sampled from the reference)
`#F4F0E6` background · `#F9F6EE` cards · `#141822` ink · `#C51E21` red · `#585E69` gray
Change them in the `:root` block at the top of `css/style.css`.

## Open it
Double-click `index.html`. Keep the folders next to it — it needs `css/`, `js/` and `fonts/`.

## Add your photos
Save three files in `images/` with exactly these names:
`level-based-seating.jpg`, `merit-board.jpg`, `continuous-evaluation.jpg`
They show automatically in black & white. Until then, gray placeholders appear.

## Edit text
Open `index.html` in any text editor and change the words directly.

## Publish
Drag the whole `kant-learning` folder into Netlify Drop, Vercel or GitHub Pages.
