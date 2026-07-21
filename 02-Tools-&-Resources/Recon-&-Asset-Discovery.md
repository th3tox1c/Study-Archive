# 🔍 The Ultimate Asset Discovery & Recon Guide

<a href="https://github.com/th3tox1c">
  <img src="https://github.com/user-attachments/assets/97c0983c-4d27-4a96-ada2-926f1fc1b7a4" align="right" width="120">
</a>

Asset Discovery means finding every digital asset that belongs to a target—like web apps, subdomains, cloud buckets, exposed code, and open ports. 

In modern cybersecurity and bug bounty, you can't protect (or test) what you don't know exists. This guide contains a hand-picked list of the best tools, frameworks, and OSINT techniques to help you perform complete reconnaissance and map out full attack surfaces.

---

## 📌 Table of Contents

- [Content Discovery](#content-discovery)
- [IP Address Discovery](#ip-address-discovery)
- [Domain & Subdomain Discovery](#domain--subdomain-discovery)
- [Email Discovery](#email-discovery)
- [Network & Port Scanning](#network--port-scanning)
- [Business Communication Infrastructure](#business-communication-infrastructure)
- [Source Code Aggregators & Information Search](#source-code-aggregators--information-search)
- [Cloud Infrastructure Discovery](#cloud-infrastructure-discovery)
- [Company Information & Associations](#company-information--associations)
- [Internet Survey Data](#internet-survey-data)
- [Social Media & Employee Profiling](#social-media--employee-profiling)
- [Data Leaks & Paste Sites](#data-leaks--paste-sites)
- [Internet Scan Engine & Archived Data](#internet-scan-engine--archived-data)
- [Contributing](#contributing)

---

## Content Discovery

- [Rustbuster](https://github.com/phra/rustbuster) — Fast files, directories, and VHost buster written in Rust.
- [ffuf](https://github.com/ffuf/ffuf) — Extremely fast web fuzzer written in Go for directory, VHost, and parameter discovery.
- [Kiterunner](https://github.com/assetnote/kiterunner) — Modern CLI tool designed specifically for API endpoint discovery and brute-forcing.
- [gau (GetAllUrls)](https://github.com/lc/gau) — Fetch known URLs from AlienVault Open Threat Exchange, Wayback Machine, and Common Crawl.
- [waybackurls](https://github.com/tomnomnom/waybackurls) — Fetch all URLs that the Wayback Machine has recorded for a target domain.

---

## IP Address Discovery

- [MXToolbox Bulk Lookup](https://mxtoolbox.com/BulkLookup.aspx) — Bulk Domain and IP lookup utility.
- [DomainToIPConverter](http://domaintoipconverter.com/) — Fast bulk domain-to-IP resolution tool.
- [MassDNS](https://github.com/blechschmidt/massdns) — High-performance DNS resolver utility for bulk lookups.
- [Google Apps Dig Tool](https://toolbox.googleapps.com/apps/dig/) — Web-based DNS lookup utility provided by Google.
- [DataSploit (IP Modules)](https://github.com/DataSploit/datasploit/tree/master/ip) — OSINT framework module for IP reconnaissance.
- [Domain Dossier](https://centralops.net/co/domaindossier.aspx) — Comprehensive domain and IP address investigation suite.
- [BGPView](https://bgpview.io/) — Search ASN, IPv4/IPv6 ranges, or organization resources.
- [Hurricane Electric BGP Toolkit](https://bgp.he.net/) — Keyword-to-ASN and routing information lookup.
- [ViewDNS](https://viewdns.info/) — Multi-purpose web tool for domain and IP intelligence.
- [UltraTools IPv6Info](https://www.ultratools.com/tools/ipv6Info) — Detailed analysis and lookup utility for IPv6 addresses.
- [Whois Command Line](https://manpages.debian.org/jessie/whois/whois.1.en.html) — Linux CLI utility to query WHOIS databases.
- [ICANN Whois](https://whois.icann.org/en) — Official ICANN WHOIS lookup portal.
- [Nslookup Guide](https://manpages.debian.org/jessie/dnsutils/nslookup.1.en.html) — Native CLI tool used for querying DNS records.

---

## Domain & Subdomain Discovery

- [Subfinder](https://github.com/projectdiscovery/subfinder) — Fast passive subdomain discovery tool by ProjectDiscovery.
- [OWASP Amass](https://github.com/owasp-amass/amass) — In-depth network mapping and attack surface discovery framework.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) — Fast Python-based subdomain enumeration tool utilizing multiple search engines.
- [Chaos](https://chaos.projectdiscovery.io/) — ProjectDiscovery dataset of actively monitored public subdomains for bug bounty programs.
- [httpx](https://github.com/projectdiscovery/httpx) — Fast and multi-purpose HTTP toolkit that allows running multiple probes.
- [httprobe](https://github.com/tomnomnom/httprobe) — Takes a list of domains and probes for working HTTP and HTTPS servers.
- [Aiodnsbrute](https://github.com/blark/aiodnsbrute) — High-speed asynchronous DNS brute-forcing utility.
- [GoBuster](https://github.com/OJ/gobuster) — High-performance URI/DNS/VHost busting tool written in Go.
- [Crt.sh](https://crt.sh/) — Search Certificate Transparency logs for subdomains.
- [CT-Exposer](https://github.com/chris408/ct-exposer) — Discover subdomains passively via Certificate Transparency logs.
- [Certgraph](https://github.com/lanrat/certgraph) — Crawling tool to map SSL/TLS Certificate Subject Alternative Names (SANs).
- [SSLScrape](https://github.com/jhaddix/sslScrape) — Scrapes hostnames directly from target SSL certificates.
- [The Art of Subdomain Enumeration](https://github.com/appsecco/the-art-of-subdomain-enumeration) — Comprehensive reference material for subdomain mapping methodologies.
- [Bluto](https://github.darryllane.com/Bluto) — DNS recon, automated subdomain bruting, and zone transfer checks.

---

## Email Discovery

- [Hunter.io](https://hunter.io/) — Find corporate email addresses associated with any domain.
- [Skrapp](https://www.skrapp.io/) — B2B lead and email discovery tool.
- [Email Extractor](https://chrome.google.com/webstore/detail/email-extractor/jdianbbpnakhcmfkcckaboohfgnngfcc) — Chrome browser extension to scrape emails from web pages.
- [ConvertCSV Email Extractor](http://convertcsv.com/email-extractor.htm) — Parse and extract raw email strings from unstructured files.
- [linkedin2username](https://github.com/initstring/linkedin2username) — OSINT tool to generate company username lists from LinkedIn profiles.
- [Office365UserEnum](https://bitbucket.org/grimhacker/office365userenum/src/master/) — Enumerate valid Microsoft 365 users via ActiveSync.

---

## Network & Port Scanning

- [Nmap](https://nmap.org/) — The gold standard open-source network exploration and vulnerability scanner.
- [Naabu](https://github.com/projectdiscovery/naabu) — Fast, reliable port scanner written in Go focused on speed and simplicity.
- [Masscan](https://github.com/robertdavidgraham/masscan) — Ultra-fast asynchronous TCP port scanner capable of scanning the entire Internet in minutes.
- [ZMap](https://github.com/zmap/zmap) — Modular network scanner designed for Internet-wide research surveys.

---

## Business Communication Infrastructure

- [MicroBurst](https://github.com/NetSPI/MicroBurst) — PowerShell scripts for Azure environment security assessment and discovery.
- [Lyncsmash](https://github.com/nyxgeek/lyncsmash) — Tools to enumerate and audit self-hosted Skype for Business / Lync.
- [Ruler](https://github.com/sensepost/ruler) — Abuse Exchange services remotely via MAPI/HTTP or RPC/HTTP.

---

## Source Code Aggregators & Information Search

- [GitHub Advanced Search](https://github.com/search/advanced) — Query publicly exposed keys, secrets, and repositories.
- [Gitrob](https://github.com/michenriksen/gitrob) — Reconnaissance tool for scanning GitHub organizations for sensitive files.
- [Trufflehog](https://github.com/trufflesecurity/trufflehog) — Searches high-entropy strings and secrets digging deep into git commits.
- [PublicWWW](https://publicwww.com/) — Source code search engine to identify signatures, tracking codes, and software snippets.
- [BuiltWith](https://builtwith.com/) — Web technology profiler identifying frameworks and analytics scripts used on targets.
- [Wappalyzer](https://www.wappalyzer.com/) — Technology profiler that uncovers technologies used on websites.

---

## Cloud Infrastructure Discovery

- [CloudScraper](https://github.com/jordanpotti/CloudScraper) — Spider target sites for cloud storage assets (AWS S3, Azure Blobs, DigitalOcean Spaces).
- [Grayhat Warfare Buckets](https://buckets.grayhatwarfare.com/) — Search engine for publicly readable Amazon S3 buckets.
- [Spaces-Finder](https://github.com/appsecco/spaces-finder) — Locate publicly accessible DigitalOcean Space resources.
- [GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute) — Google Cloud Platform bucket enumeration and privilege audit script.

---

## Company Information & Associations

- [Crunchbase](https://www.crunchbase.com/) — Business intelligence database detailing funding, acquisitions, and acquisitions.
- [OpenCorporates](https://opencorporates.com) — The largest open database of corporate entities globally.
- [Companies House UK](https://beta.companieshouse.gov.uk/) — Official UK registrar for corporate entity mapping.

---

## Internet Survey Data

- [Project Sonar](https://opendata.rapid7.com/) — Rapid7's public internet-wide survey data across common protocols.
- [Scans.io](https://scans.io) — Internet-Wide Scan Data Repository managed by the ZMap research team.

---

## Social Media & Employee Profiling

- [Social Searcher](https://www.social-searcher.com/) — Real-time social media search engine for OSINT profiling.
- [CheckUser](https://checkuser.org) — Check username availability and presence across social networks.
- [SocialBlade](https://socialblade.com/) — Track public social account analytics and metadata across platforms.

---

## Data Leaks & Paste Sites

- [Dumpmon](https://twitter.com/dumpmon) — Automated Twitter monitoring bot tracking paste sites for credential dumps.
- [Pastebin Scraper](https://github.com/Critical-Start/pastebin_scraper) — Automated monitor for Pastebin data leaks.
- [Scavenger](https://github.com/rndinfosecguy/Scavenger) — Crawler tracking paste services for leaked corporate credentials.
- [PwnedOrNot](https://github.com/thewhiteh4t/pwnedOrNot) — Python script to check breached accounts and reveal exposed passwords.

---

## Internet Scan Engine & Archived Data

- [Shodan](https://shodan.io/) — Search engine for Internet-connected IoT devices, infrastructure, and open ports.
- [Censys](https://censys.io/) — Attack surface monitoring engine mapping internet-connected assets.
- [FOFA](https://fofa.info/) — Cyberspace search engine for quick asset and endpoint discovery.
- [Wayback Machine](http://web.archive.org/) — Historical archive of websites and endpoints for discovering lost parameters.
- [ZoomEye](https://www.zoomeye.org/) — Cyberspace search engine indexing devices and web applications.
- [CachedViews](https://cachedviews.com/) — Aggregate internet cache sources for legacy site states.

---

## 🤝 Contributing

Contributions, suggestions, and tool additions are always welcome! If you know of a tool, framework, or methodology that should be included:

1. Open an **[Issue](https://github.com/th3tox1c/Study-Archive/issues)** to suggest new tools or category updates.
2. Submit a **[Pull Request](https://github.com/th3tox1c/Study-Archive/pulls)** with your proposed additions.

---

## ⭐ Support & Star

If you find this repository helpful for your learning, reconnaissance, or bug bounty research:

- **Star this repository** to show support and keep it in your bookmarks!
- **Share it** with fellow security researchers and peers.

---

> ℹ️ *Curated based on open-source resources and community-driven security frameworks.*
> 
> ⚠️ **Disclaimer:** All tools and methodologies documented here are strictly intended for legal penetration testing, bug bounty hunting with proper authorization, and educational research.


<div align="center">
  <sub>⭐️ From <a href="https://github.com/th3tox1c">th3tox1c</a></sub>
</div>
