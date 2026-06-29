# ✈️ Our Travel Diary

A beautiful full-screen slideshow travel diary website.

## 📁 Folder Structure (required)

```
your-repo/
├── index.html          ← the website
└── photos/
    ├── photo1.jpg
    ├── photo2.jpg
    ├── photo3.jpg
    ├── ...
    └── photo16.jpg
```

> ⚠️ The `photos/` folder **must** be uploaded alongside `index.html` — the images are loaded by filename, not embedded in the HTML.

## 🚀 How to Upload to GitHub Pages

1. Create a new **public** repository on GitHub.
2. Upload **`index.html`** to the root.
3. Create a `photos/` folder and upload all 16 photos named `photo1.jpg` → `photo16.jpg`.
4. Go to **Settings → Pages → Source** and set branch to `main`, folder to `/ (root)`.
5. Your site will be live at `https://yourusername.github.io/repo-name/`

## ⌨️ Controls

| Action | Key |
|--------|-----|
| Next slide | → Arrow or click right button |
| Previous slide | ← Arrow or click left button |
| Play / Pause | Space bar or pause button |
| Touch swipe | Left / Right swipe on mobile |
| Sparkle effect | Click anywhere on the photo |

## ✏️ Customising Quotes & Labels

Open `index.html` and find the `slides` array near the bottom. Each entry looks like:

```js
{
  img:    "photos/photo1.jpg",
  label:  "Where It All Began",
  quote:  "We didn't plan this trip...",
  emojis: ["🗺️","✈️","🌍"]
}
```

Edit `label`, `quote`, and `emojis` to match your own memories!
