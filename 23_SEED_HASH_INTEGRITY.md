# SEED HASH INTEGRITY

Engine version: `7.0.2-MODULAR`

Every canonical seed record in files `30_01...30_10` MUST contain:

- `seed_id`
- `seed_hash`

Rules:

1. `seed_hash` is canonical source data.
2. Never recalculate it.
3. Never infer it.
4. `seed_snapshot.seed_hash` must equal the canonical seed record.
5. root `seed_hash` must equal `seed_snapshot.seed_hash`.
6. If the canonical seed record lacks `seed_hash`, STATE 03 cannot PASS.

Required identity:

`root seed_hash == seed_snapshot.seed_hash == canonical seed_hash`

Mismatch:
`FAIL_CRITICAL`
