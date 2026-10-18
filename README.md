# StaRk Panel

A high-performance device management console with real-time Firebase integration.

## Project Structure

```text
Website/
├── public/               # Public entry & static assets
│   ├── index.html        # Main HTML entry point
│   └── favicon.ico       # Website favicon
├── src/                  # Source code files
│   ├── css/
│   │   ├── style.min.css # Optimized stylesheet (~120 KB)
│   │   └── style.css     # Formatted stylesheet
│   └── js/
│       ├── app.js        # Production bundle (358 KB)
│       └── app.formatted.js # Beautified source code for editing
├── index.html            # Root redirect to public/
├── .nojekyll             # GitHub Pages configuration
└── README.md             # Project documentation
```

## How to Run Locally

Start a local server from the project directory:

```bash
# Using Python
python -m http.server 3000

# Or using Node
npx serve .
```

Then visit [http://localhost:3000/public/](http://localhost:3000/public/) (or simply [http://localhost:3000](http://localhost:3000) which auto-redirects).

## Deployment
Hosted live on GitHub Pages:
**[https://rythampkhandelwal.github.io/stark-panel/](https://rythampkhandelwal.github.io/stark-panel/)**
