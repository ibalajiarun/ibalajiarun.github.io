# Balaji Arun — Personal Site

Static site built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages.

## Local development

```bash
hugo server -D
```

Open [http://localhost:1313](http://localhost:1313).

## Editing the homepage

Update `content/_index.md` for bio text and links. Replace `static/files/cv.pdf` to update your CV.

## Writing a blog post

```bash
hugo new posts/my-post-title.md
```

Edit the file, set `draft: false`, and commit.

## Deploy

Pushes to `main` build and deploy via GitHub Actions. After the first deploy, enable **GitHub Pages → Source: GitHub Actions** in the repository settings if it isn't already.
