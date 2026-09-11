# Project Visualization Portfolio

A single-page, mobile-friendly video portfolio designed for static hosting with GitHub Pages. Visitors select a project discipline to open its Vimeo video and view the projects featured in that category.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`, then click **Save**.

GitHub will provide a public URL after the first deployment finishes, usually in a few minutes.

## Update the content

Page content, styling, Vimeo IDs, and project lists are contained in `index.html`.

- Edit the `categories` array near the bottom of `index.html` to change categories, videos, or project names.
- Each `video` value should be the numeric Vimeo video ID.
- Vimeo videos must allow embedding for playback inside the page.
- Replace `assets/logo-placeholder.svg` with your logo. You can keep the same filename, or update the image path in `index.html`.
- Replace `assets/favicon.svg` with your favicon. If you use PNG or ICO instead, update the favicon filename and `type` in `index.html`.

## Files

- `index.html` — complete website
- `assets/logo-placeholder.svg` — replaceable header logo
- `assets/favicon.svg` — replaceable browser favicon
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files
- `README.md` — setup and editing instructions

No build process, package installation, or server-side code is required.
