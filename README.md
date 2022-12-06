# tif

... today i forgot ...

## Installation

Install and setup [`postodon`](https://github.com/msleigh/postodon).

## Usage

- Posts file is `posts.json`
- Mastodon instance is `botsin.space`
- User/registered app  is `tif`

### Manual posting

Use as per [`postodon` instructions](https://github.com/msleigh/postodon).

### GitHub Action

A GitHub Action posts twice daily. The Mastadon app (`tif`) access token is stored as GitHub secret `AUTH_TOKEN`. The Action commits / pushes the change to `posts.json` (i.e. marking the post as posted).

### Adding new posts

If using the GitHub Action, remember to `git pull` before editing `posts.json`.
