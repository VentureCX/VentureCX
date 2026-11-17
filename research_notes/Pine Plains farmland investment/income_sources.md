# Income Sources for Farmland/Acreage in Pine Plains, NY and Northern Dutchess

Research date: 2026-11-17. About 17 tool calls. Several primary sources (NASS Quick Stats API, NYSDEC stumpage PDFs, Zillow) could not be read directly. Those numbers come from secondary aggregators and are flagged as such.

## 1. Agricultural cash rents (NASS, hay/pasture, horses, Cornell guidance)

### Takeaway
Ag rent is a small offset to holding costs. Dutchess non-irrigated cropland rents for about **$54/acre/yr (2026)**, up from about $40.50 in 2025. Pasture rents for about $18–31/acre/yr in New York, and NASS has not published a Dutchess pasture figure since 2020. On 100 tillable acres that is roughly $4,000–$8,000/yr. Its main value is likely keeping the land in active agriculture so it qualifies for the NY agricultural assessment (inference; see Gaps).

### Cited Findings
- **Land values. NASS Land Values 2026 Summary (released July 31, 2026):**
  - NY farm real estate averaged $4,500/acre in 2026, up 4.7%; it was $4,300 in 2025.
  - NY cropland averaged $4,150/acre in 2026; it was $4,010 in 2025.
  - NY pasture averaged $2,040/acre in 2026; it was $1,950 in 2025.
  - Northeast cropland averaged $8,140/acre and US cropland $6,020/acre.
  - Source: [NASS Land Values 2026 Summary](https://release.nass.usda.gov/reports/land0726.pdf). The 2025 figures come from the [NASS Land Values 2025 Summary, released Aug 1, 2025](https://release.nass.usda.gov/reports/land0825.pdf).
  - Note: The 2026 Land Values PDF does not contain cash rent tables; NASS published those separately.
- **Northeast region rents, 2026:** Cropland rent is $107/acre and pasture rent is $43/acre, citing NASS Land Values 2026 — [USDA ERS Farmland Value page](https://www.ers.usda.gov/topics/farm-economy/land-use-land-value-tenure/farmland-value) (via search snippet; not verified on the page).
- **US rents, 2025:** Cropland averaged $161/acre, up 0.6%. Pasture averaged $15.50/acre, unchanged — [American Farm Bureau Market Intel](https://www.fb.org/market-intel/real-estate-rising-farmland-values-hit-record-high).
- **NASS county cash rents, 2026 (released Aug 21, 2026), via the aggregator AGSIST.** These are NASS values, but AGSIST is not endorsed by NASS, and some 2025 values were implied from its year-over-year change column. Verify them in Quick Stats. Source: [AGSIST NY cash rents](https://agsist.com/rent/new-york).

  | County | Cropland, non-irrigated, 2026 | Cropland, non-irrigated, 2025 | Pasture |
  |---|---|---|---|
  | Dutchess | $54/acre | ~$40.50/acre (+33%) | Not published (last published 2020) |
  | Columbia | $54/acre | ~$46/acre | $18/acre (2026) |
  | Ulster | $104/acre | — | — |
  | Orange | $77/acre | — | $21.50/acre (2025) |
  | Washington | $88/acre | — | $20/acre (2025) |
  | Rensselaer | $52.50/acre | — | $61.50/acre (2025) |

  - Median across NY counties: cropland is $73/acre in 2026 (47 counties) and $68.50/acre in 2025 (45 counties). Pasture is $22.25/acre in 2026 (16 counties).
- **Statewide NY averages conflict between sources:**
  - [Farm Progress](https://www.farmprogress.com/farm-business/cash-rental-rates-for-cropland-show-mixed-trends-across-northeast-mid-atlantic) reports NY non-irrigated cropland at $82.50/acre, unchanged. It reports pasture at $31/acre, up from $26.50. The article is about 409 days old, so it likely reflects the 2025 release (STALE / year uncertain).
  - Another aggregator lists NY at $89/acre in 2026 and pasture at $30.50 — [Oaken](https://www.oaken.ag/new-york-state-and-county-cash-rental-rates). It is unverified against NASS.
- **Method:** NASS publishes county rents only where enough survey responses came back and the county has at least 20,000 acres of cropland plus pasture — [NASS Cash Rents methodology 08/2025](https://www.nass.usda.gov/Publications/Methodology_and_Data_Quality/Cash_Rents/08_2025/crntqm25.pdf).
- **Older Cornell regional data (STALE, 2021):** A Central NY cash rent survey reported pasture at $22, $32 and $43/acre for low, medium and high soil classes in Chenango County — [Cornell EB 2021-02](https://business.cornell.edu/wp-content/uploads/2026/07/EB-2021-02_Central-NY-Farmland-Cash-Rental-Rate-Survey-Findings-VD.pdf).
- **Rent-setting methods:** Cornell Small Farms describes several approaches for setting a fair rent but gives no Dutchess numbers — [Cornell Small Farms: Finding a Farm to Buy or Lease](https://smallfarms.cornell.edu/guide/guide-to-farming/finding-a-farm-to-buy-or-lease/).
- **Hay ground rent formula (Indiana example, July 2025):** Rent is about one-third of total cost. A yield of 2.5 t/acre at $150/t gives about $125/acre. A pasture example based on a cow-calf stocking rate gives about $104/acre — [Purdue: Leasing Pasture and Hay Ground](https://ag.purdue.edu/commercialag/home/resource/2025/07/leasing-pasture-and-hay-ground/).
- **Local land prices:** Dutchess rural land listings have a median of about $17,000–$20,000/acre. Prime open parcels with views ask $25,000–$35,000+/acre — [Main Street Magazine](https://mainstreetmag.com/why-buy-agricultural-real-estate/). These prices are far above the NASS ag values, so ag rents yield well under 0.5% on purchase price.
- **County agriculture profile:** Dutchess's top commodities by acres are hay, beef cattle, horses and corn — [Agricultural State of Dutchess County 2017](https://www.dutchessny.gov/Departments/Planning/Docs/Agricultural-State-of-Dutchess-County-2017.pdf) (STALE).
- **Horse boarding (no Dutchess survey found):**
  - A Poughkeepsie-area directory lists pasture board at $325/month — [newhorse.com](https://www.newhorse.com/page/horseboarding/b.510.g.5309.html?page=6).
  - National guides put pasture board at $150–$450/month and rural full board at $350–$700/month — [PangoVet](https://resources.pangovet.com/pet-lifestyle/horses/cost-to-board-a-horse) and [Horse Racing Sense](https://horseracingsense.com/horse-boarding-costs/).

### Inferences
- For modeling, use these ranges:
  - **Dutchess hay/crop ground:** $40–$60/acre/yr is the base case. Use $75–$125/acre only for high-quality, well-managed hayfields with a motivated local tenant; that upper end comes from the Purdue formula, not a local survey.
  - **Pasture:** $18–$43/acre/yr.
  - Many Hudson Valley "hay for taxes" arrangements bring near-zero cash; the farmer gets the hay and the owner gets the ag assessment. This is common practice but was not sourced here.
- **Horse grazing or boarding:** Self-care pasture board at $300–$500/horse/month is gross income that needs fencing, water, shelter, liability insurance and labor. Its net is uncertain.

### Gaps
- I could not query NASS Quick Stats directly; the API key was refused. The exact Dutchess 2025 and 2026 values should be confirmed at quickstats.nass.usda.gov (Economics > Expenses > Rent, NY, Dutchess).
- I found no Cornell Cooperative Extension Dutchess lease rate survey for 2025–2026.
- I found no irrigated cropland rent for Dutchess; NASS likely does not publish one.
- I did not research NY agricultural assessment rules (the 7-acre / $10,000 gross sales minimum, or rented land qualifying). Another researcher should verify them.

## 2. Long-term rental rates (Pine Plains, Stanfordville, Millerton, Milan, Rhinebeck)

### Takeaway
Single-family and farmhouse rentals in Pine Plains are listed at about **$2,775–$4,000/month for 2–4 bedroom houses** (2025–2026 listings). Furnished or luxury estates are listed higher, around $7,500/month. County-wide average rent is about $2,100–$2,200/month.

### Cited Findings
- **3411 NY-199, Pine Plains:** 3 bedrooms, 2.5 baths, 2,350 sq ft farmhouse-style home at $4,000/month, listed Apr 30, 2026 — [Apartments.com](https://www.apartments.com/3411-ny-199-pine-plains-ny/rwyx581/) and [Coldwell Banker](https://www.coldwellbankerhomes.com/ny/pine-plains/3411-route-199-0/pid_70986807/).
- **1517 Route 83, Pine Plains:** 3 bedrooms, 1 bath, 1,500 sq ft, built 1910, on 9.59 acres, at $3,995/month — [Corcoran](https://corcoran.com/listing/for-rent/1517-route-83-pine-plains-ny-12567/92434601/regionId/106).
- **96 Hammertown Rd, Pine Plains:** 3 bedrooms, 2.5 baths, 1,792 sq ft, at $3,750/month. The listing date is "Dec 11" with no year given — [Corcoran](https://corcoran.com/listing/for-rent/96-hammertown-road-pine-plains-ny-12567/91782198/regionId/106).
- **Other Pine Plains listings:**
  - 82 Lake Rd: 4 bedrooms, 2.5 baths, $3,500/month.
  - 1684 Route 83: 2 bedrooms, 1 bath, $2,775/month.
  - Source: [Homes.com Pine Plains houses for rent](https://www.homes.com/pine-plains-ny/12567/houses-for-rent). The dates of these listings were not confirmed.
- **146 Johnny Cake Hollow Rd:** Furnished yearly rental at $7,500/month, available Oct 2024 (STALE) — [Corcoran](https://corcoran.com/listing/for-rent/146-johnny-cake-hollow-road-pine-plains-ny-12567/89228782/regionId/106).
- **Dutchess County single-family houses (Rentometer, June 2026):** The median is $1,700 for 1 bedroom and $2,300 for 2 bedrooms. A January 2026 snapshot gave $1,900–$2,000 for 1 bedroom, so the two snapshots are inconsistent — [Rentometer Dutchess](https://www.rentometer.com/average-rent-in/county/dutchess-county-ny).
- **Zillow averages:** Zillow lists Dutchess County average rent at about $2,195. Rhinecliff, the closest proxy for Rhinebeck, averages about $2,154. These come from the search snippet with no clear date — [Zillow](https://www.zillow.com/rhinecliff-ny/home-values/).

### Inferences
- For a farmhouse on acreage near Pine Plains, model **$3,000–$4,000/month gross (about $36,000–$48,000/yr)** for a 3-bedroom house.
- An accessory apartment or 1-bedroom cottage would likely rent for about $1,700–$2,200/month, based on the county 1–2 bedroom medians.
- Use a 5–8% vacancy allowance (assumption, not sourced).

### Gaps
- I found no ZORI figure or town-level median rent for Pine Plains, Stanfordville, Millerton or Milan.
- I found no listing data for Rhinebeck or Millerton houses specifically.
- I found no accessory-apartment rent comps.
- Pine Plains zoning rules for accessory dwelling units were not checked.

## 3. Short-term rental performance (Airbnb/VRBO)

### Takeaway
Pine Plains short-term rentals average about **$51,000 gross per year** (AirROI, Nov 2025–Oct 2026), with an ADR of about $483 and occupancy of about 39%. The median listing earns about $3,600/month, or about $43,000/yr. Milan and Rhinebeck do slightly better, at about $58,000–$61,000/yr.

### Cited Findings
- **AirROI, Town of Pine Plains (trailing 12 months, updated Nov 5, 2026):**
  - 27 active listings.
  - Average annual revenue of $51,036.
  - Average ADR of $483; median nightly rate of $375.
  - Occupancy of 38.6%; RevPAR of $171.
  - Average stay of 4 nights; about 27 bookings per listing per year.
  - Source: [AirROI Pine Plains](https://airroi.com/airbnb-data/united-states/new-york/town-of-pine-plains).
- **AirROI monthly revenue percentiles, per listing:**
  - Top 10%: $11,600+.
  - Top 25%: $6,880+.
  - Median: about $3,600.
  - Bottom 25%: $2,060 or less.
- **AirROI occupancy percentiles:** Top 25% reach 58%+ and the median is about 39% — same source.
- **AirROI seasonality:** July 2026 brought $8,900 at 60.8% occupancy. April 2026 brought $3,100 at 29.7% — same source.
- **AirROI nearby markets:**
  - Town of Milan: 33 listings, $60,806/yr, ADR $467, 42% occupancy.
  - Town of Rhinebeck: 47 listings, $57,989/yr, ADR $381, 46% occupancy.
  - Source: same AirROI page.
- **Earlier AirROI figures differ:**
  - An earlier 2026 snapshot showed $38,938/yr, 33.4% occupancy and a $452 ADR.
  - A 2025 report showed a median of $44,674 and 37.3% occupancy across 32 listings.
  - Source: [AirROI report](https://airroi.com/report/world/united-states/new-york/town-of-pine-plains), via search snippets.
- **AirDNA, Pine Plains:** About $35,400 annual revenue, up 3%, with a Market Score of 83. Occupancy was not visible — [AirDNA](https://www.airdna.co/vacation-rental-data/app/us/new-york/pine-plains/overview) (snippet; date unclear).
- **Permits:** AirROI shows 0% of Pine Plains listings displaying a permit number — [AirROI](https://airroi.com/airbnb-data/united-states/new-york/town-of-pine-plains).

### Inferences
- Base-case gross is **$35,000–$51,000/yr** for a typical whole-house short-term rental in Pine Plains. A top-quartile property might reach $80,000+/yr ($6,880 × 12 ≈ $82,000).
- Net income after cleaning, management (20–30%), platform fees, utilities, furnishing and supplies is likely 50–65% of gross. These are industry rule-of-thumb figures, not sourced here.
- The sources differ by up to 45%, so the model should use a range.

### Gaps
- I found no Mashvisor or Rabbu data.
- I found no Stanfordville or Millerton market figures.
- I did not check Pine Plains or Dutchess short-term rental regulations, the NY State short-term rental registry law, or occupancy tax. Another researcher should verify them.

## 4. Solar land leases (NY rates; Dutchess developer activity and interconnection)

### Takeaway
New York solar leases are quoted at **about $1,000–$1,800/acre/yr**. The full range cited by Cornell is $250–$2,500, typically on 20–25 year terms with 1–2.5% escalators. Pine Plains has approved at least one 42-acre Tier 3 farm. It also passed a Tier 3 moratorium in 2023 that was proposed for extension in 2024, and that project faced neighbor litigation. Interconnection on Central Hudson's rural circuits is the binding constraint and needs to be checked parcel by parcel on the hosting capacity map.

### Cited Findings
- **Cornell range:** Lease payments commonly range from $250 to $2,500/acre/yr, citing Cornell Cooperative Extension — [NYSAC: Balancing Renewable Energy Siting and Farmland Protection](https://www.nysac.org/media/iynjhonl/balancing-renewable-energy-siting-and-farmland-protection-in-new-york-state.pdf).
- **Farmer-reported rates (Spectrum News, 2026):**
  - One farmer cited $1,500–$1,800/acre/yr, Jul 23, 2026 — [Spectrum News, solar land use debate](https://spectrumlocalnews.com/nys/buffalo/news/2026/07/23/solar-land-use-debate).
  - Another piece cited $1,000–$1,200/acre, May 7, 2026 — [Spectrum News, Central NY](https://spectrumlocalnews.com/nys/central-ny/news/2026/05/07/solar-expansion-raises-concerns-about-loss-of-agricultural-land).
- **Developer quote:** GreenSpark Solar cites $1,500/acre/yr on 20–25 year leases with 1–2% annual escalators — [GreenSpark Solar](https://greensparksolar.com/land-hosting-opportunities-for-solar-arrays/). The source has a conflict of interest.
- **Aggregator average:** About $863/acre/yr average in NY with a $1,295–$4,315/acre signing bonus — [Smart Energy USA](https://www.smartenergyusa.com/solar-farm-lease/new-york/). This is a marketing site.
- **NYSERDA guidance:** NYSERDA's landowner guide covers lease terms (option period, decommissioning, taxes) but publishes no rate table — [NYSERDA Landowner Considerations for Solar Land Leases (2023)](https://www.nyserda.ny.gov/-/media/Project/Nyserda/Files/Programs/NY-Sun/2023-Landowner-Considerations-for-Solar-Land-Leases.pdf) and [NYSERDA Solar Land Lease Fact Sheet](https://www.nyserda.ny.gov/-/media/Project/Climate/Files/Solar-Land-Lease-Fact-Sheet.pdf).
- **Central Hudson hosting capacity map:** Central Hudson publishes a PV hosting capacity map that it updates on October 1 each year for circuits of 12 kV and above. The map models systems of 300 kW or more on three-phase mainline, and the utility says it does not account for all cost factors, including substation constraints — [Central Hudson Solar PV Hosting Capacity Map](https://www.centralhudson.com/en/my-energy/distributed-generation/solar-pv-hc-map/).
- **Pine Plains moratorium:**
  - Local Law 3 of 2023 imposed an 8-month moratorium on new Tier 3 (large-scale) solar applications — [Town of Pine Plains Local Law 3](https://www.pineplains-ny.gov/wp-content/uploads/2023/06/Local-Law-3-Solar-Moratorium.pdf).
  - A 6-month extension was noticed for a public hearing on Apr 18, 2024 — [Town of Pine Plains](https://www.pineplains-ny.gov/events/extending-a-local-law-no-3-of-2023-which-enacted-an-eight-month-moratorium-on-the-processing-and-approval-of-new-applications-for-tier-3-solar-facilities-for-a-period-of-six-additional-months/).
- **Approved project and lawsuit:**
  - The Planning Board approved Carson Power's 42-acre Tier 3 solar farm at 454 Bean River Road (Pulvers Corners) — [Millerton News](https://millertonnews.com/pine-plains/pine-plains-oks-42-acre-solar-farm).
  - Neighbors filed an Article 78 suit — [Millerton News](https://millertonnews.com/solar-flare-up-residents-sue-pine-plains-over-plans) and [NY Courts 2024 decision](https://www.nycourts.gov/reporter/3dseries/2024/2024_50696.htm).

### Inferences
- For a 200-acre parcel with suitable open land near three-phase lines, a community solar lease of about 20–40 acres at $1,000–$1,500/acre could yield **$20,000–$60,000/yr**. This is upside, not base case: it depends on hosting capacity, the town's Tier 3 rules and local opposition.
- Payments during the option period are typically much smaller than operating rent; this is general industry practice, not sourced here.
- Solar on ag land can trigger ag-assessment rollback penalties; this needs verification.

### Gaps
- I could not confirm the current (2026) status of the Pine Plains moratorium or the Tier 3 solar law.
- I found no Dutchess-specific lease rate quotes.
- Hosting capacity on the Pine Plains circuits was not read from the interactive map.
- I did not check whether NYSEG serves parts of Pine Plains.
- I did not check the 2025–2026 status of the NY-Sun incentive block or community solar program in the Central Hudson territory.

## 5. Hunting leases, timber, events and agritourism

### Takeaway
These are minor or episodic income streams. Hunting leases likely bring **$10–$50/acre/yr**, with Northeast rates toward the high end; no Hudson Valley survey exists. Timber gives a periodic lump sum, and I found no verifiable 2025–2026 southeastern NY stumpage prices. Hudson Valley barn venues advertise site fees of **$5,500–$16,500 per event**, but running one is a business requiring permits, not passive land income.

### Cited Findings
- **Hunting lease rates:**
  - National guides put hunting leases at $10–$50/acre, with the Northeast the most expensive region and some leases at $50/acre or more — [HuntingLocator: Regional Hunting Lease Costs](https://huntinglocator.com/blog/regional-hunting-lease-costs/).
  - A national survey average was $9.97/acre on 934-acre leases — [LandThink](https://www.landthink.com/pulse-land-owners-and-hunters-cant-be-far-apart-on-lease-prices/).
  - Pennsylvania averages $15–$20/acre (May 2024) — [Bradford Era](https://bradfordera.com/2024/05/11/thousands-of-forest-acres-gobbled-up-for-hunting-leases).
- **NY hunting listings:** Example leases exist in Steuben and Sullivan counties — [HLRBO Sullivan County 550 acres](https://www.hlrbo.com/listing/index/59232). The prices were not captured.
- **NY timber stumpage data:**
  - The NYS Office of Real Property Tax Services publishes 2026 forest stumpage values by region (page updated Apr 28, 2026). Values for Regions 6 and 7 are historical, with new values due for the 2027 roll year — [NYS Tax: Stumpage](https://www.tax.ny.gov/research/property/assess/stumpage.htm). Species values for the Dutchess region could not be extracted.
  - NYSDEC publishes a semi-annual Stumpage Price Report. Recent PDFs exist but were not read — [DEC Oct 2026 PDF](https://dec.ny.gov/sites/default/files/2026-10/tx000079.pdf) and [DEC Nov 2026 PDF](https://dec.ny.gov/sites/default/files/2026-11/tsx0000076.pdf).
  - A third-party estimate gives a regional range of $32–$300/MBF for NY in Q4 2025. Its methodology is unverified, and NY uses three log rules across four regions — [The Timberland Investor](https://thetimberlandinvestor.com/new-york-timber-stumpage-prices/).
- **Dutchess event venues:**
  - The Preston Barn at Old Drovers Inn (Dover Plains) charges $7,500 (Dec–Mar), $8,500 (Jul/Aug/Nov/Apr) and $13,500 (May/Jun/Sep/Oct). There is a $3,000 kitchen buyout fee for bring-your-own catering — [Here Comes The Guide](https://www.herecomestheguide.com/wedding-venues/new-york/the-preston-barn-at-old-drovers-inn).
  - Mount Gulian (Beacon) charges $5,500 per event for up to 140 guests and 5 hours, plus $500/hour beyond that — [Here Comes The Guide](https://www.herecomestheguide.com/wedding-venues/new-york/mount-gulian-historic-site).
- **Other Hudson Valley farm venues:**
  - The Barn at Black Walnut Farm (Saugerties): $13,500–$16,500 per event plus a required farmhouse stay — [Here Comes The Guide](https://www.herecomestheguide.com/wedding-venues/new-york/the-barn-at-black-walnut-farm).
  - West Song Farm (Orange County): $5,000–$10,000 per event — [Here Comes The Guide](https://www.herecomestheguide.com/wedding-venues/new-york/west-song-farm).
  - Blooming Hill Farm (Monroe): $12,000 per event — [Here Comes The Guide](https://www.herecomestheguide.com/wedding-venues/new-york/blooming-hill-farm).

### Inferences
- **Hunting:** On 50–150 wooded or brushy acres, a lease might bring $1,000–$5,000/yr. Use the low end, because Dutchess parcels are small and fragmented and hunters often get access informally.
- **Timber:** A selective harvest on a managed hardwood woodlot is a one-time payment every 15–20 years (assumption). Annualized, it is probably under $100/acre/yr, so the breakeven model should treat it as optional upside.
- **Events:** A modest venue hosting 10–20 events/yr at $5,000–$10,000 could gross $50,000–$200,000. It would need a site plan or special use permit, parking, septic, insurance and staff, so it is an operating business, not a land-holding offset.

### Gaps
- I found no Hudson Valley hunting lease survey.
- I could not extract species-level stumpage values ($/MBF for red oak, sugar maple or white pine) for the Dutchess region. The DEC PDFs listed above should be read.
- I found no Cornell or USDA data on agritourism income for Dutchess (the Census of Agriculture "agritourism receipts" figure was not retrieved).
- I did not check Pine Plains zoning rules for event venues or the NY agritourism / Right-to-Farm protections.
