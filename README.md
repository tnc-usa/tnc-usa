## Sean Newton

I build operational software: the systems that run the work, not the ones that report on it
afterwards. Based in Tennessee, working for small and medium businesses that have outgrown
off-the-shelf.

The stack follows the problem. I have shipped on edge compute, on Google Cloud, and on
low-code where low-code genuinely fits, and the interesting engineering is nearly always in
knowing which of those a given layer actually needs.

**Currently building**

- Real-time reconciliation on Cloudflare Workers and Durable Objects. One object per session,
  colocated SQLite, WebSocket Hibernation, offline-capable PWA. Sub-second shared state across
  every device on the job, because interval sync makes a live shared tally impossible by
  design rather than by configuration.
- An operations warehouse on D1 with a ten-minute cron ETL, multi-tenant from the first
  commit, over a source system that hard-deletes its own history on a rolling window.
- AI in production on the Anthropic Claude API: server-side keys, hard daily spend caps, rate
  limiting, KV caching, bot protection, and cost-based routing across two models.

**Also**

Production route optimization on Google Cloud Fleet Routing with a custom constraint layer and
crew allocator. A thirteen-app low-code estate across three countries on one shared relational
model. Two-way API integration, OAuth2 service accounts, idempotent ETL, BigQuery. AI-native
delivery through Claude Code and MCP-connected agents.

Before the engineering there was a career sales record across enterprise B2B and high-net-worth
markets, so I can run the discovery as well as the build.

**Start here**

[**solutions-engineering-portfolio**](https://github.com/tnc-usa/solutions-engineering-portfolio)
is the hub: writeups, and sanitized code samples of the patterns above. Client engagements are
generalized, and one is under an NDA.

[tnc-usa.com](https://www.tnc-usa.com) ·
[NewRoots USA](https://newroots.tnc-usa.com) ·
sean@tnc-usa.com
