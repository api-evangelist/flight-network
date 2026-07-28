# Flight Network (flight-network)

Flight Network (Flight Network Ltd, 145 King St. West Suite 2850, Toronto, Ontario, TICO Registration #50009248) is a Canadian online travel agency founded in 2005 and owned by Sweden's Etraveli Group since 2019. It retails flights plus hotels and car rentals to consumers across 75+ markets in 35 languages, sourcing air content through the GDSs — its own About Us page carries the Amadeus and Sabre marks and claims "IATA Certified Travel Agents" — and reaching buyers through its own sites, its iOS/Android apps, metasearch deep links from Skyscanner and Kayak, and third-party affiliate networks. It sits in the distribution chain as a retailer downstream of the GDSs and of its Etraveli sibling TripStack (the group's B2B LCC/NDC/virtual-interlining API), not as a content owner. Its API posture is honest and thin: no developer portal, no published API documentation, no machine-readable specification, and no exit path.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flight-network/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flight-network/refs/heads/main/apis.yml)

## Tags

- Travel
- Canada
- Aviation
- Airline
- OTA
- Booking
- Distribution
- Flights
- Hotels
- Car Rental
- GDS

## Timestamps

- **Created:** 2026-07-28
- **Modified:** 2026-07-28

## APIs

None. Flight Network publishes no developer portal, no API documentation, and no machine-readable API specification.

Every candidate developer host is NXDOMAIN — `developer.`, `developers.`, `docs.`, `api.`, `partner.`, `partners.`, `affiliate.`, `affiliates.`, `b2b.`, `apidocs.`, `sandbox.`, `connect.`, `agent.`, `portal.`, `seller.` and `travelseller.flightnetwork.com`. On the reachable Canadian host, `/openapi.json`, `/swagger.json`, `/api-docs`, `/api` and `/api/v1` all return 404, and `/graphql` returns an Akamai "Request Rejected" interstitial rather than a schema. The 439-URL sitemap contains no developer, partner, affiliate or API page.

See [review.yml](review.yml) for the full probe record and the switching-cost analysis.

## Switching Cost

| Dimension | Finding |
| --- | --- |
| Interface shape | `none-published` — no open standard, no proprietary contract, nothing |
| Second source | `interchangeable-alternatives` — Gotogate, Mytrip, Expedia.ca, Booking.com, or the carriers direct |
| Exit path | `no-export-published` — single-booking web lookup only |
| Identifier portability | IATA airport codes and airline PNR (portable); Flight Network order number and AgencyID (not) |
| Contractual lock-in | Consumer booking terms only; no partner or API agreement published |
| Access gate | `none-published` — nothing to sign, because nothing is offered |
| Distribution model | `gds-intermediated` — Amadeus and Sabre upstream, Skyscanner/Kayak metasearch downstream |
| NDC posture | Not applicable — not an airline; NDC reaches the group via sibling TripStack |

## Properties

- [Website](https://www.flightnetwork.com/)
- [Flight Network Canada](https://ca.flightnetwork.com/)
- [About](https://ca.flightnetwork.com/c/about-us)
- [Travel Conditions](https://ca.flightnetwork.com/rf/travel-conditions)
- [Privacy Policy](https://ca.flightnetwork.com/rf/privacy-policy)
- [security.txt](https://ca.flightnetwork.com/.well-known/security.txt)
- [robots.txt](https://ca.flightnetwork.com/robots.txt)
- [Sitemap](https://ca.flightnetwork.com/sitemap.xml)
- [FAQ](https://ca.flightnetwork.com/c/faq)
- [Airline Information](https://ca.flightnetwork.com/rf/carriers)
- [LinkedIn](https://www.linkedin.com/company/flight-network)
- [Etraveli Group (parent)](https://www.etraveligroup.com/)
- [TripStack (sibling B2B flight API)](https://www.tripstack.com/)

## Maintainers

- Kin Lane — kin@apievangelist.com
