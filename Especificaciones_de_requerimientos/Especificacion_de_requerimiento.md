
# ANÁLISIS, DISEÑO, DESARROLLO E IMPLEMENTACIÓN DE UNA PAGINA WEB PARA LA EMPRESA DISTRUBUCIONES Y DIDACTICOS DE LA COSTA (PAWEDIDCOS).
### (Nombre del proyecto)

## DISTRIBUSCIONES Y DIDACTICOS DE LA COSTA.
### (Nombre de la empresa)



## ESPECIFICACION DE REQUERIMIENTOS.


## 1.	Introducción.
Sistematizar la forma de organización de información de la empresa (Distribuciones y Didacticos De La Costa) con un software, este será utilizado para el manejo de los datos de la empresa, de sus clientes y proveedores, además de brindarle a la empresa un sitio web, donde posibles clientes se pueden informar de los recursos que pueden conseguir en esta empresa y comparlos mediante este.

### 1.1	 Propósito.
Facilitar a la empresa DIstribuciones y didacticos de la costa, el manejo de su información y dar a conocer el propósito de la empresa, por medio de una sitio web la cual tendrá información de la empresa y que funciones realiza, así como mostrar los materiales y herramientas que pueden conseguir por medio esta empresa.

### 1.2	Alcance.

el sistema seria un sitio web que le permitira a la empresa, vender sus productos de fotma virtual. Se le hara entrega a nuestro cliente, un software que le permitira verder sus productos mediante una pagina web y que este registrara las ventas y ganacias que su empresa obtenga, donde la empresa sera la respondable de guardar o reistrar los datos de la misma en el software.
la empresa podra publicar sus productos en el sitio y los clientes podran registrarse en este sitio web, digitando sus datos personales y poder hacer sus compras.
.

### 1.3	Definiciones, Acrónimos, y Abreviaturas.

 * (B_S_S_W_C)-SISTEMA CENTRALIZADO DE DATOS Y SITO WED COSTA.
 * SIA – Sistema Integral Académico - es una herramienta que tiene como finalidad orientar, fortalecer, direccionar y alinear los Sistemas de Gestión de manera conjunta con la dirección estratégica de la empresa.
 * BD – Bases de datos- Una base de datos es un conjunto de datos pertenecientes a un mismo contexto y almacenados sistemáticamente para su posterior uso
 * UML– Lenguaje de Modelado Unificado- Se trata de un estándar que se ha adoptado a nivel internacional por numerosos organismos y empresas para crear esquemas, diagramas y documentación relativa a los desarrollos de software (programas informáticos).
 * Requerimientos funcionales (RF): describen las capacidades o funciones que el sistema será capaz de realizar.

 * Requerimientos no funcionales (RNF): restricciones o características que de delimitan el sistema, como por ejemplo, rendimiento, interfaces de usuario, fiabilidad, seguridad, portabilidad, normas, entre otros.

 * Requerimientos de interfaz de usuario (RIU): describen lo que el usuario vera finalmente.

 * Sistema Web: también conocido como “aplicación Web” son aquellos que están creados e instalados no sobre una plataforma o sistemas operativos  (Windows, Linux). Sino que se aloja en un servidor en Internet o sobre una intranet (red local).


### 1.4	Referencias.
Proporcione una lista de todos los documentos a que hace referencia el SRS.  Identifique cada documento por título, número de reporte (cuando aplica), fecha, organización que publica. Especificar las fuentes den donde se obtuvieron las referencias. Puede referenciar a un Apéndice u otro documento.

### 1.5	Apreciación Global

  *	La sección 1 se enfoca en la explicación, objetivos, metas y descripción del documento.

  *	La sección 2 está orientada, como su nombre lo indica, a la descripción general del sistema, donde la información está orientada al cliente/usuario potencial.

  *	La sección 3 trata sobre los requisitos específicos. Se emplean términos técnicos orientados principalmente a los desarrolladores y programadores.

## 2. Descripción General.
Esta sección describe los factores generales que afectan el producto y sus requerimientos. Esta sección provee un marco general de los requerimientos definidos en detalles en la Sección 3 de este SRS.

### 2.1	Perspectivas del Producto.
Facilitar y conservar en un software  todas las compras y ganancias que esta empresa reciba y que tenga un buen impacto con su sitio web, ya que los usuarios podran hacer sus comparas mediante este sitio.

### 2.2 Funciones del Producto.
Este le va facilitar los registros de ventas y ganancias a la empresa y gracias al sitio web aumentarían las compras por la facilidad que se les brindaría a los usuarios de comprar los productos virtuales.


