# CNAME-cloacked trackers: Pi-Hole blocklist

This project aims to provide a Pi-Hole compatible version of [AdGuard's CNAME-cloaked trackers list](https://github.com/AdguardTeam/cname-trackers).

**UPDATE:** AdGuard is now providing [a Pi-Hole compatible version of their blocklist](https://github.com/AdguardTeam/cname-trackers/blob/master/combined_disguised_trackers_justdomains.txt). Use it instead of this project.

**Also note** that since [v5.0](https://pi-hole.net/2020/05/10/pi-hole-v5-0-is-here/) Pi-Hole is able to detect and block CNAME-cloaked trackers.

## What are CNAME-cloacked trackers?
CNAME-cloacked trackers are trackers that use sub-domains of a visited website to retrieve data stored in first-party cookies
and thus evade most ad and tracker blockers.

This list allows you to block those subdomains in order to prevent these trackers from tracking you. 

To learn more about this issue, you can read [NextDNS's blog post on the matter](https://medium.com/nextdns/cname-cloaking-the-dangerous-disguise-of-third-party-trackers-195205dc522a).

## How to use

It's rather simple: 
1. Browse to [pi.hole](http://pi.hole) and login
2. Click on `Group Management` then `Adlists`
3. In `Address` paste the following URL then click `Add`
   `https://raw.githubusercontent.com/axeleroy/adguard-cname-trackers-pihole/main/blocklist.txt`
