# Proyecto web 03
Sitio web que muestra información variada de una iglesia

Este sitio web fue creado con:
- **HTML:**	Permite crear la estructura del sitio web mediante etiquetas
- **CSS:**	Para definir y crear la presentación o estética del sitio web
- **SASS:**	Herramienta que permite extender las características de las hojas de estilo CSS, proveyendo de varios mecanismos, tales como variables, funciones, herencia que están presentes en los lenguajes de programación tradicionales, particularmente lenguajes orientados a objetos, pero este no están disponible para CSS3 como tal.
- **JavaScript:**	Añade características que permite agregar e implementar acciones interactivas al sitio web
- **PHP:**	Favorece la conexión entre los servidores y la interfaz de usuario

Este sitio web fue creado y desarrollado usando la plataforma **NetBeans 12.0.** Además está adaptado para ejecutarse en dispositivos móviles.

El archivo **index.php** es el que contiene la página de inicio o página principal del sitio web, cuyo diseño varía en la mayoría de elementos contenidos en relación con el proyecto llamado **“proyecto-web-01”**

La página de inicio o principal consta de tres secciones: 
- **Un encabezado:**	donde se muestra el logotipo de la organización
- **Una sección principal:**	integra los contenidos más relevantes de presentación de la organización 
- **Un pie de página:** 	muestra la información de contacto de la organización

El menú principal consta de cuatro opciones: 
- **Quienes somos:**	muestra la información que define la identidad de la organización. Integra un submenú con seis opciones adicionales, las cuales describen aspectos tales como la visión, la misión, los valores, entre otros, de la organización
- **Reflexiones:**	página dedicada a publicar artículos, noticias, mensajes y/o reflexiones con contenido bíblico
- **Actividades:**	muestra las actividades que va a realizar la organización durante el mes en curso; así como las actividades que se van a realizar en fechas posteriores 
- **Contáctenos:**	consta de dos secciones: un formulario de contacto para que la persona pueda ponerse en contacto con la organización y un mapa que muestra la ubicación junto con datos adicionales de contacto

En cada archivo de estilos CSS se utiliza la técnica de rejilla **CSS Grid Layout** para organizar de manera más eficiente cada elemento de la interfaz del sitio web, el cual los acomoda tanto a lo largo como a lo ancho de la ventana del navegador. Además, es complementado con **Flexbox,** el cual ayuda a distribuir el espacio entre los ítems de la interfaz y mejora las capacidades de alineación de cada elemento en filas o columnas.

Para el formulario de contacto se programaron validaciones tanto del lado del cliente utilizando JavaScript; así como del lado del servidor programado con PHP.

Al implementar la herramienta SASS en este proyecto me permite crear bloques de código CSS, con una sintaxis indentada para separar cada bloque y almacenarlos en archivos separados para posteriormente, llevar a cabo tareas de mantenimiento más fáciles en caso de que se requiera realizar alguna modificación o añadir nuevas líneas de código CSS

Para enviar la información del usuario a través del formulario de contacto se utiliza una herramienta  llamada **PHPMailer.** Esta es una biblioteca de código para enviar correos electrónicos de forma segura y sencilla a través de código PHP desde un servidor web. Además está basada en el componente active server ASPMail y permite de una forma sencilla tareas complejas como por ejemplo:
- Enviar mensajes de correo con ficheros adjuntos (attachments) 
- Enviar mensajes de correo en formato HTML 
- Enviar emails via sendmail, PHP mail(), o con SMTP.

Finalmente, se utiliza una librería JavaScript llamada **SweetAlert2** para mostrar al usuario mensajes personalizados que le van a indicar si los datos digitados por el cliente fueron enviados al buzón de correo del restaurante de  correcta o incorrecta.

A continuación se presentan algunas imágenes del sitio web brevemente descrito anteriormente:

![01  Inicio_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/3c7c3f92-cffa-47d3-a5fa-814c86780557)
**==========================================================================**
![01  Inicio_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/341d8193-f791-4863-88d0-98d0ede2d908)
**==========================================================================**
![01  Inicio_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/4e3beb7b-29b5-49e1-982a-adad9bb9fdbf)
**==========================================================================**
![01  Inicio_4](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/ed6c2453-1beb-4afc-bc04-164bb7031496)
**==========================================================================**
![02  QS_Nuestra visión_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/f08a296a-20b0-4cb7-8ff1-3d84f395c786)
**==========================================================================**
![02  QS_Nuestra visión_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/b64deb3e-f29c-4b2e-be47-174f2755f9bd)
**==========================================================================**
![03  QS_Nuestra misión](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/1e097139-983f-4571-98b1-cfaf5450dc95)
**==========================================================================**
![04  QS_Nuestro perfil](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/ee00678a-4134-4f06-b602-deafdff60989)
**==========================================================================**
![05  QS_Nuestra vivenciaReino](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/74bcf401-d710-46b3-9691-e8fa1264b4e4)
**==========================================================================**
![06  QS_Nuestros valores](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/68863bdb-c5db-4fda-9a4a-f61ea219a8ac)
**==========================================================================**
![07  QS_Nuestra estrategia](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/caaead72-b388-40c0-ac40-cb9b7effac54)
**==========================================================================**
![08  Reflexión_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/d56e530f-6891-402f-bb29-5ce9ddd9f295)
**==========================================================================**
![08  Reflexión_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/07e861c8-7ae1-49e5-b037-5d7aa61c2385)
**==========================================================================**
![08  Reflexión_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/20d9a40f-ce99-456e-b7d6-90295faadfa7)
**==========================================================================**
![09  Actividades_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/95c50b2d-ddb4-4505-ac27-bf0144152723)
**==========================================================================**
![09  Actividades_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/6408a952-b779-483f-8aee-077f58f66b61)
**==========================================================================**
![09  Actividades_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/92ab0542-3522-404a-95bf-fffbf20a0737)
**==========================================================================**
![10  Contacto_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/154a2656-38ce-4d47-b665-92f6b452aebe)
**==========================================================================**
![10  Contacto_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/495dcf99-3aa9-4ba9-9123-eef543ca33d8)
**==========================================================================**
![10  Contacto_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/e9f74822-529d-4879-a143-2e8b8aacae0b)
**==========================================================================**
![10  Contacto_4](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/27d2c429-28fa-4e3a-a988-34b5a3a46d19)
**==========================================================================**
![10  Contacto_5](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/eee60856-47e7-442c-b47a-7735dfdb252a)
**==========================================================================**
![10  Contacto_6](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/9f1e711d-f5ea-448e-8e17-7a83bafd5b8d)
**==========================================================================**
![10  Contacto_7](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/73e9142b-608c-4122-9469-9bdc1fa99761)
**==========================================================================**
![10  Contacto_8](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/72870585-afde-46cb-b5c7-051eeac466e3)
