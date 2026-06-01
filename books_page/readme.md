# 📚 Popular Books App Page

A responsive, multi-page books showcase web app built with HTML, CSS, and Bootstrap.

---

## 📌 Project Overview

A mobile-friendly books listing app that displays popular and recommended books with detailed description pages. Features a dark-themed UI with smooth page transitions — no page reload required.

---

## 🖥️ Pages

### Page 1 — Books Home Page (`section-book-page`)
- Popular Books section — Featured book: **Wings of Fire**
- Recommended Books section — **The 3 Mistakes of My Life** and **Harry Potter**
- Each book has a **Read Now** button linking to its detail page

### Page 2 — Wings of Fire Detail (`section-kalam-book`)
- Book cover image
- Title, author, and full description
- **Back** button to return to home
- **Buy Now** button

### Page 3 — The 3 Mistakes of My Life Detail (`section-3-mistakes`)
- Book cover image
- Title, author, and full description
- **Back** and **Buy Now** buttons

### Page 4 — Harry Potter Detail (`section-harrypotter-book`)
- Book cover image
- Title, author, and full description
- **Back** and **Buy Now** buttons

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Custom dark theme styling |
| Bootstrap 4.5 | Responsive layout, buttons, flex utilities |
| Google Fonts | Typography (Bree Serif, Roboto, Open Sans, etc.) |
| JavaScript | Page display toggle (show/hide sections) |

---

## 🎨 Fonts Used (Google Fonts)

- Bree Serif
- Caveat
- Lobster
- Monoton
- Open Sans
- Playfair Display
- Roboto
- Source Sans Pro
- Work Sans

---

## 🖼️ Images Used

| Book | Image Source |
|---|---|
| APJ Abdul Kalam photo | cdn.britannica.com |
| Wings of Fire cover | pozzpic.com |
| The 3 Mistakes of My Life | img.bookchor.com |
| Harry Potter | m.media-amazon.com |

---

## 📁 File Structure

```
popular-books/
│
├── index.html       # Main HTML file (all 4 pages)
├── index.css        # Custom styles
└── README.md        # Project documentation
```

---

## 🚀 How to Run

1. Download or clone the project folder
2. Make sure `index.html` and `index.css` are in the **same folder**
3. Open `index.html` in any browser
4. Click **Read Now** on any book to view its detail page
5. Click **Back** to return to the books home page

---

## ✅ Features

- Dark themed UI (`#1b1b1b` background)
- 4-page navigation without page reload
- Featured book card with photo and info
- Recommended books section with cover images
- Individual detail pages for each book
- Back and Buy Now buttons on every detail page

---

## 🐛 Known Issues / Fixes Needed

- `font-family: "breeserif"` and `"bree-serif"` — both are wrong, correct name is `"Bree Serif"` (with space, capital B and S)
- `.bg-cont` has `height: 100vh` — detail pages with long text will get cut off; change to `min-height: 100vh`
- `.rec-card-bg` has fixed `width: 85vh` — will overflow on small/mobile screens; use `width: 100%` instead
- Spelling errors in book descriptions:
  - Harry Potter: `mesearable` → `miserable`, `eea` → `dead`, `realtives` → `relatives`, `mystreious` → `mysterious`, `awizard` → `a wizard`
  - 3 Mistakes: `narratye` → `narrate`, `raeding` → `reading`, `againest` → `against`
  - Wings of Fire: `biginning` → `beginning`
- `buy now` button has no link/action yet — needs an `onclick` or `href`

---

## 👩‍💻 Author

**Kondaka Bhargavi**
- 📧 kondakabhargavi15@gmail.com
- 🔗 LinkedIn | GitHub
