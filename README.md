# README

[![Netlify Status](https://api.netlify.com/api/v1/badges/402b1b31-65aa-4d2e-8e1f-975e42c76af4/deploy-status)](https://app.netlify.com/sites/quizzical-stonebraker-325779/deploys)

[Personal blog](https://dariagrudzien.com/) about tech, comms, and people. Built using [Hugo](https://gohugo.io/)

## Content :memo:

All posts are written in Markdown and live in the `content` directory.

## Theme :art:

The website uses an [Ezhil](https://github.com/vividvilla/ezhil) theme for Hugo. It's installed as a git submodule and lives in the `themes` directory.

## Customization :hibiscus:

I wouldn't be me if I hadn't tinkered with the style a bit. Custom CSS can be found in `static/css`.

## Running locally :woman-running:

`hugo server -D` for local preview.

## Deploy :rocket:

Every time a pull request is created, it launches a [Netlify](https://www.netlify.com/) build. Basic cofiguration is included in `config.toml`.

* Create the PR.
* Wait for Netlify checks to pass.
* Merge the PR.
* Go get a :cake: & :coffee:, and write another post.
