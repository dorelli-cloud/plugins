# Dorelli Cloud plugins for Claude Code

One plugin, `dorelli`: put a website or app built with AI online on
[Dorelli Cloud](https://dorelli.cloud), in the Netherlands, within a minute.

```
/plugin marketplace add dorelli-cloud/plugins
/plugin install dorelli@dorelli-cloud
```

After that:

- `/dorelli` puts the site in the current folder live on `<name>.dorelli.cloud`.
- The skill `dorelli-deploy` does the same when you ask Claude to put your
  site online.
- The MCP server `dorelli` gives Claude the tools `deploy_site` and
  `site_status`.

No account needed; the management link arrives by email. Static sites and
Node apps (Next, Express, Fastify, Hono, Koa, Nuxt, Remix, SvelteKit); no PHP,
no Python. Prices and limits are on [dorelli.cloud/pricing](https://dorelli.cloud/pricing).

The source of this plugin is `packages/plugin/` in the Dorelli Cloud
platform; this repository is the mirror the marketplace fetches.
