# Lead Bank (lead-bank)

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
