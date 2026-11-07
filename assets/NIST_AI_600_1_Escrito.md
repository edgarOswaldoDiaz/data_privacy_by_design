# NIST AI 600-1 — GAI Profile

> **Documento:** síntesis académica para consulta, adaptada del escrito original en Word.  
> **Ámbito:** Legalidad y Protección de la Información.  
> **Alcance:** Perfil para riesgos específicos o intensificados por IA generativa.

[Volver al índice](./NIST_Indice.md)

---

## 1. Introducción

El NIST AI 600-1, Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile, es un perfil transversal y recurso complementario del NIST AI Risk Management Framework (AI RMF 1.0). Su propósito es adaptar el enfoque general de gestión de riesgos del AI RMF a las particularidades de la inteligencia artificial generativa (GAI), considerando que esta tecnología puede producir texto, imágenes, audio, video y otros contenidos sintéticos en una amplia variedad de sectores y casos de uso.

El documento no constituye un marco independiente ni sustituye al AI RMF 1.0. En cambio, utiliza las mismas funciones de gestión —GOVERN, MAP, MEASURE y MANAGE— para identificar riesgos que son nuevos en GAI o que pueden intensificarse con su uso, y para proponer acciones que ayuden a las organizaciones a responder de forma proporcional al contexto, al nivel de riesgo y a su tolerancia organizacional.

> [!NOTE]
> **Idea central**
>
> El GAI Profile traslada la lógica del AI RMF 1.0 a la inteligencia artificial generativa: primero identifica riesgos específicos y después propone cómo gobernarlos, mapearlos, medirlos y gestionarlos.


## 2. Naturaleza y alcance del perfil

NIST describe este documento como un cross-sectoral profile. Esto significa que su aplicación no está limitada a un sector particular; puede utilizarse en salud, educación, finanzas, gobierno, industria o cualquier otro contexto en el que se integren modelos generativos. La adaptación debe considerar los objetivos de la organización, sus recursos, su tolerancia al riesgo y los requisitos legales o regulatorios aplicables.

Para los propósitos del documento, GAI se refiere principalmente a modelos fundacionales generativos capaces de producir contenido sintético derivado de patrones aprendidos en sus datos de entrada. Esta capacidad amplía las oportunidades de automatización y apoyo a tareas humanas, pero también introduce riesgos relacionados con confiabilidad, uso indebido, privacidad, seguridad, procedencia del contenido y efectos sociales.

- No es una ley, regulación ni certificación.
- No reemplaza al AI RMF 1.0; lo complementa.
- Su aplicación es voluntaria y adaptable al contexto.
- Está orientado a riesgos de modelos, sistemas, aplicaciones y ecosistemas generativos.

## 3. Cómo entiende NIST el riesgo en GAI

El perfil conserva la definición de riesgo utilizada por el AI RMF: la combinación entre la probabilidad de que ocurra un evento y la magnitud de sus consecuencias. En GAI, el riesgo puede aparecer en diferentes etapas del ciclo de vida, desde el diseño y el entrenamiento hasta el despliegue, la operación y el retiro del sistema.

NIST también propone observar el riesgo desde varias dimensiones: el nivel en el que se presenta (modelo, aplicación o ecosistema), su fuente (datos, diseño, operación, entradas, salidas o comportamiento humano) y la escala temporal en la que se materializa. Algunos efectos pueden ser inmediatos; otros pueden acumularse y hacerse visibles con el tiempo.

| **Dimensión**   | **Qué se analiza**                                                          |
|-----------------|-----------------------------------------------------------------------------|
| Ciclo de vida   | Diseño, desarrollo, despliegue, operación y retiro.                         |
| Alcance         | Riesgos del modelo o sistema, de la aplicación y del ecosistema.            |
| Fuente          | Datos, entrenamiento, operación, entradas, salidas y comportamiento humano. |
| Escala temporal | Daños inmediatos, acumulativos o de largo plazo.                            |

> [!NOTE]
> **Perspectiva socio-técnica**
>
> El riesgo no depende únicamente del modelo. También depende de las personas, la organización, los proveedores, las herramientas conectadas y el contexto real de uso.


## 4. Riesgos únicos o exacerbados por la IA generativa

NIST identifica doce categorías de riesgo que resultan especialmente relevantes para GAI. No deben interpretarse como compartimentos aislados: un mismo incidente puede involucrar varias categorías al mismo tiempo.

### 4.1 CBRN Information or Capabilities

Posibilidad de que GAI facilite el acceso, análisis o síntesis de información relacionada con capacidades químicas, biológicas, radiológicas o nucleares. NIST mantiene una postura cautelosa: disponer de información no equivale por sí solo a contar con la capacidad material para producir un daño, pero el riesgo debe reevaluarse conforme evolucionan los modelos y sus conexiones con herramientas especializadas.

