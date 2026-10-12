# Eliazel Hitwamata — Portfolio

Responsive, dark-themed React portfolio for QA engineering, test automation, web development and digital product concepts.

## Run locally
Requires Node.js 20.19+ and npm.

```bash
npm install
npm run dev
```

Build for production with `npm run build`.

## Personalise
- Profile details are in `src/config.js`.
- Add a real LinkedIn profile URL there when ready; the link stays hidden until one is supplied.
- Add a CV at `public/Eliazel-Hitwamata-CV.pdf`, or remove/change the CV path in the config.
- Check the experience descriptions and dates for accuracy before sharing.
- Project cards are explicitly labelled as demos or concepts where appropriate; add repository links only for code that is actually published.

## Publish on GitHub Pages
This repository is configured for the project-site URL:

https://hitwamata.github.io/portifolio-eliazel/

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/deploy.yml` builds the Vite app and deploys it on pushes to `main`.
4. Check the **Actions** tab for the build/deployment status. The site is live only after a successful deployment.

## Stack
- React + Vite
- TypeScript/Playwright featured in QA portfolio examples
- Lucide React icons
- Responsive custom CSS
