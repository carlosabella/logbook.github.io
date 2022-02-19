# Log Book

[![pages-build-deployment workflow](https://github.com/carlosabella/logbook.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/carlosabella/logbook.github.io/actions/workflows/pages/pages-build-deployment)

[![draft-create workflow](https://github.com/carlosabella/logbook.github.io/actions/workflows/draft-create.yml/badge.svg)](https://github.com/carlosabella/logbook.github.io/actions/workflows/draft-create.yml)

My tech notes and thoughs built on Jekyll.

## Deploy

Just push to source repository

``` shell
git push origin main
```

## Local development

In order to make easier local builds, I've created this two alias in my "~/.zshrc" configuration file.

``` shell
alias jbuild="bundle exec jekyll build"
alias jserve="bundle exec jekyll serve"
```