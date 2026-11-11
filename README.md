# Yiming Xu’s academic website

This repository builds [xuyimingxym.github.io](https://xuyimingxym.github.io/) with Jekyll. Edit the source files below. Jekyll generates the preview in `_site/` and replaces it on each build.

## Everyday edits

| To update | Edit |
| --- | --- |
| Homepage biography and faculty search notice | [_pages/about.md](_pages/about.md) |
| News | [_includes/news-items.md](_includes/news-items.md). Add a dated Markdown bullet at the top. The homepage shows the first five and folds the rest automatically. |
| Position, affiliation, portrait, email and profile links | The `author` section in [_config.yml](_config.yml). The street address and phone number are in [_pages/contact.html](_pages/contact.html). |
| Papers and manuscripts | One Markdown file per work in [_publications/](_publications/). The bibliography and individual paper pages are generated from these records. |
| Talks and courses | One file per entry in [_talks/](_talks/) or [_teaching/](_teaching/). Use `sort_month` (e.g. `"2026-06"`) for talks and `sort_term` (e.g. `"2026-2"` for fall) for courses. |
| Projects and academic service | [_pages/projects.md](_pages/projects.md) and [_pages/services.md](_pages/services.md). Project details shared with other pages live in [_data/research.yml](_data/research.yml) and dataset citations in [_data/datasets.yml](_data/datasets.yml). |
| CV | Replace [the public PDF](files/Yiming_Xu_s_CV_C.pdf) at the same path and update the displayed date in [_pages/cv.html](_pages/cv.html). |
| Menu links and their order | [_data/navigation.yml](_data/navigation.yml) |

In this workspace, copy a revised CV into the website with `cp ../Yiming_Xu_CV.pdf files/Yiming_Xu_s_CV_C.pdf` from the site directory.

For a new paper, copy a record of the same type. Use `category: manuscripts` for published or accepted journal articles, with `authorship_group: lead` or `coauthored`. Use `conferences` for conference papers and `under-review` with a `review_order` for manuscripts under review. Keep existing filenames, permalinks and citation keys when correcting a record so its public URL and references continue to work.

To mention a paper in News, see the `robophys-3d` entry in the news file. It reads the title and year directly from the publication record. Plain announcements only need a bullet, for example `- 2026.10: 4 papers have been accepted by TRB 2027.`

## Preview locally

From the site directory (`xuyimingxym.github.io/` in this workspace), use Ruby 3.3 and Bundler:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4173
```

Open [the local preview](http://127.0.0.1:4173/). The server rebuilds when content changes. Restart it after editing `_config.yml`. If another preview already uses port 4173, choose a different port. To check a production build locally, run `JEKYLL_ENV=production bundle exec jekyll build`.

The [historical BibTeX import](markdown_generator/) contains the original bibliographies and notebook. Running it writes files into `_publications/` using the old record format. For day-to-day edits, update the Markdown records directly.

The layouts and styles are based on [Academic Pages](https://github.com/academicpages/academicpages.github.io) and [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes). See the [license](LICENSE). If you change the theme JavaScript, run `npm install` and `npm run build:js` to regenerate the checked-in bundle.
