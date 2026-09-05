#### Principios OECD Privacy Guidelines

Las OECD Privacy Guidelines proporcionan un marco conceptual sencillo pero profundo: los datos personales deben recopilarse de manera limitada y legítima, ser adecuados para su finalidad, utilizarse únicamente para propósitos compatibles, protegerse mediante salvaguardas apropiadas, manejarse con transparencia, permitir la participación de las personas y, sobre todo, estar respaldados por una responsabilidad organizacional demostrable.

Su importancia para Business Intelligence, Business Analytics, Data Science e Inteligencia Artificial radica precisamente en que estos principios no constituyen un conjunto de controles tecnológicos aislados. Representan una filosofía de gobierno que debe incorporarse al diseño, operación y supervisión de los sistemas de información.

Para una organización moderna, cumplir con estos principios significa pasar de una visión basada exclusivamente en “proteger bases de datos” hacia una visión integral de **gobernar el ciclo de vida de la información**. Esto resulta especialmente importante en IA generativa y agéntica, donde los datos pueden atravesar múltiples componentes y donde los sistemas pueden producir resultados o ejecutar acciones a una velocidad y escala que superan a los procesos tradicionales.

En última instancia, la privacidad debe considerarse no como una restricción para la innovación, sino como una condición para que la innovación basada en datos sea sostenible y confiable. La propia OCDE destaca que una protección de privacidad adecuada contribuye a generar confianza y facilita un entorno en el que los datos pueden utilizarse y compartirse de manera responsable.

El objetivo de este documento es explicar el significado de estos principios y, especialmente, mostrar cómo pueden convertirse en prácticas concretas de gobierno y protección de datos dentro del ciclo de vida analítico y de inteligencia artificial.

#### 1. Principio de limitación de la recopilación

El primer principio establece que la recopilación de datos personales debe tener límites y que los datos deben obtenerse mediante medios legales y justos y, cuando corresponda, con el conocimiento o consentimiento de la persona. 

Este principio cuestiona una práctica frecuente en las iniciativas de datos: recolectar información simplemente porque puede resultar potencialmente útil en el futuro. Desde una perspectiva de privacidad, almacenar grandes cantidades de información sin una finalidad claramente determinada incrementa la superficie de riesgo de la organización.

En Business Intelligence, este principio implica que una organización debe preguntarse qué atributos son realmente necesarios para construir un indicador, tablero o reporte. Por ejemplo, si un análisis de ventas requiere información agregada por región y segmento de cliente, podría no ser necesario incorporar nombres, números telefónicos, direcciones particulares u otros identificadores directos.

En Data Science, la limitación de recopilación debe incorporarse desde la etapa de diseño del conjunto de entrenamiento. Antes de incorporar una variable, el equipo debe determinar cuál es su finalidad, si es necesaria y qué riesgos introduce. Esta lógica resulta aún más importante en IA generativa, donde una organización podría estar tentada a enviar a un modelo información empresarial completa cuando solamente necesita una fracción de ella para generar una respuesta.

Una implementación práctica puede consistir en establecer un proceso de **data minimization** que incluya inventario de datos, clasificación por sensibilidad, justificación de cada atributo y revisión periódica de los datos que realmente se utilizan.

#### 2. Principio de calidad de los datos

El principio de calidad establece que los datos personales deben ser pertinentes para el propósito para el cual serán utilizados y, en la medida necesaria, deben ser exactos, completos y mantenerse actualizados. 

Este principio demuestra que privacidad y calidad de datos no son asuntos independientes. Un dato incorrecto puede generar no solamente un problema analítico, sino también consecuencias negativas para la persona a la que pertenece.

En BI, un dato incorrecto puede provocar indicadores financieros, comerciales o de comportamiento erróneos. En Data Science, datos sesgados, incompletos o desactualizados pueden producir modelos con menor capacidad predictiva. En inteligencia artificial generativa, información incorrecta utilizada como contexto puede producir respuestas incorrectas, y en sistemas agénticos puede provocar decisiones o acciones incorrectas ejecutadas automáticamente.

