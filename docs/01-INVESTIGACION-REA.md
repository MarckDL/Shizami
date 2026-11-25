# Investigación REA y competitiva

## Resumen Ejecutivo de Hallazgos

**Estado:** pendiente de investigación.

| Hallazgo que afecta al MVP | Implicación para Shizami | Evidencia en el detalle técnico |
| --- | --- | --- |

## Alcance y criterio de cierre

La investigación se da por suficiente cuando se ha mapeado y documentado todo lo observable de Mimo y Duolingo en las cinco áreas siguientes. Para cada producto, identifica el cliente observado (web o app Android/APK), su versión cuando esté disponible y las limitaciones de acceso o visibilidad. Registra los límites de la observación junto a la evidencia y marca como hipótesis cualquier inferencia.

### 1. Flujo funcional y UX

Mapear el recorrido completo desde la entrada y elección de ruta hasta el cierre de una unidad. Documentar cómo se inicia y completa una lección, qué ve el estudiante cuando acierta o falla un ejercicio y cómo continúa después de cada resultado.

### 2. APIs y comunicación cliente-servidor

Registrar las llamadas públicas o de sesión que realiza el cliente web o Android durante el uso habitual. Documentar el propósito, método y ruta observados, el esquema del payload al validar un ejercicio y la respuesta que recibe el cliente para aciertos y errores. Usar ejemplos con valores ficticios para identificadores personales y omitir credenciales y tokens de sesión.

### 3. Modelo de datos observable

Documentar cómo las respuestas JSON representan la jerarquía de curso, módulo, unidad y lección, qué tipos de preguntas se observan y qué reglas de validación aparecen en los datos o se manifiestan en el comportamiento. Registrar entidades, relaciones y ejemplos de campos observados.

### 4. Almacenamiento y estado en el cliente

Identificar qué datos aparecen en localStorage, IndexedDB, SQLite o caché, según el cliente, y qué estados se sincronizan con el backend. Rastrear progreso, XP, rachas y vidas donde existan. Documentar en qué momentos se observan sincronizaciones, escrituras, actualizaciones e invalidaciones o limpiezas de caché.

### 5. Brechas y oportunidades

Documentar puntos de fricción y necesidades que quedan sin cubrir, con atención a la profundidad de la práctica, los proyectos reales y las rutas por objetivo. Asociar cada oportunidad para Shizami con la observación que la motiva.

## Matriz de cobertura

| Área | Mimo | Duolingo |
| --- | --- | --- |
| Flujo funcional y UX | Pendiente | Pendiente |
| APIs y comunicación cliente-servidor | Pendiente | Pendiente |
| Modelo de datos observable | Pendiente | Pendiente |
| Almacenamiento y estado en el cliente | Pendiente | Pendiente |
| Brechas y oportunidades | Pendiente | Pendiente |

## Detalle técnico

### Mimo

### Duolingo

### Otros competidores

| Producto | Flujo o aspecto observado | Fuente y fecha | Hallazgo | Pregunta abierta |
| --- | --- | --- | --- | --- |

### Plantilla de hallazgo

- Área evaluada
- Fecha, cliente, versión y entorno de observación
- Flujo o fuente consultada y evidencia asociada
- Hecho observado
- Interpretación y nivel de confianza
- Implicación para Shizami
- Límite de la observación o prueba pendiente
