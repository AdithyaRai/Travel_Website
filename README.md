# Pack & GO!

Static website showcasing travel destinations (France, Italy, Japan, Australia, Greece, India).

## Purpose
Simple portfolio-style site to present destination cards and navigation for each country.

## Project structure
- index.html / pack_and_go.html — main page (index.html is the site entry)
- style.css — styles for layout and responsiveness
- about.html, contact.html, france.html, italy.html, japan.html, australia.html, greece.html, india.html — content pages
- favicon.ico — site icon
- images/ (optional) — put destination images here

## Run locally (Windows)
1. Open PowerShell:
   cd "c:\Users\Adithya\Documents\C++ Assignment\Web Technology"
2. Start a quick server:
   python -m http.server 8000
3. Open http://localhost:8000/ in your browser.

Or open index.html directly.

## Deploy (recommended: GitHub Pages)
1. Create a GitHub repo.
2. From PowerShell:
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
3. On GitHub: Settings → Pages → Deploy from branch `main` (root). Your site will be available at https://<your-username>.github.io/<repo>/.

Other hosts: Netlify (drag & drop or CLI) or Vercel (CLI).

## Notes & suggestions
- Use `images/` folder and update CSS image paths if needed.
- For better accessibility, replace background-image cards with <img> elements and add alt text.
- Test responsiveness in browser DevTools (mobile/tablet/desktop).

## License & author
Created by Adithya Rai. Use and modify freely for learning and non-commercial projects.
```// filepath: c:\Users\Adithya\Documents\C++ Assignment\Web Technology\README.md
