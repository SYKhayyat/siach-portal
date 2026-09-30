# Deployment

This is a static portal with no build step. Deploy it with Cloudflare Pages using Git integration.

Cloudflare Pages settings:

- Project name: `siachshai-portal`
- Production branch: `main`
- Build command: leave empty
- Build output directory: `.`
- Framework preset: None

The apex domain `siachshai.online` should be attached to this project. The portal links to `quiz.siachshai.online` and `games.siachshai.online`.

No Netlify configuration or deploy token is required. GitHub Actions only checks that the portal files exist.