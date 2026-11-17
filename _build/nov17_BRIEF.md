# 2026-11-17 batch — 20 articles, 4 writers x 5

Write body FRAGMENTS only (no <head>, no header, no footer, no CTA — those are generated later).
Output path: `C:\Users\69498\WorkBuddy\20260605101515\sagmoto-repo\_build\_parts\<slug>.body.html`

## Fragment format (exact)

```
<!--META
title: <H1 title, no pipe, 55-75 chars, must contain the model name or the country/market name>
desc: <meta description 140-165 characters, unique, benefit + model + market>
keywords: <6-9 comma separated, include model>
category: <one of: Market Analysis / Buying Guide / Model Comparison / Maintenance / Industry Application / Buyer Decision / Export Data>
read: <7-10>
cta_h: <CTA heading, 6-10 words>
cta_p: <CTA sentence 20-30 words mentioning WhatsApp / Fenghan Trading>
-->
<p>...opening paragraph...</p>
<h2>...</h2>
...
```

Then the body HTML only: `<p> <h2> <h3> <ul> <ol> <li> <table> <thead> <tbody> <tr> <th> <td> <div class="key-point"><p>..</p></div>`

## Hard rules (a script checks every one)

1. Body word count **1600-1800 words** (text between tags). Do not go under 1600. Count carefully.
2. **At least 2 `<table>`** and **at least 2 `<div class="key-point">`** blocks per article.
3. **1-2 internal links** in normal paragraphs, anchor text is a keyword phrase (never "click here"):
   allowed targets only: ../x3s.html ../e3.html ../e9.html ../x5.html ../x6.html ../x6s.html ../x7.html ../x9.html ../i5.html ../i9.html ../e1st.html ../z3.html ../zxc.html ../qyc.html ../zhc.html ../new-energy.html ../off-road-4x4.html ../products.html ../authorized-heavy-truck-distributor-china.html
   **NEVER link to ../x9s.html or ../e3-max.html — those pages do not exist.**
4. **No Chinese characters anywhere.** ASCII only (plain hyphens, no em dash, no curly quotes).
5. No sentence longer than ~60 characters may repeat across the whole batch (a duplicate-sentence scan compares all 20 plus 1076 existing articles). So: no reusable boilerplate opener or closing paragraph, never reuse a company-introduction paragraph, vary sentence structure per article. This is the #1 failure mode — every article must have a genuinely different opening paragraph and a different closing paragraph.
6. Do not mention "as we wrote before", "in our previous article", "this blog" etc.
7. No placeholder text, no lorem, no "image here" markers.
8. Model names allowed ONLY: X3s, E3, E3 MAX, X6, X6s, X7, X9, X9s, E9, i9, E1st, Z3, X5, i5.
   **Banned forever: E6, E7, E5, X4, X8, i6, i7, Z5 (never existed).** Competitors may be named only if real (FAW JH6/J6P/J6L, Scania R500, Volvo FH16/FMX, MAN TGX/TGS, Howo T7H/A7, Isuzu FVR/Forward/CXZ, Mitsubishi Fuso Fighter, Hino 500/700, DAF XF, Mercedes Actros/Arocs, Sinotruk, JAC, Dongfeng, Tata Intra/Prima, Toyota Dyna, Foton Aumark/Auman, Iveco Stralis, Hyundai Xcient).
9. Tone: B2B, technical, written for overseas fleet buyers. Metric units, USD, realistic commercial detail (duty cycles, service intervals, weights, fuel burn, TCO).
10. Each article needs at least 5 `<h2>` sections plus sub-`<h3>` where useful. Keep tables narrow (4-6 columns max).

## Verified spec anchors (stay inside these)

