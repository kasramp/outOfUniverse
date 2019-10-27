# Out of Universe

This repository host the contents of **Out of Universe** blog. It's using [Hugo](https://gohugo.io/) and [Jane](https://github.com/xianmin/hugo-theme-jane) theme.

## Run in `dev` machine

To run this repository in local, first run `setup.sh` script to get the Jane theme sub module and then run the Hugo server as follow,

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
$ hugo new posts/[name-of-the-post.md]
```

## Contact
* kasra@madadipouya.com
