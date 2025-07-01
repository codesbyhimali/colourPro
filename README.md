# ColourCraft Pro

**Professional Colour Picker and Palette Generator**

ColourCraft Pro is a responsive, minimal web application built with HTML, CSS, and JavaScript. It provides powerful features for picking, analyzing, and saving color values in HEX, RGB, and HSL formats. Users can generate random colors, extract colors using the EyeDropper API, and view auto-generated palettes and recent color history.

---

## Features

- Pick colors using:
  - HTML color input
  - EyeDropper API (screen picker)
  - Random generator
- View color information in:
  - HEX
  - RGB
  - HSL
- Auto-generate 5-color palettes
- Copy color formats to clipboard
- Maintain recent color history
- Save favorite colors locally
- Responsive design with clean UI

---

## Tech Stack

- **Frontend**: HTML5, CSS3 (Grid, Flexbox), Vanilla JavaScript
- **API**: Uses [EyeDropper API](https://developer.mozilla.org/en-US/docs/Web/API/EyeDropper_API) (modern browser support)
- **Storage**: In-memory data for history and saved colors

---

## Project Structure

```
ColourCraft-Pro/
├── index.html      # Main application (self-contained)
└── README.md       # This file
```

---

## Getting Started

### 1. Clone this repository:
```bash
git clone https://github.com/codesbyhimali/colourcraft-pro.git
```

### 2. Navigate to the folder:
```bash
cd colourcraft-pro
```

### 3. Open `index.html` in any modern browser (Chrome recommended).

---

##  Usage

1. Click on the **random bar** or use the **color picker** to select a color.
2. Click the **EyeDropper button** to pick a color from anywhere on screen (if supported).
3. View HEX, RGB, and HSL values.
4. Click **Copy** to copy any format.
5. Click **Save Colour** to add it to your saved list.
6. Click any past or saved color to reload and analyze.
7. Hover over the random bar for a tooltip!

---

## Compatibility

- Fully functional in modern browsers like Chrome and Edge.
- EyeDropper API requires HTTPS and may not work in all browsers.

---

## Notes

- All data is stored in memory — refreshing the page clears history.
- No external dependencies or build tools used.
- Fully responsive and accessible UI.

---

## License

© 2025 Himali M Suresh. All rights reserved.  
For educational and non-commercial personal use.

---

## Acknowledgments

- [MDN Web Docs](https://developer.mozilla.org/)
- Inspiration from Dribbble palettes and DevTools color inspectors
