# Proyecto web 03: iglesia cristiana

Sitio web que muestra y describe la información de los servicios que ofrece una iglesia

Sitio web creado con las siguientes herramientas a nivel de front-end y back-end:

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

Al implementar la herramienta **SASS** en este proyecto me permite **crear bloques de código CSS, con una sintaxis indentada para separar cada bloque y almacenarlos en archivos separados** para posteriormente, llevar a cabo tareas de mantenimiento más fáciles en caso de que se requiera realizar alguna modificación o añadir nuevas líneas de código CSS

Para enviar la información del usuario a través del formulario de contacto se utiliza una herramienta  llamada **PHPMailer.** Esta es una biblioteca de código abierto para enviar correos electrónicos de forma segura y sencilla a través de código PHP desde un servidor web. Además está basada en el componente active server ASPMail y permite de una forma sencilla tareas complejas como por ejemplo:
- Enviar mensajes de correo con ficheros adjuntos (attachments) 
- Enviar mensajes de correo en formato HTML 
- Enviar emails via sendmail, PHP mail(), o con SMTP.

Finalmente, se utiliza una librería JavaScript llamada **SweetAlert2** para mostrar al usuario mensajes personalizados que le van a indicar si los datos digitados por el cliente fueron enviados al buzón de correo del restaurante de  correcta o incorrecta.

A continuación se presentan algunas imágenes del sitio web brevemente descrito anteriormente:

![01  Inicio_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/4b72804f-e354-4afe-b913-33330f112a87)
**==========================================================================**
![01  Inicio_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/f3c43b6a-91ab-4564-a1c3-70cb008803a9)
**==========================================================================**
![01  Inicio_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/41262a29-5bd9-4864-a78c-91dd1d6db808)
**==========================================================================**
![02  quienessomos_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/27e5ffe5-cf72-4380-8a0a-1c371e581d67)
**==========================================================================**
![02  quienessomos_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/4591112e-1df7-420d-b85c-5a7736fefda6)
**==========================================================================**
![02  quienessomos_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/a6b8f967-986b-473f-a59b-8e3afd5ba89f)
**==========================================================================**
![02  quienessomos_4](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/269b0663-67a6-4df6-8017-d759577b395f)
**==========================================================================**
![02  quienessomos_5](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/f64b13e3-2180-44e1-be8e-0b49e92b3e8e)
**==========================================================================**
![02  quienessomos_6](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/fa0bc193-42e5-4038-8c30-012fe5b90fa4)
**==========================================================================**
![02  quienessomos_7](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/fcc05193-fe92-43d0-b353-00a039321295)
**==========================================================================**
![02  quienessomos_8](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/02855d32-032e-4edf-82ed-db3a0c434b37)
**==========================================================================**
![02  quienessomos_9](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/4da01e15-b403-4a43-a1e0-e793b205846c)
**==========================================================================**
![02  quienessomos_10](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/c5028f4a-5779-467c-b6ca-c0a403ad4d9d)
**==========================================================================**
![02  quienessomos_11](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/a5a9ff9d-bc56-409c-8827-a1919f53807e)
**==========================================================================**
![02  quienessomos_12](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/814b238d-9bb0-4d60-af00-5810e5061350)
**==========================================================================**
![03  Reflexión_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/3f7e9897-061b-488c-bb0b-01048ed5f30e)
**==========================================================================**
![03  Reflexión_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/81696534-1cad-41b7-99b9-d650fb679d6a)
**==========================================================================**
![03  Reflexión_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/1e868b53-ee69-4cdb-ac9f-cdab13f5e3f7)
**==========================================================================**
![04  Actividades_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/7d3cdb62-adde-4113-9cbe-10de3c0298c0)
**==========================================================================**
![04  Actividades_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/07e09f70-5219-4351-adff-ccbbecdd5ee5)
**==========================================================================**
![04  Actividades_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/715a616f-391c-4ea6-b8f4-897bdaedc3fb)
**==========================================================================**
![04  Actividades_4](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/6809a176-12e9-4616-b400-1ac739e0503d)
**==========================================================================**
![05  Contacto_1](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/35e888ad-d3e0-4fd5-8106-7150c7f0c0af)
**==========================================================================**
![05  Contacto_2](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/38c8fa7f-f814-498e-9e70-49115a7d1851)
**==========================================================================**
![05  Contacto_3](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/3e42fe3a-0327-4f4a-aa7a-496c4fe55ce5)
**==========================================================================**
![05  Contacto_4](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/2b9895ea-86b3-45a5-8bec-fa22ae171f32)
**==========================================================================**
![05  Contacto_5](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/c1474ca9-2738-4e20-85d4-9493425b48f9)
**==========================================================================**
![05  Contacto_6](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/5d14d421-2c58-4bf9-897a-87f4fbe858d6)
**==========================================================================**
![05  Contacto_7](https://github.com/misproyectosweb/proyecto-web-03/assets/98922137/6796d6cf-da1c-4bd5-828d-b28c76bef3e5)
**==========================================================================**
