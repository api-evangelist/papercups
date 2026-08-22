# Papercups (papercups)

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

Papercups is an open-source customer-messaging and live-chat platform built on Elixir/Phoenix, positioned as a self-hosted alternative to Intercom. It exposes a REST API for conversations, messages, and customers, a realtime chat surface over Phoenix WebSocket channels, and outbound webhooks. The project is in maintenance mode (community-maintained, no major new features).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/papercups/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/papercups/refs/heads/main/apis.yml)

## Tags

- Customer Messaging
- Live Chat
- Open Source
- Support
- Intercom Alternative

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Papercups Conversations API

REST endpoints to create, list, retrieve, update, and delete conversations (threads of messages), with filtering by status, priority, customer, and assignee.

- **Human URL:** [https://docs.papercups.io/api-endpoints](https://docs.papercups.io/api-endpoints)
- **Base URL:** `https://app.papercups.io/api/v1`

#### Tags

- Conversations
- Support
- Threads

#### Properties

- [Documentation](https://docs.papercups.io/api-endpoints)
- [API Reference](https://docs.papercups.io/api-endpoints)
- [OpenAPI](openapi/papercups-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/papercups-io/papercups)
- [Postman Collection](collections/papercups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/papercups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Papercups Messages API

REST endpoints to create, list, retrieve, and delete messages within conversations, including agent and customer messages and their metadata.

- **Human URL:** [https://docs.papercups.io/api-endpoints](https://docs.papercups.io/api-endpoints)
- **Base URL:** `https://app.papercups.io/api/v1`

#### Tags

- Messages
- Support
- Chat

#### Properties

- [Documentation](https://docs.papercups.io/api-endpoints)
- [API Reference](https://docs.papercups.io/api-endpoints)
- [OpenAPI](openapi/papercups-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/papercups-io/papercups)
- [Postman Collection](collections/papercups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/papercups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Papercups Customers API

REST endpoints to create, list, retrieve, update, and delete customer records (users, leads, or contacts), filterable by name, email, host, and company.

- **Human URL:** [https://docs.papercups.io/api-endpoints](https://docs.papercups.io/api-endpoints)
- **Base URL:** `https://app.papercups.io/api/v1`

#### Tags

- Customers
- Contacts
- CRM

#### Properties

- [Documentation](https://docs.papercups.io/api-endpoints)
- [API Reference](https://docs.papercups.io/api-endpoints)
- [OpenAPI](openapi/papercups-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/papercups-io/papercups)
- [Postman Collection](collections/papercups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/papercups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Papercups Notifications & Webhooks API

Outbound event subscriptions delivered as webhooks (message:created, conversation:created, conversation:updated, and a webhook:verify challenge handshake) notifying external systems of activity.

- **Human URL:** [https://docs.papercups.io/webhook-events](https://docs.papercups.io/webhook-events)
- **Base URL:** `https://app.papercups.io/api/v1`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://docs.papercups.io/webhook-events)
- [API Reference](https://github.com/papercups-io/papercups/wiki/Event-Subscriptions-with-Webhooks)
- [GitHub](https://github.com/papercups-io/papercups)

### Papercups Realtime Chat API (WebSocket / Phoenix Channels)

Bidirectional realtime live chat over Phoenix WebSocket channels. Clients join conversation, conversation-lobby, and account-room channels and exchange shout (message), messages:seen, and presence events for two-way messaging.

- **Human URL:** [https://docs.papercups.io/chat](https://docs.papercups.io/chat)
- **Base URL:** `wss://app.papercups.io/socket/websocket`

#### Tags

- Realtime
- WebSocket
- Phoenix Channels

#### Properties

- [Documentation](https://docs.papercups.io/chat)
- [AsyncAPI](asyncapi/papercups-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [GitHub](https://github.com/papercups-io/papercups)

### Papercups Webhooks

Register external HTTPS endpoints to receive Papercups events as POSTed JSON payloads of shape { event, payload }, with a verify-challenge handshake on registration.

- **Human URL:** [https://github.com/papercups-io/papercups/wiki/Event-Subscriptions-with-Webhooks](https://github.com/papercups-io/papercups/wiki/Event-Subscriptions-with-Webhooks)
- **Base URL:** `https://app.papercups.io/api/v1`

#### Tags

- Webhooks
- Events
- Integrations

#### Properties

- [Documentation](https://docs.papercups.io/webhook-events)
- [API Reference](https://github.com/papercups-io/papercups/wiki/Event-Subscriptions-with-Webhooks)
- [GitHub](https://github.com/papercups-io/webhooks-demo)

## Common Properties

- [GitHub Organization](https://github.com/papercups-io)
- [LinkedIn](https://www.linkedin.com/company/papercups)
- [Website](https://papercups.io)
- [Documentation](https://docs.papercups.io)
- [Plans](plans/papercups-plans-pricing.yml)
- [Rate Limits](rate-limits/papercups-rate-limits.yml)
- [Fin Ops](finops/papercups-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
