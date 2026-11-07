# NIST Privacy Framework 1.0

> **Documento:** síntesis académica para consulta, adaptada del escrito original en Word.  
> **Ámbito:** Legalidad y Protección de la Información.  
> **Alcance:** Marco voluntario para gestionar riesgos de privacidad derivados del procesamiento de datos.

[Volver al índice](./NIST_Indice.md)

---

## 1. Introducción

El NIST Privacy Framework 1.0 es un marco desarrollado por el National Institute of Standards and Technology con el propósito de ayudar a las organizaciones a identificar, evaluar y gestionar los riesgos de privacidad derivados del procesamiento de datos. Su enfoque parte de la idea de que el uso de datos puede generar beneficios significativos para las organizaciones y para la sociedad, pero también puede producir consecuencias adversas para las personas.

El documento propone incorporar la privacidad dentro de la gestión integral de riesgos de una organización, de forma semejante a como se administran otros riesgos operativos, financieros o tecnológicos. Esta aproximación busca que la privacidad no sea tratada únicamente como una cuestión jurídica o técnica, sino como un componente transversal de la toma de decisiones.

El Privacy Framework no establece una lista rígida de requisitos ni constituye una certificación. Su diseño es flexible y pretende adaptarse a organizaciones de distinto tamaño, sector, nivel de madurez y contexto regulatorio. El Core, que constituye el componente central del marco, se concibe expresamente como una estructura basada en riesgos y no como una lista de verificación universal.

## 2. Naturaleza del instrumento

El NIST Privacy Framework debe entenderse como un marco voluntario de gestión de riesgos de privacidad.

Esto significa que:

- no sustituye leyes o reglamentos;
- no constituye por sí mismo una obligación jurídica;
- no certifica automáticamente a una organización como “cumplida”;
- no exige aplicar todas sus categorías y subcategorías;
- permite seleccionar y priorizar resultados de acuerdo con el contexto y el nivel de riesgo.

El documento establece que las organizaciones deben elegir los elementos del Core que respondan mejor a sus objetivos, papel dentro del ecosistema de procesamiento, requisitos legales o regulatorios, prioridades de gestión del riesgo y necesidades de privacidad de las personas afectadas.

Esta característica resulta especialmente importante en el ámbito de Legalidad y Protección de la Información, porque permite distinguir entre dos niveles diferentes:

**La obligación jurídica.** deriva de leyes, reglamentos, contratos o disposiciones aplicables.

**La gestión del riesgo de privacidad.** busca prevenir o reducir consecuencias adversas derivadas del tratamiento de datos.

## 3. Objetivo del Privacy Framework

El objetivo general del marco es permitir que una organización gestione los riesgos que pueden surgir cuando sus sistemas, productos o servicios procesan datos.

El enfoque no se limita a evitar filtraciones o ataques. NIST considera que el riesgo de privacidad puede existir incluso cuando el sistema funciona correctamente y no se ha producido ningún incidente de seguridad.

Por ello, el Privacy Framework busca que la organización comprenda:

- qué datos procesa;
- qué acciones realiza sobre ellos;
- para qué los utiliza;
- quiénes participan;
- qué riesgos pueden surgir;
- qué consecuencias pueden experimentar las personas;
- qué efectos posteriores puede enfrentar la organización.

En este sentido, la privacidad se incorpora a la gestión empresarial de riesgos y deja de considerarse un asunto aislado.

## 4. Conceptos fundamentales

### 4.1 Data

NIST define los datos como una representación de información, en formato digital o no digital.

### 4.2 Data Element

Un Data Element es la unidad de datos con nombre más pequeña que transmite información significativa. Ejemplos pueden ser nombre, edad, dirección, correo electrónico o código postal.

### 4.3 Data Action

Una Data Action es una operación realizada sobre los datos durante su ciclo de vida. Puede incluir recopilación, retención, registro, generación, transformación, uso, divulgación, compartición, transmisión o disposición.

### 4.4 Data Processing

El Data Processing es el conjunto de todas esas acciones sobre los datos a lo largo de su ciclo de vida.

### 4.5 Problematic Data Action

Una Problematic Data Action es una acción sobre datos que podría causar un efecto adverso para las personas.

### 4.6 Privacy Event

Un Privacy Event es la ocurrencia o posible ocurrencia de una acción problemática sobre los datos.

### 4.7 Privacy Breach

Una Privacy Breach implica pérdida de control, compromiso, adquisición o divulgación no autorizada de datos, o bien el acceso a ellos para un propósito no autorizado.

### 4.8 Privacy Risk

