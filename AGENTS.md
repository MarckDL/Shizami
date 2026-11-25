# Instrucciones para agentes de Shizami

La memoria compartida del proyecto vive en `docs/`. Guarda allí las decisiones, los hallazgos y el trabajo pendiente que otra sesión necesite para continuar desde cualquiera de las dos computadoras.

## Al iniciar cada sesión

1. Lee siempre `docs/00-CONTEXTO.md`.
2. Lee siempre `docs/bitacora/avances.md`, incluida la entrada más reciente.
3. Abre y lee el archivo del sprint activo en `docs/sprints/`. El enlace al sprint activo está en `docs/00-CONTEXTO.md`.

## Al finalizar cada tarea o sesión

1. Actualiza `docs/bitacora/avances.md` con lo que se hizo, las decisiones tomadas y el siguiente paso concreto.
2. Si hubo errores relevantes, actualiza `docs/bitacora/errores-y-fixes.md` con el síntoma, la causa si se conoce, la corrección o el pendiente y su verificación.
3. Actualiza el estado de las tareas trabajadas en el archivo del sprint activo, incluidos los bloqueos y sus dependencias. Si cambia el sprint activo, actualiza su enlace en `docs/00-CONTEXTO.md`.

Usa fechas en formato `AAAA-MM-DD`. Distingue las propuestas de las decisiones acordadas y enlaza los documentos que las respaldan. Mantén los archivos en Markdown, con enlaces relativos para que funcionen en Obsidian y en GitHub.
