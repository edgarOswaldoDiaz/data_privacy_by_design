#### Caso de uso

La empresa **DataNova Labs, S.A. de C.V.** es una empresa ficticia especializada en el desarrollo de prototipos computacionales para organizaciones que desean experimentar y validar soluciones basadas en **Ciencia de Datos, Business Analytics, Inteligencia Artificial Generativa e Inteligencia Artificial Agéntica**.

Su modelo de negocio consiste en transformar problemas empresariales en prototipos tecnológicos que permitan evaluar rápidamente la factibilidad de una solución antes de realizar una inversión significativa en infraestructura y desarrollo productivo.

Entre sus servicios se encuentran el desarrollo de modelos predictivos, segmentación de clientes, sistemas de recomendación, procesamiento de lenguaje natural, asistentes basados en modelos de lenguaje, generación automática de reportes, análisis de grandes volúmenes de información y agentes de inteligencia artificial capaces de consultar diferentes fuentes de información y ejecutar tareas empresariales bajo determinadas reglas.

Un cliente de DataNova Labs, una empresa ficticia denominada **Comercializadora Global**, solicita el desarrollo de un prototipo de IA que permita analizar información histórica de ventas, inventarios, comportamiento de clientes y documentos internos para generar recomendaciones comerciales. En una segunda fase, el cliente solicita que el prototipo evolucione hacia un **agente inteligente** capaz de consultar los sistemas corporativos, elaborar análisis, generar reportes y proponer acciones comerciales.

Aunque técnicamente el proyecto es viable, DataNova identifica que el uso de datos corporativos y personales, modelos generativos y agentes autónomos implica riesgos importantes relacionados con privacidad, seguridad, sesgos, errores, trazabilidad y responsabilidad.

Ante esta situación, la empresa decide utilizar los **OECD AI Principles** como marco de referencia para gobernar el desarrollo del prototipo desde sus primeras etapas.

---

#### Problema empresarial

Tradicionalmente, DataNova Labs utilizaba un enfoque centrado principalmente en la factibilidad técnica. El equipo evaluaba si un algoritmo podía entrenarse, si un modelo generativo podía producir respuestas adecuadas o si un agente podía ejecutar determinadas acciones.

Sin embargo, este enfoque presentaba varios problemas.

Por ejemplo, un prototipo podía alcanzar una alta precisión predictiva, pero utilizar información personal innecesaria. Un sistema generativo podía producir respuestas convincentes pero incorrectas. Un modelo podía presentar resultados diferentes entre distintos segmentos de clientes. Un agente podía ejecutar una acción no deseada debido a una interpretación incorrecta de una instrucción.

Por esta razón, DataNova concluye que la calidad de un prototipo de IA no puede determinarse únicamente por su rendimiento técnico. También debe evaluarse su **impacto, seguridad, privacidad, explicabilidad, trazabilidad y responsabilidad**.

La organización incorpora entonces los OECD AI Principles como parte de su proceso de desarrollo.

---

#### Solución propuesta

DataNova establece un nuevo modelo denominado **Responsible AI Prototyping Framework**, cuyo propósito es incorporar principios de gobernanza responsable desde la etapa experimental del desarrollo.

El nuevo proceso incorpora cinco dimensiones alineadas con los OECD AI Principles:

1. Generación de valor inclusivo y sostenible.
2. Protección de derechos humanos, privacidad y equidad.
3. Transparencia y explicabilidad.
4. Robustez, seguridad y protección.
5. Rendición de cuentas.

La principal innovación consiste en que estos principios no se consideran únicamente requisitos legales o éticos, sino **criterios de diseño del prototipo**.

De esta manera, un prototipo solamente puede avanzar a la siguiente fase cuando demuestra no solamente que "funciona", sino que funciona de manera controlada y responsable.

---

#### Aplicación de los principios OECD al caso

#### Principio 1: Crecimiento inclusivo, desarrollo sostenible y bienestar

El primer principio orienta a DataNova a evaluar el valor que la solución generará para las personas y la organización.

