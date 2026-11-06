# What Lies Beyond the Stars — Volume One

**Official digital reading edition by the QORA Editorial Circle.**

A responsive online publication page and interactive reader for *What Lies Beyond the Stars: The Qur’an, the Big Bang, and the Search for the Edge of Reality*.

## Open the website

After enabling GitHub Pages, the site will be available at:

`https://YOUR-GITHUB-USERNAME.github.io/what-lies-beyond-the-stars/`

Replace `YOUR-GITHUB-USERNAME` with your GitHub username.

## Repository structure

```text
.
├── index.html
├── chapters.json
├── .nojekyll
└── assets/
    ├── cover.jpg
    └── what-lies-beyond-the-stars-volume-one.pdf
```

## Publish with GitHub Pages

1. Create a **public** repository named `what-lies-beyond-the-stars`.
2. Extract this ZIP archive on your computer.
3. Open the repository on GitHub and choose **Add file → Upload files**.
4. Upload the contents of the extracted folder: `index.html`, `chapters.json`, `.nojekyll`, and the complete `assets` folder. Keep the folder structure exactly as shown above.
5. Commit the upload to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main`, folder `/(root)`, then click **Save**.
9. Wait for the Pages deployment to finish, then open the URL above.

## Reader features

- Responsive QORA publication landing page
- Interactive PDF page rendering
- Previous / next page navigation
- Fit-width and zoom controls
- Chapter shortcuts and page thumbnails
- Search across selectable PDF text
- Reading position saved locally in the browser
- Direct PDF download and direct-open fallback
- Social sharing metadata

## Technical note

The interactive viewer loads PDF.js from cdnjs, so the enhanced viewer needs an internet connection. The direct PDF link remains available as a fallback. The PDF and cover are stored in this repository and served from the relative `assets/` paths.

## Publication rights

The repository intentionally includes no open-source software license. Do not add a license that grants reuse rights to the book unless the rights holder has decided to do so. Confirm that you control the rights to publish the manuscript and cover before making the repository public.
