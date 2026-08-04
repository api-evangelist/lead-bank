# Lead Bank (lead-bank)

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

Lead Bank is a Kansas City-chartered FDIC-insured bank operating as a sponsor bank and embedded-finance infrastructure provider for fintech partners. The platform is organized around four product pillars - Lend (term loans, lines of credit, BNPL, in-app financing), Move (ACH, instant payments, wires, international wires, stablecoin transfers, payment controls), Issue (physical and virtual credit / debit cards, custom account numbers), and Store (FDIC-insured multi-currency deposit accounts). APIs and file integrations (SFTP) are documented at docs.lead.bank but access is gated through Lead Bank's partner-onboarding process. Recognized on the Forbes Next Billion-Dollar Startups and CNBC Disruptor 50 lists.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lead-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lead-bank/refs/heads/main/apis.yml)

## Tags

- Banking
- Sponsor Bank
- Embedded Finance
- Banking as a Service
- Payments
- Lending
- Cards
- Deposits

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Lead Bank Lend API

Embedded-credit API supporting term loans, revolving lines of credit, in-app financing, and buy-now-pay-later products. Covers origination, underwriting, servicing, and disbursement.

- **Human URL:** [https://docs.lead.bank/api-integrations/overview](https://docs.lead.bank/api-integrations/overview)
- **Base URL:** `gated-partner-access`

#### Tags

- Lending
- Credit
- BNPL
- Origination

#### Properties

- [Documentation](https://docs.lead.bank/api-integrations/overview)
- [Postman Collection](collections/lead-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lead-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lead Bank Move API

Money-movement API spanning ACH, instant payments (RTP / FedNow), domestic and international wires, stablecoin transfers, and partner-configurable payment controls.

- **Human URL:** [https://docs.lead.bank/api-integrations/overview](https://docs.lead.bank/api-integrations/overview)
- **Base URL:** `gated-partner-access`

#### Tags

- Payments
- ACH
- RTP
- FedNow
- Wires
- Stablecoin

#### Properties

- [Documentation](https://docs.lead.bank/api-integrations/overview)
- [Postman Collection](collections/lead-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lead-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lead Bank Issue API

Card-issuing API for physical and virtual credit and debit cards plus custom-generated account numbers used in card-program back-ends.

- **Human URL:** [https://docs.lead.bank/api-integrations/overview](https://docs.lead.bank/api-integrations/overview)
- **Base URL:** `gated-partner-access`

#### Tags

- Cards
- Issuing
- Virtual Cards

#### Properties

- [Documentation](https://docs.lead.bank/api-integrations/overview)
- [Postman Collection](collections/lead-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lead-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lead Bank Store API

Deposit-account API for opening and managing FDIC-insured accounts on behalf of partner-program end users, including multi-currency balances and flexible account structures.

- **Human URL:** [https://docs.lead.bank/api-integrations/overview](https://docs.lead.bank/api-integrations/overview)
- **Base URL:** `gated-partner-access`

#### Tags

- Accounts
- Deposits
- FDIC
- Multi-Currency

#### Properties

- [Documentation](https://docs.lead.bank/api-integrations/overview)
- [Postman Collection](collections/lead-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lead-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lead Bank File Integrations (SFTP)

File-based integration channel over SFTP for partners that ingest or emit batch files (NACHA, reconciliation, settlement reports).

- **Human URL:** [https://docs.lead.bank/file-integrations/sftp-setup](https://docs.lead.bank/file-integrations/sftp-setup)
- **Base URL:** `gated-partner-access`

#### Tags

- SFTP
- File Integration
- Batch
- NACHA

#### Properties

- [Documentation](https://docs.lead.bank/file-integrations/sftp-setup)
- [Postman Collection](collections/lead-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lead-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lead Bank Webhooks

Outbound webhook events covering account, payment, card, and lending lifecycle changes. Endpoints configured per partner program.

- **Human URL:** [https://docs.lead.bank](https://docs.lead.bank)
- **Base URL:** `customer-configured`

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://docs.lead.bank)
- [Postman Collection](collections/lead-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lead-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://lead.bank/)
- [Documentation](https://docs.lead.bank/)
- [Partner Portal](https://partners.lead.bank/)
- [Changelog](https://docs.lead.bank/changelog)
- [Contact Sales](https://lead.bank/contact)
- [LinkedIn](https://www.linkedin.com/company/lead-bank)
- [L L Ms Txt](https://docs.lead.bank/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
