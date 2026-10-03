# STATE 01 — SOURCE RESOLUTION

## FUENTE CANÓNICA

Este mismo repositorio GitHub.

El LLM debe localizar los archivos de semillas dentro del repositorio.

## REGLA

Si existe acceso web:
- leer el repositorio;
- localizar `00_MANIFEST_MILO_ENGINE.md`;
- seguir los módulos de la versión congelada;
- recuperar seeds desde `30_01...30_10`.

Si el usuario proporcionó una copia local completa:
- puede usarse como fallback;
- no afirmar verificación GitHub si GitHub no fue consultado.

## RESULTADOS

Fuente accesible y módulos disponibles:
`PASS`

Fuente temporalmente inaccesible pero existe copia local completa:
`PASS_WITH_LOCAL_SOURCE`

Ninguna fuente válida:
`FAIL_CRITICAL`