### 4.2 Confabulation

Generación de contenido falso, erróneo o internamente inconsistente presentado de manera convincente. El riesgo aumenta cuando el usuario confía en la respuesta y la utiliza en decisiones relevantes. Las confabulaciones pueden incluir hechos, citas, explicaciones o razonamientos inventados.

### 4.3 Dangerous, Violent, or Hateful Content

Capacidad para producir o amplificar contenido peligroso, violento, amenazante, discriminatorio o relacionado con conductas dañinas. NIST también considera intentos de evasión de controles, como jailbreaking, y la necesidad de evaluar el sistema frente a usos maliciosos o inesperados.

### 4.4 Data Privacy

Riesgos derivados del uso de grandes volúmenes de datos y de la posibilidad de memorizar, revelar o inferir información personal o sensible. Incluso una inferencia incorrecta puede causar daño si posteriormente influye en una decisión sobre una persona.

### 4.5 Environmental Impacts

Impactos asociados con el consumo de recursos computacionales durante entrenamiento, ajuste e inferencia. NIST reconoce que la magnitud depende del modelo, la tarea, el hardware y la escala de uso, y que todavía existen limitaciones para medir estos efectos de manera uniforme.

### 4.6 Harmful Bias and Homogenization

Amplificación de sesgos y disparidades de desempeño entre grupos, idiomas o contextos. La homogenización se refiere a resultados excesivamente uniformes y puede relacionarse con dependencia de pocos modelos fundacionales o con entrenamiento excesivo sobre datos sintéticos, fenómeno que también puede contribuir a model collapse.

### 4.7 Human-AI Configuration

Riesgos derivados de la relación entre personas y sistemas generativos. Incluye confianza excesiva (automation bias), rechazo injustificado (algorithmic aversion), antropomorfización, dependencia emocional y configuraciones de supervisión poco claras.

### 4.8 Information Integrity

Afectación a la autenticidad, verificabilidad y confiabilidad del ecosistema informativo. Incluye misinformation, disinformation, deepfakes, suplantación y campañas de manipulación. El daño puede extenderse desde una pieza falsa de contenido hasta una pérdida general de confianza en información auténtica.

### 4.9 Information Security

Doble riesgo: GAI puede facilitar ciertas capacidades ofensivas y, al mismo tiempo, puede ser objeto de ataques. NIST destaca amenazas como prompt injection, data poisoning, extracción de información, ataques a dependencias y exposición de componentes del modelo.

### 4.10 Intellectual Property

Riesgos relacionados con uso de obras protegidas en entrenamiento, reproducción de contenido memorizado, generación de contenido similar a obras existentes y uso o imitación de identidad, imagen o voz. NIST reconoce que varias cuestiones jurídicas continúan sujetas a debate.

### 4.11 Obscene, Degrading, and/or Abusive Content

Facilitación de contenido íntimo no consentido, material abusivo y otras formas de contenido degradante. El riesgo puede originarse tanto en datos problemáticos como en la capacidad del modelo para sintetizar nuevo contenido dañino, incluso cuando los datos han sido depurados.

### 4.12 Value Chain and Component Integration

Riesgos heredados de datasets, modelos preentrenados, librerías, APIs y otros proveedores. La complejidad de la cadena puede dificultar trazabilidad, auditoría y asignación de responsabilidades, por lo que la organización debe gestionar también los componentes que no desarrolló directamente.

## 5. Acciones sugeridas para gestionar los riesgos de GAI

Después de identificar los doce riesgos, el perfil organiza sus acciones siguiendo las cuatro funciones del AI RMF 1.0. El documento contiene numerosas acciones específicas e identificadores técnicos; para una consulta académica general, lo más importante es conservar la lógica de cada función y su relación con la toma de decisiones.

| **Función** | **Pregunta central**                                         | **Enfoque aplicado a GAI**                                                                                                                        |
|-------------|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| GOVERN      | ¿Qué reglas, responsables y límites existen?                 | Cumplimiento legal, políticas de uso, responsabilidades, tolerancia al riesgo, inventarios, supervisión, incidentes y criterios de desactivación. |
| MAP         | ¿Qué sistema tenemos, en qué contexto y qué puede salir mal? | Propósito, usuarios, datos, componentes, límites, terceros, usos indebidos, posibles impactos y personas afectadas.                               |
| MEASURE     | ¿Cómo comprobamos los riesgos?                               | Pruebas previas al despliegue, desempeño real, confabulación, seguridad, privacidad, sesgos, procedencia y retroalimentación humana.              |
| MANAGE      | ¿Qué hacemos con los resultados?                             | Aceptar, mitigar, transferir o evitar riesgos; monitorear controles, gestionar terceros, responder a incidentes, mejorar o retirar el sistema.    |

