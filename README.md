# Cryptography Homework 1 — Exercises 1 and 2

**Author:** Mattia Livieri  
**Language:** English  
**Date:** 15 October 2026

Two independent, self-contained HTML submissions, labelled Homework 1.1 and Homework 1.2 for the two exercise columns in the course submission sheet. Each file includes its report, CSS, JavaScript, datasets, references and dedicated verification checks. They do not depend on each other.

| File | Contents |
| --- | --- |
| `homework1-1.html` | Toy elliptic-curve scalar multiplication, animated steps, statistical analysis and five built-in checks. |
| `homework1-2.html` | Ethereum wallet pipeline, an executable public-mnemonic example, statistical experiments and twelve built-in checks. |
| `index.html` | Optional landing page linking to both assignments. |
| `.nojekyll` | Publishes these static files without a Jekyll build. |

## Run locally

Open either HTML file in a current browser. No installation or external dependencies are needed. Homework 1.2 uses native Web Crypto for SHA-2, HMAC and PBKDF2; the saved report remains readable if that API is unavailable. Examples contain public test data and are educational implementations.

## Publish with GitHub Pages

1. Extract this ZIP on your computer and upload its contents to the root of your GitHub repository. Commit the files; do not upload only the ZIP.
2. Open the repository's **Settings → Pages**. Choose **Deploy from a branch**, select the branch containing the files (for example `main`) and the **/(root)** folder, then save.
3. Wait for the deployment to finish. GitHub displays the published website URL under **Settings → Pages**.
4. Open both assignment pages from the landing page and copy their browser URLs into the corresponding Homework 1.1 and Homework 1.2 cells in your course's Google Sheet.

For a project site with base URL `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`, the two separate submission URLs have this structure:

| Assignment | Live URL template |
| --- | --- |
| Homework 1.1 | `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/homework1-1.html` |
| Homework 1.2 | `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/homework1-2.html` |

The username and repository in these templates are placeholders. Use your actual published Pages URL, which may differ for user sites, organizations or custom domains.

The live GitHub Pages URL runs the interactive program. A `github.com/.../blob/...` URL displays its HTML source in the repository. Both HTML files include the complete implementation for source-code review.

Official GitHub documentation: [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Course submission labels

| Submission field | Page | Label |
| --- | --- | --- |
| Column B — Exercise 1 LINK | `homework1-1.html` | Homework 1.1 — Toy elliptic-curve multiplication |
| Column C — Exercise 2 LINK | `homework1-2.html` | Homework 1.2 — Ethereum wallet pipeline |

The root `index.html` is the navigation page. Each exercise also has its own direct URL for the corresponding submission field. The 1.1 / 1.2 labels organize the two existing exercises; their calculations and statistical experiments are unchanged.
