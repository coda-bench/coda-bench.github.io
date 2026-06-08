# CODA-BENCH Website

This directory contains the production build of the CODA-BENCH website, ready for deployment to GitHub Pages.

## Deployment Instructions

### 1. Create a GitHub Repository

Create a new repository named `<username>.github.io` or use a project repository.

### 2. Push Files to GitHub

```bash
cd web
git init
git add .
git commit -m "Initial commit: CODA-BENCH website"
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**

Your website will be available at:
- User/Organization site: `https://<username>.github.io`
- Project site: `https://<username>.github.io/<repo-name>`

## Files Overview

- `index.html` - Main HTML file
- `assets/` - CSS, JavaScript, and images
- `trajectories/` - Agent trajectory data (JSONL format)
- `traj/homepage_traj/` - Homepage trajectory metadata
- `data/` - Dataset metadata
- `.nojekyll` - Prevents Jekyll processing (required for GitHub Pages)
- `favicon.ico` - Site icon

## Built with

- Vue 3
- Vite
- Custom CSS

## License

See main repository for license information.
