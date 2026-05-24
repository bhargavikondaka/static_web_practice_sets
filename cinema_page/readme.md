# Finding Nemo — Movie Page with Bootstrap Carousel

A fun, responsive movie showcase page for **Finding Nemo** built with **HTML, CSS, and Bootstrap 4**. It features an image carousel of underwater scenes, movie details, and a similar movies section — all on a vibrant orange background.

---

## 📁 Project Structure

```
project/
├── index.html       # Main HTML file
├── index.css        # Custom stylesheet
└── README.md        # Project documentation
```

---

## 🚀 Features

- 🎠 **Bootstrap 4 Carousel** — auto-sliding image slider with previous/next controls and dot indicators
- 🟠 **Orange themed background** — vibrant `#ff8348` background colour
- 🐠 **Movie details section** — title, Watch Now button, and plot description
- 🎬 **Similar movies section** — three thumbnail images in a flex row
- 📱 **Responsive layout** — Bootstrap grid and flexbox utilities used throughout

---

## 🛠️ Tech Stack

| Technology | Version | Usage |
|---|---|---|
| HTML5 | — | Page structure |
| CSS3 | — | Custom styling |
| Bootstrap | 4.5.2 | Carousel, flexbox utilities |
| jQuery | 3.5.1 slim | Bootstrap JS dependency |
| Popper.js | 1.16.1 | Bootstrap JS dependency |
| Google Fonts | — | Multiple font families |

---

## 🎨 Design Tokens

| Property | Value |
|---|---|
| Background color | `#ff8348` (vibrant orange) |
| Movie title color | `#ffffff` (white) |
| Description color | `#ffffff` (white) |
| Button background | `white` |
| Button text color | `#ff8348` |
| Button border | `2px solid transparent` |
| Button border radius | `7px` |
| Button size | `17vh × 7vh` |
| Font family | `Roboto` |
| Movie title size | `5vh`, bold |
| Description size | `13px` |
| Suggestions heading size | `3vh` |
| Carousel border radius | `8vh` |
| Similar movie image size | `100px × 100px` |
| Similar movie border radius | `5px` |
| Carousel image size | `70vh × 50vh` |

---

## 🎠 Carousel Details

- **Library**: Bootstrap 4 Carousel (`#carouselExampleIndicators`)
- **Auto-ride**: `data-ride="carousel"`
- **Slides**: 3 underwater fish/coral reef images
- **Controls**: Previous & Next arrows
- **Indicators**: 3 dot indicators at bottom
- **Image class**: `d-block w-50 nemo-bg`

### Carousel Images

| Slide | Image URL |
|---|---|
| Slide 1 | `pxhere.com` — coral reef fish underwater |
| Slide 2 | `dreamstime.com` — aquarium tropical fish |
| Slide 3 | `ftcdn.net` — colorful underwater scene |

---

## 🖼️ Similar Movies Images

| Position | Image URL |
|---|---|
| Left | `media.craiyon.com` — cartoon fish illustration |
| Centre | `media.craiyon.com` — animated sea character |
| Right | `png.pngtree.com` — colorful animated fish PNG |

---

## 📐 Layout Breakdown

### Main Container (`.bg-container`)
- Orange background `#ff8348`
- `padding: 2vh` all around
- Bootstrap utility: `justify-content-between`

### Carousel Card (`.car-card`)
- `border-radius: 8vh` — heavily rounded corners
- `margin-top: 1vh`, `padding: 1vh`

### Movie Title + Button Row
- Bootstrap `d-flex flex-row`
- Title left, Watch Now button inline

### Similar Movies Row
- Bootstrap `d-flex flex-row justify-content-between`
- Three `100px × 100px` thumbnail images evenly spaced

---

## 🔤 Google Fonts Imported

```
Bree Serif, Caveat, Lobster, Monoton, Open Sans,
Playfair Display SC, Playfair Display, Roboto,
Source Sans Pro, Work Sans
```

Active font: **Roboto**

---

## 📦 CDN Dependencies

```html
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"/>

<!-- jQuery Slim -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>

<!-- Popper.js -->
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>

<!-- Bootstrap JS -->
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
```

---

## 📦 How to Run

1. Download or clone the project
2. Make sure `index.html` and `index.css` are in the **same folder**
3. Open `index.html` in any modern browser — no build step needed

```bash
# Optional: serve locally
npx serve .
```

> ⚠️ The carousel requires an internet connection to load Bootstrap JS from CDN

---

## ✅ Browser Compatibility

| Browser | Status |
|---|---|
| Google Chrome | ✅ Supported |
| Mozilla Firefox | ✅ Supported |
| Microsoft Edge | ✅ Supported |
| Safari | ✅ Supported |

---

## 💡 Key Techniques Used

| Technique | Where used |
|---|---|
| Bootstrap carousel | Main image slider |
| `d-flex flex-row` | Title+button row & similar movies row |
| `justify-content-between` | Even spacing in similar movies row |
| `vh` units | Responsive sizing for images, buttons, fonts |
| `border-radius: 8vh` | Rounded carousel card |
| `data-ride="carousel"` | Auto-play on page load |

---

## 📄 License

Free to use for learning and personal projects.
