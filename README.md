# Prime-Video-Filtering

Ad-Free Prime Video: The "Surgical" DNS Guide (2026)
This guide provides a verified method for neutralizing Pre-roll and Mid-roll ads on Prime Video (specifically tested on Onn TV/Android TV) using AdGuard Home on my Flint 2 Router.

1. AdGuard Home (Router/Flint 2) Configuration
To prevent the app from entering "Penalty Mode" (2:30 ads), we use a Safe Harbor strategy.

Step A: Optimized Upstream DNS
For the fastest response times and lowest buffering, use these Upstream DNS settings in Settings > DNS Settings:

Upstream DNS Servers:
Plaintext
https://dns.quad9.net/dns-query
https://dns.cloudflare.com/dns-query

DNS Strategy: Set to Parallel Requests (queries all upstreams and uses the fastest reply).

Bootstrap DNS: Use 9.9.9.9 and 1.1.1.1.
