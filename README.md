# Lee Sungyo — Engineering Portfolio

A responsive, buildless portfolio for GitHub Pages. Content is based on the supplied current CV. No package installation, external font service, or JavaScript is required.

## Publish to the existing `resume` repository

1. Upload `index.html`, `styles.css`, and `lee_sungyo_cv.pdf` to the repository's top level, replacing the previous HTML and CSS. Keep these filenames exactly as written. The PDF is already included in this package.
2. Optionally upload `.nojekyll` (included as a hidden file) to skip Jekyll processing when publishing from a branch.
3. Keep the existing Pages source if its deployment works. For a simple branch deployment, use **Settings → Pages → Deploy from a branch → main → /(root) → Save**. If changing from an old custom Pages workflow to branch publishing, disable that old deployment workflow under **Actions** to avoid two deployment paths.
4. Check the latest deployment under **Actions**, then use **Settings → Pages → Visit site** to get the final URL. Without a custom domain, the expected project URL is `https://1sk9ine.github.io/resume/`.
5. Add the website URL to LinkedIn's Featured section as a link.

The files should be at the repository root, rather than inside another `site` or ZIP folder. GitHub does not extract uploaded ZIP files; extract this package first.

## Update content

- `index.html`: biography, projects, experience, education, contact links, and metadata.
- `styles.css`: all colors, typography, responsive layouts, and print styles.
- `lee_sungyo_cv.pdf`: replace with a new PDF using the same filename to retain working view/download links.

Project implementation notes expand using native HTML disclosure controls. The project visuals are illustrative design elements, not screenshots of the projects. The GPU baseline timing is explicitly identified as a direct-convolution baseline, not a fused-kernel speed result. No unverified per-project repository links are included.

The website uses the LinkedIn URL and email from the attached CV, and the GitHub profile from the original website. The original high-school awards section and placeholder project have been replaced with current engineering work. The PDF itself is unchanged.
