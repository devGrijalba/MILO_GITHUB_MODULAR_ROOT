# MILO CORRECCIONES — HARD ENFORCEMENT

Este paquete corrige el fallo detectado en la generación de MILO-S0001:

1. La acción `papá deja la cena` fue aceptada aunque nunca se mostró físicamente.
2. La duración objetivo de 35 s fue aceptada sin comprobar la narración real.
3. Se generó `ELEVENLABS_V3_TEXT` aunque Script QA no debía haber pasado.
4. El router permitía demasiado auto-PASS interpretativo.

## Archivos

- `MILO_PROMPT_ROUTER_GITHUB_V3_2_HARD_ENFORCEMENT.md`
  Router completo corregido. No bloquea por versión.

- `PATCH_07_CAUSALITY_QA_HARD_EVIDENCE.md`
  Regla de evidencia física + seed execution map.

- `PATCH_10_DURATION_HOOK_QA_COMPUTED.md`
  Obliga a calcular duración real.

- `PATCH_12_VOICE_ENGINE_HARD_UNLOCK.md`
  Impide generar Voice antes de Script PASS.

- `PATCH_13_FINAL_GATE_EVIDENCE.md`
  Evita self-certification.

## Importante

Estos archivos PATCH no pretenden reemplazar a ciegas los módulos actuales del repositorio.
Deben integrarse en las versiones CURRENTES de esos módulos, conservando las demás reglas canónicas.

No se fija ningún `engine_version`.

La política correcta es:

VERSION = abierta
ARCHIVOS CURRENTES = autoridad
VALIDACIÓN CARGADA = obligatoria
PASS = evidencia, no interpretación