### 5.1 GOVERN

GOVERN busca evitar que la adopción de GAI sea improvisada. La organización debe alinear el desarrollo y uso con las leyes aplicables, definir políticas de uso aceptable, asignar responsabilidades y establecer niveles de riesgo tolerables. También debe documentar los sistemas generativos que utiliza, sus proveedores y sus datos, así como contar con mecanismos para supervisar incidentes y decidir cuándo limitar o desactivar un sistema.

> [!NOTE]
> **GO / NO-GO**
>
> NIST promueve el uso de criterios de aprobación antes del despliegue. Si el sistema no alcanza niveles mínimos de desempeño, seguridad o control, la decisión puede ser no desplegarlo o suspenderlo hasta reducir el riesgo.


### 5.2 MAP

MAP busca comprender el sistema dentro de su contexto real. Deben definirse el propósito, los usuarios, el alcance, las fuentes de datos, las dependencias y las limitaciones. También deben anticiparse usos no previstos, abuso, aplicaciones ilegales previsibles y efectos sobre personas, grupos, comunidades, organizaciones y el medio ambiente. NIST recomienda incorporar perspectivas interdisciplinarias y participación de usuarios o comunidades cuando resulte pertinente.

### 5.3 MEASURE

MEASURE transforma los riesgos identificados en evidencia. NIST recomienda pruebas previas al despliegue y evaluaciones en condiciones similares al uso real. Un buen resultado en un benchmark no garantiza por sí solo que el sistema sea válido o seguro en producción. Las evaluaciones pueden incluir revisión de confabulaciones, privacidad, seguridad, sesgos, confiabilidad, autenticidad del contenido y resistencia a manipulación.

El red teaming aparece como una práctica relevante: consiste en probar deliberadamente el sistema para descubrir fallos, vulnerabilidades, comportamientos dañinos o posibilidades de uso indebido. El perfil también enfatiza que la evaluación debe combinar mediciones técnicas con retroalimentación humana y experiencia de dominio.

### 5.4 MANAGE

MANAGE convierte los resultados en decisiones. Los riesgos pueden mitigarse, transferirse, evitarse o aceptarse cuando el riesgo residual se mantiene dentro de la tolerancia de la organización. NIST recomienda monitorear la eficacia de los controles, reevaluar modelos después de cambios importantes, gestionar riesgos de terceros, mantener supervisión post-despliegue y documentar incidentes y near-misses.

Cuando un sistema supera los límites definidos, la organización debe contar con procedimientos de escalamiento, remediación, desconexión o desactivación. La gestión continúa durante todo el ciclo de vida y no termina cuando la herramienta se pone en producción.

## 6. Cuatro consideraciones principales del GAI Profile

El Appendix A resume cuatro temas transversales derivados del Generative AI Public Working Group. Estos ejes influyen en las acciones propuestas a lo largo del perfil: Governance, Pre-Deployment Testing, Content Provenance e Incident Disclosure.

### 6.1 Governance

La gobernanza debe adaptar las prácticas existentes a las particularidades de GAI. Puede requerirse mayor supervisión humana, documentación, seguimiento y participación de la dirección. También se recomienda revisar riesgos de proveedores, modelos externos y datos de terceros, ya que una organización puede heredar problemas de privacidad, seguridad o propiedad intelectual de componentes que no desarrolló.

### 6.2 Pre-Deployment Testing

Las pruebas previas al despliegue buscan medir desempeño, capacidades, límites, riesgos e impactos antes de liberar el sistema. NIST advierte que las pruebas de laboratorio, exámenes o benchmarks pueden no representar el comportamiento real. Por ello, deben complementarse con pruebas de campo, red teaming y retroalimentación de usuarios cuando sea apropiado.

### 6.3 Content Provenance

Content provenance se refiere a conocer y rastrear el origen y el historial del contenido. Puede incluir información sobre creador, sistema utilizado, fecha, modificaciones y fuentes. NIST menciona mecanismos como metadatos, marcas de agua digitales, huellas digitales y autenticación humana. Estas técnicas pueden apoyar la evaluación de autenticidad, integridad, propiedad intelectual y posibles manipulaciones, aunque no constituyen una garantía absoluta por sí solas.

### 6.4 Incident Disclosure

Incident disclosure se enfoca en registrar, analizar y comunicar incidentes relacionados con GAI. La documentación puede incluir logs, historiales de versión, metadatos, errores, near-misses e impactos negativos. Compartir información con actores relevantes y, cuando corresponda, con autoridades regulatorias permite aprender de los incidentes, rastrear su origen y reducir la probabilidad de recurrencia.

