# Awesome-Cyber-Reconnaissance-Threat-Intelligence
# Awesome-Cyber-Reconnaissance-Threat-Intelligence

markdown

## Top Cyber Reconnaissance & Threat Intelligence Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Open-Source Intelligence (OSINT), Attack Surface Reconnaissance, Threat Intelligence Platforms (TIPs), Internet-Wide Scanning & Dark Web Monitoring*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cyber Reconnaissance & Threat Intelligence**. These tools discover, enumerate, correlate, enrich, and monitor external attack surfaces, domains, IP infrastructure, leaked credentials, IOCs (Indicators of Compromise), and threat actor campaigns across OSINT sources, certificate transparency logs, internet scan engines, and self-hosted Threat Intelligence Platforms (TIPs).



**Examples** include SpiderFoot HX, Maltego, Shodan Enterprise, Censys, SecurityTrails, Recon-ng, Intelligence X (IntelX), Recorded Future, WhoisXML API, DarkOwl, and d3voz/openjutsu (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for automated OSINT reconnaissance (`d3voz/openjutsu`, `SpiderFoot`, `Recon-ng`, `theHarvester`, `Amass`, `Subfinder`), self-hosted Threat Intelligence Platforms (`OpenCTI`, `MISP`, `Yeti`), and internet-wide reconnaissance & DNS/HTTP probing (`Nmap`, `Masscan`, `ProjectDiscovery httpx/naabu`) — ideal for threat intelligence analysts, red/blue teamers, bug bounty hunters, and SOC defenders.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Recorded Future](https://recordedfuture.com)**  

  Enterprise threat intelligence cloud platform aggregating open-web, dark-web, technical, and geopolitical intelligence with real-time risk scoring and SIEM/SOAR integrations.



- **[Maltego](https://maltego.com)**  

  Visual link-analysis and OSINT investigation platform connecting hundreds of commercial and open-source data transforms into interactive entity relationship graphs.



- **[Shodan & Shodan Enterprise](https://shodan.io)**  

  Premier internet-connected device search engine indexing open ports, banners, SSL certificates, ICS/SCADA systems, and exposed services worldwide.



- **[Censys](https://censys.com)**  

  Internet intelligence and external Attack Surface Management (ASM) platform continuously scanning global IPv4/IPv6 hosts, certificates, and cloud assets.



- **[SecurityTrails (Recorded Future)](https://securitytrails.com)**  

  Attack surface and DNS intelligence platform providing historical WHOIS records, passive DNS timelines, subdomain enumeration, and IP enrichment APIs.



- **[SpiderFoot HX](https://spiderfoot.net)**  

  Hosted cloud edition of SpiderFoot offering multi-target OSINT automation, continuous dark-web/leak monitoring, correlation rules, and Tor/I2P scanning.



- **[Intelligence X (IntelX)](https://intelx.io)**  

  Search engine and data archive indexing Tor, I2P, data leaks, public pastes, historical web snapshots, and domain/IP intelligence.



- **[WhoisXML API](https://whoisxmlapi.com)**  

  Domain, IP, and DNS intelligence API suite offering real-time and historical WHOIS lookups, reverse IP/MX intelligence, and newly registered domain feeds.



- **[DarkOwl](https://darkowl.com)**  

  Commercial darknet intelligence platform continuously indexing Tor, I2P, Telegram, and underground forums for leaked credentials, chatter, and threat actor monitoring.



- **[VirusTotal Enterprise (Google Threat Intelligence)](https://virustotal.com)**  

  Cloud malware, URL, domain, and IOC enrichment platform combining multi-AV scanning, behavioral sandboxes, and Threat Graph relationship hunting.





## Open-Source GitHub Projects



- **[d3voz/openjutsu](https://github.com)**  

  Open-source cyber reconnaissance and OSINT automation toolkit engineered for streamlined target enumeration, intelligence gathering, and modular security research workflows.



- **[OpenCTI (`OpenCTI-Platform/opencti`)](https://github.com)**  

  Flagship open-source Cyber Threat Intelligence (CTI) platform built on STIX 2.1 standards for structuring, correlating, and visualizing threat actors, malware, TTPs, and IOCs.



- **[MISP (`MISP/MISP`)](https://github.com)**  

  Industry-standard open-source Threat Intelligence and Sharing Platform enabling SOCs, CERTs, and ISACs to collect, store, correlate, and share structured IOCs and threat feeds.



- **[SpiderFoot (`smicallef/spiderfoot`)](https://github.com)**  

  Comprehensive open-source OSINT automation tool integrating over 200 modules to gather intelligence on IP addresses, domains, emails, names, and ASNs via CLI or web UI.



- **[Recon-ng (`lanmaster53/recon-ng`)](https://github.com)**  

  Full-featured open-source Web Reconnaissance framework written in Python featuring a Metasploit-style modular interface, database workspace, and API key management.



- **[OWASP Amass (`owasp-amass/amass`)](https://github.com)**  

  In-depth open-source attack surface mapping and asset discovery engine combining DNS enumeration, certificate transparency scraping, ASN mapping, and graph databases.



- **[Subfinder (`projectdiscovery/subfinder`)](https://github.com)**  

  Fast, passive open-source subdomain discovery tool written in Go that queries dozens of certificate transparency logs, passive DNS sources, and search engines concurrently.



- **[theHarvester (`laramies/theHarvester`)](https://github.com)**  

  Classic, widely adopted open-source OSINT reconnaissance CLI tool gathering emails, subdomains, hosts, employee names, and open ports from public search engines and PGP servers.



- **[Nmap (`nmap/nmap`) & Masscan (`robertdavidgraham/masscan`)](https://github.com)**  

  Foundational open-source network discovery, service fingerprinting (`Nmap` + NSE scripts), and internet-scale asynchronous TCP port scanning (`Masscan`) utilities.



- **[Sherlock (`sherlock-project/sherlock`) & Maigret (`soxoj/maigret`)](https://github.com)**  

  Popular open-source OSINT username and persona reconnaissance tools hunting down associated accounts and metadata across thousands of websites and platforms.



- **[Yeti (`yeti-platform/yeti`)](https://github.com)**  

  Open-source threat intelligence repository designed to organize observables, indicators, TTPs, and automated enrichment analytics in a fast, analyst-friendly interface.



### Additional Strong Open-Source Options



- **[ProjectDiscovery Suite — `httpx` (`projectdiscovery/httpx`), `naabu` (`projectdiscovery/naabu`), & `uncover` (`projectdiscovery/uncover`)](https://github.com)** for fast, composable Go reconnaissance pipelines querying Shodan, Censys, and FOFA APIs directly from the terminal.

- **[BBOT (`blacklanternsecurity/bbot`)](https://github.com)** for a recursive, modular Python OSINT and attack-surface automation scanner capable of chaining subdomain, port, web, and cloud enumeration.

- **[IntelOwl (`intelowlproject/IntelOwl`)](https://github.com)** for an open-source threat intelligence orchestration API uniting 150+ analyzers (VirusTotal, AbuseIPDB, Shodan, YARA, static malware tools) in one query.

- **[IVRE (`ivre/ivre`)](https://github.com)** for a self-hosted open-source network recon framework combining Nmap, Masscan, Zeek, and passive DNS into a Shodan-like local search engine.

- **[TruffleHog (`trufflesecurity/trufflehog`)](https://github.com)** for open-source reconnaissance of exposed credentials, API keys, and sensitive artifacts across public Git repositories.



**Frameworks for building custom systems**: Combine **Subfinder + Amass + httpx** for automated external attack-surface discovery, **SpiderFoot** or **BBOT** for multi-source OSINT enrichment, and **OpenCTI + MISP** for structured STIX 2.1 threat intelligence correlation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Authorization & Legal Compliance**: Active port scanning, service probing, and intrusive reconnaissance tools (`Nmap`, `Masscan`, `naabu`) must **only** be run against domains, IP ranges, and assets for which you have explicit authorization. Passive OSINT tools must be used in compliance with applicable privacy laws and platform Terms of Service.

Use code with caution.

• Self-hosted Threat Intelligence Platforms (OpenCTI, MISP) ingesting external threat feeds and malware samples must run inside isolated network segments with strict RBAC and HTTPS/TLS encryption.

Made for threat intelligence analysts, OSINT researchers, red/blue teamers, bug bounty hunters, and open-source contributors.

Let's make cyber reconnaissance and threat intelligence more open, collaborative, and transparent.
