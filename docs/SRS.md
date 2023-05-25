# SRS 

## 1. Introducción
La siguiente Especificación de Requerimientos de Software (SRS) del sistema a construir, surge con la finalidad de proveer toda la información de lo que quiere el cliente que contenga el software. Tales requerimientos son la base a la hora de comenzar el desarrollo del Software. En este caso el software a desarrollar es un sistema de control y organización del ingreso y salida de productos como de su precio de llegada y al momento de su venta y pedidos a domicilios realizados por los clientes por medio de la pagina   en la heladeria san delicias.

### 1.1	Propósito
El propósito de este documento es describir lo acordado con el cliente y desarrollar el paso a paso para crear el software que servirá para dar control y registro sobre los productos que van destinado al consumo del cliente, entre otros de la heladeria san delicias. Sistematizar estos procesos para ayudar a mejorar el rendimiento del área administrativa, generando informes sobre el ingreso y salida de los productos de manera semanal y mensual. Estos informes contienen El precio de entrada,  El precio de venta, Cantidad de productos, cantidad restante de productos y tambien tendra un tipo de pagina web donde los clientes pueden pedir sus productos  por medio de ella. 


### 1.2	Alcance
El sistema será una aplicación web que permitirá llevar el control del ingreso y venta de los diferentes productos del establecimiento, llevando los respectivos informes de los ingresos semanales y mensuales.
El sistema planteado dará apoyo a los siguientes procesos: 
•	Control y organización de los productos. 
•	Administración de ingresos y venta de los productos.
•   Realizacion de pedidos a domicio de los productos.

### 1.3	Definiciones, Acrónimos, y Abreviaturas
SGBD: Sistema gestor de Base de datos
UML: Lenguaje unificado para modelamiento de sistemas
HTML: Lenguaje de Marcas de Hipertexto
CSS: Hojas de estilo en cascada
JavaScript: Lenguaje de secuencias de comandos
PHP: Es un lenguaje de programación interpretado para desarrollo web
Usuario: Persona o empresa que usará el sistema para gestionar procesos
ERS: Especificación de Requisitos Software
RF: Requerimiento funcional
RNF: Requerimiento No Funcional	

### 1.4	Referencias
 https://blog.powerdata.es/el-valor-de-la-gestion-de-datos/que-es-un-gestor-de-datos-y-para-que-sirve#:~:text=Entre%20sus%20funciones%20se%20encuentran,hacer%20an%C3%A1lisis%20para%20generar%20informes.
https://es.wikipedia.org/wiki/Aplicaci%C3%B3n_web 
https://es.wikipedia.org/wiki/HTML
https://es.wikipedia.org/wiki/CSS
https://es.wikipedia.org/wiki/Base_de_datos


### 1.5	Apreciación Global
A continuación podemos ver los diferentes puntos clave que caracterizan nuestro proyecto


## 2.	Descripción General

### 2.1	Perspectivas del Producto
Perspectivas del Producto
Con este sistema se espera una mejora en la forma de cómo se maneja la parte administrativa en productos y producido en el transcurso del mes en la empresa
### 2.2	Funciones del Producto
El software cumplirá con las siguientes funciones:
1. Administrador 
2. Registro de los productos que entran de la empresa.
3. Precio de los productos que entran a la empresa.
4. Registro de los productos que salen de la empresa.
5. Registros de los productos que se van vendiendo.
6. Registro de pedidos realizados por clientes.

### 2.3 Características de Usuario
Los usuarios que interactuaran con este sistema son personas capacitadas para el manejo de ingresos en ventas y en productos, ya que se hace énfasis en el inventario y pedidos a domicilio por medio de la pagina web de la empresa.

### 2.4	Restricciones
las posibles restricciones son el tiempo que tomará el desarrollo del sistema apropiado, recursos donde se implantará el sistema tales como herramientas digitales y dinero si es necesario, el nivel del lenguaje programación para nosotros como administradores de los recursos de la empresa y que este mismo sea claro y eficaz en su trabajo.


### 2.5	Atención y Dependencias
Nuestra propuesta consiste en un modelo aplicativo para organizar y contabilizar la salida y entrada de productos como tambien realizar pedidos a domicilio por medio de la pagina web, como también calcular el total de ganancias.

3.2 Requerimientos no funcionales
| codigo | RFN-001 |
|---------|-------|
| Nombre | DESEMPEÑO |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | El tiempo de respuesta y la duracion de las opciones funcionales del sofware sera lo mas rapido posible.
por tanto el nivel de servicios requerido es tal que el sistema imformacion con el tiempo no sufra una disminucion en su desempeño (degradacion) respecto al nivel previo al de la puesta de produccion |

| codigo | RFN-002 |
|---------|-------|
| Nombre | SEGURIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | Este requerimiento es de suma importancia igual que todos los demas, sin embargo la seguridad prima en cualquier sistema es por esto que para aplicar esta se hara uso de una contraseña y un usuario unico con rol, lo cual permite controlar el acceso a la imformacion alojada |

| codigo | RFN-003 |
|---------|-------|
| Nombre | USABILIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | El software debera ser lo suficiente facil de manejar por el usuario, es decir este ultimo podra hacer todad las operaciones del sistema sin ningun problema, sin embargo, cualquier duda que surja podra ser consultada en "ayuda". |

| codigo | RFN-004 |
|---------|-------|
| Nombre | DISPONIBILIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | La disponibilidad del sistema le corresponde a la heladeria san delicias, que el servidor se alojara el sistema este en funcionamiento en los horarios de atencion de la heladeria  |

| codigo | RFN-005 |
|---------|-------|
| Nombre | FIABILIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | Lo definimos como la probabilidad de que este producto funcione sin fallos durante un lapso de  (6 meses) sin recibir mantenimiento correctivo |

| codigo | RFN-006|
|---------|-------|
| Nombre | MANTENIBILIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion |  El sistema debera tener capacidad de recuperarse en lo posible frente a los posibles fallos que puedan presentarse. asegurar que no se pierda los datos de la base de datos. en caso de falla del servidor la responsabilidad le corresponde a la heladeria san delicias. |

| codigo | RFN-007 |
|---------|-------|
| Nombre | PORTABILIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | En cuanto a este requerimiento,
podemos asegurar que el sistema sera totalmente portable en cuanto a sistemas operativos, ya que este sistema funcionara desde navegador, bien sea google chorme o mozilla firefox debera de funcionar adecuadamente.

 |