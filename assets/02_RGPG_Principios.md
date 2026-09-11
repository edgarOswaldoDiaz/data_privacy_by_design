# Principios del Reglamento General de Protección de Datos (RGPD)

## 1. Introducción

El artículo 5 del Reglamento General de Protección de Datos (RGPD) establece los principios fundamentales que deben respetarse durante el tratamiento de datos personales.

Estos principios orientan la forma en que una organización debe recopilar, utilizar, almacenar, actualizar, proteger y eliminar información personal.

Los siete principios son:

1. Licitud, lealtad y transparencia.
2. Limitación de la finalidad.
3. Minimización de datos.
4. Exactitud.
5. Limitación del plazo de conservación.
6. Integridad y confidencialidad.
7. Responsabilidad proactiva.

Estos principios deben considerarse durante todo el ciclo de vida de los datos personales y sirven como base para determinar si un tratamiento se realiza de manera adecuada conforme al RGPD.

---

# 2. Principio de licitud, lealtad y transparencia

## Definición

Los datos personales deben ser tratados de manera **lícita, leal y transparente** respecto de la persona interesada.

Este principio reúne tres elementos:

* **Licitud:** debe existir una base jurídica válida que permita realizar el tratamiento.
* **Lealtad:** los datos no deben utilizarse de manera injusta, engañosa o perjudicial para el interesado.
* **Transparencia:** la persona debe recibir información clara sobre quién utiliza sus datos, para qué los utiliza y cómo serán tratados.

## ¿Qué implica?

Una organización no debe recopilar información personal simplemente porque técnicamente puede hacerlo.

Antes de realizar el tratamiento debe determinar su fundamento jurídico e informar a las personas de manera clara y comprensible sobre el uso de sus datos.

## Ejemplo

Una plataforma solicita nombre y correo electrónico para crear una cuenta.

Antes de completar el registro, informa al usuario sobre:

* quién es responsable del tratamiento;
* para qué utilizará sus datos;
* durante cuánto tiempo los conservará; y
* cuáles son sus derechos.

## Ejemplo de incumplimiento

Una aplicación recopila información indicando que será utilizada exclusivamente para prestar un servicio, pero posteriormente utiliza esos datos para otros tratamientos sin informar adecuadamente a los usuarios ni contar con una base jurídica que los permita.

## Aplicación en sistemas de información e IA

Un sistema que utiliza datos personales debe permitir identificar:

* el origen de los datos;
* la finalidad del tratamiento;
* la base jurídica correspondiente;
* los usuarios o sistemas autorizados para acceder a ellos; y
* la información proporcionada al interesado.

En sistemas basados en Inteligencia Artificial también debe analizarse si las personas comprenden de manera suficiente cómo intervienen sus datos personales en el tratamiento.

## Pregunta de diagnóstico

> ¿La persona sabe quién utiliza sus datos, para qué serán utilizados y cuál es la base jurídica que permite su tratamiento?

## Fundamento jurídico

**Artículo 5.1.a del RGPD.**

## Palabras clave

Licitud, lealtad, transparencia, tratamiento lícito, información al interesado, privacidad, RGPD, GDPR.

---

# 3. Principio de limitación de la finalidad

## Definición

Los datos personales deben recopilarse con **fines determinados, explícitos y legítimos** y, como regla general, no deben utilizarse posteriormente de manera incompatible con esos fines.

## ¿Qué implica?

Antes de recopilar datos personales debe existir una razón concreta para hacerlo.

No es suficiente indicar finalidades excesivamente generales como:

> "Recopilamos información para utilizarla cuando sea necesaria."

La organización debe poder explicar qué pretende hacer con los datos.

## Ejemplo

Una institución solicita el correo electrónico de una persona exclusivamente para enviarle información relacionada con un curso en el que se encuentra inscrita.

El correo debe utilizarse conforme a esa finalidad y a la base jurídica aplicable.

