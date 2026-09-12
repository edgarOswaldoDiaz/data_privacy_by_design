#### OWASP Top 10 for LLM Applications: seguridad y gestión de riesgos en aplicaciones de inteligencia artificial

El OWASP Top 10 for LLM Applications (Top 10 de OWASP para Aplicaciones de Modelos de Lenguaje Grande) es un marco de trabajo desarrollado por la comunidad de expertos en ciberseguridad para identificar las vulnerabilidades de seguridad más críticas específicas de las aplicaciones construidas con inteligencia artificial generativa y LLMs.

El **OWASP Top 10 for LLM Applications** representa una referencia fundamental para comprender y gestionar los riesgos de seguridad asociados con las aplicaciones de inteligencia artificial generativa. Su evolución demuestra que los riesgos no permanecen estáticos: conforme los LLM adquieren acceso a datos, herramientas, memoria y sistemas empresariales, también aumenta el impacto potencial de sus vulnerabilidades.

Nota: La edición 2026 coloca especialmente en evidencia esta transformación. **Prompt Injection** permanece como el principal riesgo, mientras que **Excessive Agency** asciende al tercer puesto, reflejando la importancia creciente de las arquitecturas en las que los modelos pueden ejecutar acciones. Además, la incorporación o reformulación de categorías como **Hidden Context Exposure** e **Improper Output Handling** muestra que la seguridad de la IA exige analizar toda la cadena de procesamiento y no solamente el modelo. En consecuencia, adoptar el OWASP Top 10 no debería entenderse como una actividad aislada de cumplimiento, sino como parte de una estrategia integral de **AI Security, Data Governance, Application Security y Risk Management**. Las organizaciones que pretendan utilizar inteligencia artificial de forma responsable deben diseñar sus sistemas bajo una premisa fundamental: un modelo puede equivocarse, ser manipulado o producir resultados inesperados. La arquitectura de seguridad debe estar preparada para que, aun cuando el modelo falle, el sistema conserve sus propiedades de confidencialidad, integridad, disponibilidad, trazabilidad y control. En última instancia, la seguridad de las aplicaciones LLM no consiste en construir un modelo que nunca pueda ser engañado. Consiste en construir un sistema suficientemente robusto para que, cuando el modelo sea manipulado o se equivoque, las consecuencias permanezcan controladas. Esta filosofía constituye uno de los principios centrales que actualmente orientan la evolución del trabajo de OWASP en seguridad de IA. 

Los diez riesgos son:

#### Prompt Injection: uno de los principales desafíos

El **Prompt Injection** consiste en manipular las entradas que recibe un modelo para modificar su comportamiento de una manera que no estaba prevista por los desarrolladores. Una característica particularmente importante de esta vulnerabilidad es que la entrada maliciosa no tiene necesariamente que provenir directamente del usuario. Puede encontrarse en documentos recuperados por un sistema RAG, resultados de herramientas, memoria persistente, imágenes, audio, video u otras fuentes procesadas por el modelo. 

Este riesgo es especialmente importante porque los modelos de lenguaje no establecen una frontera arquitectónica perfecta entre instrucciones y datos. En consecuencia, una aplicación que simplemente confía en que el modelo distinguirá correctamente entre una instrucción legítima y contenido malicioso puede quedar expuesta.

En un entorno empresarial, un ataque de *Prompt Injection* podría alterar una respuesta, inducir al sistema a revelar información confidencial o generar instrucciones que posteriormente sean ejecutadas por otro componente. El peligro aumenta cuando el LLM está conectado a herramientas, APIs, bases de datos o agentes.

Por ello, una arquitectura segura debe asumir que los datos procesados por el modelo pueden ser manipulados y debe establecer controles fuera del propio modelo.

#### Sensitive Information Disclosure: la protección de los datos

El segundo riesgo corresponde a la **divulgación de información sensible**. Las aplicaciones LLM pueden manejar información personal, financiera, estratégica, propiedad intelectual, credenciales, datos de clientes o información interna de una organización.

El problema puede producirse tanto por la forma en que los datos ingresan al sistema como por la manera en que se recuperan y presentan posteriormente. Una aplicación puede estar correctamente autenticada y, aun así, devolver información que el usuario no debería conocer.

Este riesgo tiene una relación directa con la privacidad y la confidencialidad de los datos. En aplicaciones corporativas de Business Intelligence, Data Science y analítica avanzada, por ejemplo, resulta indispensable aplicar controles de autorización y clasificación de información antes de proporcionar datos al modelo.