Por ello, implementar este principio implica establecer controles de **data quality** durante todo el ciclo de vida del dato. Entre ellos se encuentran reglas de validación, detección de duplicados, controles de integridad, mecanismos de actualización, trazabilidad de los datos y responsables claramente definidos para su calidad.

Una práctica especialmente relevante es asociar los datos críticos a un propietario o *data owner*, definir criterios de calidad y establecer mecanismos para identificar cuándo un dato deja de ser válido para determinado uso.

#### 3. Principio de especificación del propósito

La especificación del propósito exige que las finalidades de la recopilación sean determinadas, como máximo, en el momento de obtener los datos y que los usos posteriores se limiten a esas finalidades o a otras compatibles que sean especificadas cuando cambie el propósito. 

Este principio es fundamental para controlar el llamado *function creep*, es decir, la expansión progresiva de los usos de la información hacia finalidades que originalmente no habían sido previstas.

En un entorno de BI, por ejemplo, obtener información de clientes con el propósito de generar reportes comerciales no significa automáticamente que dicha información pueda utilizarse para construir un sistema de evaluación automatizada o alimentar un modelo de IA.

La implementación requiere registrar, para cada conjunto de datos, elementos como:

**dato → propietario → propósito → base jurídica aplicable → usuarios autorizados → sistemas que lo procesan → período de conservación → posibles usos posteriores.**

En Data Science, esta práctica puede materializarse mediante un **registro de casos de uso analíticos**. Cada proyecto debería documentar qué datos utiliza, para qué finalidad, qué resultados generará y si el procesamiento representa un cambio de propósito respecto de la recopilación original.

En IA generativa y agéntica, el principio adquiere especial importancia debido a que un mismo modelo puede utilizar información para múltiples funciones. La organización debe definir explícitamente si los datos pueden emplearse para inferencia, generación de contenido, recuperación mediante RAG, entrenamiento, evaluación, monitoreo u otras finalidades.

#### 4. Principio de limitación del uso

El principio de limitación del uso establece que los datos personales no deben divulgarse, ponerse a disposición o utilizarse para finalidades distintas de aquellas especificadas, salvo que exista consentimiento o autoridad legal que lo permita. 

Este principio convierte la privacidad en una cuestión de **control de acceso y control del propósito**.

En una plataforma de BI, por ejemplo, no debería ser suficiente que un usuario tenga acceso al sistema; también debe determinarse qué información puede consultar. Un ejecutivo podría necesitar indicadores agregados, mientras que un analista especializado podría necesitar información de mayor granularidad.

En Data Science, es recomendable utilizar entornos separados para desarrollo, pruebas y producción y evitar que los equipos trabajen directamente con datos personales completos cuando pueden utilizar datos anonimizados, seudonimizados o sintéticos.

En IA generativa, el principio puede implementarse mediante políticas que impidan incorporar información confidencial en herramientas o modelos que no hayan sido aprobados por la organización. También implica definir qué información puede utilizar un modelo como contexto y qué datos puede devolver.

En IA agéntica, la limitación del uso debe extenderse a las **acciones** del agente. Un agente puede tener capacidad para consultar bases de datos, ejecutar procesos, enviar mensajes o modificar registros. Por tanto, el control no debe limitarse al acceso al dato, sino también al alcance de las acciones que pueden realizarse con ese dato.

#### 5. Principio de salvaguardas de seguridad

El principio de seguridad exige proteger los datos personales mediante salvaguardas razonables frente a riesgos como pérdida, acceso no autorizado, destrucción, uso, modificación o divulgación. 

Este principio es especialmente relevante para la confidencialidad de los datos utilizados en analítica e inteligencia artificial.

La implementación debe combinar controles técnicos, administrativos y organizacionales. Entre los controles técnicos pueden incluirse cifrado, gestión de identidades y accesos, autenticación multifactor, segmentación de redes, registro de actividades, monitoreo, copias de seguridad y mecanismos de prevención de pérdida de información.

En BI, es recomendable implementar **seguridad a nivel de fila o columna**, de acuerdo con las necesidades del negocio. En Data Science, deben establecerse controles para los notebooks, repositorios, almacenes de datos, pipelines y ambientes de experimentación.

