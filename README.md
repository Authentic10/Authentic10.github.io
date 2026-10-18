# Ahmed Tchagnaou

Personal portfolio — https://atchagnaou.me

This website uses [hugo-noir](https://github.com/prxshetty/hugo-noir), which is licensed under the MIT License.

## Development

Requirements: [Hugo extended](https://gohugo.io/installation/) 0.157.0 and Node.js.

```sh
git submodule update --init   # theme
npm ci                        # Tailwind CSS
hugo server                   # http://localhost:1313
```

Content lives in `data/{fr,en}/*.yaml` (experience, projects, tech stack, certifications) and `content/`.
Pushing to `main` deploys to GitHub Pages (`.github/workflows/gh-pages.yml`).