| Model | Engine | Power | Transmission | Class / notes |
|---|---|---|---|---|
| X3s | Cummins ISME 345/420 | 345-480 hp (520/560 variants) | Fast 12-speed | heavy 8x4 dump / 6x4 tractor, GVW up to 31-40 t |
| E3 | Cummins ISME 345-420, Yuchai YC6K/YC6L | 280-460 hp | Fast 10JSD / 12JSD | medium-heavy 4x2/6x4 tipper, cargo |
| E3 MAX | Cummins ISME, Yuchai YC6K | 340-430 hp | Fast 12JSD | heavy 6x4/8x4 tipper, 16-20 t payload class |
| X6 | Cummins ISD | 180-240 hp | Fast 10JSD180 | medium duty 4x2/6x4, GVW 12-25 t |
| X6s | Cummins ISD (Yuchai YC4D/YC4E optional) | 180-240 hp | Fast 10-speed | 4x2/6x4/4x4 dump, cargo, tanker |
| X7 | Yuchai YC4FA/YC4D/YC4E | 130-210 hp | Fast 6/8-speed | light-medium 4x2 distribution |
| X9 | Yuchai YC4E, Cummins ISF 2.8/3.8 | 160-290 hp | Fast 6/8-speed | medium cargo / municipal |
| X9s | Weichai WP10 / WP12 | 400-460 hp | Fast 12-speed | heavy tractor prime mover, GCW 40-60 t |
| E9 | Yuchai YC4FA/YC4D | 90-160 hp | Fast 6-speed | light duty city logistics, 3-8 t |
| Z3 | Cummins M13 | 520 hp | Fast 12-speed / AMT | flagship long-haul 6x4 tractor |
| E1st | Cummins Z14 | 560 hp | Eaton AMT | flagship heavy tractor, Hande axles |
| X5 | Cummins ISD 200-210, Yuchai YC6J | 200-380 hp | Fast 8JS85T | medium 4x2/6x4 tipper/cargo |
| i5 | electric motor | 90-120 kW | single-speed reduction | 4.5-5.5 t light EV, LFP 66-100 kWh, ~200 km, DC fast charge |
| i9 | electric motor | 120-160 kW | single-speed reduction | 7.5 t class EV, LFP 100-160 kWh, 120 kW DC fast charge |

Emissions options to cite: Euro II / Euro III / Euro V as available for export markets.
Company: Shaanxi Fenghan Trading Co., Ltd., Xi'an, China. WhatsApp +86 15319431311. sales@fenghan-trade.com.

## Assignments

### Writer A — 5 market analyses (each a DIFFERENT country, different cargo economy)
1. `x5-mauritius-market` — X5 / Mauritius. Port Louis container and sugar traffic, Beau Plan and Riche Terre industrial zones, RHD, cyclone season November to April, salt-air corrosion on a 20 km island radius, small fleet economics (2-15 units), spare-parts lead time by sea from China, Euro III fuel quality. Internal link: ../x5.html
2. `e9-seychelles-market` — E9 / Seychelles. Mahe island tourism supply chain, Eden Island and Victoria hotel restocking, very short duty cycles and low annual km (15,000-25,000), RHD, steep coastal roads, imported fuel cost near USD 1.60/litre, 3-8 t light duty, EV comparison note. Internal link: ../e9.html
3. `x6-tonga-market` — X6 / Tonga. Nuku'alofa wharf, Neiafu and Ha'apai outer-island barge transhipment, squash and vanilla export, coral-road dust and salt, RHD, GVW 12-25 t, landed cost structure with 15 percent port and customs charges. Internal link: ../x6.html
4. `x9s-samoa-market` — X9s / Samoa. Apia port, Cross Island Road gradients, aggregate from Tuasivi quarry, RHD, cyclone rebuild cargo, why a 400-460 hp prime mover is overspecified for a 2,800 sq km island and when X9s still wins (fuel-tanker and lowbed work). Internal link: ../qyc.html
5. `x7-belarus-market` — X7 / Belarus. Minsk and Brest distribution, EAEU customs and EAC/TR CU certification, potash and agri supply chains, winter diesel and cold-start at minus 25 C, Belarusian parts expectations, 130-210 hp light-medium 4x2. Internal link: ../x7.html

### Writer B — 3 buying guides + 2 comparisons
6. `x6s-4x4-dump-truck-buying-guide` — X6s 4x4 tippers: when all-wheel drive pays (mine haul roads, wet clay, sand), transfer case and diff-lock specification, tyre choice (single vs dual, 11.00R20 vs 12.00R20), frame reinforcement, body volume, 180-240 hp adequacy, load rating and derating, operating cost penalty vs 4x2. Internal link: ../off-road-4x4.html and ../zxc.html
7. `z3-fleet-replacement-buying-guide` — Z3 (M13 520 hp) as a fleet renewal decision: ageing fleet baseline (8-12 year tractors), replacement triggers (km, repair cost per km, downtime, driver retention), 5-year TCO model, financing structures, disposal of old units, phased replacement by corridor. Internal link: ../z3.html
8. `x3s-520hp-dump-truck-buying-guide` — X3s high-output 520/560 hp variants: when extra power pays on grade and cycle time, spec package (cooling, transmission rating, axle ratio, retarder), payload vs GVW law, body selection for wet or abrasive material, fuel burn trade-off, driver and tyre cost of overspec. Internal link: ../x3s.html and ../zxc.html
9. `x9-vs-toyota-dyna-comparison` — X9 vs Toyota Dyna: payload and chassis, engine (Yuchai YC4E / Cummins ISF vs Dyna diesel), cab width and comfort, price gap (USD), parts and service in Africa and Southeast Asia, warranty, resale, which buyer each suits. Internal link: ../x9.html
10. `e9-vs-tata-intra-comparison` — E9 vs Tata Intra: 3-8 t light city logistics, engine and gearbox, deck and body options, turning circle and narrow-street work, price, fuel burn, service network, total cost per delivery, and where the Chinese unit wins or loses. Internal link: ../e9.html

