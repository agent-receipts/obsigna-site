# obsigna-site

This repo serves the [obsigna.dev](https://obsigna.dev) landing page via GitHub Pages (source: GitHub Actions).

It is intentionally separate from the [agent-receipts](https://github.com/agent-receipts) monorepo. A static landing page has no dependency on product code and occupies its own GitHub Pages slot — the monorepo's slot is already taken by agentreceipts.ai. Keeping them decoupled avoids entangling a one-file site with the build pipeline of a larger project.

If the site grows to include live spec content or SDK documentation that is generated from the monorepo, it may make sense to fold it back in at that point.
