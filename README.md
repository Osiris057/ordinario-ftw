*Proyecto: Sistema de Gestión para "Atlas Corporation"*
Este proyecto es el resultado del trabajo final para la asignatura de Fundamentos de Tecnologías Web. Se trata de un sistema de gestión de inventarios y punto de venta para la empresa ficticia "Atlas Corporation".

*Descripción del Proyecto*
El sistema permite gestionar de manera integral el inventario, proveedores, usuarios, así como el proceso de ventas y compras de mercancía. El proyecto destaca por el uso de XML como base de datos, JavaScript para la manipulación dinámica del DOM.

*Mockups (Capturas del Sistema)*
A continuación, se presentan las interfaces principales del sistema:
![panel login](assets/panel%20login.png)
![panel principal](assets/panel%20admin.png)
![panel inventario](assets/panel%20inventario.png)
![panel historial de movimientos](assets/panel%20historial%20de%20movimientos.png)
![panel ventas](/assets/panel%20ventas.png)
![panel historial ventas](/assets/panel%20historial%20ventas.png)
![panel principal proveedores](/assets/panel%20principal%20proveedores.png)
![panel gestion proveedores](/assets/panel%20gestion%20proveedores.png)
![panel gestion usuarios](/assets/panel%20gestion%20usuarios.png)

El resto de mockups no los agregue porque las interfaces no estan terminadas del todo o no tienen todas sus funcionalidades

*Prompts y Metodología Técnica*
Para el desarrollo de la lógica compleja, se utilizó la asistencia de IA siguiendo una metodología de trabajo modular. Algunos de los prompts clave fueron:

Lógica de JavaScript (Motor del Sistema)
"Necesito una función en JavaScript que lea un archivo XML, extraiga los datos de los productos y los inyecte en una tabla HTML. Además, requiero que esta función permita filtrar los resultados en tiempo real mediante un input de búsqueda."

"Para el Punto de Venta, necesito que al seleccionar un producto del inventario, se agregue a un array 'carrito'. Al presionar el botón de realizar venta, el sistema debe restar el stock actual (usando sessionStorage) y registrar el movimiento en un historial compartido."

"¿Cómo puedo hacer que los cambios realizados en el stock (ventas/compras) persistan durante la sesión del usuario usando sessionStorage para que la tabla principal se actualice automáticamente sin necesidad de recargar el XML físico?"

Diseño y Estructura (HTML/CSS)
"Crea una estructura de modal profesional para editar datos de proveedores con CSS moderno. Asegúrate de incluir el diseño con Media Queries para que sea responsivo en dispositivos móviles."

"Necesito que la barra de búsqueda del panel de ventas funcione como un combobox de autocompletado que extraiga los nombres de los productos desde el XML de inventario disponible."

*Tecnologías Utilizadas*

HTML5: Estructura semántica.

CSS3: Estilos con variables raíz, Flexbox y Media Queries.

JavaScript: Manipulación del DOM, Fetch API para XML y lógica de negocio.

XML: Almacenamiento de datos estructurado.

DTD: Validación de esquemas para los datos.