## Ejemplo de incumplimiento

La institución posteriormente entrega la base de correos electrónicos a otra empresa para realizar una campaña comercial sin haber determinado que ese tratamiento posterior sea compatible ni contar con otro fundamento jurídico adecuado.

## Aplicación en sistemas de información e IA

Cuando una base de datos es utilizada posteriormente para entrenar, alimentar o complementar un sistema de Inteligencia Artificial, debe analizarse si este nuevo tratamiento es compatible con la finalidad para la cual los datos fueron obtenidos originalmente o si requiere otro fundamento jurídico.

El hecho de que una organización ya posea los datos no significa automáticamente que pueda utilizarlos para cualquier proyecto tecnológico posterior.

## Pregunta de diagnóstico

> ¿Los datos se están utilizando para la misma finalidad para la cual fueron recopilados o existe una justificación jurídica para el nuevo tratamiento?

## Fundamento jurídico

**Artículo 5.1.b del RGPD.**

También puede resultar relevante el **artículo 6.4**, relacionado con la evaluación de compatibilidad de tratamientos posteriores.

## Palabras clave

Limitación de finalidad, propósito, reutilización de datos, tratamiento posterior, compatibilidad, IA, entrenamiento de modelos.

---

# 4. Principio de minimización de datos

## Definición

Los datos personales tratados deben ser **adecuados, pertinentes y limitados a lo necesario** para alcanzar la finalidad establecida.

## ¿Qué implica?

Una organización debe preguntarse qué información necesita realmente antes de recopilarla.

Que un dato pueda ser útil en algún momento no significa necesariamente que deba recopilarse.

## Ejemplo

Una aplicación necesita enviar al usuario una confirmación de registro por correo electrónico.

Para esa finalidad puede necesitar:

* nombre;
* correo electrónico.

En principio, no sería necesario solicitar adicionalmente información como:

* estado civil;
* domicilio;
* profesión;
* ubicación permanente.

La necesidad concreta de cada dato dependerá de la finalidad del tratamiento.

## Ejemplo de incumplimiento

Una aplicación solicita diez categorías de información personal cuando solamente necesita dos para prestar el servicio solicitado.

## Aplicación en sistemas de información e IA

Antes de incorporar una base de datos a un sistema de IA o LLM debe evaluarse si **todas las columnas, documentos o atributos personales son realmente necesarios**.

Una estrategia puede consistir en eliminar o transformar información que no sea necesaria antes de incorporarla al sistema.

Por ejemplo, si un asistente necesita consultar procedimientos internos pero los documentos contienen nombres, teléfonos y correos que no son relevantes para responder las preguntas, podría analizarse la eliminación o anonimización de esos datos antes de indexar los documentos.

## Pregunta de diagnóstico

> ¿Podría obtenerse el mismo resultado utilizando menos datos personales?

## Fundamento jurídico

**Artículo 5.1.c del RGPD.**

## Palabras clave

Minimización de datos, datos necesarios, datos excesivos, reducción de datos, anonimización, RAG, LLM, bases de datos.

---

# 5. Principio de exactitud

## Definición

Los datos personales deben ser **exactos y, cuando sea necesario, mantenerse actualizados**.

Cuando existan datos incorrectos deben adoptarse medidas razonables para rectificarlos o eliminarlos sin demora, teniendo en cuenta la finalidad del tratamiento.

## ¿Qué implica?

Las organizaciones deben evitar que decisiones o procesos se realicen utilizando información incorrecta o desactualizada.

La importancia de mantener actualizados los datos dependerá de la finalidad para la cual se utilizan.

## Ejemplo

Una empresa mantiene una base de datos de empleados utilizada para generar información administrativa.

Cuando una persona cambia de puesto, la información correspondiente debe actualizarse cuando sea necesario para que el sistema refleje correctamente su situación.

## Ejemplo de incumplimiento

