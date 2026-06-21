# Hugo Blog

A GitHub Pages blog built with Hugo and PaperMod.

## Local Preview

```bash
./.tools/hugo server -D
```

Open the local URL printed by Hugo, usually `http://localhost:1313/`.

## Create Posts

```bash
./.tools/hugo new content posts/my-new-post.md
```

Set `draft` to `false` in the post front matter before publishing.

## Publish to GitHub Pages

1. Create a repository named `sail-x.github.io` on GitHub.
2. Push this directory to the remote repository:

```bash
git remote add origin git@github.com:sail-x/sail-x.github.io.git
git push -u origin main
```

4. In repository Settings -> Pages, set Source to `GitHub Actions`.

Every push to `main` will build and deploy the site automatically.

## Repository Name

Use `sail-x.github.io` for a user site published at:

```text
https://sail-x.github.io/
```

Use any other repository name for a project site published at:

```text
https://sail-x.github.io/YOUR_REPOSITORY_NAME/
```