En IA generativa aparecen riesgos adicionales, como la exposición accidental de información confidencial mediante prompts, archivos cargados, mecanismos de recuperación documental o conversaciones almacenadas. En sistemas agénticos, además, deben considerarse riesgos derivados de herramientas externas y de las acciones ejecutadas por los agentes.

La seguridad, por tanto, debe contemplarse como una propiedad transversal del ciclo de vida del dato y no solamente como una función del departamento de tecnología.

#### 6. Principio de apertura

El principio de apertura establece que debe existir una política general de transparencia respecto de las prácticas y políticas relacionadas con los datos personales. Asimismo, deben existir medios accesibles para conocer la existencia y naturaleza de los datos tratados, sus principales finalidades y la identidad del responsable. 

En términos organizacionales, apertura significa que una persona no debería encontrarse frente a un sistema opaco en el cual desconoce qué información se utiliza sobre ella y con qué propósito.

Para implementarlo, una organización puede desarrollar avisos de privacidad, catálogos de tratamientos, registros de actividades de procesamiento, políticas internas y mecanismos de comunicación comprensibles.

En el contexto de IA, la transparencia debe ampliarse. Cuando un sistema utiliza información personal para producir resultados, la organización debería poder explicar, al nivel apropiado, qué datos intervienen, cuál es la finalidad del tratamiento y cuáles son las principales salvaguardas existentes.

Esta transparencia también es importante internamente. Los equipos de BI, Data Science e IA deberían saber qué fuentes de datos están autorizadas, qué restricciones tienen y quién puede acceder a ellas.

#### 7. Principio de participación individual

El principio de participación individual reconoce derechos de las personas respecto de sus datos. Entre ellos se encuentran conocer si un responsable posee información sobre ellas, obtener acceso a dicha información, recibir explicaciones cuando una solicitud sea rechazada y poder cuestionar los datos, incluyendo su rectificación, actualización, completitud o eliminación cuando corresponda. 

Este principio introduce al individuo como participante activo en el ciclo de vida de los datos.

En una organización orientada a datos, implementar este principio requiere desarrollar procesos capaces de localizar información personal distribuida entre distintas plataformas. Una persona puede estar registrada simultáneamente en un CRM, un data warehouse, un lago de datos, aplicaciones operativas y sistemas de IA.

Por esta razón, el gobierno de datos debe incorporar capacidades de **data lineage** y localización de información personal. Sin trazabilidad, responder adecuadamente a una solicitud de acceso, corrección o eliminación puede resultar técnicamente complejo.

En sistemas de IA, además, deben considerarse las consecuencias que la modificación de los datos fuente puede tener sobre procesos analíticos posteriores, bases vectoriales, índices de recuperación, datasets de entrenamiento y mecanismos de evaluación.

#### 8. Principio de accountability o responsabilidad

El principio de accountability establece que el responsable del tratamiento debe responder por el cumplimiento de las medidas destinadas a materializar los demás principios. 

Este principio es posiblemente el más importante desde una perspectiva de gobierno corporativo porque transforma la privacidad de una declaración de intenciones en una **responsabilidad demostrable**.

La revisión de 2013 incorporó específicamente una tercera parte dedicada a la implementación de accountability. La OCDE establece que el responsable debe contar con un **Privacy Management Programme**, adaptado a la estructura, escala, volumen y sensibilidad de sus operaciones; basado en evaluación de riesgos; integrado en la estructura de gobierno; con mecanismos de supervisión; planes de respuesta ante incidentes; y procesos de monitoreo y evaluación periódica. 

La OCDE también señala que estas salvaguardas pueden incluir disposiciones contractuales, capacitación del personal, auditorías y evaluaciones de impacto de privacidad. 

Para una organización que utiliza BI, Data Science e IA, accountability puede operacionalizarse mediante:

* un programa formal de gobierno de privacidad;
* inventario y clasificación de datos personales;
* evaluación de riesgos de privacidad;
* evaluaciones de impacto para nuevos tratamientos;
* políticas de retención y eliminación;
* controles de proveedores y terceros;
* auditorías;
* capacitación;
* gestión de incidentes;
* documentación de decisiones;
* métricas de cumplimiento;
* mecanismos de supervisión y mejora continua.

