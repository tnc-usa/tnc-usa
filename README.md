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
  limiting, KV caching and bot protection, and the judgement to take the model out where a
  bundled dataset or a static file does the job better.

**Also**

Production route optimization on Google Cloud Fleet Routing with a custom constraint layer and
crew allocator. A thirteen-app low-code estate across three countries on one shared relational
model. Two-way API integration, OAuth2 service accounts, idempotent ETL, BigQuery. AI-native
delivery through Claude Code and MCP-connected agents.

A personal sports-betting assistant that never places a bet: prices from a licensed odds
aggregator, fair-price and stake arithmetic, and a ledger graded from the scores, on a Worker
with D1 and cron jobs. I ran it live for a week in September 2026 and then mothballed it.

Before the engineering there was design, and there was selling, and all three are one career.
Nearly two decades in design: CAD kitchens and fitted furniture, then the regional agency for the
design system itself. A sales record running from high-net-worth property to enterprise B2B. And I
have co-founded businesses, written the software that ran them, and sold them, most recently a pool
service company I [started with a pickup and scaled on an ERP I wrote six months
in](https://github.com/tnc-usa/solutions-engineering-portfolio/blob/main/writeups/08_bali_pools_erp.md).

Specifying work with a customer and pricing it while they watch is where all three meet. It is why
I can run the discovery as well as the build, and why the line about small and medium businesses at
the top is not a marketing claim.

**Start here**

[**solutions-engineering-portfolio**](https://github.com/tnc-usa/solutions-engineering-portfolio)
is the hub: writeups, and sanitized code samples of the patterns above. Client engagements are
generalized, and one is under an NDA.

[tnc-usa.com](https://www.tnc-usa.com) ·
[NewRoots USA](https://newroots.tnc-usa.com) ·
sean@tnc-usa.com
