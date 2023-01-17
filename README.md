# Bootstrap White Registration Form

A clean, minimal registration form built with Bootstrap 5 and custom CSS. This project demonstrates a compact, responsive UI pattern for user sign-up pages with client-side validation styles and a lightweight structure suitable for quick prototyping.

## Preview

![Bootstrap White Registration Form Preview](https://github.com/mihaiapostol14/Bootstrap-White-Registration-Form/blob/55f908bd5321ccf8c31b15395f25ad376e16a41f/assets/preview.png)

---

## Quick Start

These instructions get you a local copy running quickly. Copy and paste the commands into your terminal.

1. Clone the repository
```bash
git clone https://github.com/mihaiapostol14/Bootstrap-White-Registration-Form.git
cd Bootstrap-White-Registration-Form
```
2. Local preview options

Option A — VS Code Live Server (recommended for quick HTML edits)
- Open the project in VS Code:
```bash
code .
```
- In the Explorer, open `html/index.html` then click "Go Live" in the VS Code status bar or right-click `index.html` → "Open with Live Server". The page will be served and opened in your browser.

Option B — Serve from the terminal with npx (Node.js required)
- Serve the repository root (then open the URL shown, typically http://localhost:5000):
```bash
npx serve -p 5000
```
- Or serve only the html folder:
```bash
npx serve ./html -p 5000
```
- Then open:
```
http://localhost:5000/html/index.html
```

Option C — Quick Python HTTP server (if you don't have Node)
```bash
python3 -m http.server 5000
```
Then open:
```
http://localhost:5000/html/index.html
```

Notes:
- For the `npx serve` option you can install `serve` globally if you prefer:
```bash
npm install -g serve
serve -p 5000
```

---

## Technologies

- HTML5
- CSS3 (custom stylesheet)
- JavaScript (lightweight / placeholder)
- Bootstrap 5.3 (CDN)
- Google Fonts (Rubik)

---

## Features

- Minimal, modern registration UI built with Bootstrap components
- Responsive layout that adapts to small and large screens
- Client-side validation states (Bootstrap validation classes in markup)
- Simple, extendable file structure for quick prototyping and customization
- Clean typography and gradient background for visual focus

---

## Project Structure

A visual tree of the repository (top-level):

```
/
├── assets/                # (empty) place images or additional assets here
├── css/
│   └── style.css          # custom styles (fonts, layout, gradient background)
├── html/
│   └── index.html         # registration page (Bootstrap CDN + local CSS/JS)
├── js/
│   └── script.js          # placeholder script (client-side logic can go here)
└── README.md              # this file
```

Key files:
- html/index.html — Main registration page. Includes Bootstrap CSS/JS, links to local `css/style.css` and `js/script.js`.
- css/style.css — Global styles and layout (importing Rubik font and background gradient).
- js/script.js — Placeholder for custom interactions/validation logic.

---

## Recommendations as a Frontend Architect

- Add semantic form labels and ARIA attributes to improve accessibility.
- Add real client-side validation and progressive enhancement (e.g., HTML5 + JS).
- Consider bundling or automating builds if you expand (Vite/Parcel) — not necessary for this small prototype.
- Add unit/visual tests and a demo URL (GitHub Pages or Vercel) for a production-ready preview.

---

If you'd like, I can:
- Generate a polished GitHub Pages demo URL and update the Live Demo link.
- Add basic JavaScript validation to `js/script.js`.
- Create a small CI workflow to deploy the `html/index.html` to GitHub Pages automatically.