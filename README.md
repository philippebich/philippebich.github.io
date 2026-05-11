# philippebich.github.io

Personal academic homepage. Built on the [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io) Jekyll template.

## Preview locally (Docker — recommended, no Ruby install needed)

```bash
cd /home/pbich/projects/website
docker run --rm -it -v "$PWD:/srv/jekyll" -p 4000:4000 \
  jekyll/jekyll:4 \
  jekyll serve --watch --host 0.0.0.0
```

Then open <http://localhost:4000>.

## Preview locally (native Ruby)

```bash
sudo apt install ruby-bundler   # one-time
bundle install
bundle exec jekyll serve --livereload
```

## Editing

- **Homepage** — `_pages/about.md` (About, News, Recent Publications, Education, Talks)
- **Full publications page** — `_pages/publications.md`
- **Nav menu** — `_data/navigation.yml`
- **Author info** — `_config.yml`
- **Images** — drop into `images/` and reference as `images/your-file.png`

To swap the profile picture, replace `images/profile.jpg` (or change `author.avatar` in `_config.yml`).

To add a new "Recent Publication" card, copy a `<div class='paper-box'>…</div>` block in `_pages/about.md`.

## Publishing

When ready, push to `philippebich/philippebich.github.io` on the `main` branch — GitHub Pages will build automatically.
