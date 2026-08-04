# Sharethrough

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

Sharethrough is a human-centric programmatic advertising platform and one of the largest independent omnichannel ad exchanges worldwide. The platform provides REST APIs and OpenRTB integrations for publishers and advertisers to manage native, display, and video ad placements through SSP/DSP integrations, header bidding via Prebid.js, and programmatic reporting. Sharethrough is Scope3 Climate Shield certified and an Ad Net Zero member, offering sustainability-focused media buying tools including a Carbon Emissions Estimator.

- **Website**: https://www.sharethrough.com
- **Support**: https://support.sharethrough.com/hc/en-us
- **Blog**: https://www.sharethrough.com/blog
- **GitHub**: https://github.com/sharethrough
- **LinkedIn**: https://www.linkedin.com/company/sharethrough
- **X**: https://x.com/sharethrough

## APIs

### Publisher Reporting API
REST API for publishers to retrieve programmatic and direct sell reporting data. Uses token-based authentication (AUTH_TOKEN). Supports CSV and JSON output formats.

- **Documentation**: https://support.sharethrough.com/hc/en-us/articles/360044449471-Sharethrough-Publisher-API-Documentation
- **Examples**: https://github.com/sharethrough/publisher-api-examples

### Header Bidding / OpenRTB Bidding API
OpenRTB 2.3+ compliant bidder adapter for SSP/DSP integrations via Prebid.js. Supports native, display, and video formats. Requires setup approval from the Sharethrough Integrations team.

- **Documentation**: https://docs.prebid.org/dev-docs/bidders/sharethrough.html
- **GitHub**: https://github.com/sharethrough/Prebid.js-inventory-growth

## Resources

- [Plans and Pricing](plans/sharethrough-plans-pricing.yml)
- [Rate Limits](rate-limits/sharethrough-rate-limits.yml)
- [FinOps](finops/sharethrough-finops.yml)
