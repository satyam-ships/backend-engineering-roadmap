# Caching
**Learn:** cache-aside, write-through, TTLs, invalidation, stampedes, HTTP caching (ETag, Cache-Control), CDN.
**Build:** cache-aside layer in front of a slow query with request coalescing.
**Test:** hit-rate metrics; behavior when the cache is down.
**Deploy:** size limits, eviction policy, monitoring.
**Interview:** What is a cache stampede and how do you prevent it? Why is invalidation hard?
**Pitfalls:** caching per-user data under a shared key · no TTL · treating the cache as the source of truth.
