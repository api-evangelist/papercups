# Papercups (papercups)

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
