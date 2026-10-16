# Awesome-Link-Management-Shortening

# Top Link Management & Shortening Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Branded Links, Click Analytics & Self-Hosted Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Link Management & Shortening**. These tools shorten URLs, create branded links, track click analytics, generate QR codes, and manage link infrastructure at scale.

**Examples** include Bitly Enterprise, Rebrandly, BL.INK, TinyURL Pro, Short.io, Dub.co, Branch.io, AppsFlyer, Ow.ly, and Sniply (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom domains, and transparent click analytics — ideal for developers, marketers, and organizations building privacy-focused, vendor-neutral link management solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Bitly Enterprise](https://bitly.com/)**  
  Market-leading URL shortener with branded links, QR codes, link-in-bio pages, and detailed click analytics. Free tier limited to 5-50 links/month; paid plans scale for enterprise .

- **[Rebrandly](https://www.rebrandly.com/)**  
  Link management platform focused on branded short URLs with custom domains, UTM builder, link retargeting, and team collaboration. Trusted by Versace and PayPal .

- **[BL.INK](https://www.bl.ink/)**  
  Branded link management service offering short, brand-focused URLs, QR codes, unlimited data capture, and marketing performance measurement .

- **[TinyURL Pro](https://tinyurl.com/)**  
  Veteran URL shortener with custom aliases, link tracking, and QR codes. Free tier offers no analytics; Pro starts at $9.99/month .

- **[Short.io](https://short.io/)**  
  White-label link shortener with custom domains, branded links, deep links, and team management features .

- **[Dub.co](https://dub.co/)**  
  Modern link management and attribution platform with conversion tracking, partner programs, and analytics; also offers a widely-adopted open-source version (see below) .

- **[Branch.io](https://branch.io/)**  
  Mobile linking and attribution platform for deep linking, deferred deep links, and cross-platform user journey tracking.

- **[AppsFlyer](https://www.appsflyer.com/)**  
  Mobile attribution and marketing analytics platform with deep linking capabilities for app growth teams.

- **[Ow.ly](https://hootsuite.com/)**  
  Link shortening available within the Hootsuite social media management dashboard .

- **[Sniply](https://sniply.io/)**  
  Link shortener with a unique twist: overlay custom CTAs onto any content you share, driving conversions through content curation. Starts at $29/month .

## Open-Source GitHub Projects

- **[Dub](https://github.com/dubinc/dub)**  
  **The leading open-source link management platform** — modern, TypeScript-based alternative to Bitly with 24.6k+ stars. Supports short links, analytics, custom domains, team collaboration, and API access. AGPL-3.0 licensed, commercial use allowed .

- **[Shlink](https://github.com/shlinkio/shlink)**  
  **Self-hosted URL shortener with REST API and CLI** — PHP-based with 5.3k+ stars, MIT licensed. Features geolocation tracking (GeoLite2), multi-domain support, QR code generation, visit tracking with browser/OS/referrer data, and Prometheus metrics. Docker-first architecture .

- **[YOURLS](https://github.com/YOURLS/YOURLS)**  
  **Your Own URL Shortener** — the veteran self-hosted solution with 12.2k+ stars, MIT licensed. PHP + MySQL, 200+ plugins, bookmarklet for quick creation, JSON/XML API. Extremely low resource usage and 15+ years of stability .

- **[Kutt](https://github.com/thedevs-network/kutt)**  
  Modern minimalist URL shortener built with Node.js and TypeScript. Clean UI, custom domains, link expiration, password protection, REST API, and browser extension. MIT licensed .

- **[Sink](https://github.com/miantiao-me/sink)**  
  **Serverless link shortener running entirely on Cloudflare** — Nuxt 4 + Cloudflare D1/KV/Analytics Engine. Features AI-assisted slug generation, smart routing by device/country, near-real-time analytics with 3D globe, QR codes, and multi-language support .

- **[Linkrift](https://github.com/link-rift/link-rift)**  
  **Enterprise-grade self-hostable URL shortener** built with Go for sub-millisecond redirect latency. Features ClickHouse-powered real-time analytics, custom domains with automatic SSL, smart redirects (device/geo/time/AB testing), bio pages, team collaboration, and API/webhooks .

- **[Lynx](https://github.com/frikishaan/lynx)**  
  Lightweight self-hosted link shortener built with Laravel, Filament, and **SQLite** — no complex database setup required. Features choice pages, custom slugs, password-protected links, QR codes, teams, custom domains, and detailed analytics .

- **[Brevio](https://github.com/numanrki/Brevio)**  
  Open-source self-hosted URL shortener with Laravel 12, Inertia.js, React 18, and TypeScript. Supports short links, QR codes, bio pages, deep links, analytics, and REST API. MIT licensed .

- **[Lstu](https://github.com/ldidry/lstu)**  
  Privacy-focused lightweight URL shortener emphasizing minimal resource usage and **no personal data collection**. Open source with custom short URLs and branding options .

- **[Polr](https://github.com/cydrobolt/polr)**  
  Open-source URL shortener with minimalist interface, analytics, API access, custom domains, and self-hosting capabilities. PHP-based, positioned as a non-profit alternative to Bitly .

- **[Lnk](https://github.com/lnk-sh/lnk)**  
  **Ultra-lightweight single-binary URL shortener** with SQLite storage — under 20 MB RAM, zero dependencies. API-only (no web UI), ideal for programmatic use and minimal deployments .

- **[Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener)**  
  KISS URL shortener — public or private (with account), minimalist and lightweight with no dependencies .

- **[redir](https://github.com/changkun/redir)**  
  Self-hosted link shortener and Go vanity import server in one binary. PostgreSQL-backed with semantic aliases, operator console, GDPR-compliant pages (impressum, privacy, contact), and per-link access control .

### Additional Strong Open-Source Options

- **[bit](https://github.com/sjdonado/bit)** — Fast, lightweight, resource-efficient compiled URL shortener (MIT, Docker/Crystal) .
- **[Chhoto URL](https://github.com/SinTan1729/chhoto-url)** — Simple, lightning-fast URL shortener with no bloat (Rust) .
- **[clink](https://git.crueter.xyz/crueter/clink)** — Super-minimal link shortening in pure C, focusing on small executable size and portability .
- **[rs-short](https://git.42l.fr/42l/rs-short)** — Rust-based lightweight shortener with caching, spambot protection, and phishing detection .
- **[Flink](https://gitlab.com/rtraceio/web/flink)** — Create QR codes and embeddable link previews with metadata scraping .
- **[Clishortener](https://github.com/Ruizennis/Clishortener)** — CLI tool supporting 14+ shortening services with zero configuration .

**Frameworks for building custom systems**: Combine **Shlink** or **Dub** as the core shortener, **PostgreSQL** for data storage, **ClickHouse** for high-volume analytics (as used by Linkrift), and **Cloudflare Workers** for serverless edge deployment (as used by Sink). For WordPress sites, **LinksTrackly** and **Royal Links** offer native plugin-based link management with affiliate cloaking .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Link shorteners can be abused for phishing and spam; implement abuse detection and reporting mechanisms if self-hosting.
- Self-hosted solutions require proper domain configuration, SSL certificates, and regular security updates.
- Respect user privacy: consider GDPR/CCPA compliance for analytics data collection, and prefer IP hashing or non-collection where possible .

---

**Made for developers, marketers, platform engineers, and privacy-conscious organizations.**  
Let's make link management more open, transparent, and vendor-neutral.
