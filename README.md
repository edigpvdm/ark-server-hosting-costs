# Best cheap ARK server hosting: what do 4–10 players actually need, where do the hidden costs hide, and should you rent or self-host? (ASE and ASA priced separately)

A four-to-eight player ARK: Survival Evolved server can run on **$8 a month**. Sparked Host lists its 8 GB plan at that price, month to month, with a 48-hour refund window. Hostinger's game panel looks close at **$13.99/mo** until you read the terms: 24 months paid upfront and a **$28.99/mo** renewal after that. If you're shopping for Survival Ascended rather than Evolved, comparing hosts is mostly wasted effort, because paid ASA hosting is effectively Nitrado-only.

Below: how the ASE/ASA split changes what you're allowed to buy, the verified prices with the billing basis attached to each one, SpinServers' full VPS and dedicated lineup for people who'd rather run the machine themselves, and four costs that never show up in the headline price.

> **Quick pick.** Playing ASE with 4–8 friends and want zero setup: a managed 8–12 GB game server at $8–$12/mo is the cheapest thing that works. Running several maps as a cluster, hosting ASA without Nitrado, or wanting root on the box: SpinServers' 8 GB KVM VPS starts at $39/mo and the 12 GB at $62/mo, both unmanaged. 👉 [Check SpinServers' current VPS prices and availability](https://bit.ly/Spinservers)

## ASE or ASA? Settle this before you compare prices

ARK: Survival Evolved (ASE) is the one with a competitive hosting market. G-Portal, Arkservers.io, Sparked Host, Hostinger's game panel and a dozen others all sell ASE servers, and you can also run one on your own hardware.

ARK: Survival Ascended (ASA) is different. Community reports going back to mid-2024 say Snail Games signed an exclusivity deal with Nitrado covering hosted ASA servers, leaving self-hosting as the only alternative. That claim doesn't rest on forum gossip alone: Gravel Host sells "ARK: Survival Ascended VPS hosting" and states in its own copy that ASA "comes with licensing terms a host cannot bundle for you," that it provides infrastructure only, and that it is not a licensee of Snail Games or Studio Wildcard. A host that wanted to sell you a ready-made ASA server would not write that paragraph.

So cheap ASA hosting is not a shopping problem, it's a licensing one. Your realistic options are Nitrado at roughly $30 per map (a community-reported figure, not a published quote) or a VPS, dedicated box, or spare PC where you install the server software yourself and take responsibility for the licence. Everything in the rest of this article about $8 managed plans applies to ASE.

## What "cheap" means: four prices, four billing models

These are the numbers readers actually compare, and they are not comparable as printed.

| Provider | Plan and specs | Listed price | What that price actually is |
| --- | --- | --- | --- |
| Sparked Host | Thatch: 8 GB RAM, 2 vCPU, 50 GB | $8.00/mo | Straight monthly, 48-hour refund |
| Sparked Host | Wood: 12 GB RAM, 2 vCPU, 50 GB | $12.00/mo | Straight monthly, 48-hour refund |
| Hostinger | Game Panel 4: 4 vCPU, 16 GB, 200 GB NVMe | $13.99/mo | 24-month prepay ($335.76 today), renews at $28.99/mo |
| Hostinger | Game Panel 8: 8 vCPU, 32 GB, 400 GB NVMe | $27.99/mo | 24-month prepay ($671.76 today), renews at $49.99/mo |
| Gravel Host | ASA Tier 1: 16 GB DDR4, unlimited NVMe | $24.00/mo | Monthly, infrastructure only, 72-hour refund on first purchase |
| Nitrado | Managed ASA/ASE | ~$30/map | Community-reported, not an official quote |

Two entries need footnotes. Sparked Host's $8 plan is the cheapest verified monthly price for a usable ASE server, but the 8 GB comes with a **2 vCPU cap**, and the optional extras add up fast: Game Management is +$20/mo, a dedicated IP +$3/mo, Discord support +$3/mo. Hostinger's $13.99 is a promotional rate for a 24-month commitment, so the honest first-year comparison is $335.76 against Sparked Host's $96.

One price you should ignore: Servers4Gamers advertised $8.75/mo for 8+ GB, but that was a mid-2024 page and the figure depended on a seasonal coupon code. Coupon prices expire; list prices are what you renew at. Their published sizing guidance is still worth keeping, and I'll come back to it.

## SpinServers' full plan list, and the case where it wins

SpinServers doesn't sell an ARK game panel. It sells unmanaged KVM VPS and bare-metal servers in the US, which means you get root, you install ARK through SteamCMD, and nobody configures your ini files for you. That's a worse deal than $8/mo if you want one map for five friends. It's a better deal when you want three maps in a cluster on one machine, or ASA without going through Nitrado.

Current KVM VPS lineup, all with RAID-10 SSD, a 1 Gbps port, 1 IPv4 and 1 IPv6, billed monthly in USD:

| Plan | vCPU / RAM | Storage | Bandwidth | Price | Order |
| --- | --- | --- | --- | --- | --- |
| KVM 2vCPU 2GB | 2 / 2 GB | 40 GB SSD | 4 TB | $12.00/mo | [See plan](https://bit.ly/Spinservers) |
| KVM 4vCPU 4GB | 4 / 4 GB | 80 GB SSD | 8 TB | $29.00/mo | [See plan](https://bit.ly/Spinservers) |
| KVM 6vCPU 8GB | 6 / 8 GB | 120 GB SSD | 8 TB | $39.00/mo | [See plan](https://bit.ly/Spinservers) |
| KVM 8vCPU 8GB | 8 / 8 GB | 160 GB SSD | 10 TB | $45.00/mo | [See plan](https://bit.ly/Spinservers) |
| KVM 12vCPU 12GB | 12 / 12 GB | 160 GB SSD | 10 TB | $62.00/mo | [See plan](https://bit.ly/Spinservers) |
| KVM 16vCPU 16GB | 16 / 16 GB | 320 GB SSD | 15 TB | $74.00/mo | [See plan](https://bit.ly/Spinservers) |
| Hybrid KVM 32vCPU 32GB | 32 / 32 GB | 500 GB SSD | 20 TB | $89.00/mo | [See plan](https://bit.ly/Spinservers) |

The 2 GB and 4 GB plans are too small for ARK. A vanilla ASE map with a handful of players will boot on 4 GB and then fall over the first time someone loads a mod-heavy save. Treat 8 GB as the floor and 12–16 GB as the range where a cluster stops being painful.

Above the VPS range, SpinServers lists bare-metal servers in Dallas and San Jose starting at **$79.00/mo** for a Xeon E3-1280 v5 with 4 cores/8 threads, 32 GB DDR4 ECC, a 1 TB NVMe drive and 30 TB of traffic on a 10 Gbps port. Dual-Xeon configurations with 128 GB to 512 GB of RAM are listed from $235/mo. These auto-provision and are aimed at people who need one machine for several game servers, not one server for one map.

Two things to know before ordering: port 25 is closed by default on every VPS (you can open a ticket if you have a reason), and nothing here is managed. No money-back window is published on the pages I reviewed, so confirm cancellation terms in writing before you pay.

## The four hidden bills on a cheap ARK server

**1. The renewal price.** Hostinger's $13.99/mo becomes $28.99/mo when the 24-month term ends, and the $27.99 plan becomes $49.99. Over three years the "cheap" 16 GB plan costs more than $900. Sparked Host's $8 has no prepay and no published renewal jump, which is part of why it undercuts bigger-sounding plans on total cost.

**2. The refund window.** Sparked Host refunds ARK servers in full within 48 hours, and explicitly does not refund VPS or dedicated servers. Gravel Host offers 72 hours but only on a new customer's first purchase, once per account, minus processing fees, and excludes renewals, add-ons and upgrades. Hostinger's page doesn't advertise a trial. Read the window before you pay, not after the server misbehaves.

**3. CPU caps and slot limits.** 8 GB of RAM means little if you only get 2 vCPU, which is exactly what Sparked Host's $8 tier provides; the Ryzen 9 7900 and 9900X hardware sits in the higher tiers. Servers4Gamers took the opposite approach, billing purely by RAM with unlimited CPU and no slot limits. Neither model is wrong, but two hosts quoting "8 GB" can deliver very different performance once eight players and a mod pack are on the map.

**4. Add-ons you'll actually want.** A dedicated IP, managed mod installation, and priority support are paid extras at some hosts. Sparked Host's $20/mo Game Management covers 10 mod installs and 10 save uploads per month. If you're comfortable with SFTP, that's $240 a year you don't need to spend.

## Rent or self-host: the rule I'd use

If you have an old desktop with 16 GB of RAM and don't mind editing a few text files, self-hosting a cluster is cheaper than any subscription after the first few months, and you own the saves. The learning curve is real: cluster configuration, port forwarding, and a pile of ini settings.

If you don't want to touch a command line, buy managed. A $8–$12/mo ASE plan costs less than two hours of your time, and the setup is a dropdown.

If you're on ASA, check the licensing reality first. Nitrado, or a box you control. There's no third option that survives contact with the terms.

Moving between hosts is the easy part. Copy the `SavedArk` folder from the old server and upload it to the new one. On a managed host that's an SFTP upload or their importer; on a VPS you drop it into the server's save directory and restart.

## How much RAM for 4, 8, or 20 players?

Servers4Gamers' published guidance is a reasonable starting point: **6 GB minimum for 10–20 players**, and **10–12 GB for larger groups or heavy mod packs**. ASA is heavier than ASE because of the Unreal Engine 5 rebuild, which is why the ASA-specific VPS tiers from Gravel Host start at 16 GB and run to 28 GB.

Mapped onto SpinServers' lineup: 8 GB ($39/mo) covers a small ASE map with light mods, 12 GB ($62/mo) covers a two-map cluster, and 16 GB ($74/mo) is where ASA starts to make sense on your own hardware. 👉 [Compare the 8 GB and 12 GB KVM plans side by side](https://bit.ly/Spinservers)

Cheap hardware doesn't have to mean a bad server. The settings that decide how the game feels live in `GameUserSettings.ini`: `DifficultyOffset` from 0.2 to 1.0 controls wild creature levels, `HarvestAmountMultiplier` at 2.0 doubles gathering, `XPMultiplier` speeds leveling, and the dino multiplier at 1.5 means 50% more wild dinosaurs. PvE mode is a single flag (`PvE Enabled = true`). None of that requires a premium plan.

## FAQ

**Can I move my existing world to a new host?** Yes. Download the `SavedArk` folder from your current server and upload it to the new one. Keep a local copy until the new server has booted once with the save in place.

**Can I install mods?** On ASE, yes, through Steam Workshop IDs added to the server's launch parameters. On a managed host there's usually a mod manager; on a VPS you add them yourself.

**Does crossplay work?** Sparked Host advertises PS4/Xbox crossplay on ASE, and ASA supports PC/Xbox/PlayStation crossplay where the game itself allows it. Confirm the specific map and platform combination with support before you pay, since this changes with game updates.

**What happens if I cancel?** Depends entirely on the window. Sparked Host: 48 hours, full refund, ARK only. Gravel Host: 72 hours, first purchase only, once per account. SpinServers doesn't publish a money-back period, so ask before ordering.

## Before you order

Match the plan to the job:

- **One ASE map, 4–8 friends, no interest in server admin** → a managed 8 GB plan at $8/mo. Cheapest verified option, 48-hour refund if it disappoints.
- **Two or three maps in a cluster, or mods you want to control** → a 12–16 GB VPS at $62–$74/mo. You'll spend an evening on setup and save money from month two onward.
- **ASA, and you don't want Nitrado** → a VPS or dedicated machine where you install the software and handle the licence yourself.
- **Several game servers, not just ARK** → a dedicated box from $79/mo beats stacking four VPS plans.

Two things to confirm before you enter card details: which game version the plan is actually set up for, and what the renewal price and refund window are in writing. The first determines whether you can legally run what you bought; the second determines what leaving costs.

👉 [Check SpinServers' current VPS and dedicated pricing](https://bit.ly/Spinservers)
