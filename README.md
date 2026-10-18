# StaRk Panel

A high-performance, modular device management console with real-time Firebase integration.

## Project Structure

```text
Website/
├── index.html            # Ultra-light (~700 bytes) modular HTML entry
├── favicon.ico           # Website favicon
├── .nojekyll             # GitHub Pages configuration
├── README.md             # Project documentation
├── css/
│   ├── style.min.css     # Production-minified stylesheet (~120 KB)
│   └── style.css         # Formatted CSS stylesheet
└── js/
    ├── app.js            # Production-optimized & minified bundle (358 KB, 56% size reduction)
    └── app.formatted.js  # Beautified JavaScript source code for easy editing
```

## Performance & Optimizations

- **Instant HTML First-Paint**: The main `index.html` is under 1 KB (down from the previous ~1 MB single file), eliminating parse lag and memory freezes.
- **56% JavaScript Bundle Compression**: `js/app.js` is reduced from ~815 KB to 358 KB using esbuild syntax compression, whitespace elimination, and dead code reduction.
- **Non-blocking Script Execution**: Scripts are loaded with the `defer` attribute to allow the browser to parse and render the DOM immediately.
- **Optimized Stylesheet**: Minified `style.min.css` (~120 KB) with optimized selectors.
- **Resource Preconnect**: Preconnect directives for Google Fonts to accelerate typography rendering.

## How to Run Locally

### Method 1: Local HTTP Server (Recommended)
```bash
python -m http.server 3000
```
Then open [http://localhost:3000](http://localhost:3000).

### Method 2: Node / npx
```bash
npx serve .
```

## Deployment
Hosted live on GitHub Pages:
**[https://rythampkhandelwal.github.io/stark-panel/](https://rythampkhandelwal.github.io/stark-panel/)**
