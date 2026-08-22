# Flight Network (flight-network)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

## Agent surface

Flight Network has no API, but it does publish a real, substantial [`llms.txt`](llms/flight-network-llms.txt) at the site root (harvested verbatim, ~25 KB, self-dated June 2026). It is not a developer document — it is a distribution and conduct policy addressed to AI systems: a map of ~80 regional domains with language logic, the flight/ancillary product catalogue (virtual interlining, self-transfer, Flexible Ticket, Cancellation Guarantee, Fast Track, AirHelp), the Booking.com referral boundary for Stays and Cars, a support-escalation hierarchy with expected response times, and explicit DO/DON'T rules (no invented promo codes, no refund promises, no PII collection, no real-time inventory claims, no impersonation). The result is a company that is addressable by agents as a referral target while remaining entirely uncallable. That posture is captured in [agentic-access/flight-network-agentic-access.yml](agentic-access/flight-network-agentic-access.yml).

## Artifacts

| Artifact | File | Method |
| --- | --- | --- |
| llms.txt | [llms/flight-network-llms.txt](llms/flight-network-llms.txt) | searched (verbatim) |
| Well-known index | [well-known/flight-network-well-known.yml](well-known/flight-network-well-known.yml) | searched |
| security.txt | [well-known/flight-network-security.txt](well-known/flight-network-security.txt) | searched (verbatim) |
| Apple app-site-association | [well-known/flight-network-apple-app-site-association.json](well-known/flight-network-apple-app-site-association.json) | searched (verbatim) |
| Android assetlinks | [well-known/flight-network-assetlinks.json](well-known/flight-network-assetlinks.json) | searched (verbatim) |
| Agentic access | [agentic-access/flight-network-agentic-access.yml](agentic-access/flight-network-agentic-access.yml) | searched |
| Conformance | [conformance/flight-network-conformance.yml](conformance/flight-network-conformance.yml) | derived |
| Vulnerability disclosure | [security/flight-network-vulnerability-disclosure.yml](security/flight-network-vulnerability-disclosure.yml) | searched |
| Domain security | [security/flight-network-domain-security.yml](security/flight-network-domain-security.yml) | probed |

No `openapi/`, `asyncapi/`, `mcp/`, `skills/`, `packages/`, `scopes/`, `authentication/`, `conventions/`, `errors/`, `sandbox/`, `cli/` or `changelog/` artifacts exist, because none of the things they describe are published. npm, PyPI, RubyGems and crates.io return nothing first-party; [github.com/FlightNetwork](https://github.com/FlightNetwork) is a real but dormant org holding two forks and no SDK.

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
