# walkintubsflorida.com · MASTER GAMEPLAN
Last updated 2026-11-08 (overnight aging-network push). Network plan: Desktop\02 AGING SAFELY BATHS\07 Aging Safely Website Network\MASTER GAMEPLAN.md. Rules: C:\Users\zachw\aging-sweep\notes\RULES.md.

## Lane
Florida: metros, SHIP by county, paying, hurricane/humidity, hard water, contractor license.

Every page here supports agingsafelybaths.com (quotes, installs) and never targets its head terms (walk in tubs, walk in tub cost, handicap showers, roll in showers, Medicaid/grants head terms). Max 2 followed network links per page; other network links nofollow; one nofollow Eye To Ad credit.

## Business facts
Aging Safely Baths & More, LLC. 1-888-779-2284, sales@agingsafelybaths.com. BBB A+ since 2012. Published prices only (RULES.md): walk-in tub about $15,500 installed after the $2,000 promo, $15,250 veterans, roll-in showers $13,500 to $17,000, wide/transfer/bariatric from about $19,000.

## Targets (one page owns one term)
- walk in tubs florida
- walk in tub cost florida
- walk in tubs orlando / tampa / the villages

## Competitors (live check 2026-11-08; search results, not verified rank)
- retirementliving.com Tampa: itemizes plumbing $4,000 to $6,000 and electrical $1,300 to $3,000
- consumeraffairs.com Florida: brand rankings
- sponsored lead-gen content

**How we beat them:** Clear tub-only vs installed vs add-on pricing, county-level program data, SMMC LTC steps.

## Done tonight (2026-11-08)
- Quote forms now post to the company lead server (clients.eyetoad.com/lead/send.php, saves to disk first, then emails sales) through /lead-send.js, with the old sender (FormSubmit or EmailJS) as automatic fallback. Pilot verified in a live browser on walkintubsflorida.com.
- GA4 tag (property per site, events generate_lead, phone_click, estimator_use) confirmed on every indexable page; Search Console verification file googleadb17462a109b3ca.html present.
- Lighthouse (home page, live, 2026-11-08 early morning) recorded before and after in _overnight-reports/aging-sites-report.md.
- Pilot site for the lead router (live browser test passed).
- New /florida-medicaid-smmc-ltc-bathroom-modifications/ (see report for status).

## Next
1. Florida SMMC Long-Term Care home accessibility adaptation (AHCA/CARES)
1. Condo/HOA approval for walk-in tubs only with Florida Statutes ch. 718 text
1. Hurricane-season page refresh after Nov 30

## Morning to-dos (network)
- Add the six EmailJS satellites (seniorwalkintub, utahwalkintubs, walkintubdenver, walkintubscalifornia, walkintubschicago, walkintubstexas) to lead-config.php on clients.eyetoad.com so they stop falling back to EmailJS.
- Confirm where aging-site leads from the lead server are emailed (sales@agingsafelybaths.com?) and that the mail lands; fix eyetoad.com SPF/DMARC.
- Request indexing in Search Console for every new or changed URL listed in the report.
- AdSense: not added to these lead-gen pages on purpose (ads next to a quote form cost leads). Decide if any info-only page should carry it.

## Measurement
GA4 property per site (account 45765285), key events generate_lead and phone_click. Search Console: bare domain property, sitemap.xml submitted. Check queries and positions in GA4's Search Console report at the start of every project.

## 2026-11-10 (overnight, branch seo-leads-2026-11-10, not pushed)
Based on GSC Oct 25 to Nov 8: walk in tubs orlando 33 impr pos 14.9, tallahassee 11 / 12.6 (no page existed), west palm beach 14 / 17.4, almost no clicks.
- /walk-in-tubs-orlando/: new title/meta for CTR; new "what we checked" section: HB 803 $7,500 exemption excludes plumbing/electrical (City of Orlando guide), Notice of Commencement over $5,000, OUC water 7 gpg (Lower Floridan, ozone), ACS 2024 median year built 1995, Senior Resource Alliance (407) 514-1800; permit FAQ added (visible + schema).
- /walk-in-tubs-west-palm-beach/: new title/meta; section with WPB Permits FAQ (HB 803, flood-zone exclusion, Civic Access, owner-builder rules, condo flooring permit), 2025 water report (Grassy Waters surface water, TDS 243 ppm, no hardness published, utility 561-822-2222), ACS median 1988, AAA PBTC 561-684-5885; permit FAQ added.
- NEW /walk-in-tubs-tallahassee/: city vs Leon County permits (portal, phones, county veteran fee waiver), city water ~9 gpg, ACS housing age, Advantage Aging Solutions, city Housing Division and Leon County repair program. Linked from blog cities grid + ItemList, home Panhandle region, AAA table; sitemap + llms.txt.
- All sources opened Nov 10, 2026 and listed on-page. Census API now needs a key; ACS figures came from data.census.gov tables (ACSDT1Y2024 B25034/B25035).
Next: request indexing for the three URLs; recheck CTR on these pages in 3-4 weeks; condo/HOA ch. 718 page still open.
