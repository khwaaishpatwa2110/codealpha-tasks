# 🖼️ My Custom Image Gallery

A lightweight, responsive image gallery built with **vanilla HTML, CSS, and JavaScript** — no frameworks or dependencies required.

## ✨ Features

- **Category Filtering** — Filter images by Animals, Cars, Space, Food, Travel, or Nature
- **Lightbox Viewer** — Click any image to open a full-screen popup with a caption
- **Navigation** — Cycle through images within a category using Previous / Next buttons
- **Responsive Grid** — Auto-fills columns based on screen width using CSS Grid
- **Hover Animations** — Subtle scale effect on image hover for a polished feel

## 📸 Preview

| Gallery View | Lightbox View |
|---|---|
| Filterable grid of images | Full-screen overlay with navigation |

## 🚀 Getting Started

No build tools or installs needed. Just open the file in a browser.

```bash
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git

# Open the gallery
open image_gallery.html
```

Or simply download `image_gallery.html` and double-click it.

## 🗂️ Project Structure

```
image_gallery.html   # Single self-contained file (HTML + CSS + JS)
README.md
```

All logic, styles, and data live in one file for simplicity.

## 🛠️ Customization

### Adding or Replacing Images

Edit the `images` array inside the `<script>` tag:

```javascript
let images = [
    {
        src: 'https://your-image-url.com/photo.jpg',
        category: 'nature',   // must match a filter button
        title: 'My Photo'
    },
    // ...
];
```

### Adding a New Category

1. Add a filter button in the HTML:
    ```html
    <button class="filter-btn" onclick="filterGallery('architecture')">Architecture</button>
    ```
2. Add images with the matching `category` value in the `images` array.

### Changing the Layout

Adjust the grid column width in the CSS:

```css
.gallery-grid {
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* change 250px */
}
```

## 🧰 Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Transitions)
- Vanilla JavaScript (ES5-compatible)
- [Unsplash](https://unsplash.com) — Image source

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