La seguridad de un LLM, por tanto, no puede limitarse al modelo. Debe abarcar las fuentes de datos, los mecanismos de recuperación, los registros, las interfaces y los sistemas conectados.

#### Excessive Agency: cuando el modelo adquiere demasiado poder

Uno de los cambios más relevantes de la edición 2026 es la posición de **Excessive Agency**, que ocupa el tercer lugar. OWASP destaca que cuando un modelo puede utilizar herramientas, mantener memoria y ejecutar acciones, el impacto potencial de una manipulación puede extenderse mucho más allá de una conversación. 

La agencia excesiva aparece cuando una aplicación proporciona al LLM más permisos, herramientas o autonomía de la que necesita para cumplir su función.

Por ejemplo, un agente diseñado para consultar información podría recibir innecesariamente permisos para modificar registros, enviar correos, ejecutar comandos o eliminar archivos. Aunque el modelo no tenga intención maliciosa, un error, una instrucción manipulada o una respuesta incorrecta podría provocar una acción perjudicial.

La solución debe incluir el principio de mínimo privilegio, segmentación de funciones, autorización independiente de las decisiones del modelo, límites de ejecución, aprobación humana para operaciones críticas y mecanismos de reversibilidad.

#### Supply Chain: la seguridad de todo el ecosistema

Las aplicaciones modernas de IA dependen de numerosos componentes externos: modelos, APIs, conjuntos de datos, bibliotecas, frameworks, embeddings, proveedores de nube, herramientas de observabilidad y servicios especializados.

El riesgo de **Supply Chain** aparece cuando alguno de estos componentes se encuentra comprometido, manipulado o presenta vulnerabilidades. Esto demuestra que la seguridad de una solución de IA no depende solamente del código desarrollado internamente.

Una organización debe conocer de dónde provienen sus modelos y datos, cuáles son sus dependencias y qué cambios se producen durante su ciclo de vida. En este sentido, prácticas como la gestión de dependencias, evaluación de proveedores, control de versiones, validación de artefactos y monitoreo continuo adquieren una importancia creciente.

#### Data and Model Poisoning

El **Data and Model Poisoning** ocurre cuando datos utilizados para entrenamiento, ajuste, recuperación o generación de embeddings son manipulados de manera intencional o accidental.

La consecuencia puede ser un modelo o sistema que genere respuestas incorrectas, favorezca determinado contenido, reproduzca comportamiento malicioso o incorpore información manipulada.

Este riesgo demuestra que la calidad y la seguridad de los datos están estrechamente vinculadas. Para las organizaciones que utilizan Data Science y Machine Learning, esto significa que la gobernanza del dato debe contemplar no sólo exactitud, calidad y disponibilidad, sino también integridad y trazabilidad.

Los datos deben proceder de fuentes confiables, contar con controles de integridad y someterse a procesos de validación antes de incorporarse a los pipelines de inteligencia artificial.

#### Unbounded Consumption

El **Unbounded Consumption** hace referencia al consumo descontrolado de recursos asociados con aplicaciones basadas en LLM. Estos recursos pueden incluir capacidad computacional, tokens, tiempo de procesamiento, almacenamiento y llamadas a servicios externos.

El riesgo no se limita a una interrupción técnica. También puede convertirse en un problema financiero, especialmente cuando los servicios de IA se facturan según consumo.

Una aplicación que no establece límites adecuados podría ser utilizada para generar un volumen excesivo de solicitudes o realizar operaciones computacionalmente costosas.

Por ello, mecanismos como *rate limiting*, cuotas, presupuestos, límites de tokens, controles de concurrencia, monitoreo de consumo y mecanismos de detección de anomalías son elementos esenciales de una arquitectura segura.

#### Misinformation

La **Misinformation** representa uno de los desafíos más particulares de los LLM porque un modelo puede generar respuestas incorrectas con una apariencia altamente convincente.

El problema no es únicamente que el modelo pueda equivocarse, sino que los usuarios y los sistemas posteriores pueden interpretar esas respuestas como verdaderas.

En aplicaciones empresariales, el impacto puede ser considerable. Un error en una consulta analítica, una recomendación financiera, una interpretación jurídica o un reporte gerencial podría convertirse en una decisión incorrecta.

Por esta razón, los sistemas críticos deben utilizar mecanismos de validación, fuentes verificables, recuperación de información confiable, controles de calidad y supervisión humana. La inteligencia artificial debe utilizarse como apoyo a la toma de decisiones, no como sustituto automático del criterio humano en todos los escenarios.

#### Hidden Context Exposure

La categoría **Hidden Context Exposure** refleja la preocupación creciente por la información interna que forma parte del contexto utilizado por una aplicación LLM.

