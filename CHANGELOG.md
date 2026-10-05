# Changelog

Notable changes to the personal blog. Entries summarize updates relative to `master`; newest first.

## `site-modernization` - 2026-10-05

The legacy Hyde/Poole styles are dated and unmaintained, with limited responsive and layout fixes. Rather than adopt another full theme, this update replaces the bundled CSS with modular, project-owned Sass adapted from the existing layout, making future improvements easier to maintain (with some help from AI). This in preparation of a future, more thorough modernization or rewrite.

### Added
- Modular Sass stylesheets, responsive layout refinements, and accessible skip-to-content navigation.
- Jekyll SEO metadata, `robots.txt`, and voluntary AI-crawler opt-out metadata.
- NL/FR/EN language dropdown with translation-aware links, plus updated LinkedIn, GitHub, and Google Scholar logos.
- Expanded `.gitignore` coverage for build output, dependencies, editor files, and OS files.

### Changed
- Updated page layouts, headings, and language-switching markup; removed Twitter profile/metadata configuration.
- Updated `github-pages` 228 to `~> 232` for non-JRuby builds; JRuby uses Jekyll `~> 3.10.0` with explicit plugins.
- Updated constraints: `minima` `>= 2.0` to `~> 2.5`; `jekyll-feed` `~> 0.6` to `~> 0.17`; `tzinfo-data` to `~> 1.2026.3`; `wdm` `~> 0.1.0` to `~> 0.2.0`; `webrick` `~> 1.8` to `~> 1.9.2`.
- Added `jekyll-seo-tag` `~> 2.8`; pinned `jekyll` `~> 3.10.0`, `jekyll-paginate` `1.1.0`, and `jekyll-redirect-from` `~> 0.16.0`. JRuby compatibility now explicitly includes `http_parser.rb`, `base64`, `csv`, and `bigdecimal`.

### Removed
- Legacy Hyde/Poole CSS files and the social-media sprite, replaced by Sass sources.
- Twitter, Facebook, Instagram, and TikTok profile links; no JavaScript or icon package was added.
- The JRuby lockfile no longer resolves the full GitHub Pages 228 bundle and its unused themes/integrations; GitHub Pages remains for non-JRuby builds.

### AI assistance
- GitHub Copilot, GPT-6 Luna.