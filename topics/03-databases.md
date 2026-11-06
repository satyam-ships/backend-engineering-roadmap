# Databases
**Learn:** relational modeling, normalization, indexes (B-tree), query plans (`EXPLAIN`), transactions and isolation levels, migrations, connection pooling.
**Build:** a schema with migrations; find and fix a slow query using `EXPLAIN ANALYZE`.
**Test:** migration up/down on a copy of prod-like data; concurrent-update tests.
**Deploy:** pooled connections, backups with restore drills, read replicas.
**Interview:** What is an N+1 query? Explain isolation levels and anomalies. When does an index not help?
**Pitfalls:** missing indexes on foreign keys · long transactions · unrestorable backups · destructive migrations without a rollback plan.
