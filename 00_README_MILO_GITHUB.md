# MILO — REPOSITORIO MODULAR GITHUB

Este repositorio contiene el motor modular MILO.

Todos los archivos están diseñados para vivir en la RAÍZ del repositorio.

No crear subcarpetas.

## OBJETIVO

Permitir que un LLM con acceso web trabaje por estados y consulte únicamente los módulos necesarios en cada fase:

1. resolver fuente;
2. seleccionar semilla;
3. recuperar registro;
4. normalizar seed_snapshot;
5. generar candidato;
6. validar schema;
7. validar causalidad;
8. validar actores;
9. validar temporalidad;
10. validar duración/hooks;
11. validar payoff;
12. reparar;
13. generar voz;
14. ejecutar final gate;
15. emitir.

## REGLA DE VERSIONADO

La ejecución debe congelar una versión de engine al inicio.

Versión actual:

`MILO_ENGINE_VERSION = 7.0.1-MODULAR`

El archivo de entrada principal es:

`00_MANIFEST_MILO_ENGINE.md`

El router principal es:

`01_MILO_ROUTER.md`

## FUENTE CANÓNICA DE SEMILLAS

Las semillas están incluidas en 10 archivos:

`30_01_MILO_SEEDS_NOTEBOOKLM_0001-0100.md`
...
`30_10_MILO_SEEDS_NOTEBOOKLM_0901-1000.md`

No recalcular seed_hash.
No reescribir seeds.
No inventar campos.

## REGLA GENERAL

Cada módulo debe ser consultado únicamente cuando el router lo indique.

El LLM NO debe cargar todos los módulos simultáneamente salvo que el entorno lo requiera explícitamente.


## CAMBIOS 7.0.1

- agregado `21_SEED_PRIORITY_INDEX.md`;
- agregado `22_SERIES_STATE.md`;
- selección automática ya no escanea 1000 semillas;
- ausencia de historial ya no puede bloquear;
- STATE 02 usa índice precomputado + estado explícito.
