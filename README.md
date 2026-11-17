# Yun Kang — personal academic website

This repository contains Yun Kang's static, responsive academic website. It was
rebuilt from the available legacy ASU Public Web files and revised in November
2026 using the current curriculum vitae as the authoritative academic source.

## Structure

- `index.html` — academic profile and research overview
- `research.html` — research programs and topics
- `lab.html` — Mathematical Modeling Lab
- `publications.html` — selected recent and representative publications
- `people.html` — current researchers, PhD alumni, and scholars
- `teaching.html` — teaching philosophy, curriculum, and courses
- `mentoring.html` — mentoring philosophy and pathways
- `conferences.html` — academic leadership, talks, and service
- `assets/` — shared responsive styles and navigation behavior

Legacy filenames redirect to their new locations so old bookmarks continue to work.

## Design and content

The site preserves the ASU maroon-and-gold visual identity while using an
original, accessible design with responsive navigation, semantic HTML,
structured profile metadata, reduced-motion support, and print styling.

## Legacy source limitations

The supplied archive did not include the original `files/` or `pictures/`
folders. Missing image and download references were not carried into the new
public presentation. The original content remains recoverable from repository
history if those source assets become available later.

## GitHub Pages

This project is published from the public repository
`yunkang2021/yunkang2026.github.io`. Because the repository name does not match
the account name, its GitHub Pages address is:

`https://yunkang2021.github.io/yunkang2026.github.io/`

The workflow in `.github/workflows/pages.yml` deploys the static files whenever
the `main` branch changes. In the repository's **Settings → Pages**, set the
publishing source to **GitHub Actions** before the first deployment.
