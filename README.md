A Github Pages template for academic websites. This was forked from the [AcademicPages Jekyll Theme](https://github.com/academicpages/academicpages.github.io/), which is released under the MIT License. See LICENSE.md.

# Instructions

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll serve --config _config.yml,_config.dev.yml` to generate the HTML and serve it from `localhost:4000`. The local server automatically rebuilds pages on change.

## Research blog

The blog lives at `/blog/` and automatically lists posts newest first. The top navigation and homepage link to it. Posts use the existing site theme, with dates, reading times, topic tags, and an RSS feed at `/feed.xml`.

### Write an entry

1. Copy `_drafts/experiment-template.md` or `_drafts/idea-template.md` to a new file in `_drafts/`, such as `_drafts/prompt-comparison.md`.
2. Fill in the title, excerpt, tags, and content. Set `note_type` to `Experiment log`, `Idea`, `Reading note`, or `Research note`.
3. Preview drafts with `bundle exec jekyll serve --drafts --config _config.yml,_config.dev.yml` and open `http://localhost:4000/blog/`. This also previews the template files; they are excluded from normal builds.
4. When ready, move the completed entry to `_posts/YYYY-MM-DD-short-title.md`, using its publication date. Add a matching `date: YYYY-MM-DD` to the front matter. It will have a stable URL at `/blog/YYYY/MM/DD/short-title/`.
5. Commit and push the changes to your GitHub Pages publishing branch using your usual website workflow.

Keep unfinished entries in `_drafts/`: the site's existing `future: true` setting means a future date does **not** keep a file in `_posts/` unpublished. Drafts are excluded from the built site, but their source is still visible if committed to a public repository.

### Figures, tables, and updates

Use Markdown tables and fenced code blocks directly in posts. Store figures in `images/blog/short-title/` and embed them with descriptive alternative text:

```liquid
![Hallucination rate by prompt variant]({{ '/images/blog/short-title/results.png' | relative_url }})
```

For a later revision, keep the original date and filename, add `modified: YYYY-MM-DD` to the front matter, and describe the change in the post. The first entry, `_posts/2026-09-26-vlm-hallucination-notebook.md`, is an introductory note you can edit before publishing.

Validate a normal build with `bundle exec jekyll build`. Generated files in `_site/` are ignored by Git.

## Markdown Generator

There are python files in `scripts/` that convert a TSV containing structured data about talks (`talks.tsv`) or presentations (`presentations.tsv`) into individual markdown files that will be properly formatted for the academicpages template. The notebooks contain a lot of documentation about the process. The .py files are pure python that do the same things if they are executed in a terminal, they just don't have pretty documentation.