Un sistema utiliza información laboral antigua y clasifica incorrectamente a una persona porque los datos no fueron actualizados.

## Aplicación en sistemas de información e IA

Este principio es especialmente relevante cuando los datos personales son utilizados para:

* generar recomendaciones;
* clasificar personas;
* realizar perfiles;
* generar reportes;
* apoyar decisiones;
* automatizar procesos.

Un modelo puede funcionar técnicamente de manera correcta y, aun así, producir resultados incorrectos si la información utilizada está desactualizada o contiene errores.

## Pregunta de diagnóstico

> ¿Los datos utilizados por el sistema representan correctamente la situación actual de la persona?

## Fundamento jurídico

**Artículo 5.1.d del RGPD.**

## Palabras clave

Exactitud, calidad de datos, actualización, datos incorrectos, rectificación, calidad de información, IA.

---

# 6. Principio de limitación del plazo de conservación

## Definición

Los datos personales deben conservarse de forma que permitan identificar a las personas **únicamente durante el tiempo necesario** para cumplir las finalidades del tratamiento.

## ¿Qué implica?

Una organización no debería conservar información personal indefinidamente únicamente porque dispone de capacidad para almacenarla.

Debe establecer criterios o periodos para:

* conservar;
* revisar;
* archivar;
* anonimizar; o
* eliminar los datos.

Existen situaciones en las que los datos pueden conservarse durante periodos más prolongados, por ejemplo, para determinados fines de archivo en interés público, investigación científica o histórica o fines estadísticos, siempre que se cumplan las condiciones y garantías previstas en el RGPD.

## Ejemplo

Una organización recibe currículums para cubrir una vacante.

Una vez terminado el proceso debe determinar durante cuánto tiempo existe una razón válida para conservar esa información.

## Ejemplo de incumplimiento

La organización mantiene indefinidamente todos los currículums recibidos sin haber definido una finalidad o política de conservación adecuada.

## Aplicación en sistemas de información e IA

Los sistemas deben contemplar políticas de retención.

En soluciones que utilizan LLM pueden existir diferentes lugares donde se almacena información:

* documentos originales;
* bases de datos;
* índices de búsqueda;
* historiales de conversación;
* registros del sistema;
* copias de seguridad.

La organización debe analizar el periodo de conservación correspondiente a cada componente.

## Pregunta de diagnóstico

> ¿Existe una razón válida para seguir conservando estos datos personales?

## Fundamento jurídico

**Artículo 5.1.e del RGPD.**

## Palabras clave

Conservación, retención, eliminación, almacenamiento, ciclo de vida, historial, logs, copias de seguridad.

---

# 7. Principio de integridad y confidencialidad

## Definición

Los datos personales deben tratarse de manera que se garantice una **seguridad adecuada**, incluida su protección frente al tratamiento no autorizado o ilícito y frente a pérdida, destrucción o daño accidental.

Para ello deben utilizarse medidas técnicas y organizativas apropiadas.

## ¿Qué implica?

La protección de datos no consiste solamente en colocar una contraseña.

Dependiendo del riesgo y del tratamiento realizado, pueden considerarse medidas como:

* controles de acceso;
* autenticación;
* cifrado;
* seudonimización;
* copias de seguridad;
* registro y supervisión de accesos;
* administración de privilegios;
* capacitación del personal;
* procedimientos para responder a incidentes.

## Ejemplo

Una organización mantiene una base de datos con información personal y establece diferentes niveles de acceso dependiendo de las funciones de cada usuario.

## Ejemplo de incumplimiento

Todos los empleados tienen acceso a una base de datos que contiene información personal aunque la mayoría no necesita consultar esos datos para realizar sus funciones.

## Aplicación en sistemas de información e IA

En un sistema basado en LLM debe analizarse, entre otras cuestiones:

