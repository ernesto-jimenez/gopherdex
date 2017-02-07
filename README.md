# Contributing a gopher to Gopherdex

1. Fork the repository
2. Copy the png of the gopher to `static/images/gophers`
3. Create the `.md` file at `content/gophers` with the same name as your image
4. Create a pull request to this repo

An example:

```shell
$ ls static/images/gophers/run.png
static/images/gophers/run.png

$ cat content/gophers/run.md
+++
date = "2017-01-26T15:50:35Z"
title = "The original gopher"
author = "Renee French"
credit = "http://reneefrench.blogspot.com/"
license = "Creative Commons Attributions 3.0"
+++

Some history about this actual gopher.
```

*Make sure you specify the current date, the name of the author, and the
license*

# Contributing to the design

You will need to install [hugo][hugo] to genereate the website.

After cloning the site, you can make changes and monitor the result with `hugo server`.

[hugo]: https://gohugo.io/
