# 📱 Mobile_About X — Product Specifications Page

A beginner-friendly product page for the iPhone X built with **HTML, CSS, and Bootstrap 4**. It displays a hero phone image with rounded corners, a specifications list, and a Buy Now button — all centred using Bootstrap flex utilities.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure and content |
| **CSS3** | Custom styling, `vh` units, border-radius |
| **Bootstrap 4.5.2** | Flexbox utilities (`d-flex`, `justify-content-center`) |
| **Google Fonts** | Roboto and other font families via CDN |
| **jQuery + Popper.js** | Bootstrap JS dependencies |

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

### 1. Bootstrap Flex Utilities
Instead of writing CSS flexbox manually, Bootstrap provides shortcut classes:
```html
<!-- Centers content horizontally in a row -->
<div class="d-flex flex-row justify-content-center">

<!-- Stacks content vertically -->
<div class="d-flex flex-column justify-content-between">
```
- `d-flex` → `display: flex`
- `flex-row` → `flex-direction: row`
- `flex-column` → `flex-direction: column`
- `justify-content-center` → centres items horizontally

---

### 2. vh Units (Viewport Height)
All sizing uses `vh` — percentage of the screen height:
```css
.top-section  { height: 50vh; }     /* 50% of screen height */
.heading      { font-size: 5vh; }   /* scales with screen */
.u-l          { padding: 1vh; }
```
> 💡 **Tip:** `vh` units make your design scale automatically on different screen sizes.

---

### 3. Border Radius & Image Styling
```css
.top-section {
    border-radius: 5vh;      /* rounds the image corners */
    background-size: cover;  /* image covers the full area */
    margin: 2vh;
}
```

---

### 4. Bootstrap Button
```html
<button class="btn btn-primary">Buy now</button>
```
- `btn` — base Bootstrap button style
- `btn-primary` — blue filled button (Bootstrap's primary colour)

---

### 5. List Styling
```css
.u-l {
    list-style-type: circle;   /* hollow circle bullets */
    color: #707070;            /* grey text */
    font-family: "roboto";
}
```

---

## 🎨 Design Tokens

| Property | Value |
|---|---|
| Hero image height | `50vh` |
| Image border radius | `5vh` |
| Heading color | `#0a1f44` (dark navy) |
| Heading font size | `5vh` |
| List text color | `#707070` (grey) |
| List style | `circle` |
| Font | `Roboto` |

---

## 📋 Page Sections

| Section | Content |
|---|---|
| **Top** | iPhone X image centred with rounded corners |
| **Heading** | "Specifications" in dark navy bold |
| **List** | 6 iPhone X specs (RAM, display, cameras, processor, battery) |
| **Button** | Blue Bootstrap "Buy now" button |

---

## 📦 How to Run

1. Save `index.html` and `index.css` in the **same folder**
2. Open `index.html` in any browser — no installation needed!

```bash
# Optional local server
npx serve .
```

> ⚠️ Requires internet for Bootstrap CDN and Google Fonts to load

---

## Resources

mobile_phone_image : "https://storage.googleapis.com/lmo/2017/11/5e1490bb-iphone-x-wooden-table-test-drive.jpg"

---

## 📖 Learning Resources

| Topic | Link |
|---|---|
| Bootstrap Flexbox | getbootstrap.com/docs/4.5/utilities/flex |
| CSS `vh` units | developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units |
| Border radius | developer.mozilla.org/en-US/docs/Web/CSS/border-radius |
| Bootstrap buttons | getbootstrap.com/docs/4.5/components/buttons |
| Google Fonts | fonts.google.com |

---

## 📄 License

Free to read, use, and practise. Great for beginners learning Bootstrap and CSS units! 🚀
