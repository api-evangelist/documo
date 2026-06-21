# Documo (documo)

Documo (mFax) is a cloud fax and document delivery platform. The Documo REST API lets developers send and receive faxes, provision and manage fax numbers, subscribe to delivery events via webhooks, and manage account resources over a JSON/HTTPS interface secured with an API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/documo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/documo/refs/heads/main/apis.yml)

## Tags

- Fax
- Cloud Fax
- Document Delivery
- HIPAA
- Communications

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Documo Fax API

Send a fax to one or more recipients with cover page, scheduling, tags, and custom fields; resend a previously failed fax; retrieve fax detail and status; list fax history; and download delivered fax documents as PDF or TIFF.

- **Human URL:** [https://docs.documo.com/](https://docs.documo.com/)
- **Base URL:** `https://api.documo.com/v1`

#### Tags

- Fax
- Send
- Receive

#### Properties

- [Documentation](https://docs.documo.com/)
- [API Reference](https://docs.documo.com/#send-a-fax)
- [OpenAPI](openapi/documo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/documo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Documo Numbers API

Search available inbound fax numbers, provision (add) numbers to an account, list provisioned numbers, and release numbers no longer needed.

- **Human URL:** [https://docs.documo.com/](https://docs.documo.com/)
- **Base URL:** `https://api.documo.com/v1`

#### Tags

- Numbers
- Provisioning
- DID

#### Properties

- [Documentation](https://docs.documo.com/)
- [OpenAPI](openapi/documo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/documo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Documo Webhooks API

Create, list, and delete webhook subscriptions at the account or number level to receive inbound/outbound fax succeed and failed events plus number add and release events.

- **Human URL:** [https://docs.documo.com/#create-webhook](https://docs.documo.com/#create-webhook)
- **Base URL:** `https://api.documo.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.documo.com/#create-webhook)
- [OpenAPI](openapi/documo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/documo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Documo Account API

Retrieve account profile and settings information. API keys carry an admin or user access level that governs which endpoints they can call.

- **Human URL:** [https://docs.documo.com/](https://docs.documo.com/)
- **Base URL:** `https://api.documo.com/v1`

#### Tags

- Account
- Settings

#### Properties

- [Documentation](https://docs.documo.com/)
- [OpenAPI](openapi/documo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/documo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/documo)
- [Website](https://www.documo.com/)
- [Documentation](https://docs.documo.com/)
- [Plans](plans/documo-plans-pricing.yml)
- [Rate Limits](rate-limits/documo-rate-limits.yml)
- [Fin Ops](finops/documo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
