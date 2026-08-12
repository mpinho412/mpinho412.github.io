# mpinho412.github.io

Personal portfolio website of **Miguel Pinho** - Industrial &amp; Systems Engineering student at Virginia Tech.

Live site: https://mpinho412.github.io/

## Built with

- [Astro](https://astro.build/) static site framework
- Plain CSS (no framework), Poppins via Google Fonts
- Deployed automatically to GitHub Pages by the workflow in `.github/workflows/deploy.yml`

## Project structure

```
.
|- public/
|  `- profile.jpg          # hero portrait
|- src/
|  |- pages/
|  |  `- index.astro       # all page content + resume data
|  `- styles/
|     `- global.css        # site-wide styling
|- astro.config.mjs
`- package.json
```

## Editing the content

All resume content (experience, leadership, skills, awards, contact details) lives in the
frontmatter arrays at the top of `src/pages/index.astro`. Edit those arrays and push to
`main` - GitHub Actions rebuilds and redeploys the site automatically.

## Running locally

```bash
npm install
npm run dev
```
# mpinho412.github.io
Personal portfolio website of Miguel Pinho - built with Astro
