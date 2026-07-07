<p align="center"><img src="https://raw.githubusercontent.com/go-yjs-relay/brand/main/social/go-yjs-relay.png" alt="go-yjs-relay/go-yjs-relay.github.io" width="720"></p>

# go-yjs-relay.github.io

The organization's institutional landing page, served at
<https://go-yjs-relay.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-yjs-relay/docs](https://github.com/go-yjs-relay/docs), served at
<https://go-yjs-relay.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
