# Chenbo Xin · Research homepage

This site uses Jekyll and the existing GitHub Pages workflow. The homepage and `/publications/` share the same publication data.

## Local preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open the local address printed by Jekyll. Changes pushed to the configured GitHub Pages branch are built and deployed by `.github/workflows/pages-deploy.yml`.

## Updating content

- Edit `_data/publications.yml` to add or update a paper. Use `group: published`, `review`, or `preparation` to choose its section. List authors in order, with `*` after names for equal contributions; the templates highlight `Chenbo Xin` or `C. Xin` automatically.
- Add a paper image under `assets/image/papers/` and set its `image` and descriptive `image_alt`. When an image is not available, the page displays a neutral placeholder. Remove `authors_incomplete: true` when the full list has been added.
- Edit `index.html` for the profile, news, honors, patents, and contact details. Layout and styling are in `_layouts/research.html` and `assets/css/research.css`.

## Publication image sources

The paper thumbnails are cropped from figures in the papers: figure 2 of [Velocity Ambiguity Profiles](https://arxiv.org/abs/2610.30107), figure 1 of the [ForesightFlow preprint](https://arxiv.org/abs/2606.04968), figure 2 of the [ICLR proceedings version of HVD](https://proceedings.iclr.cc/paper_files/paper/2026/hash/86dbb21b9fd447c6e289563d67c44760-Abstract-Conference.html), and figure 1 of [LLM4Robot-Bench](https://arxiv.org/abs/2610.34527). The ForesightFlow preprint uses a different title from the accepted paper.

The repository retains the original Chirpy starter dependencies and MIT license.
