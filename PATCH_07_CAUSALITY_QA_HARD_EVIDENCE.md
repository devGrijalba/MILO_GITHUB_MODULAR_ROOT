# PATCH — 07_CAUSALITY_QA — HARD EVIDENCE

## Purpose

Prevent false PASS where an action is described retrospectively but never occurs on screen.

## Mandatory seed execution map

Before PASS, internally map:

```yaml
conflicto:
  beat_id:
  evidence:
accion_visible:
  beat_id:
  agent:
  physical_action:
  object:
  evidence:
objeto_emocional:
  beat_id:
  evidence:
giro_posible:
  beat_id:
  evidence:
```

Every required seed element must resolve to actual candidate evidence.

## Visible action rule

`accion_visible` PASS requires:
- exact agent identifiable;
- agent listed in beat `characters`;
- agent explicitly visible in `visual_action`;
- physical action itself occurs in `visual_action`;
- required object/target participates in that action.

Aftermath, implication, memory, exposition and retrospective wording are insufficient.

INVALID evidence examples:
- "la cena que papá había dejado"
- "Milo comprende que papá preparó..."
- "el plato estaba ahí porque papá..."
- "papá lo había hecho antes"

VALID style:
- "Papá coloca la cena sobre la mesa y tapa el plato."

If there is no qualifying beat:
`REPAIR_REQUIRED`.

Do not allow semantic interpretation to substitute physical execution.
