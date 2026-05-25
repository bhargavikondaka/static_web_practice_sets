# 📡 The Conference —  Web Page

A two-section interactive conference page for **The Things Conference** built with **HTML, CSS, and Bootstrap 4**. Clicking "Know More" reveals a YouTube video, stats, and a back button — powered by the CCBP UI Kit's `display()` function.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure and content |
| **CSS3** | Custom styling, `vh` units |
| **Bootstrap 4.5.2** | Flex utilities, responsive video embed |
| **Google Fonts** | Roboto font via CDN |
| **CCBP UI Kit JS** | `display()` function for page switching |

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

### 1. Multi-Section Page Switching
Two `<div>` sections with unique IDs toggle visibility using the CCBP `display()` function:
```html
<button onclick="display('sectionpage2')">Know more</button>
<button onclick="display('sectionpage1')">Back</button>
```
> 💡 Only one section is visible at a time — like a mini single-page app.

---

### 2. Bootstrap Responsive Video Embed
```html
<div class="embed-responsive embed-responsive-16by9 w-50 m-auto">
    <iframe class="embed-responsive-item"
        src="https://www.youtube.com/embed/VIDEO_ID?rel=0"
        allowfullscreen>
    </iframe>
</div>
```
- `embed-responsive-16by9` — maintains 16:9 aspect ratio
- `w-50` — video takes 50% of page width
- `m-auto` — centres the video horizontally

---

### 3. Bootstrap Flex Utilities
```html
<div class="d-flex flex-row justify-content-center">
<div class="d-flex flex-column">
```
- `d-flex` → `display: flex`
- `flex-row` / `flex-column` → direction
- `justify-content-center` → horizontal centering

---

### 4. vh Units for Sizing
```css
.heading   { font-size: 6vh; }
.card-head { font-size: 5vh; height: 5vh; }
.card-s    { height: 15vh; width: 20vh; }
```

---

## 🎨 Design Tokens

| Property | Value |
|---|---|
| Heading color | `#183b56` (dark navy) |
| Paragraph color | `#5a7184` (muted blue) |
| Heading font size | `6vh` (main), `4vh` (sub) |
| Card stat size | `5vh` |
| Image size | `700px × 500px` |
| Font | `Roboto` |

---

## 📊 Conference Stats (Section 2)

| Stat | Value |
|---|---|
| 👥 Attendees | 1400+ |
| 🛠️ Workshops | 100+ |
| 🎤 Speakers | 120+ |
| 🌍 Countries | 10+ |

---

## ⚠️ Known Error — YouTube Video (Error 153)

> **"Watch video on YouTube — Error 153 — Video player configuration error"**

**Cause:** The embedded YouTube video has **embedding disabled** by the video owner. This is not a code bug — it is a YouTube permission restriction.

**There were two issues:**
1. ❌ URL had `v=` in embed link → `embed/v=ID` (typo — now fixed)
2. ❌ Even after fix → Error 153 because the video owner disabled embedding

**Fix — replace the `src` with a working embeddable video:**
```html
<!-- ✅ Replace this -->
src="https://www.youtube.com/embed/EfyjQMv4U0g?rel=0"

<!-- ✅ With any of these working alternatives -->
src="https://www.youtube.com/embed/LlhmzVL5bm8?rel=0"   <!-- IoT explained -->
src="https://www.youtube.com/embed/ZsVhYiX4_6o?rel=0"   <!-- LoRaWAN explained -->
src="https://www.youtube.com/embed/vKJ6nXE_6Hc?rel=0"   <!-- Working test video -->
```

**How to check if a YouTube video allows embedding:**
1. Open the video on YouTube
2. Click **Share → Embed**
3. If embed option exists → ✅ safe to use
4. If embed option is missing → ❌ will show Error 153

---

## 📦 How to Run

1. Save `index.html` and `index.css` in the **same folder**
2. Open `index.html` in any browser
3. Click **Know More** to switch to Section 2
4. Click **Back** to return to Section 1

```bash
# Optional local server
npx serve .
```

---

## 📖 Learning Resources

| Topic | Link |
|---|---|
| Bootstrap embed video | getbootstrap.com/docs/4.5/utilities/embed |
| Bootstrap flex | getbootstrap.com/docs/4.5/utilities/flex |
| YouTube embed guide | developers.google.com/youtube/player_parameters |
| CSS `vh` units | developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units |

---

## 📄 License

Free to read, use, and practise. Happy coding! 🚀
