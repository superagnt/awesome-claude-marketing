# awesome-claude-marketing

Claude connectors, MCP servers and skills for marketing work: ads, SEO and AI search, social listening, leads and outbound, content and analytics. Each one was checked on the day, from its own repo or page.

Every row says what the entry does, whether it's hosted or runs on your machine, whether it needs your own key or account with that vendor, its license and the month of its last commit. The rows, with the page each was checked on and the date, are in [data.json](data.json).

## How this list works

superagnt keeps this list. superagnt is a marketing plugin for Claude and ChatGPT that helps businesses find customers through outbound, SEO and ads. Its own entries are in the list too, each marked where it is named.

- **Order.** Sections run by the job. In each section, superagnt's own entries come first, then the rest by the month of their last commit, newest first, then by name. A hosted connector with no public repo has no last commit and comes after those.
- **Checked.** Each entry was read on the date in its row, from its own repo or page: what it does from its README or docs, the license from the repo, the last commit from its default branch. An entry that stops existing, or stops being for marketing, comes out.
- **Your own key.** "Yes" means it needs your own account or API key with the platform it reads or acts on, or with another paid service (an ad platform's token, an SEO tool's plan, your CRM), and the note says which. "No" means the entry's own sign-in, if it has one, is all it takes.
- **Suggest an entry:** open an issue with its repo or page. It joins once it's checked the same way.

