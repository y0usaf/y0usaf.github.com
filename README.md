# Resume Website

This site renders directly from `resume.tex` in GitHub.

## Source of truth

`index.html` fetches the latest `resume.tex` at runtime from:

`https://raw.githubusercontent.com/y0usaf/y0usaf.github.com/main/resume.tex`

No local build script is required.

## Update flow

1. Update `resume.tex` in the source repo.
2. Push changes.
3. Reload the site.
