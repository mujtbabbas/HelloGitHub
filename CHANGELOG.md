# Changelog

All notable changes to this standalone edition of HelloGitHub are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` (the Chinese main README; the section is kept in English per the project template) with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus pip updates for `script/github_bot` (the only `requirements.txt` in the tree).
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — the repository's first workflow, since upstream ships none); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Licence flag recorded: upstream has no standalone licence file; the READMEs declare CC BY-NC-ND 4.0, which restricts redistribution of modified versions. Nothing about the licence was changed.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [521xueweihan/HelloGitHub](https://github.com/521xueweihan/HelloGitHub) at upstream release vol.126 (snapshot commit `030121514da552ed91e640ef8bde4083c753dd52`, upstream HEAD dated 2026-09-28).
- Fork history severed; all files preserved exactly as-is.
