# bjornieee125.github.io

Portfolio of Haissam MOUSSA (Bjornieee) — built with [devlopr-jekyll](https://github.com/sujaykundu777/devlopr-jekyll) (MIT), deployed to GitHub Pages by `.github/workflows/deploy.yml` (push to `main` → build → `gh-pages`).

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

## Content

- **Profile, skills, experience, education**: `_config.yml`
- **Photo**: add it to `assets/img/` and set `author_logo` in `_config.yml` (and `avatar` in `_data/authors.yml`)
- **Projects**: `_projects/*.md`
- **CTF writeups**: copy `_templates/ctf-writeup.md` to `_posts/YYYY-MM-DD-nom-ctf-challenge.md`.
  Set `categories:` to one of `web | mobile | forensics | crypto | reverse | pwn | osint | misc`
  (filter pages live in `categories/`).
