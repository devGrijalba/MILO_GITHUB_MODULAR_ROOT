# REPAIR PROTOCOL

Estados:
- PASS
- REPAIR_REQUIRED
- FAIL_CRITICAL

Proceso:

`DETECTAR -> CLASIFICAR -> REPARAR -> REVALIDAR`

Máximo 3 ciclos.

Después de reparar narration:
- recontar palabras;
- revalidar hook;
- revalidar causalidad;
- revalidar actor consistency;
- revalidar payoff;
- revalidar voice.

Después de reparar visual_action:
- revalidar characters;
- revalidar causalidad;
- revalidar continuidad;
- revalidar world_id.

Si persiste REPAIR_REQUIRED o FAIL_CRITICAL:
`OUTPUT_BLOCKED`
