# colincron.github.io

Personal security research blog. Recon writeups, tool builds, and bug bounty findings.

## Setup

1. Create a repo named exactly `colincron.github.io` on GitHub
2. Clone it locally
3. Copy everything in this folder into the repo root
4. Push to main
5. Go to repo Settings → Pages → Source: Deploy from branch → main / root
6. Your blog is live at https://colincron.github.io within a few minutes

## Adding a new post

1. Write the post HTML in `posts/your-post-slug.html` (copy `posts/api-key-gov-site.html` as a template)
2. Add a new post card to `index.html` in the `post-list` section
3. Push to main — GitHub Pages deploys automatically

## Structure

```
index.html          ← homepage
posts/
  api-key-gov-site.html
  your-next-post.html
_config.yml         ← tells GitHub Pages not to apply a Jekyll theme
README.md
```
