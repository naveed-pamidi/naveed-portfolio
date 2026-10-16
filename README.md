# Naveed Pamidi: Developer Portfolio

A static portfolio site (HTML + CSS) served with Vite. No JavaScript framework needed.

## Project structure

```
naveed-portfolio/
  index.html          Page content (Experience, Projects, Skills, Education, Contact)
  src/styles.css      All styling, with light and dark mode
  public/favicon.svg  Browser tab icon
  package.json        Scripts and dependencies
```

## Run it on Windows with VS Code

1. Install Node.js (LTS) from https://nodejs.org if you don't have it. Check with `node -v`.
2. Unzip the folder, then in VS Code choose File > Open Folder and select `naveed-portfolio`.
3. Open the terminal (Ctrl + `) and run:

```
npm install
npm run dev
```

4. Open http://localhost:5173 in your browser. Edits to `index.html` and `src/styles.css` refresh the page automatically.

## Build for hosting

```
npm run build
```

This creates a `dist` folder. Upload its contents to Netlify, Vercel, GitHub Pages, or any static host.

## Without Node.js

Open `index.html` with the VS Code Live Server extension (recommended in `.vscode/extensions.json`).
Opening the file by double-click will not load the stylesheet because it uses a root-relative path.

## Notes

- Fonts (Bricolage Grotesque and Source Serif 4) load from Google Fonts, so you need an internet connection for the exact look.
- To change content, edit the text in `index.html`. To change colors, edit the variables at the top of `src/styles.css`.
- PowerShell error "running scripts is disabled"? Run `Set-ExecutionPolicy -Scope CurrentUser RemoteSigned` once, or use Command Prompt instead.
