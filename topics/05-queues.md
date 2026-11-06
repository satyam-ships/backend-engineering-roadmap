# Queues
**Learn:** producers/consumers, at-least-once delivery, idempotent consumers, retries with backoff, dead-letter queues, ordering.
**Build:** a job pipeline: enqueue, process with retries, dead-letter after N failures.
**Test:** crash a worker mid-job; deliver the same message twice.
**Deploy:** autoscale workers on queue depth.
**Interview:** At-most-once vs at-least-once vs exactly-once? How do you make a consumer idempotent?
**Pitfalls:** poison messages blocking a queue · no DLQ · unbounded retries · non-idempotent handlers.