En el proyecto de Comercializadora Global, el sistema inicialmente estaba diseñado para maximizar las ventas mediante recomendaciones automáticas. Sin embargo, durante el análisis se identifica que una estrategia basada únicamente en maximización de ventas podría perjudicar determinados segmentos de clientes.

DataNova modifica el objetivo del prototipo.

En lugar de optimizar exclusivamente:

**"maximizar ventas"**

el modelo busca equilibrar:

**ventas + satisfacción del cliente + sostenibilidad + equidad + riesgo.**

Esto permite que el prototipo genere recomendaciones comerciales considerando diferentes variables y no solamente el beneficio económico inmediato.

#### Valor agregado para la empresa

La implementación de este principio genera valor porque permite:

* diseñar soluciones alineadas con objetivos empresariales y sociales;
* reducir riesgos reputacionales;
* identificar impactos negativos antes del despliegue;
* incorporar criterios de sostenibilidad;
* desarrollar productos de IA con mayor aceptación por parte de los usuarios.

Por lo tanto, DataNova deja de vender únicamente "modelos de IA" y comienza a ofrecer **soluciones de IA orientadas a generar valor sostenible**.

---

####. Principio 2: Derechos humanos, valores democráticos, equidad y privacidad

Esta dimensión es especialmente importante debido a que el prototipo utiliza información de clientes y empleados.

Durante el desarrollo, DataNova realiza un inventario de los datos utilizados y clasifica la información en diferentes categorías:

* datos públicos;
* datos corporativos;
* datos personales;
* información confidencial;
* información estratégica.

El equipo determina que no todos los datos son necesarios para desarrollar el prototipo.

Por ejemplo, para predecir la probabilidad de recompra de un cliente no necesariamente se requiere almacenar atributos personales que no aporten valor al modelo.

Se aplica entonces un criterio de **minimización de datos**.

Además, DataNova implementa mecanismos de anonimización o pseudonimización cuando son suficientes para el propósito experimental.

En los prototipos de IA generativa se establece adicionalmente una política que prohíbe introducir información confidencial de clientes en servicios de modelos externos sin autorización y controles adecuados.

#### Valor agregado para la empresa

La aplicación de este principio permite a DataNova:

* disminuir la exposición de información sensible;
* reducir riesgos de privacidad;
* generar confianza en los clientes;
* facilitar procesos de auditoría;
* mejorar la calidad de los conjuntos de datos;
* reducir la cantidad de información innecesaria almacenada.

La privacidad deja de ser considerada exclusivamente una obligación jurídica y se convierte en una **característica de diseño del producto tecnológico**.

---

#### Principio 3: Transparencia y explicabilidad

En una etapa inicial, DataNova observa que el modelo predictivo puede generar recomendaciones comerciales sin que los usuarios comprendan por qué fueron generadas.

Para resolver este problema, el equipo incorpora mecanismos de explicabilidad.

Por ejemplo, cuando el sistema recomienda aumentar el inventario de un producto, el usuario puede consultar factores como:

* comportamiento histórico de ventas;
* estacionalidad;
* tendencia de demanda;
* disponibilidad actual;
* comportamiento de productos similares.

En la solución generativa se añade una arquitectura de **trazabilidad de fuentes**.

Cuando el usuario pregunta:

> "¿Por qué el sistema recomienda incrementar el inventario?"

el sistema muestra las fuentes de información utilizadas y diferencia entre:

**datos recuperados → análisis realizado → inferencia del modelo → recomendación generada.**

En el agente de IA, cada acción se registra.

Por ejemplo:

**Usuario → agente → consulta de inventario → consulta de ventas → análisis → generación de recomendación → aprobación humana.**

#### Valor agregado para la empresa

La transparencia produce beneficios importantes:

* los usuarios comprenden mejor las recomendaciones;
* aumenta la confianza en la solución;
* disminuyen decisiones basadas ciegamente en el algoritmo;
* facilita auditorías;
* permite identificar errores;
* mejora la adopción empresarial.

