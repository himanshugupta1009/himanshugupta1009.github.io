# himanshugupta1009.github.io

Source for my personal academic website: https://himanshugupta1009.github.io

It's built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template. Every push to `master` triggers a GitHub Actions build (`.github/workflows/deploy.yml`), which publishes the site to the `gh-pages` branch.

## Common updates

| To change...              | Edit                                                                 |
| ------------------------- | -------------------------------------------------------------------- |
| Bio / intro text          | `_pages/about.md`                                                    |
| Photo                     | replace `assets/img/prof_pic.jpg`                                    |
| Publications              | `_bibliography/papers.bib` (`selected = {true}` shows it on the home page) |
| Venue badge colours       | `_data/venues.yml`                                                   |
| News items                | add a file in `_news/` (copy an existing one, change `date` and text) |
| CV (currently hidden)     | add `_pages/cv.md` + a PDF in `assets/pdf/` (see git history)       |
| Social links              | `_data/socials.yml`                                                  |
| Site name, URL, features  | `_config.yml`                                                        |

Useful BibTeX fields per entry: `abbr` (venue badge), `pdf`, `arxiv`, `website`, `code`, `video`, `slides`, `selected`.

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

The original template README is in `docs/AL_FOLIO_README.md`. Note that `AGENTS.md` and `CLAUDE.md` describe the upstream template repo, which uses an `/al-folio` baseurl. This site uses a blank baseurl because it's served at the domain root.
