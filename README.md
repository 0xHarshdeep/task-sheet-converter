# Bulk Task Sheet Formatter (Standalone Web App)

A completely standalone, zero-dependency client-side web application to convert any client Google Sheet, raw table, or CSV into the exact format required by the Reddit Microtasks Discord bot (`/bulktask`).

## 🚀 Features

- **100% Client-Side**: No backend, no database, no Node.js/Python server needed. Runs directly in any web browser.
- **Smart Column Detection**: Auto-detects Reddit post URLs and pre-written comment text regardless of column names (`Posts link`, `comment content`, `Reddit URL`, etc.).
- **Banner/Header Filter**: Automatically cleans out dates, banner labels, empty rows, and non-URL metadata rows.
- **Configurable Defaults**: Adjust default reward (e.g. `$1.00`), slots, hold hours (e.g. `24h`), and task type (`comment`, `post`).
- **Interactive Editor**: Preview all extracted tasks, edit values, check duplicate links, and calculate campaign budget.
- **1-Click Export**:
  - **"Copy for /bulktask"**: Formats and copies standard CSV directly to your clipboard, ready to paste straight into Discord's `/bulktask` modal.
  - **"Download Clean CSV"**: Saves as a clean `.csv` file.

## 💻 How to Run

### Method 1: Open Locally in Browser
Simply open `index.html` in your web browser:
```bash
xdg-open /home/harshdeep/task-sheet-converter/index.html
# or double-click index.html in file manager
```

### Method 2: Host for Free (Zero Server)
You can deploy this folder to any free static host in 30 seconds:
- **GitHub Pages**: Push this folder to a GitHub repository and turn on Pages under repo Settings.
- **Vercel / Netlify / Cloudflare Pages**: Drag and drop the `index.html` file.
