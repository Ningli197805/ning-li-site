# Ning Li personal site

This directory is a self-contained static website for GitHub Pages.

## Publishing

1. Create a GitHub repository.
2. Push this directory as the repository root.
3. In repository Settings → Pages, choose **Deploy from a branch**.
4. Select the main branch and the repository root (`/`).
5. Save and wait for the GitHub Pages deployment to finish.

No build command, Node runtime, database, server middleware or GitHub Actions workflow is required.

## Site structure

- `/`: Chinese homepage
- `/en/`: English homepage
- `/marathon/`: Chinese marathon pages
- `/en/marathon/`: English marathon pages
- `/practices/`: Chinese leading-practice page
- `/en/practices/`: English leading-practice page
- `/credits.html`: photo sources and usage boundaries

## Current boundaries

- The Yili client case is intentionally excluded pending client disclosure permission.
- The formal portrait, work photograph and marathon photograph were supplied by Ning Li. Photographer, event-organizer and race-photo permissions must be confirmed before public deployment.
- The site uses a mail link. It does not process form submissions, payments or sensitive data.
- The custom domain is not configured in this package. A `CNAME` file should be added only after DNS is ready.