* quién puede consultar el sistema;
* a qué documentos puede acceder;
* qué información puede aparecer en las respuestas;
* cómo se protegen las credenciales;
* dónde se almacenan los datos;
* qué información queda registrada;
* cómo se controla el acceso a las fuentes utilizadas por el modelo.

Un sistema no debería permitir que un usuario obtenga mediante una consulta información personal a la que normalmente no tendría autorización para acceder.

## Pregunta de diagnóstico

> ¿Los datos están protegidos frente a accesos, modificaciones, divulgaciones, pérdidas o destrucciones no autorizadas?

## Fundamento jurídico

**Artículo 5.1.f del RGPD.**

La seguridad del tratamiento se desarrolla también, entre otros, en el **artículo 32 del RGPD**.

## Palabras clave

Integridad, confidencialidad, seguridad, control de acceso, cifrado, autorización, filtración, brecha de datos, LLM.

---

# 8. Principio de responsabilidad proactiva

## Definición

El responsable del tratamiento debe **cumplir los principios establecidos en el RGPD y ser capaz de demostrar dicho cumplimiento**.

Este principio también es conocido como **accountability**.

## ¿Qué implica?

No basta con afirmar que una organización protege los datos personales.

Debe poder demostrar las decisiones, controles y medidas adoptadas para cumplir con la normativa.

Dependiendo del tratamiento y de las obligaciones aplicables, esto puede involucrar elementos como:

* políticas y procedimientos;
* documentación de tratamientos;
* asignación de responsabilidades;
* controles internos;
* evaluaciones de riesgo;
* medidas de seguridad;
* capacitación;
* revisiones periódicas;
* evaluaciones de impacto cuando correspondan.

## Ejemplo

Una organización implementa un nuevo sistema que utiliza información personal.

Antes de ponerlo en funcionamiento identifica:

1. qué datos utilizará;
2. para qué serán utilizados;
3. cuál es la base jurídica;
4. quién tendrá acceso;
5. cuánto tiempo serán conservados;
6. cuáles son los riesgos;
7. qué medidas se aplicarán para reducir esos riesgos.

Además, conserva documentación que permite demostrar las decisiones adoptadas.

## Ejemplo de incumplimiento

Una organización afirma cumplir con el RGPD, pero no puede explicar qué datos trata, quién puede acceder a ellos, cuánto tiempo se conservan ni qué controles se aplican.

## Aplicación en sistemas de información e IA

Antes de implementar un sistema de IA que utilice datos personales conviene documentar las decisiones relacionadas con protección de datos.

Por ejemplo:

* fuentes de información utilizadas;
* categorías de datos personales;
* finalidad;
* base jurídica;
* controles de acceso;
* riesgos identificados;
* medidas de mitigación;
* políticas de conservación;
* mecanismos para atender derechos de los interesados.

La responsabilidad proactiva convierte la protección de datos en un proceso continuo y demostrable.

## Pregunta de diagnóstico

> ¿La organización puede demostrar por qué y cómo su tratamiento de datos personales cumple con el RGPD?

## Fundamento jurídico

**Artículo 5.2 del RGPD.**

## Palabras clave

Responsabilidad proactiva, accountability, cumplimiento, evidencia, documentación, auditoría, gobernanza, gestión de riesgos.

---

# 9. Relación entre los principios

Los siete principios no deben analizarse de manera completamente aislada.

Un mismo tratamiento puede involucrar simultáneamente varios principios.

### Ejemplo

Una aplicación solicita:

* nombre;
* correo electrónico;
* fecha de nacimiento;
* domicilio;
* ubicación;
* profesión.

Sin embargo, para prestar el servicio solamente necesita el nombre y el correo electrónico.

Además, conserva toda la información indefinidamente y cualquier empleado puede consultarla.

En este escenario podrían existir problemas relacionados con diferentes principios:

