# Prime-Video-Filtering
This project has been a massive undertaking. Please be patient as this is still in experimental stages. 

Traditional ad blocking techniques are NOT effective against a machine of a company that thrives off of ad revenue. New game --> trick the app into thinking it played the content when it actually bypasses it. I've found that the harder you block the domains, the more ads the app throws at you - it's pretty much a never ending fight and it slows the responsiveness of the app and degrades the overall watching experience. Please remember, this has worked in a specific instance I've set up, so I can't guarantee your results will be the same as mine. Hopefully, if the ads haven't been fully eliminated, they have been reduced by duration. Enjoy!


Ad-Free Prime Video: The "Surgical" DNS Guide (2026)
This guide provides a verified method for neutralizing Pre-roll and Mid-roll ads on Prime Video (specifically tested on Onn TV/Android TV) using AdGuard Home on my Flint 2 Router.

1. AdGuard Home (Router/Flint 2) Configuration
to prevent the app from entering "Penalty Mode" (2:30 ads), we use a Safe Harbor strategy. This means that instead of increasing ad duration by blocking the domains, we allow them to think that they are being played. Reverse Uno!

Step A: Optimized Upstream DNS
For the fastest response times and lowest buffering, use these Upstream DNS settings in Settings > DNS Settings:

Upstream DNS Servers:

https://dns.quad9.net/dns-query

https://dns.cloudflare.com/dns-query

DNS Strategy: Set to Fastest IP Address Requests (queries all upstreams and uses the fastest reply).

Disable resolving of the IPv6 addresses

Bootstrap DNS: Use 9.9.9.9 and 1.1.1.1.
