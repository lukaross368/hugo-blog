# Hugo Resume Blog

This repo is a bootstrapped Hugo site designed as a resume-focused blog. It includes:

- engineering posts
- film and book reviews
- gaming posts
- lightweight responsive theme
- GitHub Actions workflow to build the static site

## Usage

- Run locally: `hugo server --buildDrafts`
- Create a new post: `hugo new engineering/my-post.md`
- Deploy: build the site and upload the generated `public/` folder to Cloudflare Pages

## Cloudflare Pages setup

1. Create a new Cloudflare Pages project.
2. Set the build command to `hugo --minify`.
3. Set the publish directory to `public`.
5. Configure the custom domain to `blog.luka-ross.com`.

## Notes

`baseURL` is already set to `https://blog.luka-ross.com/`.
Update `hugo.toml` with your name, email, GitHub, and LinkedIn.

If you want, I can also add a project section with skills and contact details.
