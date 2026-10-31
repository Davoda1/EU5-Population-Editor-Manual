# Deploying the manual

The generated `dist/` directory is a complete static website. It can be served at a domain root or under a project subdirectory, with no application server or external browser dependencies. The generated pages include the license and third-party notices.

## GitHub Pages

The bundled **Deploy manual to GitHub Pages** workflow publishes from `master` through the `github-pages` environment. It does not require a separate publishing branch.

1. Enable GitHub Pages for the repository and select **GitHub Actions** as the build source.
2. Set the repository Actions variable `ENABLE_PAGES` to `true`.
3. From the Actions tab, run **Deploy manual to GitHub Pages** on `master`.
4. Use the URL returned by the successful deployment.

Deployment is manually dispatched. The `ENABLE_PAGES` variable is an explicit deployment switch; the deployment job is skipped when it is not `true`. The workflow rebuilds and validates the site before publishing, and grants Pages write and identity-token permissions only to the deployment job.

## Other static hosts

Run the build and checks described in the repository README, then upload the contents of `dist/` to the host's document root or a subdirectory. Keep the `assets/` directory beside the HTML files. Relative links, styles, search and theme controls work without rewriting URL paths.

The **Build manual** CI workflow also produces a ready-to-host website artifact. Download and extract that artifact to obtain the same directory structure.