En consecuencia, DataNova descubre que la explicabilidad no solamente reduce riesgos, sino que también **incrementa el valor percibido del producto**.

---

#### Principio 4: Robustez, seguridad y protección

La evolución del proyecto hacia inteligencia artificial agéntica introduce nuevos riesgos.

El agente es capaz de:

1. recibir una solicitud del usuario;
2. consultar bases de datos;
3. utilizar herramientas analíticas;
4. generar un informe;
5. enviar una propuesta al responsable comercial.

DataNova identifica que otorgar autonomía completa al agente sería innecesariamente riesgoso.

Por ello, establece diferentes niveles de autonomía.

#### Nivel 1: Consulta

El agente puede recuperar información y generar respuestas.

#### Nivel 2: Análisis

El agente puede ejecutar modelos y producir recomendaciones.

#### Nivel 3: Acción controlada

El agente puede ejecutar determinadas acciones previamente autorizadas.

#### Nivel 4: Acción crítica

Las acciones que puedan producir consecuencias financieras, contractuales o reputacionales requieren autorización humana.

Por ejemplo, el agente puede generar una orden propuesta de compra, pero no puede ejecutarla directamente.

Además, DataNova incorpora:

* autenticación y autorización;
* segmentación de permisos;
* registros de actividad;
* monitoreo de comportamiento;
* pruebas de seguridad;
* validación de entradas y salidas;
* mecanismos de interrupción;
* límites de uso de herramientas;
* mecanismos de apagado seguro.

### Valor agregado para la empresa

Este principio permite:

* disminuir la probabilidad de incidentes;
* limitar el impacto de errores;
* controlar la autonomía de los agentes;
* proteger los sistemas corporativos;
* reducir riesgos operativos;
* aumentar la confiabilidad de los prototipos.

Esto proporciona una ventaja competitiva importante porque DataNova puede demostrar que sus prototipos fueron diseñados considerando la seguridad **desde el inicio y no después del desarrollo**.

---

### Principio 5: Rendición de cuentas

DataNova establece que ningún proyecto de IA puede desarrollarse sin definir responsables.

Para cada prototipo se crea una estructura de responsabilidades:

| Rol                 | Responsabilidad                |
| ------------------- | ------------------------------ |
| Product Owner       | Define el objetivo empresarial |
| Data Scientist      | Diseña y valida los modelos    |
| AI Engineer         | Implementa la solución         |
| Data Engineer       | Gestiona los datos             |
| Privacy Officer     | Evalúa privacidad              |
| Cybersecurity       | Evalúa seguridad               |
| Business Owner      | Autoriza utilización           |
| AI Governance Board | Revisa riesgos y aprobación    |

También se crea un expediente digital del prototipo que registra:

* propósito del sistema;
* fuentes de datos;
* versiones del modelo;
* parámetros relevantes;
* pruebas realizadas;
* riesgos identificados;
* incidentes;
* decisiones humanas;
* modificaciones;
* resultados de validación.

De esta manera, es posible responder preguntas como:

**¿Quién desarrolló el modelo?**

**¿Qué datos utilizó?**

**¿Qué versión estaba funcionando?**

**¿Qué controles se aplicaron?**

**¿Quién autorizó su uso?**

#### Valor agregado

La rendición de cuentas permite mejorar:

* gobernanza;
* auditoría;
* control interno;
* gestión de riesgos;
* respuesta ante incidentes;
* confianza del cliente.

La organización puede demostrar que existe una responsabilidad humana y organizacional detrás del sistema de IA.

---

#### El ciclo de vida responsable del prototipo

Uno de los principales beneficios para DataNova es que los OECD AI Principles se convierten en parte del ciclo de vida del desarrollo.

El proceso queda estructurado de la siguiente manera:

**Problema de negocio → evaluación de riesgos → gobierno de datos → diseño del prototipo → desarrollo → pruebas → evaluación ética/privacidad/seguridad → piloto → monitoreo → decisión de despliegue.**

