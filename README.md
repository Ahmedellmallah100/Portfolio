# Ahmed Hamed Ellmallah – Portfolio

Static portfolio (HTML, CSS, JavaScript). No build step, no dependencies.

## Before publishing
1. Your photo is `assets/photo.jpg` and project images are in `assets/`. Replace those files to change them.
2. Optional: add your GitHub profile link in the hero `.social` block, and repo buttons inside each project card (see the comment in `index.html`).

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Deploy to GitHub Pages
1. Create a new repository on GitHub (for example `portfolio`).
2. Upload all files from this folder, including the hidden `.github` folder, to the `main` branch.
3. In the repository go to **Settings > Pages**, and under **Source** choose **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` runs on every push to `main`. When it finishes, the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Update later
Edit `index.html` (all content), `style.css` (design), or replace `assets/photo.jpg`, then commit to `main`. The site redeploys automatically.
