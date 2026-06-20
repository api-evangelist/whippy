# Whippy (whippy)

Whippy is an AI-powered customer communication platform unifying SMS, email, voice, and fax into a single omnichannel inbox. Its public REST API (X-WHIPPY-KEY header) lets developers send messages, manage contacts and conversations, run campaigns and automated sequences, configure channels, and subscribe to webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/whippy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/whippy/refs/heads/main/apis.yml)

## Tags

- Communication
- Messaging
- SMS
- Email
- Voice
- AI
- Campaigns
- Sequences

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Whippy Messaging API

Send SMS/MMS, email, and fax messages from an organization channel to a contact, with attachments, opt-in handling, conversation status, and scheduled delivery.

- **Human URL:** [https://docs.whippy.ai/reference/sendsms](https://docs.whippy.ai/reference/sendsms)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Messaging
- SMS
- Email
- Fax

#### Properties

- [Documentation](https://docs.whippy.ai/docs/getting-started)
- [API Reference](https://docs.whippy.ai/reference/sendsms)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whippy Contacts API

Create, read, update, delete, search, and upsert contacts, manage per-channel communication preferences (opt in / opt out), and list a contact's sequences.

- **Human URL:** [https://docs.whippy.ai/reference/createcontact-1](https://docs.whippy.ai/reference/createcontact-1)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Contacts
- CRM
- Communication Preferences

#### Properties

- [Documentation](https://docs.whippy.ai/recipes/create-a-contact)
- [API Reference](https://docs.whippy.ai/reference/createcontact-1)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whippy Conversations API

List, show, search, and update conversations across phone, email, and fax channels, and list or search the messages within them.

- **Human URL:** [https://docs.whippy.ai/reference/getconversations](https://docs.whippy.ai/reference/getconversations)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Conversations
- Messages
- Inbox

#### Properties

- [Documentation](https://docs.whippy.ai/recipes/sync-conversations-messages)
- [API Reference](https://docs.whippy.ai/reference/getconversations)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whippy Campaigns API

Send SMS campaigns and list, show, and inspect campaign-level analytics (sent, responses, link clicks, unsubscribes) and campaign contacts.

- **Human URL:** [https://docs.whippy.ai/reference/getcampaigns](https://docs.whippy.ai/reference/getcampaigns)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Campaigns
- Bulk Messaging
- Analytics

#### Properties

- [Documentation](https://docs.whippy.ai/recipes/send-an-sms-campaign)
- [API Reference](https://docs.whippy.ai/reference/getcampaigns)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whippy Sequences API

List and show automated multi-step sequences, add or remove contacts, and inspect sequence runs for drip and follow-up automation.

- **Human URL:** [https://docs.whippy.ai/reference/getsequences](https://docs.whippy.ai/reference/getsequences)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Sequences
- Automation
- Drip

#### Properties

- [Documentation](https://docs.whippy.ai/recipes/add-contacts-to-a-sequence)
- [API Reference](https://docs.whippy.ai/reference/getsequences)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whippy Channels API

List and show channels (phone, email, fax) with opening hours, AI-agent configuration, and automatic response settings, and manage channel membership.

- **Human URL:** [https://docs.whippy.ai/reference/getchannels](https://docs.whippy.ai/reference/getchannels)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Channels
- Phone Numbers
- Locations

#### Properties

- [Documentation](https://docs.whippy.ai/docs/getting-started)
- [API Reference](https://docs.whippy.ai/reference/getchannels)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whippy Webhooks API

Subscribe developer endpoints to resource events (message.created, campaign.updated, etc.) with HMAC-SHA256 signed payloads, and push first-party custom events into Whippy individually or in bulk.

- **Human URL:** [https://docs.whippy.ai/docs/introduction](https://docs.whippy.ai/docs/introduction)
- **Base URL:** `https://api.whippy.co/v1`

#### Tags

- Webhooks
- Events
- Custom Events

#### Properties

- [Documentation](https://docs.whippy.ai/docs/introduction)
- [API Reference](https://docs.whippy.ai/reference/createcustomevent)
- [OpenAPI](openapi/whippy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Review](review.yml)
- [Postman Collection](collections/whippy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whippy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/whippy-ai)
- [Website](https://www.whippy.ai)
- [Documentation](https://docs.whippy.ai)
- [Plans](plans/whippy-plans-pricing.yml)
- [Rate Limits](rate-limits/whippy-rate-limits.yml)
- [Fin Ops](finops/whippy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
