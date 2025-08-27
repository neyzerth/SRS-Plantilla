
# Especificación de Requisitos de Software
## Para <nombre del proyecto>

Versión 0.1  
Hecho por <autor>  
<organización>  
<fecha de creación>  

Tabla de Contenidos
=================
* [Historial de Revisiones](#historial-de-revisiones)
* 1 [Introducción](#1-introducción)
  * 1.1 [Propósito del Documento](#11-propósito-del-documento)
  * 1.2 [Alcance del Producto](#12-alcance-del-producto)
  * 1.3 [Definiciones, Acrónimos y Abreviaturas](#13-definiciones-acrónimos-y-abreviaturas)
  * 1.4 [Referencias](#14-referencias)
  * 1.5 [Visión General del Documento](#15-visión-general-del-documento)
* 2 [Descripción General del Producto](#2-descripción-general-del-producto)
  * 2.1 [Perspectiva del Producto](#21-perspectiva-del-producto)
  * 2.2 [Funciones del Producto](#22-funciones-del-producto)
  * 2.3 [Restricciones del Producto](#23-restricciones-del-producto)
  * 2.4 [Características de los Usuarios](#24-características-de-los-usuarios)
  * 2.5 [Supuestos y Dependencias](#25-supuestos-y-dependencias)
  * 2.6 [Distribución de Requisitos](#26-distribución-de-requisitos)
* 3 [Requisitos](#3-requisitos)
  * 3.1 [Interfaces Externas](#31-interfaces-externas)
    * 3.1.1 [Interfaces de Usuario](#311-interfaces-de-usuario)
    * 3.1.2 [Interfaces de Hardware](#312-interfaces-de-hardware)
    * 3.1.3 [Interfaces de Software](#313-interfaces-de-software)
  * 3.2 [Funcionales](#32-funcionales)
  * 3.3 [Calidad de Servicio](#33-calidad-de-servicio)
    * 3.3.1 [Rendimiento](#331-rendimiento)
    * 3.3.2 [Seguridad](#332-seguridad)
    * 3.3.3 [Confiabilidad](#333-confiabilidad)
    * 3.3.4 [Disponibilidad](#334-disponibilidad)
  * 3.4 [Cumplimiento](#34-cumplimiento)
  * 3.5 [Diseño e Implementación](#35-diseño-e-implementación)
    * 3.5.1 [Instalación](#351-instalación)
    * 3.5.2 [Distribución](#352-distribución)
    * 3.5.3 [Mantenibilidad](#353-mantenibilidad)
    * 3.5.4 [Reusabilidad](#354-reusabilidad)
    * 3.5.5 [Portabilidad](#355-portabilidad)
    * 3.5.6 [Costo](#356-costo)
    * 3.5.7 [Plazo de Entrega](#357-plazo-de-entrega)
    * 3.5.8 [Prueba de Concepto](#358-prueba-de-concepto)
* 4 [Verificación](#4-verificación)
* 5 [Apéndices](#5-apéndices)


## Historial de Revisiones
| Nombre | Fecha    | Motivo de los Cambios  | Versión   |
| ------ | -------- | ---------------------- | --------- |
|        |          |                        |           |
|        |          |                        |           |
|        |          |                        |           |


## 1. Introducción
> Esta sección debe proporcionar una visión general de todo el documento

### 1.1 Propósito del Documento
Describa el propósito de la ERS y su audiencia prevista.

### 1.2 Alcance del Producto
Identifique el producto cuyos requisitos de software se especifican en este documento, incluyendo el número de revisión o versión. Explique qué hará el producto cubierto por esta ERS, especialmente si esta ERS describe solo una parte del sistema o un solo subsistema. Proporcione una breve descripción del software especificado y su propósito, incluyendo beneficios, objetivos y metas relevantes. Relacione el software con los objetivos corporativos o estrategias de negocio. Si existe un documento separado de visión y alcance, refiérase a él en lugar de duplicar su contenido aquí.

### 1.3 Definiciones, Acrónimos y Abreviaturas

### 1.4 Referencias
Enumere cualquier otro documento o dirección web a la que se refiera esta ERS. Estos pueden incluir guías de estilo de interfaz de usuario, contratos, normas, especificaciones de requisitos del sistema, documentos de casos de uso o un documento de visión y alcance. Proporcione suficiente información para que el lector pueda acceder a una copia de cada referencia, incluyendo título, autor, número de versión, fecha y fuente o ubicación.

### 1.5 Visión General del Documento
Describa qué contiene el resto del documento y cómo está organizado.


## 2. Descripción General del Producto
> Esta sección debe describir los factores generales que afectan al producto y sus requisitos. Esta sección no establece requisitos específicos. En cambio, proporciona un contexto para esos requisitos, que se definen en detalle en la Sección 3, y facilita su comprensión.

### 2.1 Perspectiva del Producto
Describa el contexto y el origen del producto especificado en esta ERS. Por ejemplo, indique si este producto es un miembro sucesor de una familia de productos, un reemplazo de ciertos sistemas existentes, o un producto nuevo y autónomo. Si la ERS define un componente de un sistema mayor, relacione los requisitos del sistema mayor con la funcionalidad de este software e identifique las interfaces entre ambos. Un diagrama simple que muestre los principales componentes del sistema general, interconexiones de subsistemas e interfaces externas puede ser útil.

### 2.2 Funciones del Producto
Resuma las funciones principales que el producto debe realizar o permitir al usuario realizar. Los detalles se proporcionarán en la Sección 3, por lo que solo se necesita un resumen de alto nivel (como una lista de viñetas) aquí. Organice las funciones para que sean comprensibles para cualquier lector de la ERS. Una imagen de los principales grupos de requisitos relacionados y cómo se relacionan, como un diagrama de flujo de datos de alto nivel o un diagrama de clases de objetos, suele ser eficaz.

### 2.3 Restricciones del Producto
Esta subsección debe proporcionar una descripción general de cualquier otro elemento que limite las opciones del desarrollador. Estos pueden incluir:

* Interfaces con usuarios, otras aplicaciones o hardware.  
* Restricciones de calidad de servicio.  
* Cumplimiento de normas.  
* Restricciones de diseño o implementación.

### 2.4 Características de los Usuarios
Identifique las diversas clases de usuarios que se anticipa utilizarán este producto. Las clases de usuarios pueden diferenciarse según la frecuencia de uso, el subconjunto de funciones del producto utilizadas, experiencia técnica, niveles de seguridad o privilegio, nivel educativo o experiencia. Describa las características pertinentes de cada clase de usuario. Ciertos requisitos pueden corresponder solo a ciertas clases de usuarios. Distinga las clases de usuarios más importantes para este producto de aquellas menos importantes de satisfacer.

### 2.5 Supuestos y Dependencias
Enumere cualquier factor asumido (en oposición a hechos conocidos) que pueda afectar los requisitos establecidos en la ERS. Estos pueden incluir componentes de terceros o comerciales que planea usar, cuestiones relacionadas con el entorno de desarrollo u operación, o restricciones. El proyecto podría verse afectado si estos supuestos son incorrectos, no se comparten o cambian. También identifique cualquier dependencia que el proyecto tenga de factores externos, como componentes de software que se pretende reutilizar de otro proyecto, a menos que ya estén documentados en otro lugar (por ejemplo, en el documento de visión y alcance o el plan del proyecto).

### 2.6 Distribución de Requisitos
Distribuya los requisitos de software entre los elementos de software. Para los requisitos que requieran implementación en varios elementos de software, o cuando la asignación a un elemento de software sea inicialmente indefinida, esto debe indicarse. Se debe utilizar una tabla de referencia cruzada por función y elemento de software para resumir la distribución.

Identifique los requisitos que pueden retrasarse hasta futuras versiones del sistema (por ejemplo, bloques y/o incrementos).


## 3. Requisitos
> Esta sección especifica los requisitos del producto software. Especifique todos los requisitos de software con el nivel de detalle suficiente para permitir a los diseñadores diseñar un sistema de software que satisfaga esos requisitos y a los evaluadores probar que el sistema cumple con los requisitos.

> Los requisitos específicos deben:
* Ser identificables de manera única.
* Indicar el sujeto del requisito (por ejemplo, sistema, software, etc.) y lo que debe hacerse.
* Opcionalmente indicar las condiciones y restricciones, si las hay.
* Describir cada entrada (estímulo) al sistema de software, cada salida (respuesta) del sistema de software y todas las funciones realizadas por el sistema en respuesta a una entrada o en apoyo de una salida.
* Ser verificables (por ejemplo, la realización del requisito puede demostrarse a satisfacción del cliente)
* Cumplir con la sintaxis, palabras clave y términos acordados.

### 3.1 Interfaces Externas
> Esta subsección define todas las entradas y salidas requeridas del sistema de software. Cada interfaz definida puede incluir el siguiente contenido:
* Nombre del elemento
* Fuente de entrada o destino de salida
* Rango válido, precisión y/o tolerancia
* Unidades de medida
* Temporización
* Relaciones con otras entradas/salidas
* Formatos/organización de pantalla
* Formatos/organización de ventana
* Formatos de datos
* Formatos de comandos
* Mensajes finales

#### 3.1.1 Interfaces de Usuario
Defina los componentes de software para los que se necesita una interfaz de usuario. Describa las características lógicas de cada interfaz entre el producto software y los usuarios. Esto puede incluir imágenes de pantalla de ejemplo, cualquier estándar de GUI o guías de estilo de familia de productos que deban seguirse, restricciones de diseño de pantalla, botones y funciones estándar (por ejemplo, ayuda) que aparecerán en cada pantalla, atajos de teclado, estándares de visualización de mensajes de error, etc. Los detalles del diseño de la interfaz de usuario deben documentarse en una especificación separada de interfaz de usuario.

Puede dividirse aún más en requisitos de Usabilidad y Conveniencia.

#### 3.1.2 Interfaces de Hardware
Describa las características lógicas y físicas de cada interfaz entre el producto software y los componentes de hardware del sistema. Esto puede incluir los tipos de dispositivos soportados, la naturaleza de las interacciones de datos y control entre el software y el hardware, y los protocolos de comunicación que se utilizarán.

#### 3.1.3 Interfaces de Software
Describa las conexiones entre este producto y otros componentes de software específicos (nombre y versión), incluyendo bases de datos, sistemas operativos, herramientas, bibliotecas y componentes comerciales integrados. Identifique los elementos de datos o mensajes que entran y salen del sistema y describa el propósito de cada uno. Describa los servicios necesarios y la naturaleza de las comunicaciones. Refiérase a documentos que describan protocolos detallados de interfaz de programación de aplicaciones. Identifique los datos que se compartirán entre componentes de software. Si el mecanismo de compartición de datos debe implementarse de una manera específica (por ejemplo, uso de un área de datos global en un sistema operativo multitarea), especifíquelo como una restricción de implementación.

### 3.2 Funcionales
> Esta sección especifica los requisitos de los efectos funcionales que el software debe tener en su entorno.

### 3.3 Calidad de Servicio
> Esta sección establece requisitos adicionales relacionados con la calidad que los efectos funcionales del software deben presentar.

#### 3.3.1 Rendimiento
Si existen requisitos de rendimiento para el producto bajo diversas circunstancias, indíquelos aquí y explique su justificación, para ayudar a los desarrolladores a comprender la intención y tomar decisiones de diseño adecuadas. Especifique las relaciones de temporización para sistemas en tiempo real. Haga estos requisitos lo más específicos posible. Puede ser necesario indicar requisitos de rendimiento para requisitos funcionales individuales o características.

#### 3.3.2 Seguridad
Especifique cualquier requisito relacionado con la seguridad o privacidad en el uso del producto o la protección de los datos utilizados o creados por el producto. Defina cualquier requisito de autenticación de identidad de usuario. Refiérase a cualquier política o regulación externa que contenga cuestiones de seguridad que afecten al producto. Defina cualquier certificación de seguridad o privacidad que deba cumplirse.

#### 3.3.3 Confiabilidad
Especifique los factores necesarios para establecer la confiabilidad requerida del sistema software en el momento de la entrega.

#### 3.3.4 Disponibilidad
Especifique los factores necesarios para garantizar un nivel de disponibilidad definido para todo el sistema, como puntos de control, recuperación y reinicio.

### 3.4 Cumplimiento
Especifique los requisitos derivados de normas o regulaciones existentes, incluyendo:
* Formato de informes
* Nomenclatura de datos
* Procedimientos contables
* Trazabilidad de auditoría

Por ejemplo, esto podría especificar el requisito de que el software trace la actividad de procesamiento. Dichos rastreos son necesarios para que algunas aplicaciones cumplan con estándares regulatorios o financieros mínimos. Un requisito de trazabilidad de auditoría puede, por ejemplo, indicar que todos los cambios en una base de datos de nómina deben registrarse en un archivo de rastreo con los valores antes y después.

### 3.5 Diseño e Implementación

#### 3.5.1 Instalación
Restricciones para asegurar que el software funcione correctamente en la plataforma de implementación objetivo.

#### 3.5.2 Distribución
Restricciones sobre los componentes de software para adaptarse a la estructura geográficamente distribuida de la organización anfitriona, la distribución de los datos a procesar o la distribución de los dispositivos a controlar.

#### 3.5.3 Mantenibilidad
Especifique los atributos del software que se relacionan con la facilidad de mantenimiento del propio software. Estos pueden incluir requisitos de cierta modularidad, interfaces o limitación de complejidad. No deben colocarse requisitos aquí solo porque se consideran buenas prácticas de diseño.

#### 3.5.4 Reusabilidad
<!-- TODO: redactar una descripción -->

#### 3.5.5 Portabilidad
Especifique los atributos del software que se relacionan con la facilidad de portabilidad del software a otras máquinas anfitrionas y/o sistemas operativos.

#### 3.5.6 Costo
Especifique el costo monetario del producto software.

#### 3.5.7 Plazo de Entrega
Especifique el cronograma de entrega del producto software.

#### 3.5.8 Prueba de Concepto
<!-- TODO: redactar una descripción -->

## 4. Verificación
> Esta sección proporciona los enfoques y métodos de verificación planificados para calificar el software. Se recomienda que los elementos de información para la verificación se presenten de manera paralela a los elementos de requisitos de la Sección 3. El propósito del proceso de verificación es proporcionar evidencia objetiva de que un sistema o elemento del sistema cumple con sus requisitos y características especificados.

<!-- TODO: dar más orientación, similar a la sección 3 -->
<!-- ieee 15288:2015 -->

## 5. Apéndices
