# StaRk Panel

A modern device management console with real-time Firebase integration.

## Project Structure

```text
Website/
├── index.html            # Standalone single-file production website
├── favicon.ico           # Website favicon
├── README.md             # Project documentation
└── src/                  # Modular development source files
    ├── index.html        # Clean HTML linking external CSS and JS
    ├── favicon.ico       # Website favicon
    ├── css/
    │   └── style.css     # Formatted Tailwind CSS & animations
    └── js/
        ├── app.js        # Client application bundle with StaRk branding
        └── app.formatted.js # Beautified / formatted bundle for easy editing
```

## How to Run Locally

You can open the website in any modern web browser:

### Method 1: Direct File Opening
Double-click `index.html` or open it with your browser.

### Method 2: Local HTTP Server (Recommended)
Using Python:
```bash
python -m http.server 8080
```
Then visit `http://localhost:8080` or `http://localhost:8080/src/`.

### Method 3: Using Node / npx
```bash
npx serve .
```

## Application Details
- **Title**: StaRk Panel
- **Branding**: StaRk Device Management Console & Admin Console
- **Framework**: React 18, Tailwind CSS, Lucide Icons, JSZip
- **Functionality**: Device management panel with Firebase Realtime Database integration.
