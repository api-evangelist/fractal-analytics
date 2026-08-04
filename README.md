# Fractal Analytics

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

Fractal Analytics Limited (fractal.ai) is an enterprise artificial intelligence services and
products company founded in 2000, headquartered in New York with a large delivery footprint in
India and roughly 5,000 employees across 18 global locations. Fractal sells AI consulting, data
engineering, decision-science and design services to Fortune 500 clients in consumer packaged
goods, retail, healthcare and life sciences, technology/media/telecom, financial services,
insurance and industrials, and builds products on top of that practice — most notably Cogentiq,
its enterprise agentic AI platform, plus LLM Studio and brands including Flyfish, Asper.ai,
Kalaido.ai, Vaidya.ai and iqigai. The company listed on the NSE and BSE under the symbol FRACTAL
in February 2026.

**No public API surface.** As of the 2026-08-04 enrichment pass, Fractal publishes no developer
portal, no API reference, and no machine-readable contract (no OpenAPI/Swagger, AsyncAPI, GraphQL
SDL, hosted MCP server, or A2A agent card) reachable anonymously on any Fractal-controlled host.
API access is delivered inside client engagements and gated product tenants — the Cogentiq tenant
host `cogentiq.fractal.ai` answers `502` from its Azure Application Gateway to anonymous requests,
and every `/.well-known/*` path on `fractal.ai` returns `404`. See
[`well-known/fractal-analytics-well-known.yml`](well-known/fractal-analytics-well-known.yml) for
the probe record.

- https://fractal.ai/
- https://fractal.ai/products/cogentiq/