## 7. Relación con Legalidad y Protección de la Información

El NIST AI 600-1 resulta especialmente pertinente para una materia orientada a legalidad y protección de la información porque vincula la gestión técnica de GAI con obligaciones y riesgos organizacionales. El perfil no sustituye el análisis jurídico aplicable en cada jurisdicción, pero ayuda a identificar dónde pueden surgir problemas que requieren revisión legal, de privacidad, de seguridad o de gobernanza.

- Privacidad: uso de datos personales, memorización, inferencias y exposición de información sensible.
- Propiedad intelectual: origen y licencias de datos, reproducción de contenido y uso de identidad, imagen o voz.
- Seguridad: protección de modelos, datos, dependencias e interfaces frente a ataques o manipulación.
- Transparencia: documentación del sistema, procedencia del contenido y trazabilidad de decisiones e incidentes.
- Responsabilidad: definición de roles, supervisión humana, gestión de proveedores y criterios de desactivación.
- Integridad de la información: mitigación de misinformation, disinformation, deepfakes y suplantación.

## 8. Relación con los otros marcos NIST revisados

Los tres documentos pueden entenderse como capas complementarias. El NIST Privacy Framework aporta una estructura específica para gestionar riesgos de privacidad derivados del procesamiento de datos. El AI RMF 1.0 proporciona un marco general para gestionar riesgos de inteligencia artificial. El AI 600-1 toma ese marco y lo especializa para riesgos de inteligencia artificial generativa.

| **Documento**              | **Enfoque**              | **Pregunta orientadora**                                                                |
|----------------------------|--------------------------|-----------------------------------------------------------------------------------------|
| NIST Privacy Framework 1.0 | Riesgo de privacidad     | ¿Cómo gestionar los efectos del procesamiento de datos sobre las personas?              |
| NIST AI RMF 1.0            | Riesgo general de IA     | ¿Cómo gobernar, mapear, medir y gestionar los riesgos de sistemas de IA?                |
| NIST AI 600-1              | Riesgo específico de GAI | ¿Qué riesgos propios o intensificados por IA generativa deben atenderse y cómo hacerlo? |

## 9. Limitaciones y alcance del documento

El GAI Profile debe interpretarse como una guía de gestión de riesgos y no como una norma jurídica autónoma. Las acciones sugeridas no aplican de forma idéntica a todos los actores ni a todos los sistemas. Su pertinencia depende del contexto, del nivel de riesgo, de la etapa del ciclo de vida y del rol de cada organización.

NIST reconoce además que GAI evoluciona con rapidez, que varios métodos de medición siguen en desarrollo y que las pruebas previas al despliegue pueden no anticipar todos los efectos en el mundo real. Por ello, la gestión del riesgo debe ser iterativa, documentada y capaz de incorporar nueva evidencia.

## 10. Conclusiones

El NIST AI 600-1 ofrece una extensión práctica del AI RMF 1.0 para el contexto de la inteligencia artificial generativa. Su mayor valor no radica en proporcionar una lista cerrada de controles, sino en organizar la toma de decisiones alrededor de riesgos concretos que pueden afectar a personas, organizaciones y al ecosistema informativo.

El perfil identifica doce categorías de riesgo y propone gestionarlas mediante GOVERN, MAP, MEASURE y MANAGE. De forma transversal, destaca la importancia de la gobernanza, las pruebas antes del despliegue, la procedencia del contenido y la divulgación de incidentes. El mensaje central es que la adopción responsable de GAI requiere reglas claras, comprensión del contexto, evidencia sobre el desempeño, supervisión continua y capacidad para responder cuando los riesgos exceden los límites aceptables.

> [!NOTE]
> **Síntesis final**
>
> La inteligencia artificial generativa no debe evaluarse sólo por lo que puede hacer, sino también por cómo se usa, qué datos y terceros intervienen, qué daños puede producir y qué capacidad tiene la organización para detectar, explicar, corregir o detener sus fallos.


## Referencia principal

National Institute of Standards and Technology. (2024). Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (NIST AI 600-1). U.S. Department of Commerce.

Nota: esta síntesis fue elaborada exclusivamente con base en el contenido del NIST AI 600-1 proporcionado para la actividad. Se simplificaron identificadores y acciones altamente técnicas para priorizar comprensión conceptual, sin alterar la estructura general ni los riesgos definidos por el documento.

---

**Material relacionado:** [Caso práctico](./NIST_AI_600_1_Caso_Practico.md) · [Ishikawa del marco](./NIST_AI_600_1_Ishikawa_Documento.md) · [Ishikawa del caso](./NIST_AI_600_1_Ishikawa_Caso.md)
