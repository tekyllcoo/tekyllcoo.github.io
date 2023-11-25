# Live demo of Coo theme

This is a live demonstration of the [Coo][coo] Jekyll theme.  The demo is based
on the [tekyll][tekyll] template.  See the [project page][coo] of the theme or
[tekyll][tekyll] for more details.

## How to merge commits from tekyll

To sync this repository with [tekyll][tekyll], merge the commits as follows:

```sh
$ git remote add tekyll https://github.com/quacksouls/tekyll.git
$ git fetch tekyll --tags
$ git merge --allow-unrelated-histories tekyll/main
$ git remote remove tekyll
```

You might have to manually resolve merge conflicts.

[coo]: https://github.com/quacksouls/jekyll-theme-coo
[tekyll]: https://github.com/quacksouls/tekyll
