# Louay Blel — Interactive Portfolio

A responsive, interactive portfolio for **Louay Blel** (`@blellouay`). Built with plain HTML, CSS, and JavaScript, without a framework or build tooling.

## Features

- Responsive animated layout with dark/light theme toggle
- Project filters for GenAI, machine learning, and computer vision
- GitHub public API integration for live repository star counts and repository count (with a fallback when offline / rate limited)
- Career timeline, technical skills, verified project results, contact button
- Reduced-motion accessibility support
- No tracking, API keys, paid hosting or dependencies required

## How to deploy on GitHub Pages

1. On GitHub, create a **public repository named `blellouay.github.io`** in your `blellouay` account.
2. Add the `index.html`, `styles.css`, and `script.js` files to the repository root. Include this README if desired.
3. Open **Settings → Pages → Build and deployment**.
4. Set **Source: Deploy from a branch**, then **Branch: main**, folder **/(root)**, and save.
5. Once deployed, visit **https://blellouay.github.io/**.

You can also choose a different repository name, then your site URL is `https://blellouay.github.io/REPOSITORY-NAME/`.

## Edit the content

- **Projects:** Edit the `projects` array in `script.js`. Only set `repo` for projects you actually published. Keep `repo: null` otherwise.
- **Text, skills, experience:** Edit `index.html`.
- **Colors, layout, visual design:** Edit CSS variables at the top of `styles.css`.
- **LinkedIn:** Add your own verified profile URL before publishing it.
- **Education status:** The supplied CV lists ESSAI, 2024–present. Confirm and update the date on the site if needed.

## Important distinctions

This is a **GitHub Pages website**, not an interactive GitHub profile README: GitHub strips JavaScript from profile READMEs. You should keep the separate `blellouay` profile README and put the website URL in the README, GitHub bio, and profile Website field.

The supplied CV included personal contact information. The site publishes **email only**, not the phone number. Do not upload private internship documents, private data, model weights, or confidential employer materials.

The GitHub API is public and rate-limited. The site works without it, using curated project descriptions.

## Local preview

Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and open `http://localhost:8000`.
