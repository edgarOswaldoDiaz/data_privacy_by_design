# Caso práctico: aplicación del NIST Privacy Framework 1.0

> **Caso hipotético de aplicación.** Material elaborado con fines académicos a partir del documento NIST correspondiente.

[Volver al índice](./NIST_Indice.md) · [Consultar el escrito base](./NIST_Privacy_Framework_Escrito.md)

Una empresa de entregas a domicilio utiliza una aplicación móvil que recopila nombre, teléfono, dirección, ubicación GPS e historial de pedidos de sus clientes. Durante una revisión interna detecta que la ubicación precisa continúa recopilándose incluso cuando no existe una entrega activa, se conserva durante más tiempo del necesario y parte de la información se comparte con un proveedor externo de analítica. Aunque no ha ocurrido una filtración ni un ataque informático, estas prácticas pueden generar riesgos de privacidad, ya que permiten inferir rutinas, lugares frecuentes y patrones de comportamiento de los usuarios.

La aplicación del NIST Privacy Framework 1.0 comienza con Identify-P, donde la empresa inventaría los datos, sistemas, finalidades, terceros involucrados y posibles acciones problemáticas. Después, mediante Govern-P, define políticas, responsabilidades, requisitos aplicables y su tolerancia al riesgo. Con Control-P, limita la recopilación de ubicación al periodo realmente necesario, establece reglas de conservación y facilita mecanismos para revisar, modificar o eliminar datos. A través de Communicate-P, informa de forma clara al usuario para qué se utiliza su ubicación, con quién se comparte y qué opciones tiene sobre su tratamiento. Finalmente, con Protect-P, restringe el acceso interno según funciones, fortalece la autenticación, protege los datos en reposo y en tránsito y establece mecanismos de respaldo y gestión de vulnerabilidades. Estas cinco funciones permiten abordar el problema desde la identificación del riesgo hasta su control y protección.

El resultado no es eliminar el uso de la ubicación, ya que sigue siendo necesaria para prestar el servicio, sino reducir el tratamiento al nivel necesario, justificar su finalidad y gestionar los riesgos asociados. Este caso muestra una idea central del marco: un sistema puede ser seguro desde el punto de vista técnico y, aun así, presentar riesgos de privacidad si el tratamiento de los datos es excesivo, poco transparente o inadecuadamente controlado.

**Fuente:** *Elaboración propia con base en National Institute of Standards and Technology (2020), NIST Privacy Framework: A Tool for Improving Privacy Through Enterprise Risk Management, Version 1.0.*

---

**Diagrama de causas:** [Ver el Ishikawa del caso](./NIST_Privacy_Framework_Ishikawa_Caso.md).
