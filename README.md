# Innovation Lens Resources Ltd — Website

Official website for **Innovation Lens Resources Ltd**, a professional business services firm delivering turnaround solutions in IT/Telecom and Management Consulting.

## Live Site
[https://innolensresources.com](https://innolensresources.com)

## Tech Stack
- Pure HTML5, CSS3, Vanilla JS
- No build tools, no dependencies
- Google Fonts (Playfair Display + DM Sans)
- Deployable to any static host (GitHub Pages, Netlify, Vercel, cPanel)

## Project Structure
```
innolensresources/
├── index.html          # Main website (single page)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── assets/             # (add images, icons here when ready)
    ├── images/
    └── favicon/
```

## Local Development
No build step needed. Just open `index.html` in a browser:

```bash
# Option 1: Direct open
open index.html

# Option 2: VS Code Live Server (recommended)
# Install the Live Server extension, right-click index.html > Open with Live Server

# Option 3: Python simple server
python -m http.server 8080
# Then visit http://localhost:8080
```

## Deployment

### GitHub Pages
1. Push to GitHub (see below)
2. Go to repo Settings > Pages
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io/innolensresources`
5. Add custom domain `innolensresources.com` in the Pages settings

### Netlify (drag and drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag the entire project folder onto the deploy area
3. Set custom domain in site settings

### cPanel / Traditional Hosting
Upload `index.html` (and assets folder) to `public_html/`

## TODO
- [ ] Connect contact form (Formspree or EmailJS)
- [ ] Add favicon
- [ ] Add OG meta tags for social sharing
- [ ] Add actual phone number and full address
- [ ] Add LinkedIn URL in footer
- [ ] Create `assets/images/` folder and add any photos/logos