<!-- LIST:START: generated from data.json, do not edit -->
## Ads

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [get-mcp-ads/meta-ads-mcp-server](https://github.com/get-mcp-ads/meta-ads-mcp-server) | Meta Ads MCP server with 42 read tools and 24 opt-in write tools that preview each change before applying it | MCP server | Hosted or local | Yes: Meta access token (ads_read) | Apache-2.0 | 2026-11 |
| [googleads/google-ads-mcp](https://github.com/googleads/google-ads-mcp) | Google Ads MCP server from Google: GAQL reporting queries, plus asset and label changes behind a confirm step | MCP server | Local | Yes: Google Cloud project, OAuth credentials with Google Ads access | Apache-2.0 | 2026-11 |
| [mharnett/mcp-marketing-suite](https://github.com/mharnett/mcp-marketing-suite) | Seven MCP servers as Claude Code plugins: Google, Microsoft, LinkedIn and Reddit Ads, GA4, Search Console, GTM | MCP server | Local | Yes: API credentials for each ad and analytics platform | MIT | 2026-11 |
| [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) | Meta Ads MCP server for launching campaigns, uploading creatives, changing budgets and reading results | MCP server | Hosted or local | Yes: Pipeboard sign-in and your Meta ad account | BUSL-1.1 | 2026-10 |
| [feel-t/meta-ads-mcp](https://github.com/feel-t/meta-ads-mcp) | MCP server for the Meta Marketing API: campaigns, insights, targeting research, and creating or updating ads | MCP server | Local | Yes: Meta access token | None | 2026-04 |
| [Meta ads MCP server](https://developers.facebook.com/documentation/ads-commerce/ads-ai-connectors/ads-mcp-server/ads-mcp-server-overview) | Meta's hosted MCP server for ads: reporting, campaign and ad editing, catalogs, A/B tests and lift studies | Connector | Hosted | Yes: Facebook login with access to a Meta ad account | Proprietary | n/a |

## SEO and AI search

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [superagnt/supereo-audit](https://github.com/superagnt/supereo-audit) (made by superagnt, which keeps this list) | Free AEO audit as a Claude Code plugin, CLI and local MCP server: what AI crawlers can read on any page | Plugin | Hosted or local | No (supereo sign-in) | MIT | 2026-11 |
| [superagnt/supereo-mcp](https://github.com/superagnt/supereo-mcp) (made by superagnt, which keeps this list) | supereo's hosted MCP server for AEO: how often AI engines recommend your brand, tracked prompts and tests | Connector | Hosted | No (supereo sign-in) | MIT | 2026-11 |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | SEO audit plugin for Claude Code: technical, E-E-A-T, schema, AI search, local and e-commerce, with a plan | Plugin | Local | No (optional add-ons connect paid services) | MIT | 2026-11 |
| [AminForou/mcp-gsc](https://github.com/AminForou/mcp-gsc) | Google Search Console MCP server: search analytics, period comparisons, URL inspection, indexing, sitemaps | MCP server | Local | Yes: Google Cloud OAuth client or service account with Search Console access | MIT | 2026-11 |
| [nurdamiron/claude-code-skills](https://github.com/nurdamiron/claude-code-skills) | SEO and AI-search audit skill: 19 sub-commands for technical SEO, schema, E-E-A-T and AI Overviews | Skill | Local | No | MIT | 2026-07 |
| [Ahrefs MCP server](https://docs.ahrefs.com/en/mcp/docs/introduction) | Ahrefs' hosted MCP server: Site Explorer, Keywords Explorer, Rank Tracker, Site Audit and Brand Radar data | Connector | Hosted | Yes: Ahrefs plan, Lite or higher | Proprietary | n/a |
| [Semrush MCP server](https://developer.semrush.com/api/v3/introduction/semrush-mcp/) | Semrush's hosted MCP server for its SEO API, Trends traffic and market API, and read-only Projects data | Connector | Hosted | Yes: Semrush plan with API units, or a Trends API plan | Proprietary | n/a |

## Social and community

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [insightsocial/cli](https://github.com/insightsocial/cli) | CLI and MCP server for public data from 61 platforms (TikTok, LinkedIn, YouTube, X, Reddit and more), one key | MCP server | Hosted or local | No (InsightSocial sign-in) | MIT | 2026-11 |
| [reduck-ai/reddit-mcp](https://github.com/reduck-ai/reddit-mcp) | Reduck's Reddit tools over MCP: search, read full threads and subreddits, and comment, through your own Chrome | Connector | Hosted | Yes: Reduck account, its Chrome extension, your Reddit login | None | 2026-11 |
| [robgaunt/claude-skills](https://github.com/robgaunt/claude-skills) | Claude Code skill that reads Reddit threads and subreddits by handing the fetch to OpenAI's Codex CLI | Skill | Local | Yes: ChatGPT sign-in for OpenAI's Codex CLI | MIT | 2026-11 |
| [dialog-tools/reddit-research-mcp](https://github.com/dialog-tools/reddit-research-mcp) | Reddit research MCP server: semantic subreddit discovery, search, posts and comment threads, with citations | MCP server | Hosted | No (OAuth sign-in, no Reddit keys) | MIT | 2026-10 |
| [XenSide/claude-research-skills](https://github.com/XenSide/claude-research-skills) | Two Claude Code skills for Windows: read Reddit with your own login, and search YouTube videos and transcripts | Skill | Local | Yes: Reddit login in Firefox; Windows only | MIT | 2026-10 |
| [mokouliszt/fxtwitter-skill](https://github.com/mokouliszt/fxtwitter-skill) | Claude skill and Python CLI that read X posts, threads, profiles, followers and trends via the FxTwitter API | Skill | Local | No | MIT | 2026-08 |
| [xdevplatform/xmcp](https://github.com/xdevplatform/xmcp) | X Developer Platform's local MCP server that exposes the X API (posts, users, search and more) as tools | MCP server | Local | Yes: X Developer Platform app and tokens | None | 2026-04 |

## Leads and outbound

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [superagnt MCP server](https://www.superagnt.com/mcp) (made by superagnt, which keeps this list) | superagnt's hosted MCP server: live social data, lead enrichment, a work email finder, SEO data and Postgres | Connector | Hosted | No (superagnt sign-in) | Proprietary | n/a |
| [apolloio/apollo-mcp-plugin](https://github.com/apolloio/apollo-mcp-plugin) | Apollo's official hosted MCP server: find people and companies, enrich contacts and load leads into sequences | Connector | Hosted | Yes: Apollo.io account (OAuth) | MIT | 2026-09 |
| [HubSpot MCP server](https://developers.hubspot.com/ai-tools/mcp) | HubSpot's hosted MCP server: read and write CRM records and engagements; read campaigns, pages and blog posts | Connector | Hosted | Yes: HubSpot account and a user-level app | Proprietary | n/a |

## Content and email

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [getbrevo/brevo-skills](https://github.com/getbrevo/brevo-skills) | Brevo's skills for its hosted MCP server: write and check email templates, draft campaigns, read results | Plugin | Hosted | Yes: Brevo account | MIT | 2026-11 |
| [marcosmodly/marketing-skill](https://github.com/marcosmodly/marketing-skill) | Claude Code plugin with 14 marketing skills: content calendars, ad copy, email sequences, video, posts | Plugin | Local | No | MIT | 2026-11 |
| [Canva MCP server](https://www.canva.dev/docs/apps/mcp/) | Canva's hosted MCP server: create, edit, search and export designs, and use assets, brand kits and templates | Connector | Hosted | Yes: Canva account | Proprietary | n/a |
| [Klaviyo MCP server](https://developers.klaviyo.com/en/docs/klaviyo_mcp_server) | Klaviyo's MCP server for your account: campaign and flow performance reports, and creating email campaigns | Connector | Hosted or local | Yes: Klaviyo account (Owner, Admin or Manager), or a private API key locally | Proprietary | n/a |

## Analytics

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [googleanalytics/google-analytics-mcp](https://github.com/googleanalytics/google-analytics-mcp) | Google Analytics MCP server: account and property details, and core, funnel, conversion and realtime reports | MCP server | Local | Yes: Google Cloud project and credentials with Analytics access | Apache-2.0 | 2026-11 |
| [microsoft/clarity-mcp-server](https://github.com/microsoft/clarity-mcp-server) | Microsoft Clarity MCP server: traffic and behavior metrics, session recordings, AI visibility citations, bots | MCP server | Local | Yes: Microsoft Clarity account (browser sign-in) | MIT | 2026-11 |

## Skill collections

| Name | What it does | Type | Runs | Your own key | License | Last commit |
|---|---|---|---|---|---|---|
| [superagnt/plugins](https://github.com/superagnt/plugins) (made by superagnt, which keeps this list) | superagnt's Claude plugins: packaged skills for social research, competitor ads, outbound and SEO | Plugin | Hosted | No (superagnt sign-in) | MIT | 2026-11 |
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 53 marketing skills for AI agents: CRO, copywriting, SEO and AI search, ads, analytics, email and launches | Plugin | Local | No (optional: your own marketing tool accounts) | MIT | 2026-11 |
| [Insightful-Pipe/marketing-skills](https://github.com/Insightful-Pipe/marketing-skills) | 414 marketing skills (ads, analytics, SEO, content, email, social, PR, sales) that can read live data over MCP | Plugin | Local | No (optional: InsightfulPipe account for live data) | MIT | 2026-11 |
| [manifoldmcp/marketing-skills](https://github.com/manifoldmcp/marketing-skills) | Marketing skills plugin for Manifold's hosted data server: search, AI answers, Reddit, social, ad libraries | Plugin | Hosted | No (Manifold sign-in) | MIT | 2026-11 |
| [OpenClaudia/openclaudia-skills](https://github.com/OpenClaudia/openclaudia-skills) | 78 open-source marketing skills for SEO, content, email, social, ads, analytics; some use APIs with your keys | Plugin | Local | No (API-powered skills need their own keys) | MIT | 2026-11 |
| [cognyai/claude-code-marketing-skills](https://github.com/cognyai/claude-code-marketing-skills) | Marketing skills for SEO audits, ad copy, tracking and email; free ones use web search, premium ones live data | Plugin | Local | No (premium skills need a Cogny plan) | None | 2026-10 |
| [anthropics/knowledge-work-plugins: marketing](https://github.com/anthropics/knowledge-work-plugins/tree/main/marketing) | Anthropic's marketing plugin: draft content, plan campaigns, check brand voice, brief on rivals, audit SEO | Plugin | Local | No (optional: accounts for the connectors you use) | Apache-2.0 | 2026-09 |
<!-- LIST:END -->

## License

The list is MIT licensed. See [LICENSE](LICENSE). Each entry has its own license, in its row.
