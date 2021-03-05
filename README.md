# CNAME-cloacked trackers: Pi-Hole blocklist

This project aims to provide a Pi-Hole compatible version of [AdGuard's CNAME-cloaked trackers list](https://github.com/AdguardTeam/cname-trackers).

## What are CNAME-cloacked trackers?
CNAME-cloacked trackers are trackers that use sub-domains of a visited website to retrieve data stored in first-party cookies
and thus evade most ad and tracker blockers.

To learn more about this issue, you can read [NextDNS's blog post on the matter](https://medium.com/nextdns/cname-cloaking-the-dangerous-disguise-of-third-party-trackers-195205dc522a).

## How to use

It's rather simple: 
1. Browse to [pi.hole](http://pi.hole) and login
2. Click on `Group Management` then `Adlists`
3. In `Address` paste the following URL then click `Add`
   `https://raw.githubusercontent.com/axeleroy/adguard-cname-trackers-pihole/main/blocklist.txt`