### 2.3	Características de Usuario.
En el caso de la empresa, los distintuos usuarios que la amnejen, estaran publicando productos de acuerdo a las necesidades y al pendiente de los pedidios que le realicen a la empresa. Por otro lado, los usuarios que deseen comprar en esta pagina, tengran que poseer de internte para que se registren y puedan realizar sus compras.

### 2.4	Restricciones.
Para este sistema las posibles restricciones son el tiempo que tomará el desarrollo de este, recursos donde se implantara el sistema, el nivel del lenguaje programación para los desarrolladores.

Es de suma importancia que los usuarios se registren en el sitio web y registren sus datos para que estos puedan realizar sus compras y se quede registrado estos datos en la base de datos. Que tengan interntet disponible para poder ingresar al respectivo sitio web.

## 2.5	Atención y Dependencias.
Este software le facilitara comercializar sus distintos productos por medio web, los clientes podran visitar la pagina y conocer todos los elementos que estan a al venta y realizar sus respectiva compra. Gracias a este sitio, la empresa podra distribuir sus productos por todo la ciudad y darse a conocer en otras.

### 3.	Requerimientos Específicos
En esta sección se tienen con más detalle los requerimientos específicos del sistema a desarrollar.

## 3.1	Requerimientos Funcionales:
###Código: RF-001
###Nombre: MÓDULO DE LOGIN DE ADMINISTRADOR 	
###Fecha: 07-07-2020
###Grado Necesidad: ALTO

###Descripción:
Al sistema solo accederá personal autorizado mediante roles asignados.

Entradas: Datos personales (Usuario y contraseña).
Fuente: Base de datos.
Salida: Interfaz Menú principal.
Destino: Interfaz de Menú Principal	.
Restricciones:  Solo se accederá a ciertos módulos del sistema según el rol del usuario.

###Proceso
• Ingresar nombre y contraseña de usuario para Iniciar sesión.
*Cabe aclarar que el usuario previamente se encuentra registrado en la base de datos del sistema*
• Este Login No contará con opciones de recuperación de contraseña.

###Efecto Colateral:
Errar la contraseña o nombre de usuario niega el ingresó a la aplicación web, teniendo un límite de cinco (5) intentos.

###Código: RF-002
###Nombre: REGISTRO TRABAJADOR. 	
###Fecha: 07-07-2020
###Grado Necesidad: MEDIO.

###Descripción:
El sistema debe permitir el registro de usuarios, asignándoles un rol (Administrador-trabajador), estos usuarios son quienes harán uso de las funcionalidades del sistema.

Entradas: Datos personales: Identificación, Nombres, Apellidos
Fuente: Formulario de Registro para trabajadores.
Salida: Registro satisfactorio
Destino: Base de Datos.
Restricciones:  Un usuario tiene únicamente un rol.

###Proceso
•	Recolección datos básicos personales (nombre, apellido, celular)
•	Registro satisfactorio del usuario.
*Solo los usuarios que tengan el Rol de Administrador podrán hacer el registro de los usuarios que tendrán el rol de trabajador.
Los usuarios que deseen hacer el registro tienen que ser trabajadores de la empresa.*

###Efecto Colateral:
Los usuarios que tenga el rol de trabajador no tendrán acceso a todas las funcionalidades del sistema.
Una vez el trabajador sea despedido debe ser eliminado de la base de datos.

###Código: RF-003
###Nombre: REGISTRO DE PRODUCTOS.
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
El sistema debe permitir el registro de los productos que se encuentren disponibles.

Entradas: Datos del producto: Código, Nombre, Cantidad, Proveedor
Fuente:	Formulario de Registro de producto.
Salida: Registro del producto.
Destino: Base de Datos.
Restricciones:  NINGUNO.

###Proceso:
• Recolección datos del producto (nombre, código, cantidad, etc.).
• Agregar categoría de producto.
• Registro satisfactorio del producto en la base de datos.
*Una vez este registrado el producto solo será necesario tener en cuenta la cantidad de producto que se encuentre en el stock, y la información del proveedor.*

###Efecto Colateral:
Relacionar información con el módulo de producto.

###Código: RF-004
###Nombre: REGISTRO DE PROVEEDORES.
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
El sistema debe permitir el registro de los proveedores que surtan a la empresa de los productos.

