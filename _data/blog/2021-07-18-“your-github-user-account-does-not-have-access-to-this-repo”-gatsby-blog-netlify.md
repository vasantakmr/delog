---
template: BlogPost
path: >-
  /Your GitHub user account does not have access to this repo gatsby blog
  netlify
date: 2021-07-18T08:40:04.683Z
title: >-
  “Your GitHub user account does not have access to this repo” gatsby blog
  netlify
---
1) Go to static/admin/config.yml

2) change repo to yourname/yourreponame

3) commit and push changes to github.

```yaml
backend:
  name: github
  # change repo to your git repository url
  repo: vasantakmr/delog

```