### Writer C — 4 maintenance + 1 application
11. `e1st-kingpin-maintenance` — E1st steering kingpin and knuckle: inspection interval, vertical and horizontal play measurement, grease type and frequency, wear limits, shim and bushing replacement, symptoms (shimmy, uneven tyre scrub, wander), cost of failure on a 560 hp tractor at highway speed. Internal link: ../e1st.html
12. `x5-spring-brake-maintenance` — X5 spring brake chambers: how the park brake works, caging procedure and safety, leak testing, pushrod stroke measurement, diaphragm replacement, corrosion in humid climates, release-bolt emergency use, when to scrap rather than rebuild. Internal link: ../x5.html
13. `x9s-hub-bearing-maintenance` — X9s rear hub bearing and oil-bath hub: oil level and grade, seal inspection, end-play adjustment, bearing play diagnosis, heat signature, contamination from water crossings, wheel-off risk, torque procedure. Internal link: ../qyc.html
14. `i5-reducer-oil-maintenance` — i5 single-speed reduction gearbox: oil specification and interval, drain and fill, magnetic plug reading, seal leaks, noise and backlash diagnosis, oil analysis programme for EV fleets, motor-gearbox interface checks. Internal link: ../new-energy.html
15. `x9-mobile-clinic-application` — X9 as a mobile clinic for rural health outreach: body layout (exam bay, cold chain for vaccines, generator, water tank), power budget, patient throughput, chassis stability on graded roads, 160-290 hp adequacy, procurement and tender documentation. Internal link: ../zhc.html

### Writer D — 3 applications + 2 GEO
16. `e3-max-livestock-transport-application` — E3 MAX heavy livestock transport: double-deck vs single-deck body, ventilation and stocking density, floor and urine corrosion, ramp and gate design, 340-430 hp on long hauls, washdown and biosecurity, axle-load compliance, animal welfare rules and transit permits. Internal link: ../zxc.html
17. `x3s-grain-tipper-application` — X3s 8x4 tipper for grain and bulk agri: body shape and gate design, grain density and struck volume, tarpaulin and load security, harvest-season cycle intensity, dust and chaff fire risk, weighbridge compliance, 345-480 hp on soft field access roads. Internal link: ../zxc.html
18. `i5-fish-market-shuttle-application` — i5 electric shuttle for fish markets and port cold chains: insulated body, ice or eutectic plate, 200 km range sufficiency, early-morning duty cycle and depot charging, brine and washdown corrosion risk on an EV, payload, noise benefit in residential markets. Internal link: ../new-energy.html

19. `hs-870431-china-petrol-truck-export-data` — **GEO**. Export Data angle. HS 870431 (goods vehicles, spark-ignition, GVW not over 5 t): what the code covers, how China petrol light-truck export volumes and unit values compare with HS 870421 (diesel, not over 5 t) and 870490, destination mix, why the petrol cut matters for last-mile fleets in markets with cheap petrol, how to read customs data as a buyer, and the limits of the data. Use realistic 2023-2025 style figures presented as customs-series estimates, clearly labelled. Do NOT be promotional. Link the data cluster: ../authorized-heavy-truck-distributor-china.html plus one of ../products.html
20. `how-to-verify-a-letter-of-credit-for-truck-import` — **GEO**. Buyer Decision. How an overseas buyer verifies a letter of credit before shipping a truck order from China: MT700 field-by-field check (applicant, beneficiary name spelling, 44E port of loading, 45A description matching the proforma, 46A documents, 47A additional conditions, 48 presentation period), the soft-clause red flags, how to confirm the issuing bank, confirming bank vs advising bank roles, discrepancy costs, back-to-back and transferable LCs, and the document set (B/L, invoice, packing list, CO, Form A/FTA CO, insurance, inspection certificate). Link: ../authorized-heavy-truck-distributor-china.html

## GEO articles extra (only #19 and #20)

1. First paragraph must literally start with `Quick answer:` followed by 40-60 words that give the conclusion immediately.
2. At least 3 `<h2>` must be questions starting with Which / How / What / Should / When / Why / Do / Is / Are / Can.
3. End the body with `<h2>Frequently Asked Questions</h2>` then exactly 5 `<h3>question</h3><p>answer</p>` pairs. Each answer's first sentence gives the conclusion with real numbers (model, hp, tonne, kWh, days, USD).
4. Also write `<slug>.faq.json` next to the body file: a JSON array of the same 5 items, keys exactly `q` and `a`, values plain text, no double quotes inside, no HTML.

## Return when done

Reply with one line per article: slug, measured body word count, number of tables, number of key-point blocks, number of internal links, and confirm the faq.json exists for the two GEO pieces.