Esto modifica significativamente la metodología anterior.

Antes, el éxito del proyecto se medía principalmente mediante:

**"¿El modelo funciona?"**

Con el nuevo enfoque se evalúa:

**"¿El modelo funciona, genera valor, respeta la privacidad, es seguro, es explicable y existe responsabilidad sobre su utilización?"**

---

#### Aplicación específica a Inteligencia Artificial Generativa

En los proyectos de IA generativa, DataNova crea un **AI Gateway** que funciona como una capa de control entre los usuarios y los modelos de lenguaje.

Esta arquitectura permite controlar:

* qué información puede introducir un usuario;
* qué información puede enviarse al modelo;
* qué modelo puede utilizarse;
* qué información puede recuperarse;
* qué contenido puede generarse;
* qué acciones están permitidas.

Por ejemplo, si un usuario intenta introducir información confidencial de un cliente en un modelo externo, el sistema puede detectar dicha información y bloquear o anonimizar la solicitud.

También se incluyen mecanismos para:

* identificar contenido generado por IA;
* registrar interacciones;
* controlar versiones de prompts;
* evaluar respuestas;
* detectar información potencialmente incorrecta;
* aplicar revisión humana en casos sensibles.

De esta manera, DataNova utiliza los principios de la OCDE como criterios de arquitectura y no únicamente como recomendaciones documentales.

---

#### Aplicación específica a Inteligencia Artificial Agéntica

La inteligencia artificial agéntica representa el mayor desafío del proyecto porque el sistema puede pasar de **generar información** a **realizar acciones**.

DataNova establece el siguiente principio operativo:

> **La autonomía del agente debe ser proporcional al riesgo de la acción que pretende ejecutar.**

Por ejemplo:

| Acción del agente             | Autonomía                    |
| ----------------------------- | ---------------------------- |
| Consultar datos               | Alta                         |
| Crear análisis                | Alta                         |
| Generar reporte               | Alta                         |
| Recomendar una compra         | Media                        |
| Crear una orden de compra     | Baja                         |
| Ejecutar un pago              | Requiere autorización humana |
| Modificar información crítica | Requiere autorización humana |

Esto convierte los OECD AI Principles en un mecanismo práctico para diseñar la gobernanza de agentes.

El resultado es un sistema donde la autonomía no significa ausencia de control.

---

#### Valor agregado generado por la implementación

La aplicación de los principios produce beneficios tanto internos como comerciales.

### Valor operacional

Los controles incorporados desde la etapa de prototipo permiten identificar tempranamente problemas relacionados con datos, seguridad y modelos.

Esto reduce el costo de corregir errores en fases posteriores.

### Valor tecnológico

Los prototipos incorporan desde su diseño mecanismos de seguridad, trazabilidad, explicabilidad y monitoreo.

Por lo tanto, resulta más sencillo evolucionar desde un prototipo hacia una solución productiva.

### Valor comercial

DataNova puede diferenciarse de otros proveedores porque no solamente ofrece capacidad técnica, sino también un enfoque estructurado de **Responsible AI**.

Esto puede convertirse en una ventaja competitiva durante procesos de licitación o selección de proveedores.

### Valor reputacional

Los clientes perciben mayor confianza al saber que sus datos no se utilizan indiscriminadamente y que existen mecanismos para controlar los sistemas de IA.

### Valor estratégico

La organización desarrolla una capacidad interna de gobernanza que puede reutilizarse en diferentes proyectos.

Por tanto, el conocimiento adquirido en un prototipo puede convertirse en un activo organizacional.

---

#### Indicadores para medir el éxito

DataNova establece indicadores para demostrar que los principios no son únicamente declaraciones conceptuales.

Entre los principales indicadores se encuentran:

