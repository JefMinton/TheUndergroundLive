# The Underground Live - Website

Official website for The Underground Live, a premier live music venue in Camp Hill, PA.

## 🌐 Live Website

**Deployed at:** `https://jefminton.github.io/TheUndergroundLive/`

The site is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the main branch or this PR branch.

## About The Venue

The Underground Live is located at 1104 Carlisle Rd, Camp Hill, PA 17011. We are a community-focused music venue supporting local musicians and hosting unforgettable concerts featuring diverse genres from rock and blues to metal and alternative.

## Website Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **About Section**: Information about the venue and what makes it special
- **Workshops Section**: Details about upcoming educational workshops and events
- **Contact Information**: Location, social media links, and venue details
- **Modern UI**: Clean, professional design with smooth animations

## How to View the Website

Simply open `index.html` in any modern web browser. No build process or dependencies required!

### Quick Start
```bash
# Open the website directly in your default browser
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

Or you can use a simple HTTP server:
```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000 in your browser
```

## File Structure

- `index.html` - Main website HTML structure
- `styles.css` - All styling and responsive design rules
- `script.js` - JavaScript for smooth scrolling and animations
- `README.md` - This file

## Customization

### Updating Workshop Information

To add or modify workshops, edit the `index.html` file and locate the workshops section (starting around line 84). Each workshop is contained in a `workshop-card` div. You can:
- Update workshop titles and descriptions
- Change dates from "Coming Soon" to actual dates
- Add new workshop cards by copying the existing structure
- Modify duration and level information

### Updating Venue Information

Venue details can be updated in the contact section (starting around line 140) and about section (starting around line 42).

## Browser Compatibility

This website works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## 🚀 Deployment

This site is configured for automatic deployment to GitHub Pages:

1. **Automatic Deployment**: The site deploys automatically when changes are pushed to the main branch or PR branch
2. **GitHub Actions**: Uses the `.github/workflows/deploy-pages.yml` workflow
3. **Live URL**: Once deployed, the site will be available at `https://jefminton.github.io/TheUndergroundLive/`

### Manual Deployment

To enable GitHub Pages manually (first-time setup):
1. Go to repository Settings → Pages
2. Under "Build and deployment", select "GitHub Actions" as the source
3. The workflow will automatically deploy on the next push

## Social Media

Follow us on Facebook: [@TheUndergroundLiveMusic](https://www.facebook.com/TheUndergroundLiveMusic)

## License

All content © 2026 The Underground Live. All rights reserved.
