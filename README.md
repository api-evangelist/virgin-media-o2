# Virgin Media O2 (virgin-media-o2)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Virgin Media O2 is the United Kingdom's converged fixed and mobile network operator, formed in 2021 as a 50/50 joint venture between Telefonica and Liberty Global by merging Virgin Media's cable broadband business with O2 UK's mobile network. It serves roughly half the UK population across mobile, broadband, and fixed wholesale, and sits at the connectivity layer of the telecom value chain rather than the developer-tools layer. Its API posture is partner-gated and sales-led: probing `developer.virginmediao2.co.uk`, `developers.virginmediao2.co.uk`, `docs.virginmediao2.co.uk`, `api.virginmediao2.co.uk`, `opengateway.virginmediao2.co.uk`, `developer.o2.co.uk` and the `virginmediao2business.co.uk` equivalents returns DNS failure or HTTP 404 in every case, and neither the o2.co.uk sitemap nor the corporate site contains a developer or API section. Virgin Media O2 is a GSMA Open Gateway participant and on 23 September 2025 joined BT/EE, Vodafone and CK Hutchison (Three UK) in the commercial UK launch of CAMARA-standardised KYC Age Verification and KYC Tenure APIs, with SIM Swap already live and KYC Match committed; but developers reach that network-API surface only through third-party aggregators such as JT Group and TMT.ID, never through a Virgin Media O2 portal. There is no public self-serve signup, no downloadable OpenAPI, no sandbox, and no first-party SDK. Its GitHub organisation exists and is empty.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/virgin-media-o2/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/virgin-media-o2/refs/heads/main/apis.yml)

## Tags

- Telecommunications
- United Kingdom
- Mobile Network Operator
- Broadband
- Network APIs
- CAMARA
- Open Gateway
- Identity Verification
- SIM Swap
- Age Verification
- Converged Operator
- Partner Gated

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

Virgin Media O2 publishes no public API documentation, no API reference, and no OpenAPI of its own. Every candidate developer host was probed on 2026-07-25 and recorded in [review.yml](review.yml) — `api.o2.co.uk` resolves but returns HTTP 500 for `/openapi.json`, `/swagger.json`, `/api-docs` and `/docs`.

The one callable, self-describing API Virgin Media O2 serves on a host it controls is the newsroom's WordPress REST API at [news.virginmediao2.co.uk/wp-json/](https://news.virginmediao2.co.uk/wp-json/) — 253 routes, anonymous reads, with a draft-04 JSON Schema per collection. It is a press-content API, not a product or network API, and it is catalogued as such.

## Artifacts

| Artifact | File | Method |
| --- | --- | --- |
| JSON Schema (5 newsroom objects) | [json-schema/](json-schema/_index.yml) | searched — served verbatim by news.virginmediao2.co.uk |
| WordPress REST route index | [well-known/virgin-media-o2-newsroom-wp-json-index.json](well-known/virgin-media-o2-newsroom-wp-json-index.json) | searched |
| Well-known probe record | [well-known/virgin-media-o2-well-known.yml](well-known/virgin-media-o2-well-known.yml) | searched — no security.txt, OIDC, OAuth metadata or api-catalog on any host |
| Conformance | [conformance/virgin-media-o2-conformance.yml](conformance/virgin-media-o2-conformance.yml) | searched |
| Lifecycle | [lifecycle/virgin-media-o2-lifecycle.yml](lifecycle/virgin-media-o2-lifecycle.yml) | searched |
| Domain security | [security/virgin-media-o2-domain-security.yml](security/virgin-media-o2-domain-security.yml) | probed |
| llms.txt | [llms/virgin-media-o2-llms.txt](llms/virgin-media-o2-llms.txt) | generated |

No packages, MCP server, sandbox, CLI, changelog, conventions, error catalog, agent skills, or Arazzo workflows are recorded — there is no first-party API surface to ground them in, and none were fabricated.

**Security posture:** Virgin Media O2 publishes a versioned, public [Security Schedule](https://news.virginmediao2.co.uk/wp-content/uploads/2026/01/Virgin-Media-O2-Security-Schedule-Version-7.0-Jan-2026.pdf) (v8.0, July 2026) setting the minimum security standards its suppliers must meet — ISO/IEC 27001, Cyber Essentials, PCI DSS, Sarbanes-Oxley, the UK NIS Regulations 2018, the Telecommunications (Security) Act, CVSS v3.x remediation bands, and a required supplier vulnerability disclosure policy. Virgin Media O2 requires a VDP of its suppliers while publishing no `security.txt` or disclosure page of its own, and no trust center or certificate listing was found.

## CAMARA and GSMA Open Gateway

Virgin Media O2 is a GSMA Open Gateway participant with a real commercial CAMARA launch behind it — this is not a press release with nothing callable. What is missing is the developer channel, not the capability.

| CAMARA API | Status | Evidence |
| --- | --- | --- |
| KYC Age Verification | Commercially launched in the UK, 2025-09-23 | GSMA / PR Newswire joint operator announcement naming Virgin Media O2 |
| KYC Tenure | Commercially launched in the UK, 2025-09-23 | GSMA / PR Newswire joint operator announcement naming Virgin Media O2 |
| SIM Swap | Already available across the four UK operators before the 2025-09-23 launch | Telefonica Open Gateway UK article naming Virgin Media O2 |
| KYC Match | Committed for end-2025; nothing callable found | GSMA / PR Newswire joint operator announcement |

No evidence was found for Number Verification, Device Location, Device Status, Quality on Demand, Carrier Billing, Scam Signal, Device Swap, or Population Density.

**How developers actually reach it:** through aggregators. The joint UK launch names Jersey Telecom (JT Group) and TMT.ID as the partners already processing hundreds of thousands of network API calls a month against the UK operators. Shareholder Telefonica runs its own Open Gateway developer portal at [developers.opengateway.telefonica.com](https://developers.opengateway.telefonica.com/) — a real self-serve surface, but Telefonica's, covering Telefonica's own footprint rather than the UK network.

## Other findings

- **TM Forum:** no Open API conformance certification found listed for Virgin Media O2.
- **3GPP:** no public NEF/SCEF surface, no network-slicing API, no edge/MEC API.
- **Auth:** not published. CAMARA specifies OIDC and CIBA, but no Virgin Media O2 artifact states it, and no `/.well-known/openid-configuration` is served.
- **Webhooks / AsyncAPI:** none published.
- **SDKs / GitHub:** [github.com/VirginMediaO2](https://github.com/VirginMediaO2) exists with 0 public repositories; a second empty org, `Virgin-Media-O2`, also exists. No first-party packages on npm, PyPI, Maven, or NuGet.
- **Wholesale:** Virgin Media Business Wholesale surfaces serviceability and quoting to partners through Connectbase, a third-party API-driven platform — again a partner channel, not a Virgin Media O2 developer surface.

## Links

- [Virgin Media O2](https://www.virginmediao2.co.uk/)
- [Virgin Media O2 Business](https://www.virginmediao2business.co.uk/)
- [O2 UK](https://www.o2.co.uk/)
- [Newsroom](https://news.virginmediao2.co.uk/news-views/)
- [GitHub](https://github.com/VirginMediaO2)
- [LinkedIn](https://www.linkedin.com/company/virgin-media-o2)
- [Review](review.yml)
