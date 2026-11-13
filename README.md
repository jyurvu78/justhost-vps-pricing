# 1 Dollar VPS: What $1 Really Buys, Where the Hidden Costs Sit, and Which JustHost Plan Fits (Full Lineup and 12-Month Pricing Compared)

A one-dollar VPS is real, and the specs are predictable: 1 to 2 vCPU, 256MB to 1GB of RAM, 10 to 30GB of SSD or NVMe, and 500GB to 1TB of monthly traffic. The headline number rarely survives checkout, because most of these plans only reach $1 through a 12-month prepayment, a first-invoice discount, or a rate quietly quoted per day instead of per month.

JustHost has no $1 plan. The cheapest is **$1.99/month** for 1 core, 512MB RAM and 5GB of NVMe, and IPv6-only instances start at **$1.60**. Whether that beats a literal $1 offer depends on two things most roundups skip: what the port speed caps you at, and what an IPv4 address adds to the bill.

> **Quick pick:** **VPS Promo at $1.99/month** (1 core, 512MB RAM, 5GB NVMe, 10 Mbps fair-share port, roughly a 4TB monthly ceiling) handles cron jobs, uptime monitors, tunnel endpoints, IRC bouncers and small IPv6 services. For a site with a database and a control panel, start at **New Star, $3.81/month** ($3.05 on 12-month billing) for 1GB RAM and 10GB NVMe.
>
> 👉 [Check the VPS Promo plan and its current 12-month rate](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392)

## JustHost VPS lineup and prices

All plans run on KVM with NVMe storage and DDoS protection, priced in USD. The second price is the 12-month rate, 20% below the monthly one and available on orders of three months or more.