NIST define el riesgo de privacidad mediante la combinación de la probabilidad de que las personas experimenten problemas derivados del procesamiento y el impacto de esos problemas si ocurren. De manera conceptual: Riesgo de privacidad = probabilidad + impacto.

### 4.9 Privacy Risk Assessment

La Privacy Risk Assessment es el subproceso utilizado para identificar y evaluar riesgos específicos de privacidad.

### 4.10 Privacy Risk Management

La Privacy Risk Management es el conjunto de procesos organizacionales para identificar, evaluar y responder a los riesgos de privacidad.

## 5. Privacidad y ciberseguridad

Uno de los aportes conceptuales más importantes del Privacy Framework es distinguir entre privacidad y ciberseguridad.

Ambas disciplinas se relacionan, pero no son equivalentes.

La ciberseguridad suele centrarse en proteger:

- confidencialidad;
- integridad;
- disponibilidad.

El glosario define estos tres principios como restricciones adecuadas de acceso y divulgación, protección frente a modificación o destrucción indebida, y disponibilidad oportuna y confiable de la información.

Sin embargo, un sistema puede mantener estas propiedades y todavía generar problemas de privacidad.

Por ejemplo, una organización puede almacenar de manera segura información de ubicación y evitar todo acceso no autorizado, pero el simple hecho de conservar esa información durante periodos excesivos o utilizarla para inferir hábitos personales puede generar un riesgo de privacidad.

Por ello, un sistema seguro no es necesariamente un sistema que gestiona adecuadamente la privacidad.

## 6. Estructura general del Privacy Framework

El Privacy Framework se estructura en tres componentes principales: Core, Profiles e Implementation Tiers.

### 6.1 Core

El Core contiene las actividades y resultados de privacidad organizados en: Functions → Categories → Subcategories.

Las Functions representan el nivel más general; las Categories agrupan resultados relacionados; y las Subcategories describen resultados específicos de gestión o técnicos.

Las cinco Functions son:

- Identify-P;
- Govern-P;
- Control-P;
- Communicate-P;
- Protect-P.

## 7. Functions del Privacy Framework

### 7.1 Identify-P

Identify-P busca desarrollar el conocimiento organizacional necesario para gestionar los riesgos de privacidad derivados del procesamiento de datos.

Sus Categories son:

- ID.IM-P — Inventory and Mapping
- ID.BE-P — Business Environment
- ID.RA-P — Risk Assessment
- ID.DE-P — Data Processing Ecosystem Risk Management

Esta Function permite responder preguntas como:

- ¿qué datos se procesan?
- ¿de quién son?
- ¿dónde se encuentran?
- ¿qué sistemas participan?
- ¿qué terceros intervienen?
- ¿qué riesgos existen?

Su propósito es que la organización comprenda su entorno antes de tomar decisiones.

### 7.2 Govern-P

Govern-P se enfoca en crear una estructura de gobierno capaz de gestionar continuamente las prioridades de riesgo relacionadas con privacidad.

Sus Categories son:

- GV.PO-P — Governance Policies, Processes, and Procedures
- GV.RM-P — Risk Management Strategy
- GV.AT-P — Awareness and Training
- GV.MT-P — Monitoring and Review

Incluye aspectos como:

- políticas;
- roles;
- responsabilidades;
- requisitos legales y contractuales;
- tolerancia al riesgo;
- capacitación;
- monitoreo.

El Core establece expresamente que los requisitos legales, regulatorios y contractuales relacionados con privacidad deben comprenderse y gestionarse.

### 7.3 Control-P

Control-P busca permitir que organizaciones e individuos gestionen los datos con suficiente granularidad para reducir riesgos de privacidad.

Sus Categories son:

- CT.PO-P — Data Processing Policies, Processes, and Procedures
- CT.DM-P — Data Processing Management
- CT.DP-P — Disassociated Processing

Incluye:

- autorizar procesamiento;
- revocar autorizaciones;
- revisar datos;
- transferirlos;
- modificarlos;
- eliminarlos;
- destruirlos;
- registrar operaciones;
- aplicar técnicas que reduzcan identificación o vinculación.

Además, NIST contempla mecanismos de desidentificación, tokenización, procesamiento local o reducción de inferencias sobre las personas.

### 7.4 Communicate-P

Communicate-P busca que organizaciones e individuos tengan conocimiento confiable sobre cómo se procesan los datos y puedan mantener un diálogo sobre los riesgos asociados.

Sus Categories son:

- CM.PO-P — Communication Policies, Processes, and Procedures
- CM.AW-P — Data Processing Awareness

Incluye:

