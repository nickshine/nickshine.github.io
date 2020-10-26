# [nshine.dev](https://nshine.dev)

---

## Publishing

This GitHub Pages site is built with [Hugo]. The `main` branch contains the source code and `gh-pages` branch contains the rendered static content from the Hugo build.

In order to publish content to Hugo's default public folder (`public/`), [add a git worktree][hugo-gh-pages] for the `public/` folder:

```bash
git worktree add -B gh-pages public origin/gh-pages
```

Quick script to deploy and commit new changes:

```bash
./deploy.sh
```

With this method, you can build the static site with hugo, and the content changes will be reflected in the `gh-pages` branch, ready to be committed and pushed for publishing.

Note: The `public` folder is ignored everywhere but the `gh-pages` branch.

[hugo]:https://gohugo.io
[hugo-gh-pages]:https://gohugo.io/hosting-and-deployment/hosting-on-github/#build-and-deployment
