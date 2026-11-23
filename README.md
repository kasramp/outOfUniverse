# Out of Universe [![Deploy](https://github.com/kasramp/outOfUniverse/actions/workflows/deploy.yml/badge.svg)](https://github.com/kasramp/outOfUniverse/actions/workflows/deploy.yml)

This repository host the contents of **Out of Universe** blog. It's using [Hugo](https://gohugo.io/) and [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.
Pushes to `master` are built and deployed to GitHub Pages by GitHub Actions (`.github/workflows/deploy.yml`).

## Run in `dev` machine

To run this repository in local, first run `setup.sh` script to get the PaperMod theme submodule and then run the Hugo server as follow,

```bash
$ hugo server
```

To see the changes on a draft blog post run,

```bash
$ ./watch.sh
```

## Build the blog

To generate the static content, just run:

```bash
$ hugo
```

## Add a new post

To add a new post use `hugo` command like below,

```bash
$ hugo new post/[name-of-the-post.md]
```

## Contact
* kasra@madadipouya.com

