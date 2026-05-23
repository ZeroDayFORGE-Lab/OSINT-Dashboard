# 🛰️ OSINT Arsenal — README

> **Open Source Intelligence Toolkit Dashboard**
> A curated, searchable, browser-based directory of 150+ OSINT tools and resources, organized into 14 categories.

---

## 📁 File

| File | Description |
|------|-------------|
| `osint-dashboard.html` | Self-contained single-file dashboard — open in any browser, no installation needed |

---

## 🚀 Quick Start

1. Download `osint-dashboard.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Brave)
3. No server, no dependencies, no internet required to load the UI

---

## ✨ Features

| Feature | Details |
|---------|---------|
| 🔍 Live Search | Instantly filter tools by name as you type |
| 🏷️ Category Filters | One-click filter by topic (DNS, Email, Social, Dark Web, GEOINT…) |
| 📊 Stats Bar | Shows total tools, categories, and newly added tools at a glance |
| 🔽 Collapsible Sections | Click any category header to expand or collapse |
| 🆕 New Badge | All newly added tools are clearly marked |
| 🌐 Direct Links | Every tool opens in a new tab |

---

## 🗂️ Categories

| # | Category | What It Covers |
|---|----------|----------------|
| 1 | **Company Intelligence** | Corporate research, SEC filings, offshore leaks, business registries |
| 2 | **DNS & Network Recon** | Shodan, Censys, FOFA, DNS history, IP/ASN lookup, site tech stack |
| 3 | **Email Intelligence** | Email verification, breach lookup, account discovery (Hunter, HIBP, GHunt…) |
| 4 | **Phone Number Lookup** | Carrier lookup, reverse phone, PhoneInfoga, TrueCaller |
| 5 | **People Search** | Public records, genealogy, people aggregators |
| 6 | **Username & Identity** | Cross-platform username search (Sherlock, Maigret, WhatsMyName…) |
| 7 | **Social Networks** | Direct links to all major platforms including Telegram, TikTok, Bluesky |
| 8 | **Social Media Analysis** | Analytics, account investigation, hashtag/geo tools per platform |
| 9 | **Image & Face Search** | Reverse image search, facial recognition, EXIF metadata extraction |
| 10 | **Video Intelligence** | YouTube geo-search, video verification (InVID), open video archives |
| 11 | **Search Engines** | Google, Bing, DuckDuckGo, Yandex, Baidu, Brave, Startpage + dorking |
| 12 | **Dark Web & Data Leaks** | Tor search engines, breach databases, dark web monitors |
| 13 | **Geolocation & Mapping** | Satellite imagery, shadow analysis, GPS extraction, geo-OSINT tools |
| 14 | **Threat Intelligence** | IOC lookup, malware, IP reputation, threat feeds |
| 15 | **OSINT Frameworks** | Maltego, Spiderfoot, Recon-ng, Bellingcat toolkit, OSINT Framework |
| 16 | **Documents & Metadata** | FOCA, Metagoofil, pastebin, Google Hacking Database |
| 17 | **Crypto & Blockchain** | Blockchain explorers, wallet tracing, Etherscan, Chainalysis |

---

## 🆕 Newly Added Tools (v2.0)

**Geolocation / GEOINT** (new category)
- GeoSpy AI, SunCalc, Sentinel Hub EO Browser, Mapillary, NASA Worldview, Pic2Map, GeoHack

**Threat Intelligence** (new category)
- VirusTotal, URLScan.io, AbuseIPDB, AlienVault OTX, Pulsedive, Talos Intelligence, Malware Bazaar

**Crypto / Blockchain** (new category)
- Etherscan, Blockchain Explorer, Chainalysis, Crystal Blockchain, TRM Labs, WalletExplorer

**Documents & Metadata** (new category)
- FOCA, Metagoofil, Exploit-DB Google Hacking DB, Pastebin, DocFetcher

**DNS / Network**
- Censys, FOFA, ZoomEye, IPinfo, URLScan.io, Wappalyzer, RiskIQ Community, ASN Lookup

**Email**
- GHunt, Holehe, BreachDirectory, LeakCheck, IntelX Email

**Social Media**
- Sherlock, Maigret, TikTok, Bluesky, Discord Lookup, Mastodon, Reddit Investigator, Telegago

**People**
- Spokeo, FastPeopleSearch, ClustrMaps, WebMii

**Dark Web**
- Ahmia, DarkSearch.io, SnusBase, Leak-Lookup, BreachForums Monitor

---

## ⚠️ Legal & Ethical Disclaimer

> This toolkit is intended **for authorized research, journalism, law enforcement, and cybersecurity professionals only.**
>
> - Always comply with applicable laws in your jurisdiction
> - Respect Terms of Service of each platform
> - Do not use these tools to harass, stalk, or harm individuals
> - Some tools (dark web searches, breach databases) may be restricted in certain regions
>
> **The authors bear no responsibility for misuse of this toolkit.**

---

## 🔧 Customization

The dashboard is a single HTML file with all data defined in a JavaScript array (`DATA`) near the bottom of the `<script>` tag. To add a new tool:

```js
{ name: 'Tool Name', url: 'https://example.com', badge: 'new' }
```

To add a new category, append a new object to the `DATA` array:

```js
{
  id: 'my-category',
  title: 'My Category',
  icon: '🔬',
  filter: 'all',          // or a custom filter key
  tools: [
    { name: 'Example Tool', url: 'https://example.com', badge: 'new' }
  ]
}
```

---

## 📦 Version History

| Version | Changes |
|---------|---------|
| v1.0 | Original bookmark export (Netscape HTML format) |
| v2.0 | Full dashboard redesign; 4 new categories; 60+ new tools added; live search & filter |

---

*Generated for OSINT research purposes. Use responsibly.*