- transparencia;
- avisos;
- visibilidad;
- retroalimentación;
- registros de divulgaciones;
- procedencia;
- linaje de datos;
- notificación de eventos de privacidad;
- mecanismos de mitigación.

NIST contempla expresamente mantener registros de divulgaciones y compartir información sobre correcciones, eliminaciones, procedencia y linaje de los datos.

### 7.5 Protect-P

Protect-P busca desarrollar e implementar salvaguardas apropiadas para el procesamiento de datos.

Sus Categories son:

- PR.PO-P — Data Protection Policies, Processes, and Procedures
- PR.AC-P — Identity Management, Authentication, and Access Control
- PR.DS-P — Data Security
- PR.MA-P — Maintenance
- PR.PT-P — Protective Technology

Incluye:

- configuraciones seguras;
- respaldos;
- control de acceso;
- autenticación;
- mínimo privilegio;
- protección de datos en reposo y tránsito;
- gestión de vulnerabilidades;
- mantenimiento seguro;
- resiliencia.

NIST también contempla planes de respuesta, continuidad y recuperación, así como pruebas de esos planes.

## 8. Profiles

Los Profiles permiten adaptar el Privacy Framework al contexto particular de cada organización.

Un Profile consiste en una selección priorizada de Functions, Categories y Subcategories.

Se distinguen dos tipos principales:

**Current Profile.** representa la situación actual de la organización.

**Target Profile.** representa los resultados de privacidad que la organización desea alcanzar.

La diferencia entre ambos permite identificar:

- brechas;
- prioridades;
- necesidades de recursos;
- acciones de mejora.

Por tanto: Current Profile → brecha → Target Profile.

## 9. Implementation Tiers

Los Implementation Tiers sirven como referencia para evaluar cómo una organización comprende y gestiona el riesgo de privacidad y si cuenta con procesos y recursos adecuados.

Existen cuatro niveles:

**Tier 1 — Partial.** Gestión informal, reactiva y poco estructurada.

**Tier 2 — Risk Informed.** Existe reconocimiento del riesgo, pero la gestión todavía no está completamente institucionalizada.

**Tier 3 — Repeatable.** Los procesos son formales, repetibles, revisados y aplicados de forma organizacional.

**Tier 4 — Adaptive.** La organización aprende de eventos previos, identifica nuevos riesgos y adapta continuamente sus prácticas.

Es importante aclarar que estos Tiers no representan una certificación ni una obligación automática de alcanzar el nivel 4.

## 10. Aplicación práctica del Privacy Framework

NIST propone el modelo Ready → Set → Go para establecer o mejorar un programa de privacidad.

**Ready.** La organización analiza misión, contexto jurídico, tolerancia al riesgo, sistemas, servicios, riesgos y roles dentro del ecosistema.

**Set.** Construye o completa Current Profile, Target Profile, análisis de brechas y plan de acción.

**Go.** Implementa las acciones priorizadas y ajusta las prácticas existentes. El proceso puede repetirse y no necesita ser estrictamente secuencial.

## 11. Integración con el ciclo de vida de los sistemas

El Privacy Framework puede integrarse con el System Development Life Cycle.

NIST considera fases como: plan → design → build/buy → deploy → operate → decommission, y señala que los requisitos de privacidad deben incorporarse desde la planeación y mantenerse durante toda la vida del sistema.

Además, el ciclo de vida del sistema debe alinearse con el ciclo de vida de los datos, desde su creación o recopilación hasta su destrucción o eliminación.

Esto permite incorporar privacidad desde el diseño, en lugar de tratarla únicamente al final.

## 12. Gestión del riesgo de privacidad

El Appendix D desarrolla de manera más operativa la gestión del riesgo.

NIST propone considerar:

- Problematic Data Action
- Likelihood
- Impact

La evaluación del riesgo permite identificar y priorizar riesgos producidos por sistemas, productos o servicios.

NIST reconoce que el impacto puede ser difícil de valorar porque las consecuencias son experimentadas por las personas y pueden ser subjetivas.

Después de identificar y priorizar riesgos, las respuestas posibles incluyen:

- mitigación;
- transferencia o compartición;
- evitación;
- aceptación.

## 13. Capacidades y requisitos de privacidad

NIST identifica tres objetivos de ingeniería de privacidad:

**Predictability.** que individuos y operadores puedan realizar suposiciones confiables sobre cómo se procesarán los datos.

**Manageability.** que exista capacidad para administrar los datos de manera granular.

**Disassociability.** que el procesamiento pueda realizarse sin asociar innecesariamente los datos con personas o dispositivos.