| Situación                                                | Principio relacionado                |
| -------------------------------------------------------- | ------------------------------------ |
| Se solicitan datos innecesarios                          | Minimización de datos                |
| No se explica claramente para qué se utilizarán          | Transparencia                        |
| Los datos se utilizan posteriormente para otra finalidad | Limitación de la finalidad           |
| Se conservan indefinidamente                             | Limitación del plazo de conservación |
| Cualquier empleado puede acceder                         | Integridad y confidencialidad        |
| No existen políticas ni documentación                    | Responsabilidad proactiva            |

Por lo tanto, el análisis de cumplimiento debe considerar el tratamiento completo y no solamente un principio de manera individual.

---

# 10. Aplicación de los principios en un LLM

Cuando un sistema basado en un Large Language Model procesa información personal, los principios pueden utilizarse como una guía inicial de análisis.

| Principio                        | Pregunta aplicada a un LLM                                                                  |
| -------------------------------- | ------------------------------------------------------------------------------------------- |
| Licitud, lealtad y transparencia | ¿Existe una base jurídica y las personas conocen cómo se utilizan sus datos?                |
| Limitación de la finalidad       | ¿Los datos se utilizan para la finalidad para la que fueron obtenidos?                      |
| Minimización                     | ¿El modelo necesita realmente todos los datos personales disponibles?                       |
| Exactitud                        | ¿La información utilizada está actualizada y es suficientemente correcta para la finalidad? |
| Limitación de conservación       | ¿Durante cuánto tiempo permanecen los datos en documentos, registros e historiales?         |
| Integridad y confidencialidad    | ¿Puede el sistema revelar información a usuarios no autorizados?                            |
| Responsabilidad proactiva        | ¿Puede la organización demostrar las decisiones y controles aplicados?                      |

Estos principios permiten realizar una primera evaluación, pero no sustituyen el análisis de otras disposiciones del RGPD, como las bases jurídicas, los derechos de los interesados, la seguridad del tratamiento o las reglas relacionadas con determinadas decisiones automatizadas.

---

# 11. Guía rápida para identificación de principios

Ante un caso práctico pueden utilizarse las siguientes preguntas:

**¿Se recopilan más datos de los necesarios?**
→ Minimización de datos.

**¿Los datos se utilizan para algo diferente de la finalidad original?**
→ Limitación de la finalidad.

**¿La persona desconoce qué se hace con sus datos?**
→ Licitud, lealtad y transparencia.

**¿La información es incorrecta o está desactualizada?**
→ Exactitud.

**¿Los datos se conservan sin una justificación temporal?**
→ Limitación del plazo de conservación.

**¿Personas no autorizadas pueden consultar la información?**
→ Integridad y confidencialidad.

**¿La organización no puede demostrar qué controles aplica?**
→ Responsabilidad proactiva.

Un caso puede relacionarse con **más de un principio simultáneamente**.

---

# 12. Conceptos clave para recuperación de información

**Palabras clave generales:** RGPD, GDPR, principios de protección de datos, artículo 5, licitud, lealtad, transparencia, finalidad, minimización, exactitud, conservación, integridad, confidencialidad, responsabilidad proactiva, accountability, protección de datos, privacidad, Inteligencia Artificial, LLM.

**Artículo principal:** artículo 5 del Reglamento (UE) 2016/679.

**Artículos relacionados:** artículos 6, 25 y 32, entre otros, dependiendo del tratamiento analizado.

---

# 13. Fuentes oficiales

* Reglamento (UE) 2016/679 — EUR-Lex:
  https://eur-lex.europa.eu/eli/reg/2016/679

* Comisión Europea — Principios del RGPD:
  https://commission.europa.eu/law/law-topic/data-protection/information-business-and-organisations/principles-gdpr_en

* Comisión Europea — Protección de datos explicada:
  https://commission.europa.eu/law/law-topic/data-protection/data-protection-explained_en

---

> **Nota:** Este documento tiene fines académicos e informativos y no constituye asesoramiento jurídico.
