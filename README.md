# Currency Converter Support Website

This repository contains the static support website for the iOS App "Currency Converter - Pro rate".

## Features
- Pure HTML and CSS (no frameworks)
- Fully responsive on all mobile devices
- "Dark, modern, premium" aesthetic
- Includes:
  - `index.html` (Landing/FAQ)
  - `privacy.html` (Privacy Policy)
  - `terms.html` (Terms of Use)

## Deployment to GitHub Pages

To deploy this site on GitHub Pages, follow these steps:

1. **Initialize Git Repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit of static support site"
   ```

2. **Create a GitHub Repository:**
   - Go to [GitHub](https://github.com/new).
   - Create a new public repository (e.g., `currency-converter-support`).
   - Do not initialize with a README, .gitignore, or license.

3. **Push to GitHub:**
   ```bash
   git remote add origin https://github.com/your-username/your-repo-name.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to your repository settings on GitHub.
   - Navigate to the **Pages** section on the left sidebar.
   - Under **Build and deployment > Source**, ensure `Deploy from a branch` is selected.
   - Under **Branch**, select `main` and `/ (root)`, then click **Save**.
   
5. **View Your Site:**
   - It may take a couple of minutes for GitHub to build and deploy the site. Once ready, your site will be live at `https://your-username.github.io/your-repo-name/`.

## Local Development
Since this site contains no build steps or frameworks, you can simply open `index.html` in your favorite web browser (e.g., Safari or Chrome) to preview the pages.
