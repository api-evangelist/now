# DNOW (now)

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

Profile for DNOW Inc. (formerly NOW Inc., operating as DistributionNOW) in the API Evangelist network. Fortune F1000 (rank 792). NYSE: DNOW.

DNOW is a Houston-headquartered global distributor of pipe, valves, fittings (PVF), pumps, and packaged, engineered process and production equipment serving the upstream, midstream, downstream energy, and industrial sectors. The company was spun off from National Oilwell Varco in 2014 and operates with a heritage that spans more than 160 years.

## Product and Digital Lines

DNOW's customer-facing digital surface is delivered under the **DigitalNOW** umbrella:

- **DigitalNOW B2B eCommerce** ([shop.dnow.com](https://shop.dnow.com/)) — Contract-priced eCatalog covering more than 160,000 SKUs, real-time inventory, online ordering, custom approval workflows, order status and history, invoicing, and shipment notifications.
- **DigitalNOW ERP Punchout (cXML / OCI)** — Customer ERP and procurement systems (SAP, Oracle, Ariba, Coupa, SciQuest-class) punch out to shop.dnow.com using cXML or OCI, with automated PO creation, approvals, invoicing, and shipment notifications routed back into the ERP.
- **eSpec Product Configurator** — Web-based configurator for engineered equipment packages that produces 3D drawings and priced technical proposals.
- **AccessNOW Automated Inventory Control** — 24/7 secured tool-crib / stockroom access via badge, keypad, or facial recognition with barcode/RFID transactions and cloud-based monitoring.
- **DNOW Mobile App Library** — Customer-facing iOS / Android apps that sync with shop.dnow.com for carts, order status, history, favorites, reference content, and branch locators.

Core distribution categories include PVF, pumps and packaged process equipment, drilling and completions, artificial lift, electrical, instrumentation and measurement, air compressors and blowers, paint and coatings, safety and PPE, tools, and industrial / facilities supplies. Services include supply chain and material management, engineering, design and fabrication, valve actuation and automation, and safety services.

## APIs

DNOW does **not** publish a public developer portal, OpenAPI specifications, SDKs, CLI, webhooks, sandbox environment, or rate-limited API plans. Programmatic customer integration is delivered through configured **cXML / OCI punchout / roundtrip** sessions tied to enterprise ERP and procurement systems, set up per customer by the DNOW account team. There is no public `github.com/dnow` or `github.com/distributionnow` organization hosting SDKs or API clients.

This profile therefore catalogs the DigitalNOW surfaces as digital integration capabilities rather than as public REST APIs, and intentionally does not contain `openapi/`, `capabilities/`, `rules/`, or other artifact folders, per the network's "no placeholder specs" rule.

## Notable 2025 Event

On **June 26, 2025**, DNOW and MRC Global jointly announced a definitive all-stock merger agreement valued at approximately **$1.5 billion**, under which DNOW will acquire MRC Global. Once the merger closes, MRC Global's PVF distribution footprint and digital surfaces are expected to be combined with DNOW's DigitalNOW platform; this profile may need to be re-run to incorporate the combined company.

## Files

- [`apis.yml`](apis.yml) — APIs.json index documenting DNOW's DigitalNOW surfaces, ERP integrations, IoT inventory, and notable absences.

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23