| Plan | vCPU / RAM / NVMe | Port (fair-share) | Monthly | 12-month rate | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 / 512MB / 5GB | 10 Mbps | $1.99 | not listed | [ Order Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 / 1024MB / 10GB | 100 Mbps | $3.81 | $3.05 | [ Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 / 2048MB / 20GB | 200 Mbps | $7.08 | $5.67 | [ Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Bright Star | 4 / 4096MB / 30GB | 300 Mbps | $9.80 | $7.84 | [ Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Sirius | 1 / 1024MB / 20GB | 300 Mbps | $4.85 | $3.88 | [ Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 / 2048MB / 30GB | 300 Mbps | $6.92 | $5.53 | [ Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 / 2048MB / 40GB | 400 Mbps | $8.99 | $7.19 | [ Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Vega | 2 / 4096MB / 80GB | 500 Mbps | $13.44 | $10.75 | [ Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 / 4096MB / 120GB | 750 Mbps | $18.30 | $14.64 | [ Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

The lineup continues past Capella with Rigel (4 cores, 8GB RAM, 200GB NVMe) and larger configurations; those are listed with current prices on the same page.

Two details in that table matter more than the CPU column. Traffic is unmetered, but the port is shared and fair-share, so your real ceiling is the port speed. JustHost's own arithmetic works out to 4+ TB per month at 10 Mbps, 93+ TB at 300 Mbps and 232+ TB at 750 Mbps. A "10 Mbps unmetered" plan is not a web-serving plan.

👉 [See every JustHost VPS plan with its 12-month rate](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## The same hardware, two different prices

JustHost's VPS landing page runs a separate promo list. The configurations match the table above, the prices don't:

- **Sirius Special** (1 core, 1GB RAM, 20GB NVMe): $2.81/month, or $2.25 on 12-month billing, against $4.85 and $3.88 on the pricing page
- **Arcturus Special** (1 core, 2GB, 30GB): $4.01 / $3.21
- **Vega Special** (2 cores, 4GB, 80GB): $7.79 / $6.23
- **Yildun Special** (4 cores, 8GB, 200GB): $16.20 / $12.96

If Sirius Special is available when you order, it beats New Star on every spec except port speed, at a lower price than New Star's monthly rate. Check both pages before you pay; the promo list rotates.

## Storage type changes the price by less than a dollar

JustHost also lets you pick HDD, SSD or NVMe on its dual-stack line, and the gap between them is small enough that the cheap choice is rarely worth it.

| Same config | HDD | SSD | NVMe |
| --- | --- | --- | --- |
| 1 core / 512MB / 5GB | $3.25 ($2.60 annual) | $3.90 ($3.12 annual) | $4.22 ($3.38 annual) |
| 2 cores / 2GB / 25GB | $11.00 ($8.80 annual) | $13.20 ($10.56 annual) | $14.30 ($11.44 annual) |
| 4 cores / 4GB / 50GB | $22.00 ($17.60 annual) | $26.40 ($21.12 annual) | $28.60 ($22.88 annual) |

Moving from HDD to NVMe at the entry level costs $0.78/month on annual billing. That is the cheapest upgrade on this entire page, and the one most likely to decide whether a small box feels usable. JustHost's IPv4 + IPv6 instances start at **$2.60/month** on annual billing (the 1 core / 512MB / 5GB HDD configuration), while IPv6-only starts at **$1.60**.

👉 [Compare the IPv4 and IPv6 entry configurations](https://justhost.asia/en/vps?ref=196392)

## What $1 actually buys in a VPS

A recently updated roundup of $1 VPS plans puts the typical spec band at 1 to 2 vCPU, 256MB to 1GB RAM, 10 to 30GB NVMe or SSD, and 500GB to 1TB of monthly transfer. These plans exist for experiments, staging environments, small WordPress installs and personal projects. Heavy processing, large databases and high-traffic sites need a tier or two up, and no amount of tuning fixes a 512MB box running WooCommerce.

Four things mark a bad $1 offer: HDD storage instead of SSD or NVMe, low IOPS, an aging CPU, and an "unlimited traffic" promise on a $1 plan. Overselling is the norm at this price, so several instances share the same physical hardware and performance drops under sustained load. Support tends to be slower, and disk space is small enough that hosting files is out of the question.

Measured against that band, VPS Promo looks unusual: 512MB and NVMe are both in range, but 5GB of disk is below the 10 to 30GB norm, and the 10 Mbps port caps you near 4TB. You are trading storage and throughput headroom for NVMe and a fixed, published price. For a headless box that pushes almost nothing, that trade works.

## Four ways a "1 dollar" VPS is sold

The gap between the headline and the invoice follows a few repeatable patterns. Each of these was checked on the vendor's own page.

**The keyword says one dollar, the plan list says $7.71.** LightNode's page is titled "1 Dollar VPS" and the purchase button announces "$1", while the cheapest plan on it is $7.71/month for 2GB DDR4, 1 vCPU, 50GB NVMe and 1TB of bandwidth across 40+ data centers. Hourly billing starts at $0.012/hour, and the page claims 99.95% network uptime. The label describes a category, not a price.

**€1 per month, IPv6-only, and the backup expires in a day.** VPS1Dollar, a French host, sells a base plan at €1/month with 1 Xeon vCPU, 1GB RAM, 20GB storage and a 100 Mbps port with unlimited traffic. It is IPv6-only, reachable from IPv4 networks through NAT64, Cloudflare proxy, or the IPv4 SSH proxy bundled with each server. A public IPv4 address costs extra. Each VPS includes 20GB of FTP backup space on a private VLAN and one snapshot, with automated backups kept for **24 hours**. Deployment takes under a minute, billing is monthly with no contract, and the page promises 24/7 monitoring without an uptime percentage.

**"Starting at $1" with no $1 plan shown.** CloudSurph's homepage advertises VPS hosting from $1, and the plan list beneath it starts at $9.99/month for 4GB RAM, 2 vCPU and 100GB SSD. Nothing on the page states the CPU, RAM or disk of the $1 tier. The same page does publish a 99.99% uptime SLA covering network, power and virtual server availability, with downtime credit if it's missed, plus a 5-day full refund window.

**$1 per day, not per month.** One Dollar Web Host's page still carries a "Get Started For $1" call to action, and its body text says "starting as low as $1 per day". The actual VPS plans are $30/month for 10 cores, 10GB RAM and 100GB NVMe, then $45 and $60. The page dates from February 2024, so treat it as an illustration of the wording rather than a current quote.

## What to confirm before you pay

1. **Divide the annual total by 12.** A $12/year plan is $1/month; a $1/month plan billed quarterly is $3 per quarter. Compare like for like.
2. **Separate the first-term price from the renewal price.** Promotional rates expire, and renewal is where cheap hosts recover margin.
3. **Check storage type and IOPS, not just capacity.** JustHost charges $2.60 for HDD and $3.38 for NVMe on the same 1 core / 512MB / 5GB configuration with annual billing.
4. **Read what "unmetered" means.** JustHost pairs unmetered traffic with a fair-share port, and 10 Mbps works out to about 4TB a month no matter what the traffic policy says.
5. **Confirm whether IPv4 is included.** JustHost's gap between IPv6-only ($1.60) and dual-stack ($2.60) is $1/month; VPS1Dollar treats public IPv4 as a paid add-on.
6. **Ask how long backups are kept.** VPS1Dollar's automated backups last 24 hours. A backup you can't restore from last week is not a backup.
7. **Read the uptime wording.** CloudSurph publishes 99.99% with credit, LightNode publishes 99.95% for network uptime, and VPS1Dollar publishes monitoring without a number. These are three different promises.
8. **Find the refund window before prepaying a year.** CloudSurph offers 5 days. JustHost's plan pages don't state one, so ask support in writing before you commit to 12 months.

## Which plan fits your workload

- **Cron jobs, monitoring, a tunnel endpoint, an IPv6 lab:** VPS Promo at $1.99, or the IPv6-only entry at $1.60 if you have no use for IPv4.
- **One small site with caching:** New Star at $3.81 ($3.05 annual) for 1GB RAM. Check whether Sirius Special is live first; at $2.81 it has double the RAM and double the disk.
- **Two or three sites, a control panel, a handful of Docker containers:** Double Star at $7.08 or Vega at $13.44 if the sites are heavier.
- **Anything with a database you care about:** 2GB RAM minimum, which means Arcturus or above.
- **A cheap box that must answer on IPv4:** the NVMe Start++ configuration at $3.38/month on annual billing, not the $1.60 IPv6-only entry.

👉 [Start with New Star at $3.81/month](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)

## FAQ

**Can a $1 VPS run WordPress?**
512MB to 1GB of RAM runs a single small WordPress site with basic plugins and a caching layer, on NVMe storage. Below 512MB, or with a plugin stack and no cache, page loads and admin work become painful. A 5GB disk also fills quickly once you add themes, uploads and backups.

**Why are so many cheap VPS plans IPv6-only?**
IPv4 addresses cost the provider money, so they're sold separately or omitted to hit a price point. IPv6-only hosts bridge the gap with NAT64, a proxy, or a dedicated IPv4 SSH proxy, which lets you connect but doesn't make your site reachable over IPv4 without extra configuration.

**Is "$1" per month or per year?**
Both appear in listings, and so does "$1 per day". A plan advertised at $1/month with a $12 annual invoice is genuinely $1/month; a plan advertised at $1 that requires a $36 quarterly payment is not. Multiply out the invoice and divide.

**Do I need the 12-month rate?**
A 20% discount on a $3.81 plan saves about $9 a year. Take it only after you've confirmed the refund window and how the plan behaves under your workload for a month. Monthly billing costs more and buys you the option to leave.

**Does JustHost let you change data center or IP later?**
Yes. A March 2026 review of the São Paulo node documents one-click data center switching and one-click IP switching, with up to 50 switches per VM. That matters if you're buying a cheap box to test which region performs best for your users.

## Final rules

If you want the absolute lowest number and have no need for IPv4, the IPv6-only entry at $1.60 is the floor here. If you want a working server you won't have to babysit, VPS Promo at $1.99 is the honest starting point, and New Star at $3.81 is what most people actually need once a database enters the picture.

Two things to settle before paying for 12 months: the refund window, which isn't published on the plan pages, and whether the lower-priced Special listing is currently live for the configuration you want. Both take one message to support, and both cost more than the discount if you skip them.

👉 [See current JustHost VPS pricing and 12-month rates](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)
