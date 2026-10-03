# PATCH — 10_DURATION_HOOK_QA — COMPUTED DURATION

## Purpose

Prevent a declared target from being mistaken for measured duration.

## Mandatory calculation

Use the final candidate's actual narration:

`all beats[].narration`

Compute:
- total narration words;
- duration according to the CURRENT module's words-per-second / timing rule;
- PASS / REPAIR_REQUIRED from that computed result.

Never use `duration_target_seconds` as evidence that duration passes.

`duration_target_seconds` is a target only.

After ANY narration change:
- recount;
- recompute;
- re-check hook equality;
- re-check duration.

Internal evidence:

```yaml
duration_evidence:
  total_words:
  rule_used:
  computed_seconds:
  target_seconds:
  result:
```

If computed duration is outside current PASS range:
`REPAIR_REQUIRED`.
