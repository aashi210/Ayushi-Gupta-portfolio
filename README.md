# Ayushi Gupta — Portfolio

A responsive React portfolio built with Vite and modern CSS.

The repository includes a GitHub Actions workflow that builds the Vite site and deploys it to GitHub Pages whenever `main` is updated.

## Open the portfolio

For a quick preview, double-click `index.html` (or reopen it in your browser). It includes a self-contained static fallback so the portfolio renders when opened directly as a file.

## Run the React app locally

Install Node.js, then run these commands from this directory to use the React app with Vite:

```sh
npm install
npm run dev
```

For a production build, run `npm run build`; Vite writes the site to `dist/`.

## Publish to GitHub Pages

1. Create a **public** repository on GitHub named `ayushi-gupta-portfolio`.
2. From Terminal, run the following commands (replace `YOUR_GITHUB_USERNAME`):

   ```sh
   cd "/Users/ayushigupta/Documents/Codex/2026-11-23/project-build-a-premium-personal-portfolio/outputs/portfolio"
   git init
   git add .
   git commit -m "Add Ayushi Gupta portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/ayushi-gupta-portfolio.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
4. Open **Actions** and wait for “Deploy portfolio to GitHub Pages” to finish. The published URL appears in that run and follows `https://YOUR_GITHUB_USERNAME.github.io/ayushi-gupta-portfolio/`.

GitHub Pages is available for public repositories on GitHub Free; private repositories require a paid plan. The public repository and site expose the portfolio content, including its contact details.

## Supplied assets

- `public/assets/ayushi-gupta.jpg` is the optimized portrait used by the React build. `assets/ayushi-gupta.jpg` supports the direct-file preview.
- The LinkedIn Learning and Jio AI certificate scans were not included in the supplied files. To show their original previews, add them at `public/assets/linkedin-learning-certificate.png` and `public/assets/jio-ai-certificate.png`. The site does not synthesize certificate images.
- No resume PDF was supplied, so the site does not show a nonfunctional download button.

## Content notes

The portfolio uses the education, project, skills, language, interest, certificate, and contact details provided for this project. Date of birth is omitted for privacy. No awards, work experience, GitHub links, or project URLs have been invented.