#### 9. Cómo convertir los ocho principios en un modelo operativo

Los principios de la OCDE no deben implementarse como controles aislados. Su verdadero valor aparece cuando se incorporan al ciclo de vida completo de los datos.

Una arquitectura de gobierno puede comenzar desde la **adquisición de los datos**, donde se determina qué información se necesita y con qué finalidad. Posteriormente, durante el almacenamiento, deben establecerse controles de acceso, clasificación, retención y seguridad.

Durante la preparación para BI, Analytics o Data Science deben comprobarse calidad, pertinencia, minimización y trazabilidad. Antes de utilizar los datos en un modelo de IA debe evaluarse nuevamente el propósito, los riesgos y las salvaguardas necesarias.

En la fase de operación deben mantenerse mecanismos de monitoreo, auditoría, gestión de incidentes y revisión periódica. Finalmente, cuando los datos ya no sean necesarios, deben aplicarse políticas de eliminación o anonimización apropiadas.

En consecuencia, un modelo de implementación podría representarse conceptualmente de la siguiente forma:

**Propósito → Minimización → Calidad → Acceso controlado → Seguridad → Transparencia → Derechos individuales → Accountability → Monitoreo continuo.**

La característica fundamental de este modelo es que la privacidad no ocurre únicamente cuando se recolecta la información. Debe permanecer presente durante todo su ciclo de vida.

#### 10. Aplicación específica a IA generativa y agéntica

La llegada de la IA generativa y de los sistemas agénticos introduce nuevas dimensiones para los principios de la OCDE.

Un modelo generativo puede recibir información mediante prompts, documentos, APIs, conectores, bases vectoriales o sistemas de recuperación de información. Cada una de estas fuentes representa una posible superficie de exposición.

En consecuencia, la limitación de recopilación exige evitar enviar información que no sea necesaria; la especificación del propósito exige definir por qué el modelo procesa la información; la limitación del uso requiere controlar qué puede hacer el sistema con ella; la seguridad exige proteger prompts, archivos, embeddings, registros y resultados; la apertura requiere documentar adecuadamente el funcionamiento y las políticas del sistema; y accountability exige identificar quién es responsable de cada sistema y de sus resultados.

Los sistemas agénticos añaden otra dimensión: el agente no solamente procesa información, sino que puede ejecutar acciones. Por ello, el gobierno debe establecer **límites de autonomía**, permisos mínimos, aprobación humana para acciones de alto impacto, registro de actividades y mecanismos de reversión.

En este sentido, los principios de la OCDE pueden actuar como una capa fundamental de gobierno para sistemas de IA, independientemente de si la implementación concreta utiliza machine learning clásico, modelos generativos, RAG, agentes autónomos u otras tecnologías emergentes.

_____________________________________________________

## Referencias bibliográficas

> Organisation for Economic Co-operation and Development. (2013). *The OECD privacy framework*. OECD Publishing. [https://www.oecd.org/sti/ieconomy/oecd_privacy_framework.pdf](https://www.oecd.org/sti/ieconomy/oecd_privacy_framework.pdf)

> Organisation for Economic Co-operation and Development. (2023). *Explanatory memoranda of the OECD Privacy Guidelines*. OECD Digital Economy Papers, No. 360. OECD Publishing. [https://doi.org/10.1787/ea4e9759-en](https://doi.org/10.1787/ea4e9759-en)

> Organisation for Economic Co-operation and Development. (2023). *Report on the implementation of the OECD Privacy Guidelines*. OECD Digital Economy Papers. OECD Publishing.

> Organisation for Economic Co-operation and Development. (2024). *Privacy and data protection*. OECD. [https://www.oecd.org/en/topics/privacy-and-data-protection.html](https://www.oecd.org/en/topics/privacy-and-data-protection.html)

> Organisation for Economic Co-operation and Development. (2024). *Privacy principles*. OECD. [https://www.oecd.org/en/topics/privacy-principles.html](https://www.oecd.org/en/topics/privacy-principles.html)
