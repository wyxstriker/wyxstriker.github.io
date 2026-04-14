# Repository Guidelines

## Project Structure & Module Organization
This repository is a Jekyll-based academic homepage. Site configuration lives in `_config.yml`. Main page content is in `_pages/about.md`. Shared templates are split across `_layouts/` and `_includes/`, while styling is organized in `assets/css/`, `assets/js/`, and `_sass/`. Static images and icons live in `images/`. The `google_scholar_crawler/` directory contains a small Python utility plus its own dependencies for generating citation data used by the site and GitHub Actions workflow in `.github/workflows/google_scholar_crawler.yaml`.

## Build, Test, and Development Commands
Use Bundler for site work and Python only for the crawler.

- `bundle install`: install the Ruby gems from `Gemfile`.
- `bash run_server.sh`: start the local Jekyll live server (`bundle exec jekyll liveserve`).
- `bundle exec jekyll build`: build the static site for validation.
- `cd google_scholar_crawler && pip3 install -r requirements.txt`: install crawler dependencies.
- `cd google_scholar_crawler && GOOGLE_SCHOLAR_ID=... python3 main.py`: generate citation JSON locally.

## Coding Style & Naming Conventions
Keep Markdown front matter and YAML keys consistent with existing files. Use 2-space indentation in YAML and HTML/Liquid blocks. Preserve the current Jekyll naming patterns: includes use lowercase hyphenated names such as `_includes/author-profile.html`, and content pages stay under `_pages/`. Prefer small, targeted edits over broad theme changes. When updating styles, modify source files like `assets/css/main.scss` or `_sass/*.scss`, not generated/minified assets unless the source change requires it.

## Testing Guidelines
There is no formal test suite in this repository. Validate changes by running `bundle exec jekyll build` and checking the site locally with `bash run_server.sh`. For crawler changes, run `python3 main.py` inside `google_scholar_crawler/` with a valid `GOOGLE_SCHOLAR_ID` and confirm `results/gs_data.json` is produced.

## Commit & Pull Request Guidelines
Recent history uses short, imperative commit messages such as `Update about.md`. Follow that style: `Update _config.yml`, `Fix sidebar layout`, `Add scholar crawler note`. Pull requests should include a brief summary, list affected pages or assets, and attach screenshots for visible UI changes. If the change touches deployment, config, or GitHub Actions, note any required secrets or branch behavior explicitly.
