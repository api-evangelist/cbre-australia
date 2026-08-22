# CBRE Australia (cbre-australia)

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

CBRE Australia is the Australian arm of CBRE Group, the global commercial real estate services and investment firm, trading locally as CBRE (Gwsla) Pty Ltd (AU09949) and operating across the Pacific from cbre.com.au. It sits on the advisory and management side of the Australian property value chain rather than the data-infrastructure side: capital markets and investment sales, leasing and occupier advisory, valuation and advisory services, property and asset management, and project and design-and-build delivery across office, retail, industrial and logistics, build-to-rent, and alternative asset classes.

Its API posture is closed. As of 26 July 2026 no public developer portal, API documentation, machine-readable contract, or self-serve onboarding exists for CBRE Australia. `developer.cbre.com.au`, `developers.cbre.com.au`, `api.cbre.com.au`, and `docs.cbre.com.au` do not resolve, and the global `developer.cbre.com` host is NXDOMAIN as well. CBRE does run API infrastructure — `api.cbre.com` sits behind an Imperva WAF that returns 403 to every anonymous request, `api-dev.cbre.com` serves a default WSO2 API Manager landing page, and `eipportal.cbre.com` is a login-gated "Integration Platform" SPA — but none of it is published, catalogued, or reachable by an outside developer.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cbre-australia/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cbre-australia/refs/heads/main/apis.yml)

## Tags

- Real Estate
- Australia
- Commercial Real Estate
- Property Listings
- Valuation
- Property Management
- Capital Markets
- PropTech
- Leasing

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

None. CBRE Australia publishes no documented public API. Zero APIs are listed here deliberately — see [review.yml](review.yml) for every URL probed and the HTTP status returned.

## RESO Posture

**No RESO reference found. `reso_certified: false`.**

RESO Web API and RESO Data Dictionary certification are artifacts of the North American MLS system, mandated by NAR — an industry body, not a government — and only meaningful where an MLS exists. Australia has no MLS.

The public RESO Certification Status listing at [reso.org/certificates](https://www.reso.org/certificates/) was fetched on 2026-07-26 (HTTP 200, 416,233 bytes) and contains no occurrence of "CBRE" and no occurrence of "Australia". [reso.org/certification](https://www.reso.org/certification/) (HTTP 200) confirms the certification programme covers MLS systems in the United States, Canada, and a small number of other regions; Australia is not among them. The RESO Analytics directory app at `certification.reso.org` returned HTTP 400 to anonymous requests.

No `$metadata`, OData service document, or `Reso` path was found on any CBRE host. `https://www.cbre.com.au/$metadata` returns HTTP 404; `https://api.cbre.com/$metadata` returns an Imperva 403.

This is the important negative result for the sector study: CBRE Australia is not a *certified-but-closed* provider. It is simply closed, with no standards posture at all.

## Access Gate

**`none-published`.**

There is no developer registration, no API application form, no key request, no partner API programme page, and no data licence offered to developers anywhere on cbre.com.au. Access to CBRE data in Australia is a commercial client or partner engagement negotiated offline, not a developer signup.

CBRE's [Terms of Use](https://www.cbre.com/about-us/disclaimer-terms-of-use) explicitly prohibit "spidering, screen scraping, database scraping, or any other activity with the purpose of obtaining lists of users or any other information, including specifically, property listings available through the site." The phrase "application programming interface" does not appear in the Terms of Use at all. `robots.txt` carries `Disallow: /api`, marking the internal Sitecore path as closed.

## Open Data

**None.** CBRE Australia publishes no open, unlicensed, publicly callable dataset. The Australian open-data counterweight in property sits with government — state land registries and data.gov.au — not with CBRE.

## Auth Model

**None published.** `https://api.cbre.com/.well-known/openid-configuration` returns an Imperva 403 to anonymous requests; `https://api-dev.cbre.com/.well-known/openid-configuration` returns a WSO2 404. No OIDC discovery document, token endpoint, or documented scheme is served anonymously. Any real scheme is internal to CBRE and its contracted partners.

## Webhooks, Events, SDKs, Postman

None found — and the absence is the finding. `github.com/CBRE` has 0 public repositories; so do `cbreapac` (the Asia-Pacific org that would cover Australia), `cbreenterprise`, `CBRE-Shared-Code`, `cbre360`, `CBRE-DevOps`, and `CBREDigitalSpain`. `cbreemea` has 2 public repos, both forks of the third-party `oauth2_proxy` project.

## Service Family

Taken verbatim from the live cbre.com.au navigation. None of these are exposed as APIs; they are recorded so the sector study can see what a machine-readable surface would have covered.

- [Invest, Finance & Value](https://www.cbre.com.au/services/invest-finance-and-value)
- [Plan, Lease & Occupy](https://www.cbre.com.au/services/plan-lease-and-occupy)
- [Design & Build](https://www.cbre.com.au/services/design-and-build)
- [Manage Properties & Portfolios](https://www.cbre.com.au/services/manage-properties-and-portfolios)
- [Transform Business Outcomes](https://www.cbre.com.au/services/transform-business-outcomes)

Property types: Office, Retail, Industrial & Logistics, Build to Rent, Alternatives. Listings surface: [Search CBRE's Commercial Property Listings](https://www.cbre.com.au/properties) — an HTML search UI, no feed and no documented query interface.

## Common Properties

- [Website](https://www.cbre.com.au/)
- [About](https://www.cbre.com.au/about-us)
- [Services](https://www.cbre.com.au/services)
- [Property Search](https://www.cbre.com.au/properties)
- [Terms of Service](https://www.cbre.com/about-us/disclaimer-terms-of-use)
- [Pacific Privacy Notice](https://www.cbre.com.au/about-us/pacific-privacy-notice)
- [Protecting Your Data at CBRE](https://www.cbre.com.au/about-us/protecting-your-data-at-cbre)
- [Responsible AI at CBRE](https://www.cbre.com.au/about-us/responsible-ai-at-cbre)
- [Newsroom](https://www.cbre.com.au/about-us/newsroom)
- [Investor Relations](https://ir.cbre.com/investor-relations-home/default.aspx)
- [LinkedIn](https://www.linkedin.com/company/cbre-asia-pacific)
- [GitHub Organization](https://github.com/CBRE)
- [Review](review.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
