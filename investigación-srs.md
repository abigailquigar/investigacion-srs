##Investigacion SRS

###**SRS/ERS y los problemas que evita**

Es un documento que establece los requerimientos funcionales y no funcionales de un producto de software y las interfaces con su entorno. Según IEEE (1998), una buena SRS beneficia a varios personajes:

  1. Cliente: describe con precisión lo que espera recibir.
  2. Desarrollo: reduce el esfuerzo de diseño y evita construir cosas no pedidas.
  3. Mantenimiento: facilita transferir el producto y planear mejoras.

Además, ayuda a evitar problemas, como:

  1. Malentendidos con clientes.
  2. Estimaciones poco reales.
  3. Pruebas sin criterio.

**Estructura del estándar IEEE 830-1998**

Las secciones que propone el estándar IEEE 830-1998 son las siguientes:

**Sección** | **Contenido** |
--- | --- |
**Introducción** |
Propósito | Motivo del documento y a quién será dirigido.
Alcance | Nombre del producto, beneficios y objetivos.
Definiciones, acrónimos y abreviaturas | Glosario de términos usados.
Referencias | Documentos citados.
Visión general | Organización del documento.
**Descripción general** |
Perspectiva del producto | Relación con otros sistemas.
Funciones del producto | Funciones principales.
Características de los usuarios | Perfiles
Restricciones | Limitaciones legales, tecnológicas, de hardware, de plazo, entre otros.
Suposiciones y dependencias | Factores que, al cambiar, afectan los requerimientos.
Distribución de requerimientos | Requerimientos que se pospondrán a versiones futuras.
**Requerimientos específicos** |
Interfaces externas |	De usuario, de hardware, de software y de comunicaciones.
Funciones	| Qué debe hacer el sistema.
Requerimientos de rendimiento |	Tiempos de respuesta, capacidad, usuarios concurrentes.
Requerimientos lógicos de base de datos	| Información que se almacenará.
Restricciones de diseño	| Estándares, normas y limitaciones impuestas.
Atributos del sistema |	Fiabilidad, disponibilidad, seguridad, mantenibilidad, portabilidad.
Otros requerimientos |	Lo que no sale en lo anterior
**Apéndices e índice** |	Material de apoyo 

**Características de un buen requerimiento**

Según IEEE 832-1998 un buen requerimiento contiene lo siguiente:

**Característica** |	**Significado**
**Correcto** |	Refleja una necesidad real de los interesados
**No ambiguo** |	Admite una sola interpretación
**Completo** |	No omite información necesaria
**Consistente**	| No contradice a otros requerimientos
**Verificable** |	Se puede comprobar con una prueba, inspección o medición
**Modificable** |	Su estructura permite cambiarlo sin afectar a todo el documento
**Trazable** |	Tiene un identificador y se puede rastrear a su origen y a su implementación
**Priorizado** |	Se indica su importancia o estabilidad
**Singular / atómico** |	Expresa una sola cosa (29148)
**Factible** |	Es realizable con los recursos y el tiempo del proyecto (29148)

  **EJEMPLO MALO**
RF-01: El sistema debe ser rápido y fácil de usar, y permitir gestionar a los clientes de manera eficiente.

  **EJEMPLO BUENO**
RF-01: El sistema debe permitir al usuario con rol Administrador registrar un cliente capturando nombre, correo electrónico y teléfono.

RNF-01: El sistema debe mostrar los resultados de una búsqueda de clientes en un máximo de 2 segundos para el 95 % de las consultas, con hasta 50 usuarios concurrentes.


**Declaración de uso de la IA generativa.**

En este archivo se utilizó la IA Claude para hacer un borrador de esta investigación: propuso la estructura de la investigación, además de sugerir modificaciones y brindar las referencias APA 7 según donde investigamos.

**Referencias APA 7**

IEEE. (1998). IEEE recommended practice for software requirements specifications (IEEE Std 830-1998). https://doi.org/10.1109/IEEESTD.1998.88286

ISO/IEC/IEEE. (2018). Systems and software engineering — Life cycle processes — Requirements engineering (ISO/IEC/IEEE 29148:2018). https://doi.org/10.1109/IEEESTD.2018.8559686

Robertson, S., & Robertson, J. (2012). Mastering the requirements process: Getting requirements right (3.ª ed.). Addison-Wesley.

Sommerville, I. (2016). Software engineering (10.ª ed.). Pearson.

Wiegers, K., & Beatty, J. (2013). Software requirements (3.ª ed.). Microsoft Press.
