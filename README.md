# The Status Quo Immobilization Movement — starter website

This is a self-contained Jekyll starter for free GitHub Pages hosting plus Pages CMS editing.

## Upload and publish

1. Create a PUBLIC repository named YOUR_GITHUB_USERNAME.github.io.
2. Extract this ZIP onto your computer. In the GitHub repository, choose **Add file > Upload files**. Upload the *contents* of the extracted starter folder, maintaining the folders. Do not upload the ZIP itself or put everything inside a nested `status-quo-starter/` directory.
3. Some computers hide `.pages.yml`. On macOS use Command-Shift-period to show hidden files in Finder. Ensure `.pages.yml` is in your repository root.
4. In GitHub choose **Settings > Pages > Build and deployment > Deploy from a branch > main > /(root)** and save.
5. The site becomes available at https://YOUR_GITHUB_USERNAME.github.io after deployment completes.
6. Go to https://app.pagescms.org/ and sign in through GitHub. Install the Pages CMS GitHub App on the selected repository. Open the repo, select Official Publications, and create new stories.
7. To connect your own domain, use **Settings > Pages > Custom domain** and then set the DNS records in your domain provider according to GitHub's documentation. Set the custom domain on GitHub BEFORE changing DNS at your registrar.

## Contents

- `index.html`: Institutional homepage with automatically updated recent publications.
- `_layouts/`: Shared site design and individual article layout.
- `_posts/`: Markdown stories and institutional notices.
- `publications/index.html`: Automatically generated publication listing.
- `charter`, `departments`, `membership`, `about`: Editable institutional pages.
- `.pages.yml`: Pages CMS configuration. Do not rename.
- `_config.yml`: Jekyll settings and layout defaults.
- `assets/style.css`: Institutional styling.

New stories become Jekyll posts using date-based Markdown filenames. They automatically appear on Home and Publications. This template does not install comments: GitHub Pages is static, and comments require an external service, such as giscus (which requires readers to sign into GitHub) or another comment provider.

This is a starter for a **fictional** satirical institution, not a real political organisation. Edit the visible copy in Pages CMS.
