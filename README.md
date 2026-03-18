# Web Capture: Home - Canva

**Captured from**: [https://www.canva.com/](https://www.canva.com/)  
**Captured on**: 18/03/2026, 21:12:25

## 📁 Project Structure

```
.
├── index.html       # Main HTML structure
├── styles.css       # All CSS styles (consolidated)
├── metadata.json    # Capture metadata
├── ASSETS.md        # Reference to all images/assets
└── README.md        # This file
```

## 🎯 Quick Start

1. Clone this repository
2. Open `index.html` in your browser, or
3. Use a local server: `npx serve .`

## ✏️ Editing in Cursor

This capture is structured for easy editing:

- **HTML**: Edit `index.html` for structure and content
- **Styles**: All CSS is in `styles.css` for easy modification
- **Assets**: Images are referenced by URL (see `ASSETS.md`)

## 🔗 Combining Multiple Captures

To merge multiple captures:

1. Copy desired sections from each `index.html`
2. Merge relevant styles from each `styles.css`
3. Resolve any CSS conflicts by namespacing or specificity
4. Update image references as needed

## 📝 Notes

- This is a static snapshot of the original page
- External resources (images, fonts) are referenced by URL
- **External JavaScript has been removed to preserve the captured state**
- Some dynamic content may not work without the original backend
- **API keys and secrets have been removed for security**

### ⚠️ Important Note About Framework Sites

**If the page was built with Framer, React, Vue, or similar frameworks:**
- The capture contains the **rendered output** only
- External framework scripts are removed to prevent re-rendering
- This means you're editing the final HTML/CSS, not the framework code
- Interactive features that relied on JavaScript will not work
- Best for: capturing visual design, layout, and styling to reference or adapt

**For fully editable versions:**
- Export directly from the framework (e.g., Framer's export feature)
- Or use this capture as a visual reference to rebuild in your own code

## 🛠️ Customization Tips

- Add `class` attributes to elements for easier styling
- Use CSS custom properties (variables) for consistent theming
- Consider converting inline styles to CSS classes
- Replace remote images with local copies for full offline support
