# Trust Payments (trust-payments)

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

Trust Payments is a London-headquartered payment gateway and processor (formerly Secure Trading / SecureTrading) operating across the United Kingdom, Europe, and the United States. It provides online, point-of-sale, unattended, and mobile card acceptance, acquiring, alternative and local payment methods, tokenisation, recurring billing, payouts, and 3-D Secure authentication through its TRU Connect gateway.

Its developer surface is the Secure Trading Payment Platform (STPP): a server-to-server JSON Webservices API, a JWT-authenticated client-side JavaScript Library for PCI-reduced hosted card fields, and mobile SDKs. Documentation is published as reference articles in the Trust Payments help centre, with Python, PHP, ReactJS, and Swift libraries under the SecureTrading GitHub organisation. Trust Payments does not publish a downloadable OpenAPI/Swagger definition, and production Webservices access requires PCI certification, account approval, and credential exchange.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trust-payments/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trust-payments/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- Tokenization
- Subscriptions
- 3-D Secure
- Point of Sale

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Trust Payments Webservices API

Server-to-server JSON API (the Secure Trading Payment Platform / STPP) for card processing and management on the TRU Connect gateway. Supports request types including AUTH, ACCOUNTCHECK, REFUND, SUBSCRIPTION, TRANSACTIONUPDATE, and TRANSACTIONQUERY. Authenticated with a Webservices API alias (username) and password scoped to a site reference.

- **Human URL:** [https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API](https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API)
- **Base URL:** `https://webservices.securetrading.net/json/`

#### Properties

- [Documentation](https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API)
- [API Reference](https://help.trustpayments.com/hc/en-us/articles/11569681677713-Webservices-API-Guide-for-POS-developers)

### Trust Payments Payouts API

Payout / disbursement capability exposed through the Webservices API on the TRU Connect gateway, using the same STPP JSON interface and alias/password + site reference authentication.

- **Human URL:** [https://help.trustpayments.com/hc/en-us/articles/4402771924497-Payouts-with-Webservices-API](https://help.trustpayments.com/hc/en-us/articles/4402771924497-Payouts-with-Webservices-API)
- **Base URL:** `https://webservices.securetrading.net/json/`

#### Properties

- [Documentation](https://help.trustpayments.com/hc/en-us/articles/4402771924497-Payouts-with-Webservices-API)


#### Properties

- [Documentation](https://help.trustpayments.com/hc/en-us)
- [Source Code](https://github.com/SecureTrading)

## Common Properties

- [Website](https://www.trustpayments.com/)
- [Documentation](https://help.trustpayments.com/hc/en-us)
- [API Reference](https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API)
- [GitHub Organization](https://github.com/SecureTrading)
- [Status Page](https://status.trustpayments.com/)
- [Pricing](https://www.trustpayments.com/pricing/)
- [Blog](https://www.trustpayments.com/blog/)
- [Help Centre](https://help.trustpayments.com/hc/en-us)
- [Login (MyST)](https://myst.trustpayments.com/)
- [Terms of Use](https://www.trustpayments.com/terms-of-use/)
- [Privacy Policy](https://www.trustpayments.com/privacy-policy/)

## API Posture

Trust Payments does not publish a downloadable OpenAPI/Swagger definition or a dedicated developer subdomain. The API is documented as help-centre reference articles plus official SDKs (Python, PHP, ReactJS, Swift) on the [SecureTrading](https://github.com/SecureTrading) GitHub organisation. Production Webservices access is gated behind PCI certification, account approval, and credential exchange. No OpenAPI specs were harvested because none are published.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
