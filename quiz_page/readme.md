# 🧠 HTML Quiz App

A beginner-friendly quiz page built with **HTML, CSS & Bootstrap 4**. Displays a question card with an image, four multiple-choice options, a score tracker, and a submit button — all on a purple background.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure |
| **CSS3** | Custom styling, `vh` units, border-radius |
| **Bootstrap 4.5.2** | Flex utilities, card component |
| **Google Fonts** | Roboto and other font families |

---

## 📁 File Structure

```
project/
├── index.html       # Main HTML file
├── index.css        # Custom stylesheet
└── README.md        # Project documentation
```

---

## 💡 Key Concepts Covered

- **Bootstrap Cards** — `.card` component for question and options sections
- **Bootstrap Flex** — `d-flex`, `flex-row`, `flex-column`, `justify-content-center`
- **`vh` units** — all sizing uses viewport height (`3vh`, `5vh`, `20vh`)
- **List styling** — `list-style-type: none` removes default bullets from options
- **Border radius** — rounded corners on cards, options, buttons, and image
- **Score display** — right-aligned score using `text-align: right`

---

## 🎨 Design Tokens

| Property | Value |
|---|---|
| Background | `#875fc0` (purple) |
| Score text | `white` |
| Question text | `#323f4b` (dark grey) |
| Option background | `#ffffff` (white) |
| Option border | `#323f4b` |
| Submit button | `#fbaf00` (amber/yellow) |
| Card border radius | `7px` / `3vh` |
| Question image | `43vh × 20vh` |
| Font | `Roboto` |

---

## 📋 Page Sections

| Section | Content |
|---|---|
| **Score bar** | Right-aligned `Score: 25/45` |
| **Question card** | Question number, text, code image |
| **Options card** | 4 options (A–D) as list items + Submit button |

---

## ⚠️ Known Issues & Fixes

| Issue | Fix |
|---|---|
| `.background` has `dflex` (missing `-`) | Change to `d-flex` |
| `.q-card` is defined twice in CSS | Remove the duplicate block |
| Options use `.options` class but CSS also has `.option` — two similar classes | Consolidate into one class |
| No JavaScript — submit button does nothing | Add JS to check answer & update score |

---

## 📦 How to Run

1. Save `index.html` and `index.css` in the **same folder**
2. Open `index.html` in any browser

```bash
npx serve .   # optional local server
```

---

## 📖 Resources

| Topic | Link |
|---|---|
| Bootstrap Cards | getbootstrap.com/docs/4.5/components/card |
| Bootstrap Flex | getbootstrap.com/docs/4.5/utilities/flex |
| CSS `vh` units | developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units |
| List styling | developer.mozilla.org/en-US/docs/Web/CSS/list-style-type |

---

## 📄 License

Free to use for learning and personal projects. Happy coding! 🚀
