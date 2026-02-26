# Awesome Bug Bounty [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A comprehensive, curated list of resources, tools, platforms, and wordlists for bug bounty hunters — updated for **2026**.

## Table of Contents
- [Notes](#bug-bounty-notes)
- [Roadmap](#bug-bounty-roadmap)
- [Platforms](#platforms)
- [Tools](#tools)
  - [Reconnaissance - Subdomain Enumeration](#reconnaissance---subdomain-enumeration)
  - [Reconnaissance - Port Scanning](#reconnaissance---port-scanning)
  - [Reconnaissance - Passive / OSINT](#reconnaissance---passive--osint)
  - [Web Application Scanning](#web-application-scanning)
  - [Web Crawling & Spidering](#web-crawling--spidering)
  - [Content Discovery & Fuzzing](#content-discovery--fuzzing)
  - [Vulnerability Scanners](#vulnerability-scanners)
  - [Injection & Exploitation](#injection--exploitation)
  - [Parameter Discovery](#parameter-discovery)
  - [JavaScript Analysis](#javascript-analysis)
  - [API Security Testing](#api-security-testing)
  - [Cloud Security](#cloud-security)
  - [DNS & Network Tools](#dns--network-tools)
  - [Interception Proxies](#interception-proxies)
  - [Automation & Orchestration](#automation--orchestration)
  - [Miscellaneous](#miscellaneous)
- [Wordlists](#wordlists)
- [Payloads](#payloads)
- [Search Engines for Hackers](#search-engines-for-hackers)
- [Learning Resources](#learning-resources)
- [Practice Labs](#practice-labs)
- [Blogs and Write-ups](#blogs-and-write-ups)
- [Books](#books)
- [VPS](#vps)
- [Conferences and Talks](#conferences-and-talks)
- [Communities](#communities)
- [Contributing](#contributing)
- [Contributors](#contributors)

---

## Bug Bounty Notes
- [Buggy Note](https://bit.ly/defronixBugBounty-buGGy) - Bug Bounty Notes For Beginners.
- [HowToHunt](https://kathan19.gitbook.io/howtohunt) - A bug bounty methodology on how to hunt on targets.
- [KingOfBugBountyTips](https://github.com/KingOfBugBounty/KingOfBugBountyTips) - Elite one-liner tips from well-known bug hunters.
- [AllAboutBugBounty](https://github.com/daffainfo/AllAboutBugBounty) - Comprehensive notes about bug bounty vulnerability types.
- [Bug Bounty Checklist](https://github.com/sehno/Bug-bounty) - Checklist and methodology reference for bug hunters.

## Bug Bounty Roadmap
- [Cyberhub Roadmap](https://www.thecyberhub.org/roadmaps/bug-hunting) - Bug bounty Roadmap by The Cyber Hub.
- [NahamSec's Resources](https://github.com/nahamsec/Resources-for-Beginner-Bug-Bounty-Hunters) - Resources for beginner bug bounty hunters by NahamSec.
- [The Bug Hunter's Methodology](https://github.com/jhaddix/tbhm) - Jason Haddix's methodology used by top hunters.

## Platforms
- [HackerOne](https://www.hackerone.com) - Leading bug bounty platform connecting businesses with security researchers.
- [Bugcrowd](https://www.bugcrowd.com) - Platform for bug bounty and vulnerability disclosure programs.
- [Synack](https://www.synack.com) - Managed security testing platform with a vetted researcher community.
- [Intigriti](https://www.intigriti.com) - European bug bounty platform with a growing global presence.
- [YesWeHack](https://www.yeswehack.com) - Bug bounty platform offering a wide range of programs.
- [Immunefi](https://immunefi.com) - Premier bug bounty platform for Web3, DeFi, and blockchain security.
- [HackenProof](https://hackenproof.com) - Bug bounty platform focused on crypto and Web3 projects.
- [Open Bug Bounty](https://www.openbugbounty.org) - Non-profit, open bug bounty platform.
- [Cobalt](https://cobalt.io) - Modern pentesting platform combining crowdsourced and in-house testing.
- [Federacy](https://www.federacy.com) - Bug bounty platform for startups and growing companies.
- [ProjectDiscovery Cloud Platform](https://projectdiscovery.io/platform) - Cloud-based scanning and attack surface management.

## Tools

### Reconnaissance - Subdomain Enumeration
- [Subfinder](https://github.com/projectdiscovery/subfinder) - Fast passive subdomain enumeration tool using dozens of APIs. ⭐13k+
- [Amass](https://github.com/owasp-amass/amass) - In-depth attack surface mapping and asset discovery by OWASP.
- [Assetfinder](https://github.com/tomnomnom/assetfinder) - Find domains and subdomains related to a given domain.
- [Findomain](https://github.com/Findomain/Findomain) - Cross-platform subdomain enumerator with monitoring capabilities.
- [Chaos](https://chaos.projectdiscovery.io) - ProjectDiscovery's subdomain data for public programs.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers.
- [Haktrails](https://github.com/hakluke/haktrails) - Golang client for querying SecurityTrails API data.
- [xsubfind3r](https://github.com/hueristiq/xsubfind3r) - Passive subdomain discovery from multiple sources.
- [Shuffledns](https://github.com/projectdiscovery/shuffledns) - Massdns wrapper for active bruteforcing and resolution.
- [PureDNS](https://github.com/d3mondev/puredns) - Fast domain resolver and subdomain bruteforcing tool.
- [dnsgen](https://github.com/ProjectAnte/dnsgen) - Generates domain name permutations for subdomain discovery.

### Reconnaissance - Port Scanning
- [Nmap](https://nmap.org) - Network exploration and security auditing tool.
- [Naabu](https://github.com/projectdiscovery/naabu) - Fast port scanner for bug bounties and pentests. ⭐5.8k+
- [Masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner — scans the entire internet in under 5 minutes.
- [RustScan](https://github.com/RustScan/RustScan) - Blazingly fast port scanner written in Rust.

### Reconnaissance - Passive / OSINT
- [Shodan](https://www.shodan.io/) - Search engine for Internet-connected devices and services.
- [Censys](https://search.censys.io/) - Internet-wide scan data for hosts and certificates.
- [FOFA](https://fofa.info/) - Cyberspace search engine for asset discovery.
- [ZoomEye](https://www.zoomeye.org/) - Cyberspace mapping and search engine.
- [Hunter](https://hunter.how/) - Asset discovery and threat intelligence search.
- [Netlas](https://netlas.io/) - Attack surface discovery and intelligence platform.
- [GreyNoise](https://www.greynoise.io/) - Internet scanner noise filtering and intelligence.
- [CriminalIP](https://www.criminalip.io/) - Cyber threat intelligence search engine.
- [FullHunt](https://fullhunt.io/) - Attack surface management and discovery.
- [Leakix](https://leakix.net/) - Leak and exposure detection engine.
- [VirusTotal](https://www.virustotal.com/gui/) - Analyse suspicious files, domains, IPs and URLs.
- [Crt.sh](https://crt.sh/) - Certificate transparency log search.
- [SecurityTrails](https://securitytrails.com/) - DNS history, WHOIS, and subdomain data.
- [Wireshark](https://www.wireshark.org/) - The world's most popular network protocol analyzer.
- [Google Dorks](https://www.google.com/) - Advanced search operators for finding sensitive data.
- [URLScan](https://urlscan.io/) - Service to scan and analyze URLs.
- [DNSDumpster](https://dnsdumpster.com/) - DNS reconnaissance and research tool.
- [Pulsedive](https://pulsedive.com/) - Free threat intelligence platform.
- [PublicWWW](https://publicwww.com/) - Source code search engine for web pages.
- [Grep.app](https://grep.app/) - Search across GitHub code repositories instantly.
- [Pentest Tools](https://pentest-tools.com/information-gathering/find-subdomains-of-domain) - Online subdomain discovery combining passive and active methods.

### Web Application Scanning
- [Nuclei](https://github.com/projectdiscovery/nuclei) - Fast, customizable vulnerability scanner using YAML templates. ⭐27k+
- [Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates) - Community-curated vulnerability templates for Nuclei. ⭐12k+
- [Nikto](https://cirt.net/Nikto2) - Web server scanner that detects vulnerabilities and misconfigurations.
- [Nessus](https://www.tenable.com/products/nessus) - Comprehensive vulnerability scanner by Tenable.
- [OpenVAS](https://www.openvas.org/) - Full-featured open-source vulnerability scanner.
- [Metasploit](https://www.metasploit.com) - Comprehensive penetration testing framework.

### Web Crawling & Spidering
- [Katana](https://github.com/projectdiscovery/katana) - Next-generation crawling and spidering framework. ⭐15.6k+
- [Gospider](https://github.com/jaeles-project/gospider) - Fast web spider written in Go.
- [Hakrawler](https://github.com/hakluke/hakrawler) - Simple, fast web crawler for discovering endpoints and assets.
- [xcrawl3r](https://github.com/hueristiq/xcrawl3r) - Recursive web spider that traverses sitemaps and robots.txt.
- [GAU (GetAllUrls)](https://github.com/lc/gau) - Fetch known URLs from AlienVault OTX, Wayback Machine, and Common Crawl.
- [Waybackurls](https://github.com/tomnomnom/waybackurls) - Fetch all URLs the Wayback Machine knows about for a domain.
- [Waymore](https://github.com/xnl-h4ck3r/waymore) - Find way more URLs from the Wayback Machine, Common Crawl, and more.
- [xurlfind3r](https://github.com/hueristiq/xurlfind3r) - Discover URLs for a given domain from passive sources.

### Content Discovery & Fuzzing
- [ffuf](https://github.com/ffuf/ffuf) - Fast web fuzzer written in Go — the industry standard.
- [Feroxbuster](https://github.com/epi052/feroxbuster) - Fast, recursive content discovery tool written in Rust.
- [Dirsearch](https://github.com/maurosoria/dirsearch) - Web path discovery with advanced features.
- [Gobuster](https://github.com/OJ/gobuster) - Directory/file, DNS, and VHost busting tool written in Go.

### Vulnerability Scanners
- [SQLMap](https://sqlmap.org) - Automatic SQL injection and database takeover tool.
- [Ghauri](https://github.com/r0oth3x49/ghauri) - Advanced SQL injection detection and exploitation tool.
- [Dalfox](https://github.com/hahwul/dalfox) - Fast parameter analysis and XSS scanner.
- [XSSer](https://github.com/epsylon/xsser) - Automatic framework to detect and report XSS vulnerabilities.
- [kxss](https://github.com/Emoe/kxss) - Reflected parameter finder for XSS hunting.
- [Airixss](https://github.com/ferreiraklet/airixss) - XSS reflection scanner for mass testing.
- [XXElixir](https://github.com/kljunowsky/XXElixir) - Test for file upload and XXE vulnerabilities via XLSX poisoning.

### Injection & Exploitation
- [Commix](https://github.com/commixproject/commix) - Automated OS command injection exploitation tool.
- [NoSQLMap](https://github.com/codingo/NoSQLMap) - Automated NoSQL exploitation tool.
- [SSRFmap](https://github.com/swisskyrepo/SSRFmap) - Automatic SSRF fuzzer and exploitation tool.
- [tplmap](https://github.com/epinna/tplmap) - Server-Side Template Injection detection and exploitation.

### Parameter Discovery
- [Arjun](https://github.com/s0md3v/Arjun) - HTTP parameter discovery suite.
- [ParamSpider](https://github.com/devanshbatham/ParamSpider) - Mining URLs from dark corners of web archives for parameter discovery.
- [x8](https://github.com/Sh1Yo/x8) - Hidden parameters discovery suite.
- [Unfurl](https://github.com/tomnomnom/unfurl) - Pull out bits of URLs provided on stdin.
- [URO](https://github.com/s0md3v/uro) - Declutter URL lists for focused analysis.
- [gf](https://github.com/tomnomnom/gf) - A wrapper around grep for pattern matching (XSS, SQLi, SSRF, etc.).

### JavaScript Analysis
- [LinkFinder](https://github.com/GerbenJavado/LinkFinder) - Find endpoints in JavaScript files.
- [SecretFinder](https://github.com/m4ll0k/SecretFinder) - Find sensitive data (API keys, tokens) in JavaScript files.
- [JSFScan](https://github.com/KathanP19/JSFScan.sh) - Automation of JavaScript recon from multiple tools.
- [Retire.js](https://github.com/RetireJS/retire.js) - Scanner detecting use of JS libraries with known vulnerabilities.

### API Security Testing
- [Postman](https://www.postman.com) - API testing and development platform.
- [Kiterunner](https://github.com/assetnote/kiterunner) - Contextual content discovery tool for APIs.
- [jwt_tool](https://github.com/ticarpi/jwt_tool) - Toolkit for testing, tweaking, and cracking JSON Web Tokens.
- [GraphQLmap](https://github.com/swisskyrepo/GraphQLmap) - Scripting engine to exploit GraphQL endpoints.

### Cloud Security
- [CloudList](https://github.com/projectdiscovery/cloudlist) - Tool for listing assets from multiple cloud providers.
- [S3Scanner](https://github.com/sa7mon/S3Scanner) - Scan for misconfigured S3 buckets.
- [CloudBrute](https://github.com/0xsha/CloudBrute) - Cloud infrastructure enumeration tool.
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Multi-cloud security auditing tool.
- [Prowler](https://github.com/prowler-cloud/prowler) - AWS, GCP, and Azure security assessment tool.

### DNS & Network Tools
- [dnsx](https://github.com/projectdiscovery/dnsx) - Fast and multi-purpose DNS toolkit.
- [tlsx](https://github.com/projectdiscovery/tlsx) - Fast TLS data collection and analysis tool. ⭐1k+
- [httpx](https://github.com/projectdiscovery/httpx) - Fast multi-purpose HTTP toolkit for probing. ⭐9.6k+
- [asnmap](https://github.com/projectdiscovery/asnmap) - Map organization network ranges using ASN data.
- [cvemap](https://github.com/projectdiscovery/cvemap) - Navigate CVE data with powerful search and filtering. ⭐2.4k+
- [Recon-ng](https://github.com/lanmaster53/recon-ng) - Full-featured web reconnaissance framework.
- [MassDNS](https://github.com/blechschmidt/massdns) - High-performance DNS stub resolver for bulk lookups.
- [DNSReaper](https://github.com/punk-security/dnsReaper) - Subdomain takeover tool that checks for dangling DNS records.

### Interception Proxies
- [Burp Suite](https://portswigger.net/burp) - Leading tool for web application security testing.
- [Caido](https://caido.io) - Lightweight, modern web security auditing toolkit — the Burp alternative for 2026.
- [OWASP ZAP](https://www.zaproxy.org) - Free, open-source security tool for finding vulnerabilities.
- [mitmproxy](https://mitmproxy.org) - Interactive HTTPS proxy for debugging and testing.

### Automation & Orchestration
- [Notify](https://github.com/projectdiscovery/notify) - Stream tool output to multiple notification platforms.
- [Interactsh](https://github.com/projectdiscovery/interactsh) - Out-of-band interaction server for vulnerability testing. ⭐4.2k+
- [Anew](https://github.com/tomnomnom/anew) - Append lines from stdin that are not already in a file.
- [BBRF](https://github.com/honoki/bbrf-client) - Bug Bounty Reconnaissance Framework for tracking scope and data.
- [Axiom](https://github.com/pry0cc/axiom) - Dynamic infrastructure framework for parallelized scanning.
- [ReconFTW](https://github.com/six2dez/reconftw) - Tool designed to automate the entire recon process.
- [COLI](https://github.com/justakazh/coli) - Visual orchestration for CLI bug bounty workflows (subfinder→httpx→nuclei).

### Miscellaneous
- [Gowitness](https://github.com/sensepost/gowitness) - Web screenshot utility using Chrome Headless.
- [EyeWitness](https://github.com/RedSiege/EyeWitness) - Take screenshots of websites and identify default credentials.
- [Subhunter](https://github.com/umutcamliyurt/Subhunter) - Fast subdomain takeover detection tool.
- [Can I Take Over XYZ?](https://github.com/EdOverflow/can-i-take-over-xyz) - A list of services and how to claim (sub)domains with dangling DNS records.
- [Smuggler](https://github.com/defparam/smuggler) - HTTP request smuggling detection tool.

## Wordlists
- [SecLists](https://github.com/danielmiessler/SecLists) - Collection of multiple types of lists used during security assessments.
- [Assetnote Wordlists](https://wordlists.assetnote.io) - Wordlists generated from real-world data for automated and manual testing.
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - A list of useful payloads and bypasses for web application security.
- [OneListForAll](https://github.com/six2dez/OneListForAll) - Combined, deduplicated wordlist for web content discovery.
- [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) - Dictionary of attack patterns, predictable resource locations, and regex.
- [Probable-Wordlists](https://github.com/berzerk0/Probable-Wordlists) - Wordlists derived from probable password patterns.
- [CommonSpeak2](https://github.com/assetnote/commonspeak2-wordlists) - Wordlists generated from real-world datasets by Assetnote.
- [jhaddix all.txt](https://gist.github.com/jhaddix/b80ea67d85c13206125806f0828f4d10) - Jason Haddix's comprehensive content discovery wordlist.

## Payloads
- [PdfExploits](https://github.com/coffinxp/pdFExploits) - Collection of XSS PDF Exploits.
- [Image XSS Payload](https://github.com/coffinxp/img-payloads) - Collection of XSS Payload Binded in Images.
- [All Type of Payload](https://github.com/coffinxp/payloads) - Collection of All type of payload XSS, SQL, Directory Traversal, Fuzzing etc.
- [Advanced XSS](https://github.com/pgaijin66/XSS-Payloads) - List of Advanced XSS Payloads.
- [XSS Payload List](https://github.com/payloadbox/xss-payload-list) - Collection of XSS payloads for testing.
- [Superbug's Payloads](https://github.com/xsuperbug/payloads) - Repository of various payloads for different attacks.
- [Offensive Payloads](https://github.com/InfoSecWarrior/Offensive-Payloads) - Collection of offensive payloads for penetration testing.
- [PortSwigger XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) - Comprehensive cheat sheet for XSS.
- [XSS Bypass Filters](https://github.com/Edr4/XSS-Bypass-Filters) - Collection of techniques to bypass XSS filters.
- [Vulnerability Checklist](https://github.com/InfoSecExplorer/Vulnerability-Checklist) - Checklist for common vulnerabilities and how to test for them.
- [SQL Injection Payload List](https://github.com/payloadbox/sql-injection-payload-list) - Comprehensive list of SQL injection payloads.
- [Command Injection Payload List](https://github.com/payloadbox/command-injection-payload-list) - OS command injection payloads.
- [SSRF Payloads](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Request%20Forgery) - SSRF payload collection from PayloadsAllTheThings.

## Search Engines for Hackers

| Engine | URL | Focus |
|--------|-----|-------|
| Shodan | [shodan.io](https://shodan.io) | IoT & device search |
| Censys | [censys.io](https://censys.io) | Internet scan data & certificates |
| FOFA | [fofa.info](https://fofa.info) | Cyberspace search |
| ZoomEye | [zoomeye.org](https://zoomeye.org) | Cyberspace mapping |
| Hunter | [hunter.how](https://hunter.how) | Asset discovery |
| Netlas | [netlas.io](https://netlas.io) | Attack surface intelligence |
| GreyNoise | [greynoise.io](https://greynoise.io) | Internet noise filtering |
| Onyphe | [onyphe.io](https://onyphe.io) | Cyber defense search |
| CriminalIP | [criminalip.io](https://criminalip.io) | Threat intelligence |
| FullHunt | [fullhunt.io](https://fullhunt.io) | Attack surface management |
| Quake | [quake.360.net](https://quake.360.net) | Cyberspace search |
| Leakix | [leakix.net](https://leakix.net) | Leak & exposure detection |
| URLScan | [urlscan.io](https://urlscan.io) | URL analysis |
| DNSDumpster | [dnsdumpster.com](https://dnsdumpster.com) | DNS recon |
| crt.sh | [crt.sh](https://crt.sh) | Certificate transparency |
| SecurityTrails | [securitytrails.com](https://securitytrails.com) | DNS history & WHOIS |
| PublicWWW | [publicwww.com](https://publicwww.com) | Source code search |
| Grep.app | [grep.app](https://grep.app) | GitHub code search |

## Learning Resources
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) - Free, hands-on training on web security vulnerabilities.
- [Hacker101](https://www.hacker101.com) - Free video lessons and CTFs for learning how to hack.
- [Bugcrowd University](https://www.bugcrowd.com/hackers/bugcrowd-university) - Free educational content on security testing.
- [OWASP Top Ten](https://owasp.org/www-project-top-ten/) - Standard awareness document for web application security.
- [TCM Security Academy](https://academy.tcm-sec.com/) - Practical cybersecurity courses by The Cyber Mentor.
- [NahamSec's Courses](https://www.udemy.com/user/nahamsec/) - Bug bounty courses on Udemy by NahamSec.
- [ProjectDiscovery Docs](https://docs.projectdiscovery.io/) - Learn about the entire ProjectDiscovery toolchain.
- [HackerOne Hacker101 CTF](https://ctf.hacker101.com/) - Capture the Flag challenges designed for bounty hunters.

## Practice Labs
- [HackTheBox](https://www.hackthebox.com) - Online platform with vulnerable machines and challenges.
- [TryHackMe](https://tryhackme.com) - Learn cybersecurity through hands-on, guided rooms.
- [PentesterLab](https://pentesterlab.com) - Exercises to learn web penetration testing.
- [OWASP WebGoat](https://owasp.org/www-project-webgoat/) - Intentionally insecure web app for security training.
- [DVWA](https://github.com/digininja/DVWA) - Damn Vulnerable Web Application for practicing attacks.
- [XSS Game](https://xss-game.appspot.com/) - Google's XSS challenge game.
- [Juice Shop](https://owasp.org/www-project-juice-shop/) - OWASP's most vulnerable modern web application.

## Blogs and Write-ups
- [HackerOne Hacktivity](https://hackerone.com/hacktivity) - Publicly disclosed reports and write-ups from HackerOne.
- [Bugcrowd Blog](https://www.bugcrowd.com/blog) - Articles and updates from Bugcrowd.
- [Intigriti Blog](https://blog.intigriti.com) - Insights and write-ups from Intigriti.
- [Pentester Land](https://pentester.land) - Curated list of bug bounty write-ups and resources.
- [PortSwigger Research](https://portswigger.net/research) - Cutting-edge web security research from the Burp Suite team.
- [ProjectDiscovery Blog](https://blog.projectdiscovery.io/) - Technical blog covering recon, scanning, and security tooling.
- [Assetnote Blog](https://blog.assetnote.io/) - Security research and vulnerability deep-dives.
- [Labs Detectify](https://labs.detectify.com/) - Security research and ethical hacking articles.
- [Infosec Write-ups (Medium)](https://infosecwriteups.com/) - Community-driven security write-ups on Medium.
- [vidocsecurity.com Blog](https://www.vidocsecurity.com/blog/) - Modern vulnerability research articles and tool reviews.

## Books
- [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470) - Comprehensive guide to web application security testing.
- [Bug Bounty Bootcamp](https://www.amazon.com/Bug-Bounty-Bootcamp-Reporting-Vulnerabilities/dp/1718501544) - Vickie Li's guide to finding and reporting web vulnerabilities.
- [Real-World Bug Hunting](https://www.amazon.com/Real-World-Bug-Hunting-Security-Researchers/dp/1593278616) - Field guide to finding software vulnerabilities.
- [Bug Bounty Hunting Essentials](https://www.amazon.com/Bug-Bounty-Hunting-Essentials-vulnerabilities/dp/178862689X) - Guide to discovering and reporting vulnerabilities.
- [Hacking APIs](https://www.amazon.com/Hacking-APIs-Application-Programming-Interfaces/dp/1718502443) - Breaking web application programming interfaces.
- [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
- [Black Hat Python, 2nd Edition](https://nostarch.com/black-hat-python2E) - Python programming for hackers and pentesters.

## VPS
- [Ok-VPS](https://github.com/mrco24/OK-VPS) - Bug Bounty VPS Setup Tools.
- [Coffin Bughunting Tool](https://github.com/coffinxp/bughuntingtools) - Bug Bounty hunting tool for VPS.
- [Axiom](https://github.com/pry0cc/axiom) - Spin up dynamic cloud infrastructure for parallelized scanning.
- [BugBuntu](https://sourceforge.net/projects/bugbuntu/) - Custom Linux distro pre-configured for bug bounty hunting.

## Conferences and Talks
- [Black Hat](https://www.blackhat.com) - Information security conference with a focus on technical research.
- [DEF CON](https://www.defcon.org) - One of the world's largest and most notable hacker conventions.
- [NahamCon](https://www.nahamcon.com) - Free virtual security conference for bug bounty hunters.
- [OWASP Global AppSec](https://owasp.org/conferences/) - Conference focused on application security.
- [BSides](http://www.securitybsides.com/) - Community-driven security conferences held worldwide.
- [Recon Village](https://reconvillage.org) - Village at DEF CON focusing on reconnaissance.
- [Bugcrowd LevelUp](https://www.bugcrowd.com/events/) - Bugcrowd's free virtual hacking conference.

## Communities
- [ProjectDiscovery Discord](https://discord.gg/projectdiscovery) - Discord server for ProjectDiscovery tools and community.
- [HackerOne Community](https://community.hackerone.com) - Community of security researchers and ethical hackers.
- [Bugcrowd Discord](https://discord.com/invite/bugcrowd) - Official Bugcrowd Discord server.
- [NahamSec Discord](https://discord.gg/nahamsec) - NahamSec's bug bounty community.
- [Bug Bounty Forum](https://forum.bugbountyforum.com) - Community forum for bug bounty hunters.
- [r/bugbounty](https://www.reddit.com/r/bugbounty/) - Reddit community for bug bounty hunters.
- [InfoSec Twitter/X](https://twitter.com) - Follow #bugbounty, #infosec, and top researchers.

## Contributing
I want contributing to this awesome list to be as simple as possible. Just:
1. Fork the repository.
2. Add your changes to the list.
3. Add yourself to `CONTRIBUTORS.md`.
4. Submit a PR.

Thank you for contributing!

## Contributors
- [Contributor 1](https://github.com/contributor1)
- [Contributor 2](https://github.com/contributor2)
- [Contributor 3](https://github.com/contributor3)

To add your name to this list, please follow the [contributing guidelines](CONTRIBUTING.md).

## Core Team

- [itsmohitnarayan](https://github.com/itsmohitnarayan/)

---

> **Last Updated:** February 2026

## License
This repository is licensed under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication. For more information, see the [LICENSE](LICENSE) file or visit the [Creative Commons website](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

