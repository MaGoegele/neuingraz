# neuingraz.at: Affiliate / "who pays me" sheet

How each /go/\<slug\> link can earn: join a program, get a tracking URL, paste it into
`go-links.json` (+ `vercel.json` / `_redirects`). No code change per link.

Rates below are typical market ranges (EUR), **confirm the live rate at signup**, they
change. Ranking = best expected value for a Graz newcomer audience.

## Network layer (join once, then add advertisers)

| Network | Use for | Signup | Payment |
|---|---|---|---|
| **Awin** (awin.com) | The default for AT/DACH: Magenta, A1, 3, hotel/insurance/comparison advertisers | Free publisher signup, approval per advertiser | Bank transfer, monthly after validation, min. payout threshold (~€20) |
| **VIVnetworks** | AT-heavy advertisers, energy/telco lead gen | Publisher signup | Bank transfer, monthly |
| **Adcell / Digidip** | DACH, good for content/relocate blogs | Publisher signup | Bank transfer |

## Direct / comparis-style platforms (best for neuingraz)

| Slug | Provider | Program | Model | Typical payout | Rank |
|---|---|---|---|---|---|
| internet, strom, versicherung, mobilfunk, konto | **durchblicker.at** (partner.durchblicker.at) | Own affiliate program (Netrisk) | Lead / sale on switch | €5-40 per completed switch, insurance leads higher | ★★★★★ |
| strom, gas | **Check24 / Check24 Partnerprogramm** | Own program | Lead (tariff comparison complete) | ~€15-20 (Strom/Gas announced ~€20) | ★★★★★ |
| versicherung | **eHealth / durchblicker / broker portals** | Direct broker | Qualified lead | €10-50 | ★★★★ |
| internet, mobilfunk | **Magenta, A1, Drei (3)** via Awin | Network | Contract sale | €15-60 per activated contract | ★★★★ |
| strom | **Wien Energie / Verbund / Kelag / awattar** via Awin/VIV | Network | Contract switch | €10-40 | ★★★★ |
| umzug, transporter | **movinga, Umzug365, Sixt/Europcar** via Awin | Network | Booking | 3-8% of order | ★★★ |
| konto | **N26, bank99, Raiffeisen** via Awin | Network | Account opening | €20-80 | ★★★ |
| schluesseldienst, handwerker, reinigung | local directory (paid listing, not affiliate) |, | Sponsor fee | €49-249/mo listing | ★★★ |
| reisen/events, hotels | **Booking.com, GetYourGuide** (Awin/Impact) | Network | Booking | 3-5% | ★★ |

## How you actually get paid

1. **Join**, free publisher account on the network or the direct program.
2. **Get approved per advertiser**, some approve instantly, telco/insurance want to see your site first.
3. **Generate a tracking link**, e.g. `https://www.awin1.com/cread.php?awinmid=XXXX&awinaffid=YYYY&ued=<your /go page>`; direct programs give a similar link.
4. **Paste** that link into `go-links.json` for the matching slug.
5. **Payout**, networks pay by **bank transfer, monthly, after a validation window** (usually 30-60 days, so returns/cancellations are netted out). Typical minimum €20-50. Nothing is paid on a click, only on a validated lead/sale.

## Ranking summary (best → weakest for this site)
1. durchblicker.at, broadest AT coverage (internet/energy/insurance/telco), decent per-switch rate.
2. Check24, strong Strom/Gas payout.
3. Awin network (Magenta/A1/3/energy/banks), one account, many advertisers.
4. Direct broker/insurance leads, highest per-lead but only on qualified traffic.
5. Sponsorships (local businesses paying a flat monthly listing), most reliable income once traffic exists.

## Legal
Add affiliate disclosure + Impressum (operator: Nahuen Immobilien AG & KG), required once
monetized, and networks check for it at approval.
