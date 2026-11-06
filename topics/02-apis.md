# APIs
**Learn:** REST resource modeling, pagination, filtering, idempotency keys, versioning, auth (OAuth2/JWT), rate limiting, OpenAPI.
**Build:** an Orders API with auth, pagination and an OpenAPI spec (lint it with [api-toolkit](https://github.com/satyam-ships/api-toolkit)).
**Test:** contract tests from the spec; negative tests for authz (can user A read user B's order?).
**Deploy:** behind a gateway with rate limits.
**Interview:** Cursor vs offset pagination? How do you make POST safe to retry? How do you version without breaking clients?
**Pitfalls:** broken object-level authorization · leaking internal errors · breaking changes in a live version.
