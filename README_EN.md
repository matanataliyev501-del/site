# Fortuna Apps — GitHub Pages website

This is an upload-ready, multi-page bilingual website. The ZIP archive root **is the GitHub Pages repository root**. Each HTML file embeds its CSS and JavaScript so there are no missing assets if the repo does not contain a separate CSS folder. There are no external fonts, logo images or web framework dependencies.

## Pretty routes

Pages use folders containing `index.html` (`careers/index.html` for `/careers/`, etc.). English: `/`, `/careers/`, `/start-a-project/`, `/what-we-do/`, `/goals/`, `/about/`, `/process/`, `/contact/`, `/privacy/`; Polish: `/pl/` and equivalent subfolders. Internal links work under a GitHub Pages project prefix or on a custom domain.

## Deployment

1. Remove obsolete `*.html` pages and the old `assets` folder from the repository. Preserve `CNAME` if you already have a custom domain.
2. Upload **all extracted content**, with folders intact, into the repository root so `index.html` exists at that root.
3. In GitHub Settings → Pages, choose Deploy from a branch / main / (root).
4. Check the site and hard refresh your browser if necessary.

Forms submit to FormSubmit.co for hello@fortuna-apps.com and require email verification and a real delivery test. The privacy page is a draft that needs legal review before launch. Talent cards represent interest areas (not confirmed vacancies).
