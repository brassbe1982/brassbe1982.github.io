# Prof. Ibrahim Niankara — Academic Website

Source code for the personal academic website of **Prof. Ibrahim Niankara**, Professor of Applied Economics and Digital Innovation at the College of Business, Al Ain University, UAE.

Built with [Quarto](https://quarto.org/), modeled after the template of [Dr. Gang He](https://drganghe.github.io).

## Structure

| File / Folder | Purpose |
|---|---|
| `_quarto.yml` | Site configuration (navbar, theme, metadata) |
| `index.qmd` | Home page with bio and links |
| `publications.qmd` | Full publications listing |
| `publications.yml` | Publications data (auto-converted from XLSX or hand-edited) |
| `teaching.qmd` | Courses taught |
| `research.qmd` | Research interests & current projects |
| `now.qmd` | What I'm working on right now |
| `contact.qmd` | Contact information |
| `posts/` | Blog-style posts (papers, news, events) |
| `files/` | PDFs, images, scripts |
| `docs/` | Rendered HTML output (GitHub Pages) |

## Build

```bash
quarto render
```

Output is placed in `docs/` and served by GitHub Pages.

## Deploy

Push the `docs/` folder to GitHub. Configure GitHub Pages to serve from `docs/` on the `main` branch.

## License

[MIT License](LICENSE)
