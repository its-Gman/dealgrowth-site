# DealGrowth Website

Autonomous Revenue Systems — AI sales automation that scales without headcount.

## Local Development

```bash
npx serve .
```

Or simply open `index.html` in your browser.

## Deploy to Production

### Option 1: Vercel (Recommended)

1. Push to GitHub (see below)
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your GitHub repository
4. Click **Deploy** — zero config needed for static HTML
5. Add your custom domain in Project Settings > Domains

### Option 2: GitHub Pages (Free)

1. Push to GitHub (see below)
2. Go to repo Settings > Pages
3. Source: Deploy from a branch → `main` / `root`
4. Site live at `https://yourusername.github.io/dealgrowth-site`

### Push to GitHub

```bash
gh repo create dealgrowth-site --public --source=. --push
```

Or manually:

```bash
git remote add origin https://github.com/YOUR_USERNAME/dealgrowth-site.git
git branch -M main
git push -u origin main
```

## File Structure

```
├── index.html          # Main page
├── assets/
│   ├── bg-video.mp4    # Hero background video
│   ├── poster.png      # Video poster frame
│   └── Deal Growth AI.png  # Logo
└── README.md
```

## Tech Stack

- Pure HTML5 + CSS3 (no frameworks)
- Custom cursor, scroll reveal animations
- Responsive design
- ~46KB total (excluding video)
