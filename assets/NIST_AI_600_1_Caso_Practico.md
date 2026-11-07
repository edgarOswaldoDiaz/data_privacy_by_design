# Caso práctico: asistente generativo para atención a clientes

> **Caso hipotético de aplicación.** Material elaborado con fines académicos a partir del documento NIST correspondiente.

[Volver al índice](./NIST_Indice.md) · [Consultar el escrito base](./NIST_AI_600_1_Escrito.md)

*Aplicación del NIST AI 600-1 — Generative Artificial Intelligence Profile*

Una empresa de servicios implementa un asistente basado en inteligencia artificial generativa para apoyar a su área de atención a clientes. El sistema utiliza un modelo de un proveedor externo y consulta manuales internos, políticas comerciales y registros de clientes para elaborar respuestas personalizadas. Después de varias semanas, se detecta que algunas respuestas son convincentes pero incorrectas, que en una conversación apareció información perteneciente a otro cliente, que ciertos empleados comenzaron a copiar las respuestas sin verificarlas y que no existe suficiente claridad sobre los datos y cambios administrados por el proveedor. Tampoco hay un procedimiento uniforme para registrar y comunicar incidentes. El caso concentra riesgos de confabulación, privacidad, configuración humano-IA, integridad de la información y dependencia de terceros.

La aplicación del NIST AI 600-1 permite abordar la situación mediante las cuatro funciones del AI RMF. Con GOVERN, la empresa define usos permitidos, responsabilidades, requisitos de privacidad, supervisión humana y obligaciones contractuales del proveedor. Con MAP, documenta el propósito del asistente, usuarios, fuentes de datos, limitaciones, posibles usos indebidos y personas afectadas. Con MEASURE, prueba la exactitud de las respuestas, la frecuencia de confabulaciones, la posible exposición de datos personales y la resistencia frente a solicitudes diseñadas para provocar comportamientos no previstos. Con MANAGE, prioriza los resultados y decide si aumenta la revisión humana, restringe datos, modifica controles, exige cambios al proveedor o limita o desactiva el sistema cuando el riesgo supera la tolerancia establecida.

El resultado esperado no consiste necesariamente en eliminar el asistente, sino en mantenerlo como herramienta de apoyo bajo condiciones controladas. La empresa puede impedir el envío automático de respuestas sensibles, exigir revisión humana en casos definidos, limitar el acceso a datos personales, realizar pruebas periódicas, documentar fuentes y versiones del sistema y establecer un proceso formal para registrar, investigar y comunicar incidentes. El caso también ilustra las cuatro consideraciones transversales del perfil: Governance, mediante reglas y responsabilidades; Pre-Deployment Testing, mediante pruebas antes de ampliar el uso; Content Provenance, mediante trazabilidad de fuentes y contenido; e Incident Disclosure, mediante documentación y comunicación de problemas relevantes.

**Síntesis de aplicación**

| Función | Aplicación al caso |
|:--|:--|
| **GOVERN** | Define reglas de uso, responsabilidades, supervisión y obligaciones del proveedor. |
| **MAP** | Identifica contexto, datos, usuarios, limitaciones, usos indebidos e impactos potenciales. |
| **MEASURE** | Prueba confabulaciones, privacidad, seguridad, exactitud y comportamiento en escenarios adversos. |
| **MANAGE** | Prioriza riesgos, ajusta controles, monitorea incidentes y limita o desactiva el sistema si es necesario. |

**Fuente base:** National Institute of Standards and Technology (2024), Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile, NIST AI 600-1.

---

**Diagrama de causas:** [Ver el Ishikawa del caso](./NIST_AI_600_1_Ishikawa_Caso.md).
