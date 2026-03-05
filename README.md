# The Silent Neuron

## One-time setup

```bash
gem install bundler
bundle install
```

## Preview locally

```bash
bundle exec jekyll serve
# open http://localhost:4000
```

## Write a new post

1. Create a file in `_posts/` named: `YYYY-MM-DD-your-post-title.md`
2. Add this at the top:

```
---
layout: post
title: "Your Post Title"
date: 2026-03-05
excerpt: "One sentence summary shown in the post list."
---
```

3. Write your post below in plain Markdown.
4. Save, push to GitHub → it's live.

## Deploy to GitHub Pages

1. Create a repo named `yourusername.github.io`
2. Push this folder to it:

```bash
git init
git add .
git commit -m "initial site"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

3. Your site is live at `https://yourusername.github.io`

## Update your details

Everything personal (name, email, affiliation, socials) is in `_config.yml`.
Edit that file and it updates everywhere on the site automatically.

## Add your photo

Drop your photo into `assets/` and update `index.html`:
Replace the placeholder comment with:
```html
<img src="/assets/photo.jpg" alt="Antony Kiran" />
```
