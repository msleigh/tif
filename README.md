# tif

... today i forgot ...

## Requirements

Install and setup [`postodon`](https://github.com/msleigh/postodon).
Recommended: install for global use with `pipx`.

## Usage

- Posts file is `posts.json`
- Mastodon instance is `botsin.space`
- User/registered app  is `tif`

### Manual posting

Use as per [`postodon` instructions](https://github.com/msleigh/postodon).

### GitHub Action

A GitHub Action posts daily. The Mastadon app (`tif`) access token is stored as
GitHub secret `AUTH_TOKEN`. The Action commits / pushes the change to
`posts.json` (i.e. marking the post as posted).

### Adding new posts

Use as per [`postodon` instructions](https://github.com/msleigh/postodon).
If using the GitHub Action, remember to `git pull` before editing `posts.json`.