Estos objetivos complementan los objetivos clásicos de seguridad:

- confidencialidad;
- integridad;
- disponibilidad.

A partir de ellos pueden definirse Privacy Requirements, es decir, especificaciones de cómo debe funcionar un sistema para alcanzar determinados resultados de privacidad.

## 14. Trazabilidad y controles

Una vez identificados los riesgos que deben mitigarse, la organización puede:

1.  definir requisitos de privacidad;

2.  seleccionar controles;

3.  implementarlos;

4.  evaluar su efectividad;

5.  establecer trazabilidad entre riesgo, requisito y control.

NIST reconoce controles:

- técnicos;
- físicos;
- administrativos o de política.

La relación puede expresarse así: Riesgo → Requisito → Control → Implementación → Evaluación.

Esta trazabilidad fortalece la rendición de cuentas.

## 15. Relación con legalidad y protección de la información

En el contexto de la materia Legalidad y Protección de la Información, el NIST Privacy Framework es particularmente relevante porque permite estructurar la gestión de privacidad alrededor de:

- obligaciones jurídicas;
- riesgos;
- políticas;
- controles;
- responsabilidades;
- evaluación;
- monitoreo.

Sin embargo, debe mantenerse clara la diferencia entre cumplimiento normativo y gestión del riesgo de privacidad.

El propio framework contempla que los requisitos legales, regulatorios y contractuales deben ser comprendidos y gestionados, pero su función no es sustituir esos requisitos.

Por ello, una organización puede utilizar el Privacy Framework como una estructura para relacionar posteriormente:

- leyes;
- reglamentos;
- contratos;
- estándares;
- políticas internas;
- controles técnicos.

Esto hace que el framework sea especialmente útil como base para una herramienta de consulta normativa.

## 16. Limitaciones del marco

El Privacy Framework no debe interpretarse como:

- ley;
- reglamento;
- certificación;
- checklist obligatoria;
- solución técnica única;
- sustituto del análisis jurídico.

Su aplicación depende del contexto, del tipo de organización, de sus riesgos y de sus objetivos.

Asimismo, el Core no es exhaustivo y puede ampliarse con Functions, Categories o Subcategories adicionales cuando sea necesario.

## 17. Conclusiones

El NIST Privacy Framework 1.0 propone una forma estructurada de integrar la privacidad dentro de la gestión general de riesgos de una organización.

Su principal aporte consiste en ampliar la visión de privacidad más allá de la ciberseguridad y del cumplimiento formal. El marco obliga a considerar no sólo si los datos están protegidos, sino también qué información se procesa, para qué, quién participa, qué consecuencias pueden generarse y cómo debe responder la organización.

Las cinco Functions del Core permiten abordar el problema desde distintas dimensiones:

**Identify-P.** permite conocer los datos, procesos y riesgos.

**Govern-P.** establece reglas, responsabilidades y tolerancia al riesgo.

**Control-P.** permite gestionar el tratamiento de los datos.

**Communicate-P.** promueve transparencia, trazabilidad y diálogo.

**Protect-P.** establece salvaguardas técnicas y organizacionales.

Los Profiles permiten adaptar el marco al contexto de cada organización y los Implementation Tiers ayudan a analizar su nivel de desarrollo en la gestión del riesgo.

En conjunto, el Privacy Framework constituye una herramienta útil para vincular privacidad, gestión empresarial, tecnología, responsabilidades organizacionales y requisitos legales, sin sustituir las normas jurídicas aplicables.

## 18. Palabras clave para la herramienta de consulta

NIST Privacy Framework; privacidad; gestión de riesgos; datos; Data Action; Data Processing; Privacy Risk; Privacy Risk Assessment; Privacy Event; Privacy Breach; Problematic Data Action; Identify-P; Govern-P; Control-P; Communicate-P; Protect-P; Current Profile; Target Profile; Implementation Tiers; Predictability; Manageability; Disassociability; Privacy Requirement; Privacy Control; trazabilidad; rendición de cuentas; ciclo de vida del dato; SDLC; terceros; cumplimiento; riesgo.

## Referencia del documento base

National Institute of Standards and Technology. (2020). NIST Privacy Framework: A Tool for Improving Privacy Through Enterprise Risk Management, Version 1.0.

---

**Material relacionado:** [Caso práctico](./NIST_Privacy_Framework_Caso_Practico.md) · [Ishikawa del marco](./NIST_Privacy_Framework_Ishikawa_Documento.md) · [Ishikawa del caso](./NIST_Privacy_Framework_Ishikawa_Caso.md)
