# SRS 

## 1. Introducción
La siguiente Especificación de Requerimientos de Software (SRS) del sistema a construir, surge con la finalidad de proveer toda la información de lo que quiere el cliente que contenga el software. Tales requerimientos son la base a la hora de comenzar el desarrollo del Software. En este caso el software a desarrollar es un sistema de control y organización de citas que los cieltes de la barberia realizan para apartar cupo en ella y llevar control de ganancias y pagos de la venta de los productos y servicios que prestan.

### 1.1	Propósito
El propósito de este documento es describir lo acordado con el cliente y desarrollar el paso a paso para crear el software que servirá para dar control, organizacion y registro sobre ganancias, pagos y citas apartadas por los clientes , entre otros del establecimiento Adonay Style. Sistematizar estos procesos para ayudar a mejorar el rendimiento del área administrativa, generando informes semanalmente de ingresos, pagos y citas de los clientes tanto como de los productos.


### 1.2	Alcance
El sistema será una aplicación web que permitirá llevar el control de pagos a los trabajadores ingresos al establecimiento, citas hechas por los clientes y ventas de los productos,  llevando los respectivos informes de los ingresos semanales y mensuales.
El sistema planteado dará apoyo a los siguientes procesos: 
•	Control y organización de ingresos y pagos.
•	Administración de citas hechas por los clientes.
•   administracion de ventas de los productos.
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
Con este sistema se espera una mejora en la forma de cómo se maneja la parte administrativa en productos y producido en el transcurso del mes en la empresa.
### 2.2	Funciones del Producto
El software cumplirá con las siguientes funciones:
1. Administrador 
2. Registro de los productos que entran de la empresa.
3. Precio de los productos que entran a la empresa.
4. Registro de los productos que salen de la empresa.
5. Registros de los productos que se van vendiendo.
6. registro de citas de la empresa.
7. registro de pagos semanales de la empresa.
### 2.3 Características de Usuario
Los usuarios que interactuaran con este sistema son personas capacitadas para el manejo de ingresos en ventas y en productos y registro de las citas , ya que se hace énfasis tanto como de  en el inventario como de horas de servicios que los trabajadoren llevan a cabo  de la empresa.

### 2.4	Restricciones
las posibles restricciones son el tiempo que tomará el desarrollo del sistema apropiado, recursos donde se implantará el sistema tales como herramientas digitales y dinero si es necesario, el nivel del lenguaje programación para nosotros como administradores de los recursos de la empresa y que este mismo sea claro y eficaz en su trabajo.


### 2.5	Atención y Dependencias
Nuestra propuesta consiste en un modelo aplicativo para organizar y contabilizar la salida y entrada de productos y registrar ingresos semanales, pagos y prestamos a los trabajadores, como también calcular el total de ganancias.

# 3. Requerimientos Especificos 

### 3.1 Requerimeintos Funcionales 
|   Codigo  |  RF-001  | 
|---|---|
| Nombre  | MODULO LOGIN |
| Fecha  | 25/05-2023|
| Grado Necesidad    |  ALTO|
| Entradas  | (Usuario Y  Contraseña)  |
| Fuente  | Base De Datos  |
| Salida  | Interfaz Menu Principal  |
| Destino  | Interfaz Menu Principal  |
| Restricciones | Restricciones Segun Su Rol |
| Proceso | * Ingresar Usuario Y Contraseña 
|   | * La Cuenta Debe Estar Registrada Previamente   en la base de Datos  
|   | * El login No Permite Recuperacion De Cuenta  | 
| Efecto Colateral  | Fallar La Contraseña 5 Veces Bloquea El Acceso A La Pagina Web    |

|   Codigo  |  RF-002  | 
|---|---|
| Nombre  | REGISTRO DE USUARIOS |
| Fecha  | 25/05-2023|
| Grado Necesidad    |  ALTO|
| Entradas  | (NOMBRES Y APELLIDOS)  |
| Fuente  | Foemulario de registo para usuarios  |
| Salida  | Registo satisfactorio |
| Destino  | Base de datos  |
| Restricciones | Restricciones Segun Su Rol |
| Proceso | * Reoleccion de datos basicos como nombre apellido y numero telefonico
|   | * Registro sastifactorio del usuario  
|   | * Solo el personal administrativo o de un rol expecifico tendra la posibilidad del registro a los usuarios  | 
| Efecto Colateral  | estos mismos usuarios con nivel de rol administrativo no tendran el adceso adsoluto a las funciones del sistema por precausion  |



|   Codigo  |  RF-003  | 
|---|---|
| Nombre  | REGISTRO DE PROPIETARIO/POSEEDOR |
| Fecha  | 25/05-2023|
| Grado Necesidad    |  ALTO|
| Entradas  | (Identificacion Nombres apellidos)  |
| Fuente  | Formulario de registro del poosedor |
| Salida  | Proosedor regitrado  |
| Destino  | Base de datos  |
| Restricciones | un propietario puede tener 3 roles si es el caso |
| Proceso | * Recopilacion de datos basicos personales
|   | * asignacion de rol o cargo al propietario
|   | * registo satisfactorio  | 
| Efecto Colateral  | Modificacion De Registro Helados|

|   Codigo  |  RF-004  | 
|---|---|
| Nombre  | REGISTRO HELADO |
| Fecha  | 25/05-2023|
| Grado Necesidad    |  ALTO|
| Descripcion | El Sistema Permite La Modificacion De Helados Manejados En El Momento
| Entradas | LOGIN | 
|Fuente | Base De Datos | 
| Salida | Interfaz De Helados| 
|Destino | Base De Datos | 
| Proceso | El Usuario Deberia Ingresar Con Una Cuenta Que tenga Rol Propietario/poseedor |

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
| Descripcion | La disponibilidad del sistema le corresponde a la barberia Adonay Style, que el servidor se alojara el sistema este en funcionamiento en los horarios de atencion de la barberia |

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
| Descripcion |  El sistema debera tener capacidad de recuperarse en lo posible frente a los posibles fallos que puedan presentarse. asegurar que no se pierda los datos de la base de datos. en caso de falla del servidor la responsabilidad le corresponde a la barberia Adonay Style |

| codigo | RFN-007 |
|---------|-------|
| Nombre | PORTABILIDAD |
| Fecha | 25/05/2023 |
| Grado Necesidad | ALTO |
| Descripcion | En cuanto a este requerimiento,
podemos asegurar que el sistema sera totalmente portable en cuanto a sistemas operativos, ya que este sistema funcionara desde navegador, bien sea google chorme o mozilla firefox debera de funcionar adecuadamente.
