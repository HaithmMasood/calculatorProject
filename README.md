# React Calculator (No Build Tools)

A simple calculator built with React 18 and rendered directly in the browser using CDN scripts and Babel. No Node.js or bundlers required.

## Run Locally

- Double-click `index.html` to open it in your browser.
- Requires internet access to load React and Babel from CDNs.
- Keyboard shortcuts: `0-9`, `.`, `+ - * /`, `Enter` for equals, `Esc` to clear.

## Project Structure

- `index.html` — All markup, styles, and React code in one file (for simplicity).

## Push to GitHub

1. Initialize Git and commit:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: React calculator"
   git branch -M main
   ```
2. Create an empty GitHub repo (via UI) and copy its URL (e.g. `https://github.com/<you>/<repo>.git`).
3. Add the remote and push:
   ```bash
   git remote add origin <REPO_URL>
   git push -u origin main
   ```

## Notes

- This setup is great for quick prototypes. For production apps, consider a build tool (e.g., Vite) and local dependencies instead of CDNs.
