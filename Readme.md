# Mangalam Hosiery – Hosiery & Garments Website

A complete, professional, deployment-ready website for a family-run hosiery and garments shop.

## 📁 Folder Structure

```
hosiery-shop/
├── index.html          ← Home page
├── products.html       ← Products page (Men / Women / Kids tabs)
├── brands.html         ← Brands page
├── about.html          ← About Us page
├── contact.html        ← Contact page
├── css/
│   └── style.css       ← All styles
└── js/
    └── script.js       ← Interactions (tabs, nav, scroll animation)
```

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `family-threads`)
2. Upload all files maintaining the folder structure above
3. Go to **Settings → Pages**
4. Under "Source" select `main` branch, `/ (root)` folder
5. Click **Save** — your site will be live at `https://yourusername.github.io/family-threads/`

## ✏️ Customization Checklist

Before going live, update the following:

### In ALL HTML files:
- [ ] Replace `+91 99999 99999` with your real phone number
- [ ] Replace `919897561937` in all WhatsApp links with your number (no + sign, no spaces)
- [ ] Replace `123 Market Street, Your City – 000001` with your real address
- [ ] Replace `[Landmark]` and `[Area]` with actual details
- [ ] Update the business name from **Mangalam Hosiery** to your actual shop name

### In `contact.html`:
- [ ] Replace the map placeholder with a real Google Maps embed:
  1. Go to maps.google.com → search your address
  2. Click Share → Embed a map → Copy HTML
  3. Replace the `.map-placeholder` div with the `<iframe>` code

### In `index.html`:
- [ ] Update the stats (Years in business, etc.) to match your actual history
- [ ] Update "Est. 2005" in about.html to your actual year

### Business Name:
- Search & replace `Mangalam Hosiery` with your actual shop name across all files

## 🎨 Design Highlights
- Deep forest green (#1a3a2a) primary palette with warm gold (#c8973a) accents
- Playfair Display serif for headings + DM Sans for body text
- Animated brand ticker, scroll-reveal cards, hero stats
- Fully mobile responsive
- Pulsing WhatsApp float button
- Tab-based product category navigation