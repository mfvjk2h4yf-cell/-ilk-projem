# diVersIENNA website

Static one-page site for the magazine *diVersIENNA – Wien im Originalton* (ATZP Bildungs- & Kulturverein). Issue 01 appears spring 2027.

## Files
- `index.html` – the whole page (sections: cover, intro, `#ressorts`, features, `#inhalt`, `#mitmachen`)
- `style.css` – all styles; colors and fonts as CSS variables in `:root` (from the print concept)
- `img/cover.jpg` – cover image (AI concept image)
- `README.md` – short German description

## Rules
- No build step, no JS framework: plain HTML + CSS. Open `index.html` to preview.
- Site content is German (`lang="de"`); greetings in other languages keep their own `lang` (and `dir="rtl"` for Arabic).
- Use the existing color variables (`--petrol`, `--terrakotta`, `--elfenbein`, …) instead of new hex values.
- Fonts: Lora (serif headings), Inter (sans text) via Google Fonts.
- Keep it mobile-friendly; layout uses `.wrap` (max 1080px, 20px side padding).
- Code, comments and commit messages in English.

## Docs
- `CLAUDE.md` – this file; update in place, keep it short. Add `todo.md` / `notes.md` only when needed.