| Dimensión       | Indicador                                        |
| --------------- | ------------------------------------------------ |
| Privacidad      | % de proyectos con evaluación de privacidad      |
| Datos           | % de datos sensibles minimizados o anonimizados  |
| Seguridad       | % de prototipos sometidos a pruebas de seguridad |
| Transparencia   | % de modelos con documentación y trazabilidad    |
| Explicabilidad  | % de modelos con mecanismos de explicación       |
| Responsabilidad | % de sistemas con responsables definidos         |
| IA Generativa   | % de respuestas sometidas a evaluación           |
| IA Agéntica     | % de acciones críticas con supervisión humana    |
| Riesgo          | Número de incidentes detectados durante pruebas  |
| Negocio         | ROI o beneficio esperado del prototipo           |

Estos indicadores permiten conectar la gobernanza de IA con los objetivos tradicionales de gestión empresarial.

---

#### Resultado del caso de uso

Después de implementar este enfoque, Comercializadora Global obtiene un prototipo de inteligencia artificial que no solamente genera recomendaciones comerciales, sino que también proporciona mecanismos de control, trazabilidad y supervisión.

Por su parte, DataNova Labs transforma su propuesta de valor.

Inicialmente su servicio era:

**"Desarrollamos prototipos de Ciencia de Datos e Inteligencia Artificial."**

Después de implementar los OECD AI Principles, su propuesta se transforma en:

**"Desarrollamos prototipos de Ciencia de Datos e Inteligencia Artificial diseñados bajo principios de responsabilidad, privacidad, transparencia, seguridad y rendición de cuentas."**

Esta transformación tiene una consecuencia estratégica importante: la gobernanza deja de ser percibida como un costo adicional y se convierte en un **diferenciador de mercado**.


_______________________________
#### Referencias bibliográficas

Organisation for Economic Co-operation and Development. (2019). *Recommendation of the Council on Artificial Intelligence* (OECD/LEGAL/0449). OECD Legal Instruments. [https://legalinstruments.oecd.org/en/instruments/OECD-LEGAL-0449](https://legalinstruments.oecd.org/en/instruments/OECD-LEGAL-0449)

Organisation for Economic Co-operation and Development. (2019). *What are the OECD Principles on AI?* OECD Observer. [https://doi.org/10.1787/6ff2a1c4-en](https://doi.org/10.1787/6ff2a1c4-en)

Organisation for Economic Co-operation and Development. (2021). *State of implementation of the OECD AI Principles: Insights from national AI policies* (OECD Digital Economy Papers No. 311). OECD Publishing. [https://doi.org/10.1787/1cd40c44-en](https://doi.org/10.1787/1cd40c44-en)

Organisation for Economic Co-operation and Development. (2023). *The state of implementation of the OECD AI Principles four years on* (OECD Artificial Intelligence Papers No. 3). OECD Publishing. [https://doi.org/10.1787/835641c9-en](https://doi.org/10.1787/835641c9-en)

Organisation for Economic Co-operation and Development. (2024a). *AI, data governance and privacy: Synergies and areas of international co-operation* (OECD Artificial Intelligence Papers No. 22). OECD Publishing. [https://doi.org/10.1787/2476b1a4-en](https://doi.org/10.1787/2476b1a4-en)

Organisation for Economic Co-operation and Development. (2024b). *Explanatory memorandum on the updated OECD definition of an AI system* (OECD Artificial Intelligence Papers No. 8). OECD Publishing. [https://doi.org/10.1787/623da898-en](https://doi.org/10.1787/623da898-en)

Organisation for Economic Co-operation and Development. (2024c). *OECD AI Principles*. OECD. [https://oecd.ai/ai-principles](https://oecd.ai/ai-principles)

Organisation for Economic Co-operation and Development. (2024d, May 3). *OECD updates AI Principles to stay abreast of rapid technological developments*. OECD. [https://www.oecd.org/en/about/news/press-releases/2024/05/oecd-updates-ai-principles-to-stay-abreast-of-rapid-technological-developments.html](https://www.oecd.org/en/about/news/press-releases/2024/05/oecd-updates-ai-principles-to-stay-abreast-of-rapid-technological-developments.html)
