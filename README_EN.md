# 🎄 OSINT Advent Calendar 2025

> A curated collection of OSINT tools, techniques, and resources revealed daily throughout December 2025.

## 📖 Overview

Welcome to the OSINT Advent Calendar 2025! This repository presents 24 carefully selected Open Source Intelligence (OSINT) tools, techniques, and resources, unveiled one day at a time from December 1st through December 24th, 2025.

Each day brings a new insight into the world of OSINT, covering everything from reconnaissance and data gathering to analysis and visualization techniques.

## 🎁 Daily Reveals

Click on each day to discover the tool or technique:

- **[Day 1](#day-1)** - Searx - Privacy-focused Meta Search Engine
- **[Day 2](#day-2)** - Web-check - All-in-One Website Analysis Tool
- **[Day 3](#day-3)** - Sputnik - Browser Extension for Quick Website Analysis
- **[Day 4](#day-4)** - Host.io - Domain Relationship Discovery
- **[Day 5](#day-5)** - Web Archives - Multi-Source Web Archiving Extension
- **[Day 6](#day-6)** - Donut Browser - Multi-Profile Browser with Anti-Detection
- **[Day 7](#day-7)** - Pappers Immobilier - Real Estate Intelligence Platform
- **[Day 8](#day-8)** - ImportYeti - Supply Chain Intelligence Tool
- **[Day 9](#day-9)** - Hunter.io - Email Discovery and Pattern Analysis
- **[Day 10](#day-10)** - Source Code Intelligence - PublicWWW, Grep.app, Sourcegraph
- **[Day 11](#day-11)** - Google Dorking - Advanced Search Operators
- **[Day 12](#day-12)** - Ads Intelligence - Platform Ad Libraries
- **[Day 13](#day-13)** - Maritime OSINT - Equasis Ship Database
- **[Day 14](#day-14)** - Username Enumeration - RhinoUserChecker
- **[Day 15](#day-15)** - Open Data Portals - Government Data Sources
- **[Day 16](#day-16)** - Internet Monitoring - IODA, OONI, Liveuamap
- **[Day 17](#day-17)** - Alternative Mapping Services - Regional Street View Alternatives
- **[Day 18](#day-18)** - NASA FIRMS - Thermal Satellite Monitoring for Conflict Analysis
- **[Day 19](#day-19)** - Earthkit - OSINT Geographic Investigation Platform
- **[Day 20](#day-20)** - Smappen - Isochrone Mapping for Time-Based Analysis
- **[Day 21](#day-21)** - Search by Image - Multi-Engine Image Search
- **[Day 22](#day-22)** - Infrastructure Mapping - OpenInfraMap, OpenRailwayMap, Wikimapia
- **[Day 23](#day-23)** - Vehicle Tracking - ADS-B Exchange & Global Fishing Watch
- **[Day 24](#day-24)** - *Coming December 24th*

---

## 📅 Detailed Content

### Day 1
**Tool/Technique:** Searx - Privacy-focused Meta Search Engine

**Description:** Searx is an open-source meta search engine that aggregates results from dozens of search engines (Google, Bing, Qwant, etc.) while protecting your privacy. Unlike traditional search engines, Searx cleans your queries before sending them, ensuring comprehensive search results without exposing your identity or search patterns.

For OSINT investigations, this eliminates tracking, filter bubbles, and personalized results that can bias your analysis. You get raw, unbiased results from multiple sources without being profiled or tracked.

**Key Features:**
- 🔎 **Multi-source aggregation**: Search across multiple engines simultaneously for comprehensive results
- 🛡️ **Zero tracking**: No profiling, no search history, complete privacy protection
- 🧭 **Unbiased results**: No personalization based on location or history - pure, raw data
- 🔧 **Customizable & self-hostable**: Open source and configurable to your needs
- 🌍 **Location-independent**: Results not influenced by your geographical location

**Resources:**
- Public instances: https://searx.space/
---

### Day 2
**Tool/Technique:** Web-check - All-in-One Website Analysis Tool

**Description:** When launching reconnaissance on a website, you often end up juggling 5 or 6 open tabs - one for Whois, one for DNS, another to check the SSL certificate, yet another for server location... This is time-consuming and disperses attention, and you end up missing certain things.

Web-check is a "Swiss Army knife" for web analysis. Simply enter a URL and it launches a battery of tests generating a complete dashboard. It's a must-have tool for saving time during web reconnaissance.

**Key Features:**
- 📊 **All-in-one**: IP, SSL Chain, Headers, DNS, Cookies, all on a single page
- ⚡ **Speed**: Analysis takes a few seconds vs 10 minutes manually
- 🔍 **Depth**: Often detects forgotten technical info (WAF, server technologies, privacy.txt)
- 🖼️ **Visual**: Ideal for taking quick screenshots and generating comprehensive reports
- 🔓 **Open source**: No installation required for web version, but also available as self-hosted solution

**Resources:**
- Web Version: https://web-check.xyz/
- GitHub Repository: https://github.com/Lissy93/web-check
- Note: Provides "X-ray vision" of a website without installing any tools

---

### Day 3
**Tool/Technique:** Sputnik - Browser Extension for Quick Website Analysis

**Description:** Sputnik is a Chrome/Firefox extension that provides instant technical information about websites without ever leaving your browser. When investigating suspicious sites, having to copy URLs and switch to external tools breaks your workflow and wastes time. Sputnik eliminates this friction by bringing essential OSINT pivots directly into your browser.

With a single click, you get IP addresses, server locations, hosting information, and direct links to analysis platforms. It's designed for investigators who need to qualify targets continuously without breaking their rhythm.

**Key Features:**
- 🖱️ **Instant access**: One click to get IP, server location, and hosting information
- 🔗 **Quick pivots**: Direct links to VirusTotal, Censys, Shodan, and other OSINT platforms
- 📄 **Page analysis**: Automatically extracts URLs, emails, and artifacts from the current page
- 🐛 **Security insights**: Detects technologies used and associated CVEs
- 🎯 **Context menu integration**: Right-click any IP, domain, hash, or URL for instant OSINT lookups

**Resources:**
- GitHub Repository: https://github.com/mitchmoser/sputnik
- Installation: Available for Chrome/Chromium and Firefox browsers (install from GitHub releases)

---

### Day 4
**Tool/Technique:** Host.io - Domain Relationship Discovery

**Description:** Host.io is a search engine that goes beyond simple DNS lookups to map the relationships between domains. When investigating a target domain, the Whois is often anonymized (GDPR) and DNS doesn't reveal the full picture. Host.io helps you understand the complete ecosystem around a domain by analyzing backlinks, co-hosting relationships, and redirections.

Instead of looking at an isolated website, you can discover entire networks of interconnected domains - perfect for uncovering disinformation networks, Private Blog Networks (PBNs), or organized fraud operations.

**Key Features:**
- 🔗 **Backlink analysis**: See which sites link to your target, revealing networks and connections
- 📍 **Co-hosting discovery**: List all domains hosted on the same IP or server
- ➡️ **Redirection tracking**: Follow the trail to see where users are actually sent
- 🌐 **Network mapping**: Visualize connections between related domains
- 🔍 **Relationship intelligence**: Uncover hidden relationships between seemingly unrelated sites

**Resources:**
- Website: https://host.io/
- Use Cases: Network analysis, fraud investigation, domain research

---

### Day 5
**Tool/Technique:** Web Archives - Multi-Source Web Archiving Extension

**Description:** The fundamental principle of OSINT is "The Internet never forgets" (or almost never). A 404 page, a deleted tweet, or a discreetly modified article is the daily reality of investigators. While everyone knows the Wayback Machine (Internet Archive) as the baseline, it's not infallible. Sometimes it's down, sometimes pages are excluded, or simply not crawled at the right time. The Web Archives extension is an open-source tool for browsers that allows you, with a single right-click on any page (even dead ones), to simultaneously query all web archives or one by one.

This meta-archiving tool dramatically increases your chances of recovering disappeared digital evidence by searching across multiple archive services beyond just the Wayback Machine.

**Key Features:**
- 🔄 **Multi-source querying**: Access Archive.is, Yandex Cache, Memento Time Travel, and more simultaneously
- 🌍 **Geographic coverage**: Yandex Cache is particularly useful for Eastern Europe/Russia content
- ⚡ **Quick access**: Right-click context menu for instant archive searches
- 📚 **Comprehensive coverage**: Includes Megalodon, Ghostarchive, Perma.cc, and other specialized archives
- 🎯 **Fallback redundancy**: If one archive missed the page, others may have captured it

**Resources:**
- Browser Extension: https://github.com/dessant/web-archives

---

### Day 6
**Tool/Technique:** Donut Browser - Multi-Profile Browser with Anti-Detection

**Description:** When investigating, especially on sensitive cases, using your personal browser (Chrome/Edge connected to your Google account) is a critical mistake. The risk is "cross-contamination": target sites can detect your digital fingerprint including your IP address, your personal accounts get mixed with your sockpuppets, and different investigations aren't isolated from each other. There's a real risk of accidentally leaking your real identity. You must compartmentalize: each investigation or identity must live in an isolated bubble.

Donut Browser is designed specifically to manage multiple isolated profiles. Its true strength lies under the hood: it's based on Camoufox, an "anti-detection" browser engine that dynamically modifies the browser fingerprint to appear natural and random, unlike a simple VPN that often just changes the IP.

**Key Features:**
- 🛡️ **Real anonymity**: Defeats anti-bot protections (Cloudflare, etc.) much better than simple "Incognito" mode
- 🎭 **Identity management**: Switch between profiles without cross-contamination (cookies, local storage, investigation accounts)
- 🔒 **Protection**: Your searches don't leak into your real identity
- 🌐 **Proxy support**: Configure different proxies per profile for IP isolation (VPN recommended)
- 🔧 **Fingerprint randomization**: Dynamic browser fingerprint modification via Camoufox engine

**Resources:**
- Donut Browser: https://donut.surf/
- Camoufox Engine: https://camoufox.com/
- Note: Currently available on Linux & Mac, Windows version coming soon
- ⚠️ Important: Donut/Camoufox do NOT mask your IP address by default - use with VPN or proxy

---

### Day 7
**Tool/Technique:** Pappers Immobilier - Real Estate Intelligence Platform

**Description:** Knowing who owns a building, warehouse, or vacant lot has long been tedious (requests to the cadastre, delays, complexity). Pappers (the reference for company data) has released a tool that changes the game by cross-referencing their data with the cadastre. Pappers Immobilier is a map-based interface that allows you to visualize data directly on the cadastral plan. Concretely: you navigate the map, click on a plot, and the "magic" happens.

This tool transforms real estate due diligence from a multi-day process into a 3-minute task, providing X-ray vision into property ownership, financial transactions, and corporate structures.

**Key Features:**
- 📍 **X-ray vision**: Immediately see which buildings or businesses are registered on a plot
- 💰 **Financial transparency**: Access to real estate sale prices (DVF), transaction dates, and amounts involved
- 🏢 **Ownership identification**: Trace back to corporate owners (SCI, Holdings) with one click
- 🗺️ **Interactive mapping**: Visual cadastral interface for intuitive navigation
- 🔍 **Comprehensive data**: Extremely complete even in free version (doesn't cover 100% of territory with equal precision yet)

**Resources:**
- Interactive Map: https://immobilier.pappers.fr/
- Price Database Only: https://app.dvf.etalab.gouv.fr/
- Note: Probably the best free-access tool currently available for French real estate intelligence

---

### Day 8
**Tool/Technique:** ImportYeti - Supply Chain Intelligence Tool

**Description:** Knowing who your target is is one thing. Knowing who they work with (and where their money or merchandise comes from) is another. Often, companies keep their suppliers secret. But there's a flaw: customs. ImportYeti is a goldmine that aggregates over 70 million customs records (Bills of Lading) concerning imports to the United States. It allows you to graphically visualize commercial relationships between companies.

This powerful tool reveals the hidden supply chain networks behind brands and organizations, making it invaluable for due diligence, competitive intelligence, and investigation work.

**Key Features:**
- 📦 **Traceability**: Discover who actually manufactures products for a brand (e.g., Apple, Nike, or your competitor)
- 🔗 **Network mapping**: Visualize the entire network of suppliers and subcontractors
- 🕵️ **Due diligence**: Verify if a company works with controversial entities or those in high-risk zones
- 📊 **70M+ records**: Access to extensive U.S. customs import data (Bills of Lading)
- 💎 **Generous free tier**: Incredibly powerful even in the free version

**Resources:**
- Website: https://www.importyeti.com/
- Use Cases: Supply chain analysis, competitive intelligence, vendor research
- Note: Probably the most powerful tool for investigating physical flows

---

### Day 9
**Tool/Technique:** Hunter.io - Email Discovery and Pattern Analysis

**Description:** When your target is an organization (a domain name), the next step is to understand who's behind it. Who are the employees? What's the internal structure? And finding new pivots (emails are powerful...). Hunter.io is the reference for mapping email addresses from a domain name. It scans the public web to identify professional email addresses associated with a company.

This essential tool bridges the gap between analyzing a "legal entity" and identifying the "natural persons" behind it, making it invaluable for moving from organization-level to individual-level investigation.

**Key Features:**
- 🔑 **Pattern detection**: Analyzes data to deduce email creation logic (e.g., firstname.lastname@company.com or f.lastname@...). Once known, you can reconstruct anyone's email, even if it appears nowhere.
- 👥 **Employee census**: Lists "visible" emails on the web, helping draw the company's org chart (who's in accounting, who's in IT, etc.)
- 🔗 **Source attribution**: Shows where each email was found (contact page, technical PDF, blog) - excellent clue for understanding the person's real role
- 📧 **Email verification**: Built-in validation to check if discovered emails are active
- 🎯 **Domain-wide coverage**: Comprehensive scanning across public web sources

**Resources:**
- Website: https://hunter.io/
- Alternative Tools: Lusha (https://www.lusha.com/), Apollo (https://www.apollo.io/), Kaspr (https://www.kaspr.io/)
- Note: Indispensable for transitioning from entity analysis to person identification

---

### Day 10
**Tool/Technique:** Source Code Intelligence - PublicWWW, Grep.app, Sourcegraph

**Description:** Google indexes what's written on the page. An investigator must look at what's written behind it. Source code can contain tracking identifiers, developer comments, or links to test environments. Traditional search engines cannot "dork" source code effectively. For this dimension of OSINT, you need specialized tools that search through HTML, JavaScript, CSS, and Git repositories.

This trio of complementary tools allows you to search through millions of websites' source code and public repositories to find connections, configurations, and hidden links between sites.

**Key Features:**
- 🌐 **PublicWWW**: "Google for source code" - indexes HTML, JS, and CSS of millions of websites to find sites using the same code snippets
- ⚡ **Grep.app**: Search for exact strings across 500,000+ public Git repositories in fractions of a second
- 🧠 **Sourcegraph**: Developer tool for code navigation that's a goldmine for OSINT - very similar to grep.app
- 🔍 **Tracking IDs**: Find all sites using the same Google Analytics ID (UA-xxxxx) or other tracking codes
- 🔗 **Domain linking**: Discover relationships between sites through shared code signatures in footers or headers

**Resources:**
- PublicWWW: https://publicwww.com/
- Grep.app: https://grep.app/
- Sourcegraph: https://sourcegraph.com/search

---

### Day 11
**Tool/Technique:** Google Dorking - Advanced Search Operators

**Description:** Most people use search engines like a dictionary. An investigator uses them like a structured database. "Dorking" is the art of using advanced search operators to filter noise and find the needle in the internet haystack. The best OSINT tool is your brain - knowing the right syntax makes all the difference.

Don't limit yourself to Google. For precise investigation, Brave Search, Yandex, Bing, Baidu, and others often return completely different results. DuckDuckGo is often better at respecting exact string searches and special characters that Google ignores.

**Key Features:**
- 🎯 **site:** - Force search only on specific domain (e.g., site:linkedin.com "target name")
- 📄 **filetype:** - Search only for specific files (pdf, xlsx, docx, pptx) - powerful combined with site:
- 🔍 **"exact phrase"** - Indispensable. Prevents search engines from finding synonyms or approximations
- ➖ **minus operator** - Remove noise (e.g., jaguar -car to search only for the animal)
- 🔄 **Multi-engine pivoting** - Different search engines (Google, Yandex, Bing, DuckDuckGo) return different results

**Resources:**
- Google Advanced Search: https://www.google.com/advanced_search
- DuckDuckGo: https://duckduckgo.com/
- Yandex: https://yandex.com/
- Dorking Cheat Sheet: Multiple resources available online
- Note: No expensive software needed - just the right syntax

---

### Day 12
**Tool/Technique:** Ads Intelligence - Platform Ad Libraries

**Description:** Major platforms are required to make their advertisements publicly accessible. For an investigator, this is a goldmine for analyzing strategy, targeting, and the real identity of an entity. These transparency databases allow you to see who's running ads, what they're promoting, and who's really behind a page or campaign.

Covering the full spectrum requires access to multiple ad libraries across different platforms - each reveals different aspects of digital marketing operations and influence campaigns.

**Key Features:**
- 📊 **Google Ads Transparency**: Everything on Search and YouTube advertising
- 📱 **Meta Ad Library**: Reference for Facebook and Instagram - ideal for tracking who really manages a page or dropshipping operations
- 💼 **LinkedIn Ad Library**: Essential for Corporate OSINT - analyze B2B targeting and aggressive recruitment campaigns
- 🔍 **Microsoft Ad Library (Bing)**: Often forgotten but crucial for finding "malvertising" (fake ads for malware distribution)
- 📹 **TikTok Creative Center**: Analyze viral trends, video ads, and influence operations targeting youth
- 🎮 **Reddit Ads Inspiration**: Observe campaigns targeting niche communities (Tech, Crypto, Gaming)

**Resources:**
- Google: https://adstransparency.google.com/
- Meta: https://www.facebook.com/ads/library/
- LinkedIn: https://www.linkedin.com/ad-library/
- Microsoft: https://adlibrary.ads.microsoft.com/
- TikTok: https://library.tiktok.com/
- Reddit: https://ads.reddit.com/inspiration/

---

### Day 13
**Tool/Technique:** Maritime OSINT - Equasis Ship Database

**Description:** For tracking ships, everyone has the reflex to use MarineTraffic or VesselFinder. These tools are excellent for real-time visualization. But when you want to access complete history or detailed ownership structures, you often hit a paywall. Equasis is the reference tool - a public interest database (EU and France initiative) focused on ship safety and quality. Where others sell commercial data, Equasis provides administrative data.

Unlike AIS tracking that can be spoofed, Equasis provides immutable technical details and official inspection records that prove a vessel's physical presence and history.

**Key Features:**
- 🔗 **Ownership chain**: Trace complete history - who owned the ship 5 years ago? Who was the original builder?
- 🔧 **Technical DNA**: Immutable details (IMO number, shipyard, construction date) to recognize a ship even if repainted or renamed
- ⚠️ **Sanctions & Detentions**: Lists safety inspections (Port State Control) - ships banned from ports or frequently detained are immediate red flags
- 📍 **Proof of presence**: Unlike AIS which can be falsified, an inspection recorded in Equasis physically proves the ship's presence in a port on a given date
- 🌊 **Free administrative data**: Access to official records without commercial paywalls

**Resources:**
- Equasis: https://www.equasis.org/
- Aircraft Alternative: https://www.planespotters.net/ (incredible tool for planes)
- Note: Essential for verifying compliance and tracing the real history of a vessel beyond its current position

---

### Day 14
**Tool/Technique:** Username Enumeration - RhinoUserChecker

**Description:** Reusing the same username across multiple platforms is the most common OpSec mistake. It's the simplest pivot to go from an innocuous account to sensitive activity. While WhatsMyName.app is the well-known web reference, it sometimes reaches its limits in terms of false positives or coverage. Tools like RhinoUserChecker by Oscar Zulu Osint Crew offer a "revisited" approach often more performant.

This is the quintessential pivot tool for expanding your attack surface - discovering the "other lives" of a target by finding where they've reused usernames across the internet.

**Key Features:**
- 🛡️ **Rate limit bypass**: Detects potential blockages and provides direct links for manual verification if automation fails
- 🎨 **Modern UX**: More modern and readable interface than typical austere OSINT tools - facilitates quick visualization of positive results
- 🔄 **Unified suite**: Not limited to usernames - it's a hub centralizing other investigation tools (metadata, geoint) for seamless pivoting
- 🔍 **False positive reduction**: Better handling of edge cases and platform-specific quirks
- 🕵️ **Cross-platform discovery**: A user may be cautious on LinkedIn but reuse their historical username on a sketchy forum or dating site

**Resources:**
- RhinoUserChecker: https://github.com/degun-osint/RhinoUserChecker
- OSINT Is Not A Crime Hub: https://osintisnotacrime.com/ (with other interesting tools to try)
- Alternative: WhatsMyName.app for comparison
- Note: Essential for discovering alternate identities and expanding investigation scope

---

### Day 15
**Tool/Technique:** Open Data Portals - Government Data Sources

**Description:** In OSINT, going back to the primary source is essential to guarantee information reliability. Rather than depending on third-party aggregators, it's possible to directly exploit raw data made available by states. These portals are particularly useful for developers wanting to automate searches via API.

These official government portals provide the "raw material" of investigation - legal, unaltered data, often available via free APIs for mass processing.

**Key Features:**
- 🇫🇷 **France (data.gouv.fr)**: SIRENE database (companies), DVF (real estate values), National Registry of Associations
- 🇬🇧 **UK (data.gov.uk)**: Direct access to UK government data, Companies House integration, public spending transparency
- 🇪🇺 **EU (data.europa.eu)**: Entry point for EU institutional data, TED register (public tenders across Europe)
- 🇺🇸 **USA (data.gov)**: Massive federal datasets, federal contracts, FARA (foreign influence registry)
- 🇷🇺 **Russia (data.gov.ru)**: Russian administrative data, public procurement, federal statistics (may require VPN)

**Resources:**
- France: https://www.data.gouv.fr/
- United Kingdom: https://www.data.gov.uk/
- European Union: https://data.europa.eu/
- United States: https://www.data.gov/
- Russia: https://data.gov.ru/
- Example Application: Taipower Poles (uses Taiwan Open Data to geolocate power poles) - https://0d.lv/toolbox/taipower 

---

### Day 16
**Tool/Technique:** Internet Monitoring - IODA, OONI, Liveuamap

**Description:** In geopolitics, observing the state of the internet network is a precious indicator. A drop in traffic or a blockage (like those orchestrated by Roskomnadzor in Russia) can signal an imminent crisis. However, interpreting these signals requires great caution: a technical failure, overload, or power outage can look deceptively similar to a voluntary blockage.

To formulate a solid hypothesis, you must triangulate sources. The goal isn't to conclude immediately, but to create a "strategic hypothesis". For example, if IODA shows a brutal cutoff at the exact time Liveuamap signals riots, the correlation is strong, but it only becomes proof after verification.

**Key Features:**
- 📊 **IODA (Internet Outage Detection)**: Monitors global traffic to detect if a region is disconnected, but not why - detects technical anomaly without distinguishing state censorship from infrastructure failure
- 🔒 **OONI Explorer**: Uses local probes to test specific blocking of sites or apps (WhatsApp, Telegram) - reveals targeted censorship
- 🗺️ **Liveuamap**: Cartographic aggregator of incidents (conflicts, protests) based on OSINT - shows if network anomaly coincides with ground events
- ⚠️ **Triangulation required**: Cross-reference all three sources to distinguish technical issues from deliberate censorship
- 🔍 **Context is key**: Correlate with local media, satellite imagery, and other sources before drawing conclusions

**Resources:**
- IODA: https://ioda.inetintel.cc.gatech.edu/
- OONI Explorer: https://explorer.ooni.org/
- Liveuamap: https://liveuamap.com/
- Note: Digital silence can signal a crisis - but verify before concluding

---

### Day 17
**Tool/Technique:** Alternative Mapping Services - Regional Street View Alternatives

**Description:** Google Maps doesn't see everything. While Street View is omnipresent in the West, it's patchy or even useless in vast areas of the world. For an investigator, using local mapping services isn't an option - it's a necessity to obtain up-to-date images, interior floor plans, or simply coverage where Google is absent.

Each tech giant maps its own territory better than foreign competitors. Adapting your mapping tool to the geographic zone you're investigating dramatically improves data quality and coverage.

**Key Features:**
- 🇫🇷 **Panoramax (France)**: IGN/State-backed open "Wikipedia of Street View" - contributive with recent updates, no advertising tracking
- 🇷🇺 **Yandex Maps & 2GIS (Russia/CIS/Turkey)**: Better resolution than Google in Eastern Europe; 2GIS maps building interiors, floor plans, and exact entrance locations
- 🇨🇳 **Baidu Maps (China)**: Essential where Google is nearly empty - exhaustive coverage of Chinese megacities with Baidu Total View; note GCJ-02 coordinate obfuscation
- 🇰🇷 **Naver Map & Kakao Map (South Korea)**: Korea restricts map data export for security - Google is degraded; ultra-HD Street View with recent aerial views and precise local business data
- 🗺️ **Geographic adaptation**: Each region requires its specific mapping tool for optimal OSINT coverage

**Resources:**
- Panoramax (France): https://panoramax.fr/
- Mapillary: https://www.mapillary.com/app/
- Yandex Maps: https://yandex.com/maps/
- 2GIS: https://2gis.ru/
- Baidu Maps: https://map.baidu.com/
- Naver Map: https://map.naver.com/
- Kakao Map: https://map.kakao.com/
- Note: Operational interest - adapt your tool to your geographic investigation zone

---

### Day 18
**Tool/Technique:** NASA FIRMS - Thermal Satellite Monitoring for Conflict Analysis

**Description:** Optical cameras see nothing at night or through smoke. Thermal sensors do. NASA FIRMS is a tool originally designed to monitor wildfires, but it has become indispensable for detecting explosions, artillery fire, or industrial activities in real-time.

The principle is simple: If you see a thermal anomaly (intense heat) in the middle of the night in a field in Ukraine or Gaza, it's probably not a barbecue (or it went very wrong). It's potentially a strike, a burning vehicle, maybe a factory.

**Key Features:**
- 🛰️ **Thermal detection**: VIIRS sensor with 375-meter resolution detects heat sources invisible to optical cameras
- ⏱️ **Near real-time**: Approximately 3-4 hour latency - not truly real-time, but close
- 🔍 **Cross-check methodology**: Essential to confirm events by correlating multiple sources
  - **OpenInfraMap**: Check if there's a power plant or refinery under the red dot (normal heat source?)
  - **Social Media (X, Telegram)**: Search locality name + "explosion" or "noise" - are locals reporting it?
  - **Satellite Imagery (Maxar, Planet, Sentinel)**: Visually confirm impact, smoke, or destroyed buildings
- ⚠️ **Interpretation caution**: FIRMS is an alert, never immediate proof - factories and refineries also appear red
- 📍 **Precision limits**: 375m resolution means you're locating a zone, not a specific building
- 🌙 **Night vision**: Works 24/7 regardless of lighting or weather conditions (except dense cloud cover)

**Resources:**
- NASA FIRMS: https://firms.modaps.eosdis.nasa.gov/map/
- OpenInfraMap (for cross-checking): https://openinframap.org/
- Use Cases: Conflict monitoring, industrial activity tracking, wildfire detection
- Note: Always cross-reference with other sources before drawing conclusions about thermal anomalies

---

### Day 19
**Tool/Technique:** Earthkit - OSINT Geographic Investigation Platform

**Description:** We often juggle between data collection, cartographic visualization, and visual verification. Earthkit is an open-source platform that consolidates these steps into a unified workflow for geographic investigation.

The traditional workflow is fragmented: First, you extract data from Overpass Turbo (the technical search engine for OpenStreetMap) which returns raw lists of 1000+ points. Then you manually copy-paste coordinates into Google Maps to verify each one. This process is tedious and time-consuming. Earthkit bridges this gap by combining data collection, filtering, and visual verification in one interface.

**Key Features:**
- 🗺️ **Overpass Turbo integration**: Query OpenStreetMap for objects (e.g., "all cinemas within 300m of a McDonald's" or "all fire hydrants in Paris")
- 🔍 **Visual triage (Sift)**: Import Overpass data for accelerated visual sorting - each coordinate loads Satellite view, Street View, and map simultaneously
- ⚡ **Unified interface**: No more copy-pasting into Google Maps or switching tabs - scroll through results and qualify info (Relevant/False positive) in seconds
- 🤖 **AI-powered queries**: Can't code in Overpass QL? Ask the integrated AI in plain language: "Find me power plants near a river" and it writes the query for you
- 📊 **Perfect bridge**: Combines mass data collection (Overpass) with precision analysis (visual verification)

**Resources:**
- Earthkit App: https://earthkit.app/
- Source Code: https://github.com/JettChenT/earthkit
- Overpass Turbo: https://overpass-turbo.eu/
- Note: Open source platform that streamlines geographic investigation workflow

---

### Day 20
**Tool/Technique:** Smappen - Isochrone Mapping for Time-Based Analysis

**Description:** In investigation, "as the crow flies" distance is often misleading. Knowing a suspect is "5 km" from a location means nothing if there's a river without a bridge or heavy traffic. What matters isn't distance - it's access time.

Smappen is a mapping tool originally designed for marketing (catchment areas) but repurposed by investigators to generate isochrones - areas reachable within specific time frames by different transportation modes.

**Key Features:**
- ✅ **Coherence verification**: A target claims they left their office at 6:00 PM and arrived home at 6:15 PM. Draw the 15-minute driving zone from the office. If home is outside this "oil stain" zone, the story is technically impossible.
- 🎯 **Triangulation by intersection**: Most powerful for locating a residence or hideout. If you know the target lives within 10 min walking from a specific train station AND within 15 min driving from a certain sports club, trace both zones and find their intersection - reducing search area from an entire city to a few blocks.
- 📍 **Geographic profiling**: Define priority search zones around a point, distinguishing what's accessible by foot, bike, or car
- 🗺️ **Realistic mobility zones**: Move from theoretical radius (perfect circle, often wrong) to realistic mobility zones (complex shapes based on actual roads)
- ⏱️ **Time-based analysis**: Account for real-world constraints like traffic, road networks, and transportation mode

**Resources:**
- Smappen: https://www.smappen.com/
- Use Cases: Timeline verification, residence triangulation, geographic profiling
- Note: Essential for drastically reducing search zones based on realistic travel times

---

### Day 21
**Tool/Technique:** Search by Image - Multi-Engine Image Search

**Description:** Limiting yourself to Google for reverse image search is often insufficient. Each search engine has its strengths - Yandex excels at faces and Cyrillic text, Bing performs well on products and Western content, Baidu dominates for Chinese imagery. But manually testing each engine is tedious and time-consuming.

Search by Image is an open-source browser extension that automates multi-engine reverse image searches, eliminating the need to manually upload the same image to multiple platforms.

**Key Features:**
- 🚀 **Simultaneous multi-engine search**: Launch searches across all chosen engines at once (Google, Bing, Yandex, Baidu, TinEye, and more)
- ⚡ **One-click operation**: Right-click any image and search across multiple engines - no more opening 5+ tabs manually
- 🌐 **Engine diversity**: Each search engine indexes different parts of the web - maximize coverage by querying all simultaneously
- 🎯 **Targeted searches**: Option to search specific engines individually for focused investigation
- 🔓 **Open source**: Transparent code, community-maintained, free to use

**Resources:**
- GitHub Repository: https://github.com/dessant/search-by-image
- Browser Extensions: Available for Chrome, Firefox, Edge, and other Chromium-based browsers
- Supported Engines: Google, Bing, Yandex, Baidu, TinEye, and many more
- Note: Essential tool for comprehensive reverse image investigations

---

### Day 22
**Tool/Technique:** Infrastructure Mapping - OpenInfraMap, OpenRailwayMap, Wikimapia

**Description:** Consumer maps focus on roads and commercial locations. For an analyst, evaluating the logistical or industrial capabilities of an area requires specialized data. Mainstream mapping services don't show power grids, railway specifications, or industrial facility details.

This trio of specialized maps allows you to visualize technical infrastructure networks that are invisible on Google Maps but crucial for geolocation, logistics analysis, and industrial intelligence.

**Key Features:**
- ⚡ **OpenInfraMap (Electrical Network)**: Visualizes high-voltage power lines, transformers, and telecom infrastructure based on OpenStreetMap. Crucial for geolocation - filter by voltage to match specific pylon types visible in photos, drastically reducing search zones to corresponding power lines only.
- 🚂 **OpenRailwayMap (Railway Network)**: Details global railway infrastructure including maximum speed, electrification type, track gauge, and service lines. Essential for logistics analysis - assess whether a line can support heavy freight or identify industrial supply routes.
- 🏭 **Wikimapia (Site Identification)**: Collaborative map where users annotate buildings and industrial zones directly on satellite imagery. Identifies unlisted installations - where Google Maps shows a gray unnamed zone, Wikimapia often indicates precise function (e.g., "Chemical plant", "Military depot", "Penitentiary") thanks to local knowledge.
- 🔍 **Specialized data layers**: Overlay technical layers (energy, transport, industry) on physical geography to understand how a territory actually functions
- 🎯 **Geolocation precision**: Use infrastructure signatures to narrow down search areas when investigating photos or videos

**Resources:**
- OpenInfraMap: https://openinframap.org/
- OpenRailwayMap: https://www.openrailwaymap.org/
- Wikimapia: https://wikimapia.org/
- Note: Far from exhaustive - superpose technical data layers to understand real territorial functioning

---

### Day 23
**Tool/Technique:** Vehicle Tracking - ADS-B Exchange & Global Fishing Watch

**Description:** Most tracking sites (MarineTraffic, FlightRadar24) restrict access to interesting data (history, military) behind expensive paywalls or censorship. Here's a duo of free tools to bypass these limitations and access the "ground truth" without budget constraints.

These tools break the "Freemium" model by providing access to uncensored data and historical records that commercial platforms hide behind paywalls, enabling investigators to track military movements and detect suspicious maritime activities.

**Key Features:**
- ✈️ **ADS-B Exchange (Air)**: The only major air tracker that refuses to filter data on owners' requests. Unlike competitors, it displays oligarch private jets, police, and military aircraft. If it transmits, it displays. Click the "U" button at top of map to show only "Military and Interesting" traffic.
- 🚢 **Global Fishing Watch (Sea)**: Don't be fooled by the name - this ecology tool ingests AIS signals from all vessels (Tankers, Cargo, Fishing). Offers free multi-year historical data where others charge for anything beyond 24 hours.
- 🔍 **Uncensored tracking**: Access to military flights, private jets, and vessel movements that commercial platforms censor
- 📊 **Free historical data**: Multi-year tracking history without premium subscriptions
- 🎯 **Transhipment detection**: GFW automatically detects "Encounters" - when two vessels stay together at sea, indicating potential illicit transfers (embargoed oil, supplies) that traffickers try to hide
- 💰 **Budget-friendly**: Full functionality without expensive enterprise licenses

**Resources:**
- ADS-B Exchange: https://globe.adsbexchange.com/
- Global Fishing Watch: https://globalfishingwatch.org/map
- Use Cases: Military flight tracking, maritime intelligence, illicit activity detection
- Note: These tools provide "ground truth" data (real military movements, suspicious encounters at sea) with time-travel capability, no budget required

---

### Day 24
**Tool/Technique:** The Starter Pack (Training & Community)

**Description:** The best tool is you.

For 23 days, we have seen specific tools and techniques. But OSINT is a muscle: you have to train it and know where to look when you get stuck.

I would also like to thank Florian P and everyone who helped me create this advent calendar :)

For this December 24th, here is your "Starter Pack": resources to equip yourself, get trained, and never stay alone.

**Essential Resources:**

📚 **1. The Encyclopedia**
If you only keep one bookmark, this is it. Probably the most well-known collection in the field. It lists numerous tools classified by category (Username, Maps, Email, Transport...).
🔗 **The Ultimate OSINT Collection :** https://start.me/p/DPYPMz/the-ultimate-osint-collection

🎓 **2. The Training**
To start on solid ground, nothing beats a structured course. The OSINT FR association has created a free and comprehensive initiation path (in French), ideal for acquiring methodology before starting out.
🔗 **MOOC OSINT FR :** https://mooc.osintfr.com/course/view.php?id=4

🎮 **3. The Practice**
Don't remain passive. These CTF (Capture The Flag) platforms offer concrete challenges (geolocation, imagery, people search). It is the best way to learn through trial and error.
- **GeoDetective** : https://geodetective.io/
- **Challenge OSINT FR** : https://ctf.challenge-osint.fr/
- **Osintopia** : https://challenges.osintopia.fr/
- **Bellingcat** : https://challenge.bellingcat.com/
- **OSINT4Fun** : https://fr.osint4fun.eu/challenges/

🤝 **4. The Community**
OSINT is a solitary discipline that is won as a team. The Francophone community is incredibly active and welcoming. Join these servers to ask questions or participate in events.
- **OSINT FR** : https://discord.com/invite/dWY9sWFKYD
- **Projet Fox** : https://discord.com/invite/projet-fox-775480337727225879
- **Oscar Zulu** : https://discord.com/invite/oscar-zulu
- **Hack'Olyte** : https://discord.com/invite/dbNcPStqb7

---

**Closing words:**
Thank you for following this calendar. Now, close the tutorials, open the maps, and start investigating.

**Happy Holidays to all! 🎄🕵️‍♂️**

