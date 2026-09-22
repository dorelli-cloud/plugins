# Dorelli Cloud plugins voor Claude Code

Eén plugin, `dorelli`: een AI-gebouwde website of app online zetten op
[Dorelli Cloud](https://dorelli.cloud), in Nederland, binnen een minuut.

```
/plugin marketplace add dorelli-cloud/plugins
/plugin install dorelli@dorelli-cloud
```

Daarna:

- `/dorelli` zet de site in de huidige map live op `<naam>.dorelli.cloud`.
- De skill `dorelli-deploy` doet hetzelfde als je Claude vraagt je site
  online te zetten.
- De MCP-server `dorelli` geeft Claude de tools `deploy_site` en
  `site_status`.

Geen account nodig; de beheerlink komt per mail. Statische sites en Node-apps
(Next, Express, Fastify, Hono, Koa, Nuxt, Remix, SvelteKit); geen PHP, geen
Python. Prijzen en grenzen staan op [dorelli.cloud/pricing](https://dorelli.cloud/pricing).

De bron van deze plugin is `packages/plugin/` in het platform van Dorelli
Cloud; deze repository is de spiegel die de marktplaats ophaalt.
