# Student Portal — HTML &amp; CSS Basics

A small, multi-page website built with **only HTML and CSS**, for **SPG 0473 — Web Programming**.
It's a hands-on example students can read, run, and copy from.

## Pages

| File | What it teaches |
|------|-----------------|
| `index.html` | Page structure, semantic layout (header / nav / main / footer), links |
| `about.html` | Ordered lists, text content |
| `students.html` | Tables (`<table>`, `<tr>`, `<th>`, `<td>`) |
| `register/register.html` | Forms & input types: text, email, radio, checkbox, select, textarea |
| `contact.html` | Links (`mailto:`, external) and media (`<video>`, `<audio>`) |
| `index2.html` | A personal profile page — uses **internal CSS** |
| `css/style.css` | One shared stylesheet that styles every portal page — **external CSS** |

## Key ideas

- **HTML = structure, CSS = style.**
- The portal pages all share **one external stylesheet** (`css/style.css`). Edit it once and every page updates.
- `index2.html` keeps its CSS **inside the file** (internal CSS) so you can compare the two approaches.
- The header, nav and footer are the **same on every page** for a consistent look.
- The layout is **responsive** — try making the window narrow and watch the nav wrap.

## How to view it

- **Quickest:** double-click any `.html` file to open it in your browser, or
- **Like a real server:** use VS Code's *Live Server*, or put the folder in `C:\xampp\htdocs\` and open `http://localhost/`.

## Folder structure

```
html/
├── index.html          ← home
├── about.html
├── students.html
├── contact.html
├── index2.html         ← profile (internal CSS)
├── css/
│   └── style.css       ← shared styles (external CSS)
├── images/
│   └── avatar.svg
└── register/
    └── register.html   ← links use ../ to reach the root
```

## Next steps

1. **Add PHP + MySQL** to turn the static pages into a dynamic site (course Chapters 3–5).
2. **Publish it on GitHub** so anyone can see it (course Chapter 6).
