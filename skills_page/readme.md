# 💻 Skills – Coding Course Page

A responsive mobile-style web page showcasing coding foundation courses (Python, JavaScript, HTML5, Java) with a dark coding-themed background and a clean white card UI built using HTML, CSS, and Bootstrap 4.

---

## 📁 Project Structure

```
project/
├── index.html
└── index.css
```

---

## 🚀 Getting Started

### 1. Download the Project

Copy both `index.html` and `index.css` into the same folder.

### 2. Open in Browser

Simply open `index.html` in any modern web browser — no build tools or server required.

```bash
# Or use VS Code Live Server extension for hot reload
```

---

## 🎨 Features

- **Dark coding background** hero section (full viewport height)
- **White rounded card panel** slides up from the bottom
- **4 course cards** displayed in a 2×2 grid:
  - 🐍 Python
  - 🟨 JavaScript
  - 🟠 HTML5
  - ☕ Java
- Each card shows a **course logo** and **course name**
- **Roboto** font via Google Fonts
- **Bootstrap 4.5** for layout utilities (flexbox, card)
- Fully static — no JavaScript logic required

---

## 🧰 Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| HTML5 | — | Structure |
| CSS3 | — | Custom styling |
| Bootstrap | 4.5.2 | Layout & utilities |
| Google Fonts | — | Roboto font |
| jQuery | 3.5.1 | Bootstrap dependency |
| Popper.js | 1.16.1 | Bootstrap dependency |

---

## 🎨 Color Palette

| Role | Color |
|---|---|
| Page heading | `#323f4b` (dark gray) |
| Description text | `#7b8794` (muted gray) |
| Course name | `#323f4b` (dark gray) |
| Card border | `#cbd2d9` (light gray) |

---

## 🖼️ Assets Used

| Course | Logo Source |
|---|---|
| Background | wallpaperbat.com (dark coding wallpaper) |
| Python | logos-world.net |
| JavaScript | freepnglogos.com |
| HTML5 | w3.org (official W3C logo) |
| Java | edufyitechsolutions.com |

> ⚠️ All brand logos are trademarks of their respective owners. Use for educational/personal projects only.

---

## 🐛 Known Issues & Fixes

| Issue | Fix |
|---|---|
| `.cousre-name` typo in HTML | Rename to `.course-name` to match CSS |
| Missing space in `class="cousre-nametext-capitalize"` on HTML5 card | Change to `class="course-name text-capitalize"` |

---

## 📌 Notes

- The page is designed for **mobile viewport**
- The white card panel overlaps the dark hero section using `border-top-left-radius` and `border-top-right-radius: 10vh`
- Course logos are displayed at **40×40px**

---

## 📄 License

This project is for **educational purposes only**. All brand names, logos, and trademarks belong to their respective owners.
