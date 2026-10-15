# bandwagonhost canada: Vancouver data center details, full plan pricing from $49.99/year, and how to pick the right CN2 tier

Search "bandwagonhost canada" and you're usually after one of two answers: whether BandwagonHost is actually a Canadian company, and whether you can rent a VPS physically located in Canada. Both answers are yes, and the details are worth knowing before you pick a plan.

BandwagonHost is the consumer VPS brand of IT7 Networks Inc, a hosting company headquartered in Burnaby, British Columbia, that has been operating its own infrastructure since 2004. On the location side, the company runs two Vancouver data centers — CABC_1 and CABC_6 — which got a full hardware refresh in June 2025: AMD high-frequency CPUs and NVMe storage across the board.

Whether either fact matters for your purchase depends on what you're hosting. Below you'll find the Canadian side of the company, what the Vancouver location is genuinely good for (and what it's not for), the full plan lineup with current prices, and a plain explanation of the CN2 / CN2 GIA / GIA-E routing tiers that the brand built its reputation on.

> **Quick verdict:** If you specifically want a VPS in Canada, the entry KVM plan at **$49.99/year** can be deployed in Vancouver. If your priority is fast, stable access from mainland China, the **CN2 GIA-E 20G at $169.99/year** is the plan most people should buy — best balance of routing quality and price in the lineup. Promo code **BWHCGLUKKB** takes 6.78% off and keeps working on renewals. Every plan carries a 30-day money-back guarantee. 👉 [Check current BandwagonHost plan prices](https://bwh81.net/aff.php?aff=77528)

## Who runs BandwagonHost? IT7 Networks Inc, based in British Columbia

The BandwagonHost brand launched around 2012, but the company behind it is older. IT7 Networks Inc was founded in 2004 in Burnaby, British Columbia, and it operates as a hands-on infrastructure owner: it holds its own hardware, its own IP space, and its own autonomous system (AS25820). When a node breaks, there's no upstream provider to file a ticket with — they fix it themselves.

Scale has grown steadily. The company now serves over 500,000 customers across 21+ data centers in North America, Asia, and Europe. Everything runs as self-managed KVM VPS with full root access, administered through KiwiVM, a control panel IT7 built in-house. KiwiVM covers OS reloads, rDNS records, snapshots, an emergency console for when SSH locks you out, data center migration, and a full API if you want to script any of it.

That ownership model shows up in one place customers actually feel: pricing. The rate you sign up at is the rate you renew at — there's no cheap intro month followed by a doubled invoice.

## The Vancouver data center: what CABC_1 and CABC_6 actually give you

BandwagonHost operates two data centers in Vancouver, Canada, labeled CABC_1 and CABC_6 in its location list. On June 23, 2025, both were upgraded: new VMs deploy automatically on nodes with AMD high-frequency CPUs and NVMe storage. Existing Vancouver customers get the same hardware for free, but you have to claim it — the upgrade option lives in the KiwiVM control panel and doesn't apply itself.

Vancouver appears as a deployment option on BandwagonHost's entry-level KVM plans, alongside Los Angeles, New York, New Jersey, Fremont, and Amsterdam. Note what it's *not* attached to: the premium CN2 GIA-E lineup and the Hong Kong and Tokyo plans. Those live in Los Angeles, Japan, and Hong Kong, where the China-facing routing is. If China performance is your goal, Vancouver isn't the room you want.

So who is a Canada VPS for? Two groups, mostly. Projects serving users on the US West Coast or in Western Canada, where Vancouver's latency is excellent. And anyone who specifically wants their workload hosted on Canadian soil. If neither description fits, a Los Angeles location is usually the more versatile choice — it's the home of the CN2 GIA-E tier, and its DC9 room runs AMD EPYC processors with NVMe RAID-10 storage.

## Full plan lineup and current pricing

The current lineup breaks into three routing tiers plus location-specific premium plans. Prices are in USD; the CN2 and GIA-E plans bill quarterly or annually, the Hong Kong and Tokyo plans monthly or annually.

| Plan | CPU / RAM / SSD | Traffic | Port speed | Price | Buy |
| --- | --- | --- | --- | --- | --- |
| CN2 20G | 1 vCPU / 1 GB / 20 GB | 1 TB | 1 Gbps | $49.99/yr | [ Get CN2 20G](https://bwh81.net/aff.php?aff=77528) |
| CN2 40G | 1 vCPU / 2 GB / 40 GB | 2 TB | 1 Gbps | $99.99/yr | [ Get CN2 40G](https://bwh81.net/aff.php?aff=77528) |
| CN2 GIA-E 20G | 2 vCPU / 1 GB / 20 GB | 1 TB | 2.5 Gbps | $49.99/quarter or $169.99/yr | [ Get GIA-E 20G](https://bwh81.net/aff.php?aff=77528) |
| CN2 GIA-E 40G | 3 vCPU / 2 GB / 40 GB | 2 TB | 2.5 Gbps | $89.99/quarter or $299.99/yr | [ Get GIA-E 40G](https://bwh81.net/aff.php?aff=77528) |
| HK CN2 GIA 40G | 2 vCPU / 2 GB / 40 GB | 500 GB | 1 Gbps | $89.99/mo or $899.99/yr | [ Get HK 40G](https://bwh81.net/aff.php?aff=77528) |
| HK CN2 GIA 80G | 4 vCPU / 4 GB / 80 GB | 1 TB | 1 Gbps | $155.99/mo or $1559.99/yr | [ Get HK 80G](https://bwh81.net/aff.php?aff=77528) |
| Tokyo CN2 GIA 40G | 2 vCPU / 2 GB / 40 GB | 500 GB | 1.2 Gbps | $899.99/yr | [ Get Tokyo 40G](https://bwh81.net/aff.php?aff=77528) |

Two limited editions were added in July 2025 and were still listed that September: **BiggerBox Pro** at $39/year and **Tokyo v2** at $99/year, both running CN2 GIA-E routes. Limited editions rotate in and out of stock, so treat those as opportunistic grabs rather than something you can count on finding. 👉 [Browse the full plan list and current availability](https://bwh81.net/aff.php?aff=77528)

On locations: the CN2 and entry tiers cover the US rooms plus Vancouver and Amsterdam. GIA-E plans can migrate freely between more than a dozen data centers, including Los Angeles DC6/DC9, Japan Softbank, and the Netherlands. Hong Kong (HK85) and Tokyo (DC39v2 / JPOS_1) are their own premium tier. Sydney and Dubai round out the niche locations.

## CN2, CN2 GIA, and GIA-E: what the labels actually mean

China Telecom sells several grades of IP transit for traffic crossing its border. The bottom two — ChinaNet (AS4134) and CN2 GT (AS4809) — are the cheap ones, and both congest badly during Chinese evening peak hours. CN2 GIA (Global Internet Access) is the premium tier, expensive enough that wholesale transit on it can run $120 per megabit. That price is why most budget hosts don't build on it.

BandwagonHost is one of the few providers at this price point that runs CN2 GIA infrastructure as a core product. Its GIA-E plans route China Telecom traffic over CN2 GIA, China Unicom traffic over AS9929, and China Mobile traffic over CMIN2 — premium pathways on all three major carriers. One detailed third-party review puts average latency on GIA-E plans around 158 ms with near-zero packet loss during peak hours, which competing hosts at the same price generally can't match.

The plan names now make sense:

- **CN2** — the entry tier. Direct connection onto China Telecom's backbone, fine for blogs and light apps, no premium guarantees during congestion.
- **CN2 GIA-E** — the value pick. Triple-carrier premium routing at 2.5 Gbps, plus free migration between a dozen-plus data centers after purchase. Your traffic quota carries over when you move.
- **CN2 GIA (Hong Kong / Tokyo)** — the lowest-latency tier, hosted in Equinix facilities with direct CN2 GIA routing. Hong Kong plans quote sub-50 ms figures and, to many mainland cities, single-digit milliseconds. The pricing reflects it: HK starts at $89.99/month.

The GIA-E migration option deserves a second look, because it changes how you can buy. Launch in Los Angeles, and if your audience turns out to be concentrated in East Asia, migrate to Tokyo Softbank from the panel — no new server, no data purchase, no lost traffic allowance.

## Promo codes and the real cost over three years

The renewal-honest pricing makes discount codes worth more here than at most hosts, because whatever you save on day one keeps saving on every renewal. Two codes are currently in circulation:

- **BWHCGLUKKB** — 6.78% off all plans and billing cycles, verified to work on renewals as well as first orders. On the $49.99/year entry plan, that lands the effective price at about **$46.61/year** (roughly $3.88/month). On the $169.99/year GIA-E plan it saves about $11.50 per year.
- **ireallyreadtheterms8** — reportedly 7–10% off sitewide, though availability varies. Costs nothing to try at checkout.

To apply a code: pick your plan, proceed to checkout, enter it in the "Promotional Code" field, hit Validate, and confirm the discounted total appears before paying. The whole step takes about ten seconds, and because the code recurs, the savings compound — roughly $35 over three years on a GIA-E plan, for a one-time action most people skip.

Every plan also includes instant setup, a 99.9% uptime guarantee, and a 30-day refund policy. The refund window effectively makes the first month a trial: if the routing or performance doesn't match what you need, you get out clean. 👉 [Pick a plan and apply the code at checkout](https://bwh81.net/aff.php?aff=77528)

## Where BandwagonHost is the wrong choice

Two limitations catch buyers off guard, so let's put them up front.

**No managed hosting.** These are self-managed KVM servers with root access and no hand-holding. If you need cPanel, a support team that configures things for you, or phone support, this isn't that kind of host. You should be comfortable with basic Linux server administration.

**DDoS handling is blunt.** The CN2 GIA plans deal with attacks by nullrouting the target IP, which means temporary downtime while the attack lasts. High-traffic sites that need robust, always-on mitigation should look at dedicated protection providers instead.

One more thing worth saying plainly: if fast China access is your entire reason for buying, the $49.99/year entry plan will disappoint — it sits on the basic CN2 tier. The GIA-E line is where that benefit actually lives, and the $120/year price jump from entry to GIA-E 20G is exactly what you're paying for.

## Ordering a plan, start to finish

1. Choose your plan and billing cycle — quarterly terms let you test a GIA-E plan for $49.99 before committing to a year.
2. At checkout, enter **BWHCGLUKKB** in the Promotional Code field and hit Validate.
3. Confirm the discounted total shows before you pay.
4. Once deployed, your server appears in KiwiVM. From there you can reinstall the OS, set rDNS, take snapshots, or migrate data centers without opening a ticket.
5. Existing Vancouver customers: check the KiwiVM panel for the free AMD/NVMe hardware upgrade option.

## FAQ

**Is BandwagonHost a Canadian company?**
Yes. It's operated by IT7 Networks Inc, headquartered in Burnaby, British Columbia, Canada, founded in 2004. BandwagonHost launched in 2012 as its consumer VPS brand.

**Does BandwagonHost have a data center in Canada?**
Yes — two facilities in Vancouver, CABC_1 and CABC_6, upgraded in June 2025 with AMD high-frequency CPUs and NVMe storage. Vancouver is a deployment option on the entry KVM plans.

**What's the difference between CN2 and CN2 GIA-E?**
CN2 is the entry tier: direct China Telecom routing without premium guarantees. GIA-E adds premium routing on all three major Chinese carriers — CN2 GIA for Telecom, AS9929 for Unicom, CMIN2 for Mobile — at 2.5 Gbps, plus free migration between a dozen-plus data centers. For China-facing performance, GIA-E is the tier that delivers it.

**Can I move my VPS to a different data center later?**
Yes. Most plans support free migration from the KiwiVM panel. GIA-E plans can move between more than a dozen locations, and the traffic quota stays intact through the move.

**What if it doesn't work out?**
All plans carry a 30-day money-back guarantee on top of the 99.9% uptime guarantee.

## So which plan should you actually get

Match the plan to the job:

- **Want a VPS in Canada specifically?** The entry KVM plan at $49.99/year, deployed in Vancouver. With BWHCGLUKKB it comes to about $46.61 for the year — and the hardware there is fresh as of mid-2025.
- **Need fast, reliable access from mainland China on a sane budget?** CN2 GIA-E 20G at $169.99/year. Premium routing on all three Chinese carriers, 2.5 Gbps port, and you can migrate between a dozen-plus locations later if your traffic pattern shifts.
- **Running something latency-critical for China, budget secondary?** Hong Kong CN2 GIA from $89.99/month — sub-50 ms territory, priced accordingly.
- **Just need a cheap Linux box to learn on?** The entry plan in any location does the job. Apply the code anyway; it's free money.

Before paying, two quick checks: make sure the promo code shows as validated in your checkout total, and note that the 30-day refund clock starts at order date, not first use. 👉 [Compare all BandwagonHost plans and locations](https://bwh81.net/aff.php?aff=77528)
