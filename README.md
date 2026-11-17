# Yun Kang — personal academic website

This repository is a static, responsive GitHub Pages migration of the available files from Yun Kang's legacy ASU Public Web site.

## Structure

- `index.html` — biography, contact information, research interests, awards, and service
- `research.html` — research programs and topics
- `lab.html` — Modeling Lab for Social Insects
- `publications.html` — peer-reviewed publications, submissions, and preprints
- `people.html` — students, researchers, visitors, and collaborators
- `teaching.html` — archived teaching information
- `mentoring.html` — Math–Social Biology Co-Mentoring Program
- `conferences.html` — mathematical biology conferences
- `assets/` — shared responsive styles and navigation behavior

Legacy filenames redirect to their new locations so old bookmarks continue to work.

## Source limitations

The supplied archive did not include the original `files/` or `pictures/` folders. The migrated site therefore removes missing image placeholders and renders unavailable local downloads as clearly labeled archived resources instead of broken links. Add those folders later and restore the corresponding links when the assets become available.

## GitHub Pages

This project is published from the public repository
`yunkang2021/yunkang2026.github.io`. Because the repository name does not match
the account name, its GitHub Pages address is:

`https://yunkang2021.github.io/yunkang2026.github.io/`

The workflow in `.github/workflows/pages.yml` deploys the static files whenever
the `main` branch changes. In the repository's **Settings → Pages**, set the
publishing source to **GitHub Actions** before the first deployment.