En los sistemas modernos, el modelo puede recibir mucho más que el mensaje visible para el usuario. Puede existir información proveniente de instrucciones del sistema, memoria, datos recuperados, herramientas, metadatos o contexto interno.

Por esta razón, es necesario reconocer que el contexto también constituye un activo que debe protegerse.

Una arquitectura de seguridad debe determinar qué información puede ser introducida en el contexto, qué usuarios pueden acceder a ella, qué información puede permanecer en memoria y qué elementos pueden ser devueltos al usuario.

#### Vector and Embedding Weaknesses

Los sistemas de **Retrieval-Augmented Generation (RAG)** utilizan frecuentemente embeddings y bases vectoriales para recuperar información relevante. Sin embargo, estos componentes introducen nuevos riesgos.

Problemas relacionados con aislamiento de información, controles de acceso, integridad de embeddings, recuperación de documentos y segmentación entre usuarios pueden provocar que un modelo acceda a información que no debería estar disponible.

Por esta razón, un sistema RAG no debe considerarse simplemente como un mecanismo de búsqueda. Es una arquitectura de datos que requiere controles de identidad, autorización, clasificación y aislamiento de información.

#### Improper Output Handling

Finalmente, **Improper Output Handling** describe la falta de validación, sanitización y tratamiento adecuado de las salidas generadas por el modelo antes de enviarlas a otros componentes.

Este riesgo es crítico porque una salida generada por un LLM puede ser interpretada por otro sistema. OWASP señala que un manejo inadecuado puede contribuir a vulnerabilidades como XSS, CSRF, SSRF, escalamiento de privilegios o ejecución remota de código. 

La regla fundamental es tratar la salida del LLM como contenido no confiable. Antes de enviarla a una base de datos, navegador, API, terminal, sistema operativo o herramienta empresarial, debe validarse y sanitizarse de acuerdo con el contexto.

Esto conecta directamente la seguridad de los LLM con las prácticas tradicionales de Application Security. No basta con asegurar el prompt; también es necesario controlar qué ocurre después de que el modelo produce una respuesta.

#### OWASP como marco de gestión y no únicamente como lista de vulnerabilidades

Una de las principales contribuciones del OWASP Top 10 consiste en proporcionar un lenguaje común entre áreas que históricamente han trabajado de manera separada.

Los desarrolladores pueden utilizarlo para diseñar controles de seguridad. Los científicos de datos pueden emplearlo para identificar riesgos relacionados con entrenamiento y calidad de datos. Los arquitectos pueden incorporarlo al diseño de plataformas RAG y agentes. Los responsables de seguridad pueden integrarlo en threat modeling, pruebas y monitoreo. Finalmente, los líderes empresariales pueden utilizarlo como referencia para definir políticas y criterios de aceptación de soluciones de inteligencia artificial.

El enfoque también ayuda a superar una concepción limitada de la seguridad basada exclusivamente en el modelo. Un LLM puede ser técnicamente seguro en aislamiento y, sin embargo, formar parte de una aplicación vulnerable debido a una mala configuración de permisos, una fuente de datos comprometida o una integración insegura.

OWASP enfatiza precisamente esta visión sistémica: las vulnerabilidades deben analizarse dentro de la aplicación y de los componentes que rodean al modelo.

#### Relación con Business Intelligence, Business Analytics y Data Science

La relevancia del OWASP Top 10 aumenta cuando los LLM se integran con plataformas empresariales.

En Business Intelligence, por ejemplo, un asistente puede generar consultas SQL, explicar indicadores o acceder a información de múltiples sistemas. En Business Analytics puede interpretar resultados y generar recomendaciones. En Data Science puede interactuar con notebooks, repositorios, datasets y herramientas de programación.

En todos estos escenarios existe una característica común: el modelo deja de ser simplemente un generador de texto y se convierte en una interfaz inteligente hacia información y capacidades empresariales.

Consecuentemente, los principios de seguridad deben combinar controles tradicionales de ciberseguridad con controles específicos de IA. Entre ellos destacan el principio de mínimo privilegio, segregación de funciones, clasificación de datos, control de acceso, validación de entradas y salidas, monitoreo, pruebas adversariales, gestión de proveedores y supervisión humana.

#### Referencias

> OWASP GenAI Security Project. *OWASP GenAI LLM Top 10 2026*. OWASP Foundation, 2026.

> OWASP Foundation. *OWASP Top 10 for Large Language Model Applications*. Archivo histórico y evolución del proyecto.

> OWASP GenAI Security Project. *OWASP Top 10 for LLM and GenAI Initiative*. OWASP Foundation.