Entradas: Datos del proveedor: Nombre, Identificación, Teléfono, Dirección.
Fuente:	Formulario de registro de los proveedores.
Salida: Proveedor registrado.
Destino: Base de Datos.
Restricciones:  N/A

###Proceso:
• Recolección datos del proveedor (nombre, identificación, teléfono, etc.).
• Registro satisfactorio del proveedor.

###Efecto Colateral:
Relacionar información con el módulo proveedor.

###Código: RF-005
###Nombre: ANALISIS DE STOCK DE PRODUCTOS.
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
El sistema deberá realizar un análisis de la cantidad de productos que se encuentren disponibles y actualizar la información en la base de datos.

###Proceso:
• Análisis de la cantidad de productos disponibles.
• Actualización de información en la base de datos.
*Si el sistema detecta que la cantidad de producto es igual a cero (0), se enviara un mensaje de aviso a los trabajadores.*

###Efecto Colateral:
Se relacionará la información actualizada con la información anterior e identificará si un producto está agotado o sigue disponible.

###Código: RF-006
###Nombre: REGISTRO DE SOLICITUDES.
###Fecha: 07-07-2020
###Grado Necesidad: MEDIO.

###Descripción:
Los clientes podrán indicar sus peticiones y quejas referentes a cualquier inconveniente que se presente con alguna de sus compras.

Entradas: Descripción de Anotación o queja.
Fuente:	Formulario para el registro de las solicitudes.
Salida: Registro de la solicitud.
Destino: Base de Datos.
Restricciones:  NINGUNA

###Proceso:
• El usuario debe registrar el inconveniente con su compra.
• Exponer su Solicitud o reclamo.

###Efecto Colateral:
NINGUNO.

###Código: RF-007
###Nombre: SELECCIÓN DE PRODUCTOS DE LA PAGINA PRINCIPAR.
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
El cliente podrá seleccionar los productos a los que está interesado y estos se agregaran a un formulario de compra.

Entradas: El cliente ingresa a la página principal y selecciona el producto que le interese.
Fuente:	Página principal.
Salida: Formulario de compra.
Destino: Base de Datos.
Restricciones:  Si el cliente se sale de la página el formulario no se guardará en la base de datos.

###Proceso:
• El cliente selecciona los productos que le interese del sistema (y que esté disponible).
• Una vez haya seleccionado todos los productos se envía al cliente a realizar el formulario de compra.

###Efecto Colateral:
Se redirecciona al cliente al formulario de compra.

###Código: RF-008
###Nombre: FORMULARIO DE COMPRA
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
El formulario de compra contendrá la información de los productos que solicita el cliente en la compra, así como la información del cliente e información de formas de pago.

Entradas: Se solicita la información de producto: Códigos de productos, Cantidad.
Se solicita la información del cliente: Tipo (persona o entidad), Dirección, Nombre, Teléfono, Información de forma de pago.
Fuente: Formulario de compra.
Salida: Formulario de compra ha sido registrado.
Destino: Base de Datos.
Restricciones: N/A

###Proceso:
• Recolección datos ingresados por el cliente.
• Se envía el formulario de compra.
*Si el cliente cancela la compra se bórrala el formulario de compra de la base de datos*

###Efecto Colateral:
El cliente recibe un mensaje de “compra exitosa”.

###Código: RF-009
###Nombre: INFORME FINANCIERO.
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
Generar informes respectivos de las actividades financieras de la página (dinero ganado, dinero destinado a los suministros, etc.…)

Entradas: Análisis de las actividades financieras (Compras, Ventas, etc.…).
Fuente: Base de datos.
Salida: Actualización de información.
Destino: Base de Datos.
Restricciones:  Los usuarios con el rol trabajador no podrán ingresar a esta información.

###Proceso:
• Análisis de las actividades financieras (Compras, Ventas, etc.).
• Actualización de información en la base de datos.
*Solo el administrador tiene acceso a esta información.*

###Efecto Colateral:
NINGUNO.

###Código: RF-010
###Nombre: AYUDA
###Fecha: 07-07-2020
###Grado Necesidad: ALTA.

###Descripción:
El sistema tendrá un botón que permitirá que re direccionara a un archivo PDF donde se hallará información de ayuda.

Entradas:
Fuente:	Archivo PDF:
Salida: Nueva pestaña con el PDF.
Destino: Nueva pestaña con el PDF.
Restricciones:  NINGUNA

###Proceso:
El usuario del sistema podrá realizar consultar dudas en un manual de ayuda para saber cómo ejecutar una funcionalidad del sistema.

###Efecto Colateral:
NINGUNO.
