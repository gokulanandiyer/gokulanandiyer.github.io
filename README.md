# gokulanandiyer.github.io

Personal site for Gokul Anand Iyer, based on the official [al-folio Jekyll starter](https://github.com/alshedivat/al-folio/tree/fde4cbfa59a8dd5efe0cba90ddf62ebab1fad7f1). The runtime is provided by the upstream gems in `Gemfile.lock`.

GitHub Actions builds pull requests and publishes pushes to `main`. Set **Settings → Pages → Build and deployment → Source** to **GitHub Actions** before publishing this version.

For a local build, use Ruby 3.3 with Bundler and ImageMagick. Run `bundle install` and `bundle exec jekyll serve`.

| Content | Location |
| --- | --- |
| Biography and portrait | `_pages/about.md`, `assets/img/` |
| Professional experience | `_pages/experience.md` |
| Bibliography | `_bibliography/papers.bib` |
| Projects | `_projects/` |
| CV and future PDF link | `_data/cv.yml`, `_pages/cv.md` |
| Contact and social links | `_data/socials.yml` |
| Announcements | Add `_news/` entries, restore the upstream news index, and enable announcements in `_pages/about.md` |
